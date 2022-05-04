<script setup>
import TheFooter from '../components/TheFooter.vue';
import TheHeader from '../components/TheHeader.vue';
import TheButton from '../components/TheButton.vue';
import BlogCard from '../components/card/BlogCard.vue';
import ProvideCard from '../components/card/ProvideCard.vue';
</script>

<template>
  <div class="">
    <the-header></the-header>
    <main>
      <div class="bg-[#fff] py-20">
        <div class="container flex flex-col justify-between items-center">
          <div class="border-gold border-l-4 w-80 leading-none pl-5">
            <h4>
              Trusted by over <br />
              10k clients & brands
            </h4>
            <p class="text-lg font-medium text-ash">
              Lorem ipsum dolor sit amet, solor ut adipiscing elit.
            </p>
          </div>
          <div></div>
        </div>
      </div>
      <div class="bg-[#F8F3EC] py-20">
        <div class="container">
          <div class="text-center">
            <h3>What we provide</h3>
            <p class="font-meduim text-xl py-5 text-ash">
              Lorem ipsum dolor sit amet, consectetur
              adipiscing elit. In urna, <br /> non nisl tincidunt
              ut elementum turpis.
            </p>
          </div>
          <div>
            <provide-card></provide-card>
          </div>
        </div>
      </div>
      <div class="bg-[#fff] py-20">
        <div class="container flex flex-row justify-evenly items-center">
          <div class="w-96">
            <p class="font-semibold text-3xl">
              ”Lorem ipsum dolor sit amet, ut consectetur adipiscing elit.
              In urna, non nisl tincidunt ut elementum st turpis.“
            </p>
            <div class="py-7 flex flex-row items-center">
              <span><img src="../assets/images/profileLanding.png" alt=""></span>
              <div class="ml-4">
                <p class="text-black font-semibold text-2xl">Joe Elia</p>
                <p class="text-ash font-medium text-2xl">User interface Design</p>
              </div>
            </div>
          </div>
          <span><img src="../assets/images/user.png" alt=""></span>
        </div>
      </div>
      <div class="py-20 bg-black">
        <div class="container text-[#fff] text-center">
          <h2 class="py-5">Ready to increase <br />your social media performance</h2>
          <p class="pb-5 text-lg font-medium">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. In urna,
             non nisl tincidunt ut elementum turpis.</p>
          <the-button class="bg-gold text-black">GET STARTED</the-button>
        </div>
      </div>
      <div class="py-20">
        <div class="container">
          <div class="flex flex-row items-center justify-between">
            <span class="w-96">
              <h3>Read our blogs</h3>
              <p class="text-ash text-lg font-medium">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. In
                urna, non nisl tincidunt ut elementum turpis.
              </p>
            </span>
            <the-button class="text-gold bg-black">Read All Blogs</the-button>
          </div>
          <div class="">
            <blog-card></blog-card>
          </div>
        </div>
      </div>
    </main>
    <the-footer></the-footer>
  </div>
</template>
