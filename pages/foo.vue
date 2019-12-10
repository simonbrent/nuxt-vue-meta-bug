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
        hid  : 'head-script',
        src  : '/head-script.js',
        once : true,
      }],
      link: [{
        hid  : 'head-style',
        rel  : 'stylesheet',
        href : '/head-style.css',
        once : true,
      }],
    }),
  }
</script>
