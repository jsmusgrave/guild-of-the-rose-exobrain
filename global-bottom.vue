<!-- an example footer for pages -->
<template>
    <footer
      v-if="$slidev.nav.currentLayout !== 'cover'"
      class="absolute bottom-0 left-0 right-0 "
    >
      <span class="footer-left absolute bottom-0 right-0 ">
      {{ $slidev.nav.currentPage }} / {{ $slidev.nav.total }}
      </span>
      <div class="footer-center">
        guildoftherose.org
      </div>
      <div class="footer-right absolute bottom-0 ">
        {{ $slidev.configs.author }}
      </div>
    </footer>
  </template>

<style scoped>
.footer {
  /* display: flex; */
  /* justify-content: space-between; */
  /* align-items: center; */
  /* font-size: 14px; */
  /* background-color: #fafafa; */
  color: #333;
}
.footer-left, .footer-center, .footer-right {
  flex-grow: 1 0 auto;
  flex-shrink: 0;
  flex-basis: auto;
  text-align: center;
  color: grey;
  padding: 10px;
}
.footer-left {
  text-align: left;
  margin-left: 0.75rem;
}
.footer-right {
  text-align: right;
}
</style>