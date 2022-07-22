<template>
<div>
  <BaseHeader/>
  <BaseSecondHeader/>

  <main></main>
  <footer></footer>
</div>
</template>

<script>
import BaseSecondHeader from "./components/BaseSecondHeader.vue";
import BaseHeader from "./components/BaseHeader.vue";
export default {
  name:" vue-dc-comics",
  components: {
    BaseHeader,
    BaseSecondHeader
  }
}
</script>

<style>
/*Generics*/
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  font-family: 'Raleway', sans-serif;
}

img{
  max-width: 100%;
  }

  ul{
    list-style-type: none;
  }

  a{
    text-decoration: none;
  }

  /*Utils*/
  .container{
    margin: 0 auto;
    max-width: 1200px;
  }
</style>