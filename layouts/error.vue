<template>
  <FourZeroFour v-if="error.statusCode === 404" />
</template>

<script>
export default {
  props: ["error"],
  components: {
    FourZeroFour: () => import("@/pages/FourZeroFour.vue"),
  },
};
</script>
