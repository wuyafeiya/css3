<template>
  <div>
    <p>
      一个<img
        src="https://www.runoob.com/try/demo_source/logo.png"
        alt="w3cschool"
        width="270"
        height="50"
      />默认对齐的图像。
    </p>
    <p>
      一个<img
        class="top"
        src="https://www.runoob.com/try/demo_source/logo.png"
        alt="w3cschool"
        width="270"
        height="50"
      />
      text-top 对齐的图像。
    </p>
    <p>
      一个<img
        class="bottom"
        src="https://www.runoob.com/try/demo_source/logo.png"
        alt="w3cschool"
        width="270"
        height="50"
      />
      text-bottom 对齐的图像。
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style>
img.top {
  vertical-align: text-top;
}
img.bottom {
  vertical-align: text-bottom;
}
</style>