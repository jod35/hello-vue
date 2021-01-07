<template>
   <div class="card">
       <h3>Good Work</h3>
       <p class="card-text">
           Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat, incidunt.
       </p>
       <button class="mybtn">Get Started</button>
   </div>
</template>

<script>
export default {
    name:'Card'
}
</script>

<style >
    .card{
        width:95%;
        background-color: rgba(30, 143, 255, 0.356);
        color: white;
        height: 300px;
        padding:20px;
        font-size: 1.5em;
        border-radius: 7px;
        transition: 1.2s all;
    }
    .card:hover{
        background-color: rgb(1, 50, 99);
        border: 0.5px solid dodgerblue;
    }
    .card > h3 + p + button{
        margin-top: 30px;
    }
    .mybtn{
        padding: 20px;
        border: none;
        border-radius: 30px;
        background:white;
        color: dodgerblue;
        font-weight: bold;
         text-transform: uppercase;
        transition: 1.2s all;
        cursor: pointer;
    }
    .mybtn:hover{
        background: rgba(255, 255, 255, 0.247);
        border:1px solid dodgerblue;
        color:dodgerblue;
    }
    @media screen and (max-width: 700px){
        .card{
            width: 80%;
            margin:auto;
        }
    }
</style>