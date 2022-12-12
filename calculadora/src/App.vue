<template>
  <div id="app">
    <h1>Olá Vue</h1>
  </div>
</template>

<script>
export default {

}
</script>

<style>
@font-face{
    font-family: "RobotoMono";
    src: url("./fonts/RobotoMono-VariableFont_wght.ttf");
}
* {
  font-family: "RobotoMono",monospace;
}
body {
  margin:0;
}
#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;

  color:rgb(8, 8, 8);
  background-color: bisque;

}
</style>