<template>
    <div class="w-full flex flex-row items-center justify-evenly py-8">
      <div v-for="item in state" :key="item.id">
        <span><img :src="getImage(item.image)" alt="" /></span>
        <div class="font-medium w-96">
          <p class="text-[#F29764] text-lg font-semibold">{{item.date}}</p>
          <h4>{{item.title}}</h4>
          <p>
            {{item.summary}}
          </p>
          <a :href="item.link" class="font-semibold underline">READ MORE</a>
        </div>
      </div>
    </div>
</template>

<script setup>
import { ref } from 'vue';
import data from '../../utils/data.json';

const state = ref(data);

const getImage = (image) => `src/assets/images/${image}`;
</script>

<style lang="scss" scoped>
</style>
