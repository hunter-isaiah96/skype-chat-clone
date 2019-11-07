<template>
  <div id="app">
    <SideBar class="sidebar"></SideBar>
    <ChatWindow></ChatWindow>
  </div>
</template>

<script>
import SideBar from './components/SideBar.vue'
import ChatWindow from './components/ChatWindow.vue'

export default {
  name: 'app',
  components: {
    SideBar,
    ChatWindow
  }
}
</script>

<style lang="scss">
  #app {
    width: 100vw;
    height: 100vh;
    display: flex;
  }
  .sidebar {
    height: 100vh;
    flex: 0.3;
    background-color: #3F429B;
  }
</style>
