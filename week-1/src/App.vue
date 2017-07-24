<template>
  <div id="app">
    <app-navbar />
    <app-head />
    <!-- <div class="container">
      <img src="./assets/logo.png">
      <router-link :to="{path: '/hello'}">Hello</router-link>
      <router-link :to="{name: 'c2f'}">CtoF</router-link>
      <router-view></router-view>
    </div> -->
    <app-main />
    <app-footer />
  </div>
</template>

<script>


import navbar from './components/navbar.vue';
import head from './components/head.vue';
import main from './components/main.vue';
import footer from './components/footer.vue';

export default {
  name: 'app',
  components: {
    'app-navbar': navbar,
    'app-head': head,
    'app-main': main,
    'app-footer': footer,
  }
}
</script>
