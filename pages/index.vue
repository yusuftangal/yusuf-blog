<template>
  <div id="page" class="hfeed site">
    <Navbar />
    <div id="main" class="site-main">
      <div class="layout-medium"> 
        <div id="primary" class="content-area">
          <Hero />
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {

  components: {
    Navbar: () => import("@/components/Navbar.vue"),
    Hero: () => import("@/components/Hero.vue"),
},

  name: 'IndexPage'
}
</script>
