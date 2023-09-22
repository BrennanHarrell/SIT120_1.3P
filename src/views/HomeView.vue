<template>
  <div class="nav">
  </div>
  <body class="homeview">

    <div>
      <h1 class="h1home">Hi, my name is Brennan Harrell,
        I design and develop reactive websites
        <br>
        <router-link :to="{ path: 'about' }"><button class="button">Click me to learn more</button></router-link>

        

      </h1>
    </div>
    
  </body>
  
</template>

<script>


export default {
  name: 'HomeView',
  
}

</script>

<style>
@import "/public/home.css";
</style>
