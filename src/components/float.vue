<template>
  <div>
    <h1>右侧浮动</h1>
    <p>
      在下面的段落中，我们添加了一个
      <b>float:right</b> 的图片。导致图片将会浮动在段落的右边。
    </p>
    <p>
      <img
        src="https://www.runoob.com/try/demo_source/logocss.gif"
        width="95"
        height="84"
        style="float: right"
      />
      这是一些文本。这是一些文本。这是一些文本。
      这是一些文本。这是一些文本。这是一些文本。
      这是一些文本。这是一些文本。这是一些文本。
      这是一些文本。这是一些文本。这是一些文本。
      这是一些文本。这是一些文本。这是一些文本。
      这是一些文本。这是一些文本。这是一些文本。
      这是一些文本。这是一些文本。这是一些文本。
      这是一些文本。这是一些文本。这是一些文本。
      这是一些文本。这是一些文本。这是一些文本。
      这是一些文本。这是一些文本。这是一些文本。
    </p>
    <h1>段落的首字母浮动于左侧</h1>
    <div>
      <p>
        <span
          style="
            float: left;
            width: 1.2em;
            font-size: 400%;
            font-family: algerian, courier;
            line-height: 80%;
          "
          >这</span
        >是一些文本。 这是一些文本。这是一些文本。
        这是一些文本。这是一些文本。这是一些文本。
        这是一些文本。这是一些文本。这是一些文本。
        这是一些文本。这是一些文本。这是一些文本。
        这是一些文本。这是一些文本。这是一些文本。
        这是一些文本。这是一些文本。这是一些文本。
        这是一些文本。这是一些文本。这是一些文本。
      </p>

      <p>
        在上面的段落中, 第一个字嵌入在span 元素中。 这个 span
        元素的宽度是当前字体大小的1.2倍。 这个 span
        元素是当前字体的400%(相当大)， line-height 为80%。
        文字的字体为"Algerian"。
      </p>
    </div>
    <h1>创建一个水平菜单</h1>
    <ul class="Vul">
      <li><a href="#">Link one</a></li>
      <li><a href="#">Link two</a></li>
      <li><a href="#">Link three</a></li>
      <li><a href="#">Link four</a></li>
    </ul>

    <p>
      上面的示例中,我们让ul元素和元素浮动。
      li元素将显示为内联元素(没有换行符的元素之前或之后)。这迫使列表为一行。
      ul元素的宽度的100%,每一个超链接列表的宽度6 em(当前字体大小的6倍)。
      我们添加一些颜色和边界使其更高档。
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style>
.Vul {
  float: left;
  width: 100%;
  padding: 0;
  margin: 0;
  list-style-type: none;
}
a {
  float: left;
  width: 6em;
  text-decoration: none;
  color: white;
  background-color: purple;
  padding: 0.2em 0.6em;
  border-right: 1px solid white;
}
a:hover {
  background-color: #ff3300;
}
li {
  display: inline;
}
h1 {
  margin-top: 100px;
}
</style>