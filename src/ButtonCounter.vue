<template>
  <button v-on:click="count++">You clicked me {{ count }} times.</button>
</template>

<script>
export default {
  name: "ButtonCounter",
  data: function() {
    return {
      count: 0
    };
  }
};
</script>

<style>
#app {
  text-align: left;
  color: cadetblue;
}
h4 {
  font-size: 16px;
}
</style>
