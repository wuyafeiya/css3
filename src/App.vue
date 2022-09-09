<template>
  <div id="app">
    <el-button type="primary" @click="ChangeButton(1)"
      >border 边框属性</el-button
    >
    <el-button type="primary">line-height</el-button>
    <component :is="componentTag"></component>
  </div>
</template>
<script>
import VBorder from "./components/VBorder";
export default {
  components: { VBorder },
  name: "App",
  data() {
    return {
      componentTag: "",
    };
  },
  methods: {
    ChangeButton(value) {
      this.componentTag = "VBorder";
      // console.log(value);
    },
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
