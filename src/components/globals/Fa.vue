<template>
  <i :class="`fa fa-${fa}`" aria-hidden="true" v-if="fa"></i>
  <i :class="`fas fa-${fas}`" aria-hidden="true" v-else></i>
</template>

<script>
export default {
  props: {
    fa: String,
    fas: String,
  },
  mounted() {},
};
</script>

<style scoped></style>
