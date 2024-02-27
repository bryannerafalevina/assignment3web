<template>
<div class="container">
  <div class="row">
    <div class="col">
      <h1> Enjoy Our</h1>
      <h1> Delicious Meal</h1>
    </div>
      <h4>tempor erat elitr rebum at clita.Diam dolor diam ipsum sit.Aliqu diam amet diam et
      eos. Clita erat ipsum et lorem et sit, sad stet lorem sit clita dui justo magna dolore erat amet</h4>
      <div>
        <router-link to="/book-a-table" custom v-slot="{ navigate }">
          <button @click="navigate" role="link">
            Book A Table
          </button>
        </router-link>
  </div>
  </div>
</div>
  </template>
  
  <script>
  export default {
    name: 'Home',
  };
  </script>

<style scoped>
.home {
  background-color: #f8f9fa;
  text-align: center;
}

.container {
  max-width: 800px;
  margin-top: 40px;
}

h1 {
  font-size: 2.5em;
  color:black;
}

p {
  font-size: 1.2em;
  color: #333;
}

</style>