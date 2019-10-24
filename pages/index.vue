<template>
  <div class="app">
    <img src="/logo.png" alt="logo" />
  </div>
</template>

<style>
*,
*:before,
*:after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

html,
body {
  height: 100%;
}

.app {
  height: 100vh;
  width: 100vw;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #393e46;
}

img {
  height: 280px;
  width: 280px;
}
</style>
