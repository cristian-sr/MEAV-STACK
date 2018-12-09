<template>
  <div id="app">
    <img src="./assets/logo.png">
    <p>
      <router-link :to="/">Go to Home</router-link>
      <router-link :to="/About">Go to About</router-link>
    </p>
    <router-view></router-view>
  </div>
</template>
<script>
export default {
};
</script>
