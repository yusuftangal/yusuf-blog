<template>
  <div id="page" class="hfeed site">
    <Navbar />
    <div id="main" class="site-main">
      <div class="layout-medium">
        <ContactMe />
      </div>
    </div>
    <Footer />
  </div>
</template>
<script>
import ContactMe from '../components/ContactMe.vue';


export default {
  components: {
    Navbar: () => import("@/components/Navbar.vue"),
    Footer: () => import("@/components/Footer.vue"),
    ContactMe: () => import("@/components/ContactMe.vue"),
},
};
</script>