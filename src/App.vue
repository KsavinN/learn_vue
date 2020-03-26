<template>
  <div id="app">
    <button-counter></button-counter>
  </div>
</template>

<script>
import Vue from "vue";

Vue.component("button-counter", {
  data: function() {
    return {
      count: 0
    };
  },
  template:
    '<button v-on:click="count++">You clicked me {{ count }} times.</button>'
});

export default {
  name: "App",
  data: () => ({
    txt: "test"
  }),
  methods: {}
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
