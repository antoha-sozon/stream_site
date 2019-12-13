<template>
  <div class="home h-screen p-12 bg-black bg-center bg-cover bg-darken" :style="'background-image:url(' + dota2Bg + ');'">
    <div class="w-full h-full p-6 overflow-y-auto">
      <div class="flex flex-wrap">
        <div class="w-1/3 p-1">
          <div class="border rounded-sm bg-black">
            <img src="https://via.placeholder.com/500x300" alt="">
            <h3 class="px-4 mb-2 text-xl text-left text-green-500">Lorem ipsum dolor.</h3>
            <small class="block px-4 mb-2 text-left text-white">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius, rem.</small>
          </div>
        </div>
        <div class="w-1/3 p-1">
          <div class="border rounded-sm bg-black">
            <img src="https://via.placeholder.com/500x300" alt="">
            <h3 class="px-4 mb-2 text-xl text-left text-green-500">Lorem ipsum dolor.</h3>
            <small class="block px-4 mb-2 text-left text-white">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius, rem.</small>
          </div>
        </div>
        <div class="w-1/3 p-1">
          <div class="border rounded-sm bg-black">
            <img src="https://via.placeholder.com/500x300" alt="">
            <h3 class="px-4 mb-2 text-xl text-left text-green-500">Lorem ipsum dolor.</h3>
            <small class="block px-4 mb-2 text-left text-white">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius, rem.</small>
          </div>
        </div>
        <div class="w-1/3 p-1">
          <div class="border rounded-sm bg-black">
            <img src="https://via.placeholder.com/500x300" alt="">
            <h3 class="px-4 mb-2 text-xl text-left text-green-500">Lorem ipsum dolor.</h3>
            <small class="block px-4 mb-2 text-left text-white">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius, rem.</small>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
//import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  data() {
    return {
      dota2Bg: require('../assets/dota2_bg.jpg'),
    }
  },
  components: {
    //HelloWorld
  }
}
</script>


<style scoped>
  .bg-darken {
    background-blend-mode: darken;
    background-color: rgba(0, 0, 0, 0.78);
  }
</style>