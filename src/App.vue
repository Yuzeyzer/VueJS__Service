<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@function vw($value, $base: 1920) {
  @return $value / $base * 100vw;
}

@function vh($value, $base: 800) {
  @return $value / $base * 100vh;
}

@function vmin($value, $base: 375) {
  @return $value / $base * 100vmin;
}
body {
  font-family: "Roboto", "Open Sans", system-ui, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c2c2c;
  background-color: #f6f7f8;
}
.container {
  width: vw(900);
  margin: vw(50) auto;
}
</style>
