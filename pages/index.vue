<template>
<div>
  <h1>Fontdue nuxt example</h1>

  <div><NuxtLink to="/test">Test link</NuxtLink></div>

  <fontdue-buy-button collection-slug="ibm-plex"></fontdue-buy-button>

  <fontdue-store-modal></fontdue-store-modal>
</div>
</template>

<script lang="ts">
  import Vue from 'vue'

export default Vue.extend({})
</script>
