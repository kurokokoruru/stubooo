<template>
  <div>
    <Header />
    <div class="m-3">
      <Nuxt />
    </div>

  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Header from '@/components/Header.vue';
export default Vue.extend({
  components: {
    Header
  }
})
</script>
