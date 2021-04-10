<template>
<!--   <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>-->
  <router-view />

  <h1 @click="toggleModal">header 1 </h1>
  <div v-if="showModal">
    <Modal :header="header" :theme="theme" @close="toggleModal"> 
      <h6>form</h6>
      <p>data</p>
    </Modal>
  </div>
</template>

<script>
import Modal from "./components/Modal.vue";

export default {
  name: "App",
  components: { Modal },
  data() {
    return {
      title: "weekendview",
      header: "heading",
      theme: "sale",
      showModal: false,
    }
  },
  methods: {
    toggleModal() {
      this.showModal = !this.showModal;
    }
  }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
