<template>
  <div>
    <p>
      这是一个标准行高的段落。<br />
      这是一个标准行高的段落。<br />
      大多数浏览器的默认行高约为110%至120%。<br />
    </p>

    <p class="small">
      这是一个更小行高的段落。<br />
      这是一个更小行高的段落。<br />
      这是一个更小行高的段落。<br />
      这是一个更小行高的段落。<br />
    </p>

    <p class="big">
      这是一个更大行高的段落。<br />
      这是一个更大行高的段落。<br />
      这是一个更大行高的段落。<br />
      这是一个更大行高的段落。<br />
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style >
p.small {
  line-height: 70%;
}
p.big {
  line-height: 200%;
}
</style>