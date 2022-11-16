<template>
<div class="container">
  <div>
    <v-btn elevation="2" href="/">home</v-btn>
    <p class="text-5xl">Home</p>
    <h1 class="text-3xl font-bold underline">Hello world!</h1>

  </div>
</div>
</template>

<script>
export default {
  name: 'HomePage',
  layout: 'CoreLayout',


};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>