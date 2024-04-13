<!-- an example footer for pages -->
<template>
    <footer
      v-if="$slidev.nav.currentLayout !== 'cover'"
      class="absolute bottom-0 left-0 right-0 p-2"
    >
      {{ $slidev.nav.currentPage }} / {{ $slidev.nav.total }}
      Jason M
    </footer>
    <div class="global-footer">
      © 2024 My Presentation. All rights reserved.
    </div>
  </template>

<style scoped>
.global-footer {
  display: flex;
  justify-content: center;
  padding: 12px;
  font-size: 14px;
  background-color: #f3f3f3; /* Light grey background */
  color: #333; /* Dark text color */
}
</style>