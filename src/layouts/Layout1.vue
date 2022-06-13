<template>
<div class="h-screen flex flex-col">

  <!-- HEADER -->
  <div class="">
    <LargeHeader :bgColor="'bg-blue-600'" :textColor="'text-white'" />
  </div>

  <!-- VIEW / CONTENT: can be changed-->
  <div class="my-4 grow">
    <Index />
  </div>

  <!-- FOOTER -->
  <div class="justify-self-end">
    <Footer :bgColor="'bg-gray-200'" :textColor="'text-black'" />
  </div>
</div>

</template>

<script>
import LargeHeader from '../components/LargeHeader.vue'
import Footer from '../components/Footer.vue'
import Index from '../views/Index.vue'

export default {
    components: {
      LargeHeader, Footer, Index
    }
}
</script>

<style>

</style>