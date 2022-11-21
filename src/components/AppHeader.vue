<template>
  <div>
<!--    output-->
    <button v-show="loggedIn">Logout</button>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
  data() {
    return {
      loggedIn: false // input
    }
  }
}
</script>

<style scoped>

</style>