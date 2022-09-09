<template>
  <div id="app">
    <el-button
      type="success"
      v-for="(item, index) in DataList"
      :key="index"
      @click="ChangeButton(item.value)"
      >{{ item.name }}</el-button
    >
    <component :is="componentTag"></component>
  </div>
</template>
<script>
import VBorder from "./components/VBorder";
import Lineheight from "./components/Line-height";
import Verticalalign from "./components/Vertical-align.vue";
import float from "./components/float.vue";
import Overflow from "./components/Overflow.vue";
import postion from "./components/postion.vue";
import fontsize from "./components/font-size.vue";
import fontweight from "./components/fontweight.vue";
import fontfamily from "./components/font-family.vue";
import fontstyle from "./components/font-style.vue";
import color from "./components/color.vue";
import background from "./components/background.vue";
import display from "./components/display.vue";
import opacity from "./components/opacity.vue";
export default {
  components: {
    VBorder,
    Lineheight,
    Verticalalign,
    float,
    Overflow,
    postion,
    fontsize,
    fontweight,
    fontfamily,
    fontstyle,
    color,
    background,
    display,
    opacity,
  },
  name: "App",
  data() {
    return {
      componentTag: "",
      DataList: [
        {
          name: "border",
          value: "VBorder",
        },
        {
          name: "Lineheight",
          value: "Lineheight",
        },
        {
          name: "Verticalalign",
          value: "Verticalalign",
        },
        {
          name: "float",
          value: "float",
        },
        {
          name: "Overflow",
          value: "Overflow",
        },
        {
          name: "postion",
          value: "postion",
        },
        {
          name: "fontsize",
          value: "fontsize",
        },
        {
          name: "fontweight",
          value: "fontweight",
        },
        {
          name: "fontfamily",
          value: "fontfamily",
        },
        {
          name: "fontstyle",
          value: "fontstyle",
        },
        {
          name: "color",
          value: "color",
        },
        {
          name: "background",
          value: "background",
        },
        {
          name: "display",
          value: "display",
        },
        {
          name: "opacity",
          value: "opacity",
        },
      ],
    };
  },
  methods: {
    ChangeButton(value) {
      this.componentTag = value;
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
