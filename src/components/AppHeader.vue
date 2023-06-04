<script>
// import { ref } from 'vue'

// defineProps({
//   msg: String,
// })

// const count = ref(0)

export default {
  name: "AppHeader",
  // qua inserisco props e sposto i dati nel componente padre, qui nel componente figlio li lascio commentati per ricordarci da dove siamo partiti
  props: {
    links: Array
  }
  // data() {
  //   return {
  //     links: [ 
  //       {
  //         text:"CHARACHTERS",
  //         url:"#",
  //         current: false
  //     },
  //     {
  //         text:"COMICS",
  //         url:"#",
  //         current: true
  //     },
  //     {
  //         text:"MOVIES",
  //         url:"#",
  //         current: false
  //     },
  //     {
  //         text:"TV",
  //         url:"#",
  //         current: false
  //     },
  //     {
  //         text:"GAMES",
  //         url:"#",
  //         current: false
  //     },
  //     {
  //         text:"COLLECTIBLES",
  //         url:"#",
  //         current: false
  //     },
  //     {
  //         text:"VIDEOS",
  //         url:"#",
  //         current: false
  //     },
  //     {
  //         text:"FANS",
  //         url:"#",
  //         current: false
  //     },
  //     {
  //         text:"NEWS",
  //         url:"#",
  //         current: false
  //     },
  //     {
  //         text:"SHOP",
  //         url:"#",
  //         current: false
  //     },

  //     ]
  //   }
  // }
  

}

</script>

<!-- HTML -->
<template>

  <header>

    <div class="container">

      <div class="logo-div">
        <img src="../../public/dc-logo.png" alt="logo">
      </div>

      <nav>
        <ul>

          <li v-for="(link,index) in links"  :key="index">

            <a href="#" :class="link.current === true ? 'active' : '' " >
              {{ link.text }}
            </a>
            
          </li>

        </ul>

      </nav>
        

    </div>

  </header>

</template>

<!-- STILE -->

<style scoped lang="scss">

header {
  background-color: white;
}

  .container {
    height: 100px;
    width: 80%;
    margin: auto;
    // border: black 1px solid;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }



  ul {
    display: flex;
    list-style: none;
  }

  li {
    font-weight: 600;
    font-size: 14px;
    padding: 5px;

    a{
      color: black;


    }
  }

  .active {
    color: #0282f9;
    border: #0282f9 1px solid;
    padding: 5px;
  }

  img {
    width: 70px;
  }



</style>
