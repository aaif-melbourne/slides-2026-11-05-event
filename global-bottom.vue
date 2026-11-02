<template>
  <footer
    v-if="![9, $slidev.nav.total].includes($slidev.nav.currentPage)"
    class="common-footer"
  >
    <span>
      Agentic AI Melbourne ·
      5 November 2026 ·
      <a href="https://aimelb.org">aimelb.org</a>
    </span>
    <span class="footer-meta">
      {{ $slidev.nav.currentPage }} of {{ $slidev.nav.total }}
    </span>
  </footer>
</template>
