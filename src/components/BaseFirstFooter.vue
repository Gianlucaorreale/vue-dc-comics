<template>
  <div class="main">
     <div class="jumbo">
         <div class="container">
           <div class="list-container">
              <div class="first-col">
                    <ul>
                      <li><a href="#"><h2>DC COMICS</h2></a></li>
                      <li v-for="comic in comics" :key="comic.text" >
                      <a :href="comic.url">
                      {{comic.text}}</a></li>
                    </ul>
                   <ul>
                      <li><a href="#"><h2>SHOP</h2></a></li>
                      <li v-for="shop in shops" :key="shop.text">
                      <a :href="shop.url">
                      {{shop.text}}</a></li>
                   </ul>
              </div>
                <ul>
                     <li><a href="#"><h2>SITES</h2></a></li>
                     <li v-for="site in sites" :key="site.text">
                     <a :href="site.url">
                     {{site.text}}</a></li>
                </ul>
              
              <ul>
                 <li><a href="#"><h2>DC</h2></a></li>
                 <li v-for="term in terms" :key="term.text">
                 <a :href="term.url">
                 {{term.text}}</a></li>
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
       data(){
        return{
          comics:[
            {url: '#', text:'Characters'},
            {url: '#', text:'Comics'},
            {url: '#', text:'Movies'},
            {url: '#', text:'TV'},
            {url: '#', text:'Games'},
            {url: '#', text:'Video'},
            {url: '#', text:'News'},
          ],
          shops:[
            {url:'#', text:'Shop DC'},
            {url:'#', text:'Shop DC collectible'}
          ],
          sites:[
            {url:'#', text:'DC'},
            {url:'#', text:'MAD magazine'},
            {url:'#', text:'DC kids'},
            {url:'#', text:'DC universe'},
            {url:'#', text:'DC Power Visa'},
          ],
          terms:[
            {url:'#', text:'terms of use'},
            {url:'#', text:'Privacy Policy(New)'},
            {url:'#', text:'Ad Choises'},
            {url:'#', text:'Advertising'},
            {url:'#', text:'Jobs'},
            {url:'#', text:'Subscriptions'},
            {url:'#', text:'Talent Workshops'},
            {url:'#', text:'CPSC Certificates'},
            {url:'#', text:'Ratings'},
            {url:'#', text:'Shop Help'},
            {url:'#', text:'Contact Us'},
          ],
          image:[
            {url:'../assets/img/dc-logo-bg.png'}
            ]
        }
       }
   }

</script>

<style scoped>
  .jumbo{
    
    background-image: url(../assets/img/footer-bg.jpg);
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

h2{
  color: white;
}

a{
 color: lightgray;   
}


</style>