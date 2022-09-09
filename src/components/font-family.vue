<template>
  <div>
    <h1>CSS font-family</h1>
    <p class="serif">这一段的字体是 Times New Roman</p>
    <p class="sansserif">这一段的字体是 Arial.</p>
  </div>
</template>

<script>
export default {};
</script>

<style>
p.serif {
  font-family: "Times New Roman", Times, serif;
}
p.sansserif {
  font-family: Arial, Helvetica, sans-serif;
}
</style>