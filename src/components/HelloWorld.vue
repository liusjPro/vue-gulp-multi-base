<template>
  <p>{{ msg }}</p>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
};
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
</style>
