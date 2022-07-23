<template>
  <div class="footer">
    <div class="container">
        <div>
            <button>SIGN-UP NOW!</button>
        </div>
        <div class="contacts">
            <h2>FOLLOW US</h2>
            <img src="../assets/img/footer-facebook.png" alt="facebook">
            <img src="../assets/img/footer-twitter.png" alt="facebook">
            <img src="../assets/img/footer-youtube.png" alt="facebook">
            <img src="../assets/img/footer-pinterest.png" alt="facebook">
            <img src="../assets/img/footer-periscope.png" alt="facebook">
        </div>
    </div>
  </div>
</template>

<script>
   export default{
       name: "BaseFooter",
   }
</script>

<style scoped>
   .footer{
       background-color: #303030;
       height: 124px;
    }

    .container{
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    button{
        background-color: #303030;
        border-color: #0282F9;
        color: white;
        padding: 10px;
    }

   .contacts {
    display:flex
   }

   h2{
    color: #0282F9;
    padding: 0 10px;
   }

   img{
    padding: 0 10px;
   }
</style>