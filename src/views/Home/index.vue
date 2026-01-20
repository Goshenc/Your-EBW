<script setup>
import { onMounted } from 'vue';
import {ref} from 'vue'
import HomeBanner from './components/HomeBanner.vue';
import HomeCategory from './components/HomeCategory.vue';
import HomeNew from './components/HomeNew.vue';
import HomeHot from './components/HomeHot.vue';
import HomeProduct from './components/HomeProduct.vue';
import HomePanel from './components/HomePanel.vue';


</script>

<template>
  <div class="container">
    <HomeCategory/>
    <HomeBanner/>
</div>
<HomeHot/>
<HomeNew/>

<HomeProduct/>

</template>

<style scoped>
/* 样式写这里 */
</style>
