<template>
  <div class="bg-black text-[#fff]">
    <div class="container py-5">
      <div class="flex flex-col items-center py-6">
        <p class="font-bold text-4xl">Marft<span class="text-gold">.</span></p>
        <p class="text-lg font-medium text-center">
          Lorem ipsum dolor sit amet elit, sed do tempor <br />
          solor ut dolore magna
        </p>
        <div class="flex flex-row items-center justify-around w-60 py-7">
          <span class="
              cursor-pointer
              h-12
              w-12
              border-2
              rounded-full
              flex
              items-center
              justify-center
              shadow-lg
              border-ash
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
              shadow-lg
              border-ash
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
              shadow-lg
              border-ash
            "><img src="../assets/images/logos/instagram.svg" alt="instagram" /></span>
        </div>
      </div>
      <div class="flex flex-col items-center pb-5">
        <h3>Subscribe to our Newsletter</h3>
        <p class="py-4 text-lg font-medium">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
        <form @submit.prevent="">
          <div class="">
            <input type="text" name="" id="" class="
                border-[1px]
                rounded-bl-xl rounded-tl-xl
                border-ash
                bg-black
                p-6
                w-96
              " placeholder="Enter your mail" />
            <button class="
                border-ash border-[1px]
                p-6
                rounded-br-xl rounded-tr-xl
                text-gold
                font-semibold
              ">
              SUBSCRIBE
            </button>
          </div>
        </form>
      </div>
      <div class="flex flex-row justify-around py-10">
        <div>
          <p class="font-semibold text-ash">DM us on:</p>
          <p class="text-2xl">info@marft.com</p>
        </div>
        <div>
          <p class="font-semibold text-ash">Call us on:</p>
          <ul class="text-2xl">
            <li>(+1) 0139 2092 2033</li>
            <li>(+1) 0392 5938 000</li>
          </ul>
        </div>
        <div>
          <p class="font-semibold text-ash">Find us:</p>
          <p class="text-2xl">
            767 5th Street, 21st Floor, <br />
            New York, USA
          </p>
        </div>
      </div>
    </div>
    <hr class="border-ash" />
    <div class="
        container
        flex flex-row
        justify-between
        items-center
        py-5
        font-medium
        text-lg
        text-ash
      ">
      <p>©Marft 2021. All rights reserved.</p>
      <span class="flex flex-row items-center">
        <p>Privacy Policy</p>
        <p class="pl-4">Terms of Conditions</p>
      </span>
    </div>
  </div>
</template>

<script setup>
</script>

<style lang="scss" scoped>
</style>
