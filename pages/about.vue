<template>
    <div id="page" class="hfeed site">
        <Navbar />
        <div id="main" class="site-main">
            <AboutHero />
            <AboutMe />
        </div>
        <Footer />
    </div>
</template>

<script>
export default {
    
    
  components: {
    Navbar: () => import("@/components/Navbar.vue"),
    AboutHero: () => import("@/components/AboutHero.vue"),
    AboutMe: () => import("@/components/AboutMe.vue"),
    Footer: () => import("@/components/Footer.vue"), 
},
}
</script>