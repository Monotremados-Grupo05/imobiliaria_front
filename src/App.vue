<template>
  <div style="margin-top: 100px;">
    <router-view/>
  </div>
</template>

<style lang="scss">

*{
  background-color: #bebebe;
}

// Variable overrides first
$primary: #900;
$enable-shadows: true;
$prefix: "mo-";

// Then import Bootstrap
@import "../node_modules/bootstrap/scss/bootstrap";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #0080ff;
}

</style>
