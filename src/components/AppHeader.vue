<script>
// import { ref } from 'vue'

// defineProps({
//   msg: String,
// })

// const count = ref(0)

</script>

<!-- HTML -->
<template>

  <header>

    <div class="container">

      <div>
        <img src="../../public/dc-logo.png" alt="logo">
      </div>


      <ul>
        <li>
          <a href="#">
            LINK
          </a>
        </li>

        <li>
          <a href="#">
            LINK
          </a>
        </li>

        <li>
          <a href="#">
            LINK
          </a>
        </li>

        <li>
          <a href="#">
            LINK
          </a>
        </li>

        <li>
          <a href="#">
            LINK
          </a>
        </li>

        <li>
          <a href="#">
            LINK
          </a>
        </li>

        <li>
          <a href="#">
            LINK
          </a>
        </li>

      </ul>
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
    border: black 1px solid;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }



  ul {
    display: flex;
    list-style: none;
  }

  li {
    font-size: 10px;
    padding: 5px;
  }



</style>
