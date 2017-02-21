<template>
  <div id="app">
    <div class="img-container">
        <img src="./assets/logo.png">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/Plus_symbol.svg/1000px-Plus_symbol.svg.png">
        <img src="https://app.shippable.com/mktg/images/logos/github-square.svg">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4d/Equal_symbol.svg/1000px-Equal_symbol.svg.png">
        <img src="https://railsgirlssummerofcode.org/img/blog/2016/l1ghtsab3r-partyparrot.gif">
    </div>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.img-container{
  display: flex;
  justify-content: center;
  align-items: center;
  height:20rem;
  img{
    height:100%;
  }
}

</style>
