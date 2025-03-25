<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import "@/variables/variables.scss";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

body {
  background-color: #f8f8f8;
  margin: 0;
  padding: 0;
}

p,
b,
a {
  font-size: $font-size-p-lg;
  line-height: $line-height-p-lg;
  letter-spacing: $letter-spacing;
  color: $color-text-dark;
  text-decoration: none;
  margin: 0;
  padding: 0;

  @include respond(tablet) {
    font-size: $font-size-p-sm;
    line-height: $line-height-p-sm;
  }
}
</style>
