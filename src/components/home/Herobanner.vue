<template>
   <div class="bg-img bg-no-repeat bg-cover pt-15px h-685px w-full bg-blend-soft-light">
       <div class="container mx-auto h-full">
           <div class="flex h-full items-center text-white">
               <div class="w-6/12">
                   <p>ABOUT</p>
                   <div class="text-7xl">Your cradit scores</div>
                   <div class="text-7xl">should be free</div>
                   <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maiores velit magni natus obcaecati, expedita blanditiis exercitationem sequi commodi quisquam eveniet!</p>
               </div>
               <div class="w-6/12">
                   <img class="w-10/12" :src="tym" alt="mister tym">
               </div>
           </div>
       </div>
   </div>
</template>

<script lang="ts">
import {defineComponent} from 'vue'
import tym from '../../assets/image/tym.png'

export default defineComponent({
    setup(){
        return{
            tym
        }
    }
})
</script>

<style scoped>
.bg-img{
    background-image: url('../../assets/image/background.jpg');
}
</style>