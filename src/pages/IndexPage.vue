<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >
    <banner></banner>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import Banner from '../pages/Banner.vue';

export default defineComponent({
  components: { Banner },
  name: 'IndexPage'
})
</script>
