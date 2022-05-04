<template>
  <div class="bg-light py-10">
    <div class="container">
      <div class="grid md:grid-cols-2 lg:grid-cols-3 place-items-center">
        <the-navigation />
        <p class="font-bold text-4xl text-black">Marft<span class="text-gold">.</span></p>
        <div class="flex flex-row items-center justify-around w-60">
          <span class="
              cursor-pointer
              h-12
              w-12
              border-2
              rounded-full
              flex
              items-center
              justify-center
            "><img src="../assets/images/logos/facebook.svg" alt="facebooklogo" /></span>
          <span class="
              cursor-pointer
              h-12
              w-12
              border-2
              rounded-full
              flex
              items-center
              justify-center
            "><img src="../assets/images/logos/behance.svg" alt="behancelogo" /></span>
          <span class="
              cursor-pointer
              h-12
              w-12
              border-2
              rounded-full
              flex
              items-center
              justify-center
            "><img src="../assets/images/logos/instagram.svg" alt="instagram" /></span>
        </div>
      </div>
      <hr class="border-[1px] border-[#bbbbbb] mt-7" />
      <!-- nav end -->
      <div class="flex flex-row justify-between items-center py-10">
        <div class="w-96">
          <h2 class="py-5">
            Increase your performance on
            social media
          </h2>
          <p class="text-xl font-medium text-ash">
            Lorem ipsum dolor sit amet,
            consectetur adipiscing elit. In urna,
            non nisl tincidunt ut elementum turpis.
          </p>
          <div class="py-5">
            <the-button class="text-black bg-gold">GET STARTED</the-button>
          </div>
        </div>
        <div class="hidden lg:flex flex-row items-center">
          <span><img src="../assets/images/first.png" alt=""></span>
          <span class="ml-4"><img src="../assets/images/second.png" alt=""></span>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import TheNavigation from './TheNavigation.vue';
import TheButton from './TheButton.vue';

</script>

<style lang="scss" scoped>
</style>
