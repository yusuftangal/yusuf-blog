<template>
  <div id="page" class="hfeed site">
    <Navbar />
  </div>
</template>

<script>
export default {

  components: {
    Navbar: () => import('@/components/Navbar'),
  },

  name: 'IndexPage'
}
</script>
