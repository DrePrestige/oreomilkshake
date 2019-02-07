<template>
  <header class="header">
    <div class="grid">
      <img alt="Vue logo" src="../assets/logo.png">kkkkkk
      <div>test1</div>
      <div>test2</div>
      <div>test3</div>
    </div>
  </header>
</template>

<script>
export default {
  name: "top"
};
</script>

<style scoped>
.header {
  background: aquamarine;
  /* grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); */

  /* grid-column-gap: 40px; */
}
.grid {
  display: grid;
  grid-template-columns: 3fr;
  /* grid-template-columns: 70px, 230px, 40px, 1000px, 150px, 40px, 150px, 70px; */
  grid-template-rows: 70px, 100px;
  grid-gap: 2em;
}
.grid div:nth-child(even) {
  background-color: blueviolet;
}
</style>
