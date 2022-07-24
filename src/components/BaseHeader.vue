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
        <li v-for="link in links" :key="link.text">
        <a :href="link.url"
        >{{link.text}}</a>
        </li>
      </ul>
    </nav>
    </div>
  </header>
</template>

<script>
   export default{
       name: "BaseHeader",
       data(){
        return{
          links: [
            {url: '#', text:'CHARACTERS'},
            {url: '#', text:'COMICS'},
            {url: '#', text:'MOVIES'},
            {url: '#', text:'TV'},
            {url: '#', text:'GAMES'},
            {url: '#', text:'COLLETTIBLES'},
            {url: '#', text:'VIDEOS'},
            {url: '#', text:'FANS'},
            {url: '#', text:'NEWS'},
            {url: '#', text:'SHOP'},
          ]
        }
       }
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

  a:hover{
    color: white;
  }

  li:hover{
    background-color: #0282F9;
  }

  ul{
    height: 100%;
    display: flex;
    align-items: center;
  }
</style>