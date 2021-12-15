<template>
  <div class="h-15 absolute w-full">
    <div class="container mx-auto">
      <div>
        <div class="h-10 md:h-15 flex justify-between items-center">
          <div
            class="
              h-full
              w-2/5
              md:w-1/5
              bg-white
              px-5
              rounded-b-lg
              flex
              justify-center
              items-center
            "
          >
            <span class="text-blue-700 md:text-2xl">compare</span
            ><span class="text-blue-400 md:text-2xl">offers</span>
          </div>
          <div class="hidden md:block w-3/5 md:w-3/5 md:flex justify-evenly text-white">
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
    <div class="absolute top-1 right-0 block md:hidden w-8 h-8 bg-white p-1 mr-5 rounded-x clicked">
      <div class="h-1 bg-black my-1 rounded-xl"></div>
      <div class="h-1 bg-black my-1 rounded-xl"></div>
      <div class="h-1 bg-black my-1 rounded-xl"></div>
      <div class="absolute top-10 act bg-white p-3 block md:block">
        <div>loons</div>
        <div class="border-h bg-black"></div>
        <div>cradit card</div>
        <div class="border-h bg-black"></div>
        <div>saving</div>
        <div class="border-h bg-black"></div>
        <div>life incherance</div>
        <div class="border-h bg-black"></div>
        <div>cradit score</div>
        <div class="border-h bg-black"></div>
        <div>learn</div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import LOGO from "../../assets/logo.png";

export default defineComponent({
  setup() {
    return {
      LOGO,
    };
  },
});
</script>

<style scoped>
.border-h {
  height: 1px;
}
.clicked{
  overflow: hidden;
}
.clicked:active{
  overflow: visible;
}
.clicked:active .act{
  right:0;
}
.act{
  right: -200px;
}
</style>
