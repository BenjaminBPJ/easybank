<template>
  <EasyBank />
</template>

<script>
import EasyBank from './components/Easybank.vue';

export default {
  name: 'App',
  components: {
    EasyBank
  }
}
</script>

<style>
@font-face{
  font-family: 'public';
  src: url(./assets/font/PublicSans-Regular.ttf);
}

:root{
  --font-color: hsl(233, 26%, 24%);
  --second-font-color: hsl(151, 30%, 32%);
  --third-font-color: hsl(233, 8%, 62%);
  --fourth-color: hsl(136, 65%, 51%);
  --fifth-color: hsl(192, 70%, 51%);
}

*, ::before, ::after{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body{
  font-family: 'public';
  font-size: 1.2em;
  color: var(--font-color);
  width: 1440px;
  margin: auto;
}

ul{
  display: flex;
  list-style: none;
  color: var(--third-font-color);
}

li{
  cursor: pointer;
}

p{
  color: var(--third-font-color);
}
</style>
