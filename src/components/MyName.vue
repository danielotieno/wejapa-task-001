<template>
  <div>
    <h1 class="name">{{ name }}</h1>
  </div>
</template>

<script>
export default {
  name: 'MyName',
  props: {
    name: String,
  },
};
</script>

<style scoped>
.name {
  font-weight: bolder;
  background-image: linear-gradient(120deg, #f093fb 0%, #f5576c 100%);
  color: #ffffff;
}
</style>
