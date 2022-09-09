<template>
  <div>
    <h3>display:inline</h3>
    <p style="display: inline">这两个段落生成内联盒子,和它的结果</p>
    <p style="display: inline">这两个元素之间没有距离。</p>

    <h3>display:none;</h3>
    <h1 style="margin-top: 50px">这是一个可见标题</h1>
    <h1 class="hidden">这是一个隐藏标题</h1>
    <p>注意, 实例中的隐藏标题不占用空间。</p>

    <h3>visibility:hidden</h3>
    <h1 style="margin-top: 50px">这是一个可见标题</h1>
    <h1 style="visibility: hidden">这是一个隐藏标题</h1>
    <p>注意, 实例中的隐藏标题仍然占用空间。</p>
  </div>
</template>

<script>
export default {};
</script>

<style>
h1.hidden {
  display: none;
}
h3 {
  margin-top: 20px;
}
</style>