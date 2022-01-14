<template>
  <main>
    <intro />
    <experience />
    <education />
  </main>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style lang="postcss" scoped>
.cap::before,
.idioma::before {
  @apply md:absolute mb-2;
  content: "";
  display: block;
  top: -4px;
  left: -36px;
  width: 24px;
  height: 24px;
}

.cap::before {
  background: url("~/static/cap.svg") no-repeat center center;
}

.idioma::before {
  background: url("~/static/idiomas.svg") no-repeat center center;
}
</style>