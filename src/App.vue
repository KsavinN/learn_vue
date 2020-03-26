<template>
  <div id="app">
    <ButtonCounter />
  </div>
</template>

<script>
import ButtonCounter from "./ButtonCounter";

export default {
  name: "App",
  data: () => ({
    txt: "test"
  }),
  methods: {},
  components: {
    ButtonCounter
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
