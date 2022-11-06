<template>
  <div class="header">
    <div class="container">
      <div class="logo">Nour Vue</div>
      <nav>
        <router-link to="/" exact>Home</router-link>
        <router-link to="/blog" replace>Blog</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/help" replace>Help</router-link>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style lang="scss" scoped>
.header {
  background-color: #333;
  color: #fff;
  overflow: hidden;
  .logo {
    font-size: 24px;
    padding: 20px;
    float: left;
    width: 200px;
  }
  nav {
    padding: 30px;
    float: left;
    width: calc(100% - 200px);
    margin: 0%;
    a {
      padding: 20px;
      font-size: 18px;
      font-weight: bold;
      color: #fff;

      &.router-link-exact-active {
        color: #42b983;
      }
    }
  }
}
</style>
