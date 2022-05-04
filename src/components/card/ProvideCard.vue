<template>
  <div class="container grid grid-cols-3 gap-6">
    <div class="bg-[#EAE4DC] p-16" v-for="item in items" :key="item.id">
      <span><img :src="getIcon(item.image)" alt=""></span>
      <h3 class="py-8">{{item.title}}</h3>
      <p class="pb-8">
        {{item.summary}}
      </p>
      <a :href="item.link" class="font-bold underline">LEARN MORE</a>
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue';
import data from '../../utils/provide.json';

const items = ref(data);

const getIcon = (image) => `src/assets/images/logos/${image}`;
</script>

<style lang="scss" scoped>

</style>
