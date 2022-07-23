<template>
  <div class="main">
     <div class="jumbo">
         <div class="container">
           <div class="list-container">
              <div class="first-col">
                    <ul>
                      <li><a href="#"><h2>DC COMICS</h2></a></li>
                      <li><a href="#">characters</a></li>
                      <li><a href="#">comics</a></li>
                      <li><a href="#">movies</a></li>
                      <li><a href="#">TV</a></li>
                      <li><a href="#">games</a></li>
                      <li><a href="#">videos</a></li>
                      <li><a href="#">news</a></li>
                   </ul>
                   <ul>
                      <li><a href="#"><h2>SHOP</h2></a></li>
                      <li><a href="#">shop DC</a></li>
                      <li><a href="#">shop DC collectible</a></li>
                   </ul>
              </div>
              <ul>
                     <li><a href="#"><h2>SITES</h2></a></li>
                     <li><a href="#">DC</a></li>
                     <li><a href="#">MAD magazine</a></li>
                     <li><a href="#">DC kids</a></li>
                     <li><a href="#">DC universe</a></li>
                     <li><a href="#">DC power visa</a></li>
              </ul>
              
              <ul>
                 <li><a href="#"><h2>DC</h2></a></li>
                 <li><a href="#">terms of use</a></li>
                 <li><a href="#">privacy policy (new)</a></li>
                 <li><a href="#">Ad choises</a></li>
                 <li><a href="#">adevertising</a></li>
                 <li><a href="#">jobs</a></li>
                 <li><a href="#">subscriptions</a></li>
                 <li><a href="#">talent workshops</a></li>
                 <li><a href="#">CPSC certificates</a></li>
                 <li><a href="#">ratings</a></li>
                 <li><a href="#">shop help</a></li>
                 <li><a href="#">contact us</a></li>
              </ul>
          </div>
          <div class="dc">
              <img class="dc-logo-bg" src="../assets/img/dc-logo-bg.png" alt="dc-logo-bg">
          </div>
        </div>
     </div>
  </div>
</template>

<script>
   export default{
       name: "BaseMain",
   }
</script>

<style scoped>
  .jumbo{
    
    background-image: url(../assets/img/jumbotron.jpg);
    background-size: cover;
    
}

.list-container{
  display: flex;
}

.dc-logo-bg{
  height: 425px;
}

.container{
    display: flex;
    justify-content: space-between;
}

ul{
    padding: 20px;
}

a{
 color: black;   
 text-shadow: 2px 2px white;  
}


</style>