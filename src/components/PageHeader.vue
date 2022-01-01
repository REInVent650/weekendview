<template>
  <!--Import Google Icon Font-->
  <link
    href="https://fonts.googleapis.com/icon?family=Material+Icons"
    rel="stylesheet"
  />
  <!--Import materialize.css-->
  <link
    type="text/css"
    rel="stylesheet"
    href="css/materialize.min.css"
    media="screen,projection"
  />
  <nav class="white z-depth-0">
    <div class="container">
      <div class="header">
        <div>
          <img src="../assets/logo.png" alt="logo" />
        </div>
        <div>
          <h1>weekendview</h1>
          <em>Travel somewhere new, learn a programming language</em>
        </div>
      </div>
      <ul id="nav-mobile" class="right hide-on-small-and-down"></ul>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
.header {
  padding: 10px;
  text-align: left;
  margin: 0px;
}

img {
  max-height: 100px;
  display: block;
}

.brand {
  background: #cbb09c !important;
}
.brand-text {
  color: #cbb09c !important;
}
form {
  max-width: 460px;
  margin: 20px auto;
  padding: 20px;
}
.pizza {
  width: 100px;
  margin: 40px auto -30px;
  display: block;
  position: relative;
  top: -30px;
}
</style>
