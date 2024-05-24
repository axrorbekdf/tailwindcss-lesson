<script setup lang="ts">
import { styles } from '@/util/style';
</script>


<template>
  <!-- <h1 class="text-3xl font-bold underline bg-black text-asosiy md:text-red-600 font-montserrat">
      Hello world!
    </h1> -->
  <div class="bg-asosiy w-full overflow-hidden font-montserrat container">
    
    <div :class="[styles.padding, 'container']">
      <!-- <div class="container"> -->
      <div :class="[styles.container, 'container', styles.flexCenter]">
        <p class="xs:text-rose-600 md:text-white">Navbar</p>
      </div>
    </div>

    <div class="bg-slate-500 container">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora fugit numquam repudiandae accusantium, temporibus voluptatum nostrum quis ducimus! Pariatur quam, qui labore rem omnis consectetur totam accusamus alias excepturi. Ullam?
      </p>
    </div>
  </div>
</template>
