<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Index</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
  * {
    padding: 0;
    margin: 0;
  }
  a {
    text-decoration: none;
  }
  ul, li {
    list-style: none;
  }
</style>
