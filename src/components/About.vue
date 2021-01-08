<template>
    <section class="about" id="about">
        <div class="left">
            <img src="../assets/logo.png" alt="Vue logo">
        </div>
        <div class="right">
             <h3>{{msg}}</h3>
        </div>
    </section>
</template>

<script>
export default {
    name:'About',
    data(){
        return{
            "msg":"Vue is awesome",
        }
    }
}
</script>

<style >
    .about{
        min-height: 100vh;
        display: flex;
        justify-content: space-between;
        background:repeating-linear-gradient(24deg,black, rgb(87, 194, 105));
    }
    .left{
        width: 40%;
    }
    .left img{
        margin-top: 100px;
        width: 100%;
        height:auto;
    }
    .right{
        width: 60%;
        display: flex;
        padding:20px;
        justify-content: center;
        align-items: center;
        font-size: 3em;
        color:white;
          
    }
    @media screen and (max-width: 600px){
        .about{
            display: block;
        }
    }   
</style>