<template>
    <div class="container">
       <div class="otasi">
        <h1 class="nex_1">Features for a better experience</h1>
         <div class="flex">
            <div class="parent">
             <img src="../assets/images/icon.svg" alt="logo">
             <div class="next">
                 <h1>Video mesaging</h1>
                 <p>This software is very easy for you to <br>
                  manage You can use it as you wish
                </p>
             </div>
        </div>

        <div class="parent">
             <img src="../assets/images/22.svg" alt="logo">
             <div class="next">
                 <h1>Save your time</h1>
                 <p>This software is very easy for you to <br>
                  manage You can use it as you wish
                </p>
             </div>
        </div>

        <div class="parent">
             <img src="../assets/images/33.svg" alt="logo">
             <div class="next">
                 <h1>Keep safe & private</h1>
                 <p>This software is very easy for you to <br>
                  manage You can use it as you wish
                </p>
             </div>
        </div>
         </div>
       </div>
     </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .nex_1{
        text-align: center;
        font-size: 50px;
    }
    img{
        border-radius: 50%;
        height: 70px;
        width: 70px;
    }
    .parent{
        display: flex;
        justify-content: space-around;
    }
    .parent h1{
        font-size: 30px;
    }
    .otasi{
        margin-top: 50px;
    }
    .otasi .parent{
        margin-top: 30px;
    }
    .flex{
        display: flex;
        gap: 400px;
        
    }
</style>