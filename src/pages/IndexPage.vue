<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >
  <Banner></Banner>
  <!-- <exampleComVue></exampleComVue> -->
  </q-page>
</template>

<script>
import exampleComVue from 'src/components/exampleCom.vue'
import { defineComponent } from 'vue'
import Banner from "./Banner.vue"
export default defineComponent({
  components: {Banner},
  name: 'IndexPage'
})
</script>
