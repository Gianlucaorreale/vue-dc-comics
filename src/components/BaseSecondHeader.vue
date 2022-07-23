<template>
   <div class="second-header">
     <div class="container">
        <h1>Content goes here</h1>
     </div>
   </div>
</template>

<script>
   export default{
       name: "BaseSecondHeader",
   }
</script>

<style scoped>

    .second-header{
      height: 100px;  
      background-color: black;
    }

    .container{
        height: 100%;
        display: flex;
        align-items: center;
    }

    h1{
      color: white;
    }
</style>