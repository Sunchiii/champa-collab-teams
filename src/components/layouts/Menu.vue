<template>
  <div class="h-15 absolute w-full">
    <div class="container mx-auto">
      <div>
        <div class="h-15 flex justify-between items-center">
          <div class="h-full w-1/5 bg-white px-5 rounded-b-lg flex justify-center items-center">
            <span class="text-blue-700 text-2xl">compare</span
            ><span class="text-blue-400 text-2xl">offers</span>
          </div>
          <div class="w-3/5 flex justify-evenly text-white">
            <div>loons</div>
            <div>cradit card</div>
            <div>saving</div>
            <div>life incherance</div>
            <div>cradit score</div>
            <div>learn</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import LOGO from "../../assets/image/logo.png";
export default defineComponent({
  setup() {
    return {
      LOGO,
    };
  },
});
</script>

<style scoped>
</style>
