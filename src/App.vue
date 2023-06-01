<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue'


export default {
  components: {
    AppHeader,
    AppFooter
  }
}
</script>

<template>
  
  <AppHeader />
  <main>
    <div class="container">
      CONTENT GOES HERE
    </div>
    
  </main>
  <AppFooter />
</template>

<style lang="scss">

@use './styles/partials/variables.scss' as *;
@use './styles/general.scss' as *;


main {
  background-color: green;
  height: 100px;
  display: flex;
  justify-content: center;
  align-items: center;

  .container {
  margin: 0 auto;
  height: 50%;
  width: 80%;
  border: 1px solid red;
  text-align: center;
  
}
  
}



</style>
