<template>
  <div id="page" class="hfeed site">
    <Navbar />
    <div id="main" class="site-main">
      <div class="layout-medium">
        <NotFound />
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
export default {
  components: {
    Navbar: () => import("@/components/Navbar.vue"),
    Footer: () => import("@/components/Footer.vue"),
    NotFound: () => import("@/components/NotFound.vue"),
  },
};
</script>
