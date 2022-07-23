<template>
  <header>
    <div class="container">
      <figure>
       <a href="#">
        <img src="../assets/img/dc-logo.png" alt="dc-logo">
       </a>
    </figure>
    <nav>
      <ul>
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </nav>
    </div>
  </header>
</template>

<script>
   export default{
       name: "BaseHeader",
   }
</script>

<style scoped>

  .container{
    height: 100px;
    display:flex;
    justify-content: space-between;
  }
  a{
    color: black;
    font-size: 12px;
    font-weight: bold;
  }

  li{
    margin: 5px;
  }

  ul{
    height: 100%;
    display: flex;
    align-items: center;
  }
</style>