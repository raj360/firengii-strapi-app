<template>
  <div class="container">
    <Hero/>
    <LargeCardDisplay/>
  </div>
</template>

<script>
import { largeCardSections, smallCardSections } from "@/assets/data.js"
export default {
  data(){
  return{ largeCardInfo:largeCardSections}
  }
};
</script>
