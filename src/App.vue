<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
body,
html {
  background: #222;
}
#app {
  //top level element
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  max-width: 325px;
  font-size: 1.2rem;
  padding: 15px;
  margin: 0 auto; //center horizontially
  text-align: center;
  height: 400px;
}
.notes {
  margin-bottom: 20px;
}
.art {
  height: 16rem;
}
.wrapper {
  background-color: #efe;
  padding: 20px;
  border-radius: 10px;
}
.content {
  ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
  }
  li {
    display: inline;
    img {
      height: 30px;
      margin: 10px;
    }
  }
}
</style>
