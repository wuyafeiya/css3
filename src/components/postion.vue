<template>
  <div>
    <h2 style="position: absolute; left: 100px; top: 150px">
      这是一个绝对定位了的标题
    </h2>
    <p>
      用绝对定位,一个元素可以放在页面上的任何位置。标题下面放置距离左边的页面100
      px和距离页面的顶部150 px的元素。
    </p>
    <h2>这是位于正常位置的标题</h2>
    <h2 class="pos_left">这个标题相对于其正常位置向左移动</h2>
    <h2 class="pos_right">这个标题相对于其正常位置向右移动</h2>
    <p>相对定位会按照元素的原始位置对该元素进行移动。</p>
    <p>样式 "left:-20px" 从元素的原始左侧位置减去 20 像素。</p>
    <p>样式 "left:20px" 向元素的原始左侧位置增加 20 像素。</p>
  </div>
</template>

<script>
export default {};
</script>

<style>
h2.pos_left {
  position: relative;
  left: -20px;
}

h2.pos_right {
  position: relative;
  left: 20px;
}
</style>