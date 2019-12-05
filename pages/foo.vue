<template>
  <div class="container">
    <nuxt-link to="/">index</nuxt-link>
    foo
  </div>
</template>
<script>
  export default {
    head: () => ({
      script: [{
        vmid : 'head-script',
        src  : '/head-script.js',
      }],
    }),
  }
</script>
