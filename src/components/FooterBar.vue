<template>
  <footer class="footer">
    Copyright © {{ thisYear }} | Powered by
    <a
      href="https://github.com/verdipratama/ekarya-blog"
      rel="noopener"
      target="_blank">ekarya-blog</a>
  </footer>
</template>

<script>
  export default {
    data () {
      return {
        thisYear: new Date().getFullYear()
      }
    }
  }
</script>
