<template>
  <div id="app">

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
</style>
