<template>
  <div id="app">
    <section class="menu">
      <img class="about" src="images/about.png" alt="Pinewood" sizes="" srcset="">
    </section>
    <div class="content">
      <transition>
        <keep-alive>
      <router-view></router-view>
        </keep-alive>
    </transition> 
    </div>
  </div>
</template>

<script>

export default {
  data: function() {
      return {
        
      }
  }
  
}
</script>

<style>
  @import './assets/css/base.css';
  @import './assets/css/mixin.css';
  @import './assets/css/menu.css';
</style>
