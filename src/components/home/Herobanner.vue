<template>
  <div
    class="
      bg-img bg-no-repeat bg-cover
      pt-15px
      h-685px
      w-full
      bg-blend-soft-light
    "
  >
    <div class="container mx-auto h-full">
      <div class="dir h-full md:items-center text-white">
        <div class="w-12/12 md:w-6/12">
          <p class="align">ABOUT</p>
          <div class="text-7xl align">
            Your cradit scores
          </div>
          <div class="text-7xl align">
            should be free
          </div>
          <p class="align">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maiores
            velit magni natus obcaecati, expedita blanditiis exercitationem
            sequi commodi quisquam eveniet!
          </p>
        </div>
        <div class="w-12/12 md:w-6/12 flex justify-center">
          <img class="w-6/12 md:w-10/12" :src="tym" alt="mister tym" />
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import tym from "../../assets/images/tym.png";

export default defineComponent({
  setup() {
    return {
      tym,
    };
  },
});
</script>

<style scoped>
.bg-img {
  background-image: url("../../assets/images/background.jpg");
}

.dir {
  display: flex;
  flex-direction: flex;
}
.align {
  text-align: start;
}
@media screen and (max-width: 640px) {
  .dir {
    flex-direction: column-reverse;
  }
  .align {
    text-align: center;
  }
}
</style>