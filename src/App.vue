<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>

  * {
    margin: 0;
    padding: 0;
    outline: 0;
    box-sizing: border-box;
  }

  html, body, #app {
    min-height: 100%;
  }

  body {
    background: #0747a6;
    -webkit-font-smoothing: antialiased !important;
  }

  body {
    font-size: 14px;
    font-family: Arial, Helvetica, sans-serif;
  }

  button {
    cursor: pointer;
  }

</style>
