<template>
  <div class="font-sans text-black antialiased">
    <navigation></navigation>
    <nuxt />
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import axios from 'axios'
axios.defaults.headers.common['user-key'] = '41172b6051b977eb96d2f9170409e350'
axios.defaults.headers.common['X-Requested-With'] = 'XMLHttpRequest'
export default {
  components: {
    Navigation
  }
}
</script>
