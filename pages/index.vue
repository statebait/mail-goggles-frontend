<template>
  <div id="app" class="container">
    <h1 class="app-title">Mail Goggles</h1>
  </div>
</template>

<script>
export default {
  head: {
    title: "👓 Mail Goggles"
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Montserrat:800&display=swap");

body {
  background: linear-gradient(180deg, #3f2b96 0%, #5484ff 100%);
  height: 100vh;
  color: azure;
}

.app-title {
  padding-top: 30px;
  font-family: "Montserrat", sans-serif;
  color: azure;
  font-size: 60px;
  text-shadow: 2px 4px 3px rgba(0, 0, 0, 0.1);
}
</style>
