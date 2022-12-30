<template>
  <div id="page" class="hfeed site">
    <Navbar />
    <div id="main" class="site-main">
      <div class="layout-medium">
        <Hero />
        <BlogPost />
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
export default {
  components: {
    Navbar: () => import("@/components/Navbar.vue"),
    Hero: () => import("@/components/Hero.vue"),
    BlogPost: () => import("@/components/BlogPost.vue"),
    Footer: () => import("@/components/Footer.vue"),
  },
};
</script>
