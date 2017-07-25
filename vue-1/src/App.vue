<template>
  <div id="app">
    <app-navbar />
    <router-view></router-view>
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
    'app-footer': footer,
  }
}
</script>
