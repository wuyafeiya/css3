<template>
  <div>
    <p class="normal">This is a paragraph.</p>
    <p class="light">This is a paragraph.</p>
    <p class="thick">This is a paragraph.</p>
    <p class="thicker">This is a paragraph.</p>
  </div>
</template>

<script>
export default {};
</script>

<style>
p.normal {
  font-weight: normal;
}
p.light {
  font-weight: lighter;
}
p.thick {
  font-weight: bold;
}
p.thicker {
  font-weight: 900;
}
</style>