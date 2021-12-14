<template>
   <div class="w-full relative">
       <Menu />
       <Banner />
       <InfoCard />
       <CraDitCard />
       <FiService />
       <Sponsor />
       <Safety />

       <Footer />
   </div>
</template>

<script setup lang="ts">
import Banner from '../components/home/Herobanner.vue'
import Menu from '../components/layouts/Menu.vue'
import InfoCard from '../components/home/infocard.vue'
import CraDitCard from '../components/home/credit.vue'
import FiService from '../components/home/financial_service.vue'
import Sponsor from '../components/home/sponsor.vue'
import Safety from '../components/home/safety.vue'

import Footer from '../components/layouts/footer.vue'
</script>

<style>

</style>