<template>
  <div id="app">
    <img class="logo" alt="Farm logo" src="./assets/images/farm.png" />
    <h1>HelloFarm, your trusty Farm Manager</h1>
    <router-view class="content" />
  </div>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  padding: 40px 20px;
  max-width: 960px;
  margin: 0 auto;
}

.logo {
  display: block;
  width: 120px;
  margin: 0 auto;
}

h1 {
  text-align: center;
}

.content {
  margin-top: 40px;
}
</style>
