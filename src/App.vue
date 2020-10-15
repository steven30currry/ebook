<template>
  <div id="app">
    <span class="icon-back"></span>
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
document.addEventListener('DOMContentLoader', () => {
  const html = document.querySelector('html')
  html.style.fontSize = window.innerWidth / 10 + 'px'
})
</script>
<style>

</style>
