<template>
  <div class="navbar">
    <nav>
      <h1>
        <router-link :to="{ name: 'SignUpTo' }">Enoca</router-link>
      </h1>
      <div class="links">
          <router-link class="tags" :to="{ name: 'SignUpTo' }">Signup</router-link>
          <router-link class="tags" :to="{ name: 'LoginTo' }">Login</router-link>
        </div>
    </nav>
  </div>
</template>

<script>

export default {
  setup() {


    return { };
  },
};
</script>

<style scoped>
.navbar {
  padding: 16px 10px;
  margin-bottom: 60px;
  background: white;
}
nav {
  display: flex;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
}
nav img {
  max-height: 60px;
}
nav h1 {
  margin-left: 20px;
}
nav .links {
  margin-left: auto;
}
nav .links a,
button {
  margin-left: 16px;
  font-size: 14px;
}
span {
    font-size: 14px;
    display: inline-block;
    margin-left: 16px;
    padding-left: 16px;
    border-left: 1px solid #eee;

}
</style>
