<template>
  <div id="app">
    <MyName name="Daniel Otieno" />
  </div>
</template>

<script>
import MyName from './components/MyName';

export default {
  name: 'App',
  components: {
    MyName,
  },
};
</script>

<style>
#app {
  text-align: center;
  margin: 4% auto;
}
</style>
