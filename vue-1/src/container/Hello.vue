<template>
  <div id="hello">
    <app-head></app-head>
    <div class="container">
      <!-- Example row of columns -->
      <div class="row">
        <div class="col-md-4">
          <h2>Head1</h2>
          <p>123123</p>
          <p>
            <a class="btn btn-secondary" href="#" role="button">ReadMe</a>
          </p>
        </div>

        <div class="col-md-4">
          <h2>Head1</h2>
          <p>123123</p>
          <p>
            <a class="btn btn-secondary" href="#" role="button">ReadMe</a>
          </p>
        </div>
        <div class="col-md-4">
          <h2>Head1</h2>
          <p>123123</p>
          <p>
            <a class="btn btn-secondary" href="#" role="button">ReadMe</a>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import head from '../components/head.vue';
  import main from '../components/main.vue';


  var list = [7, 8, 9];

  export default {
    components: {
      'app-head': head,
      'app-main': main,
    },
  }

</script>
