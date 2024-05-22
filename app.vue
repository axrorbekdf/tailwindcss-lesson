<script setup lang="ts">
import {styles} from '@/util/style';

console.log(styles); 

</script>


<template>
  <!-- <h1 class="text-3xl font-bold underline bg-black text-asosiy md:text-red-600 font-montserrat">
      Hello world!
    </h1> -->
  <div class="bg-asosiy w-full overflow-hidden font-montserrat">
    
    <div :class="[styles.padding]">
      <p class="text-white">Navbar</p>
    </div>

  </div>
</template>
