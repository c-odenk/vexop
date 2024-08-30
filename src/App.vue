<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
@import '@/variables/variables.scss';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

body {
  background-color: #F8F8F8;
  margin: 0;
  padding: 0;
}

/*
h1 {
  font-size: $font-size-h1-lg;
  line-height: $line-height-h1-lg;
  letter-spacing: $letter-spacing;
  text-transform: uppercase;
  margin: 0;
  padding: 0;

  @include respond(tablet) {
    font-size: $font-size-h1-sm;
    line-height: $line-height-p-sm;
  }
}
*/

p, b, a {
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
