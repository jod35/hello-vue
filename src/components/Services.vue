<template>
    <section id="services">
       <div class="card-sect">
            <Card/>
       </div>
       <div class="card-sect">
             <Card/>
       </div>
       <div class="card-sect">
             <Card/>
       </div>
       <div class="card-sect">
             <Card/>
       </div>
        <div class="card-sect">
             <Card/>
       </div>
        <div class="card-sect">
             <Card/>
       </div>
        <div class="card-sect">
             <Card/>
       </div>
        <div class="card-sect">
             <Card/>
       </div>
        <div class="card-sect">
             <Card/>
       </div>
        <div class="card-sect">
             <Card/>
       </div>
        <div class="card-sect">
             <Card/>
       </div>
        <div class="card-sect">
             <Card/>
       </div>
    </section>
</template>
<script>
import Card from './Card.vue'
export default {
    name:'Services',
    components:{
        Card
    }
}
</script>

<style>
    #services{
        min-height: 80vh;
        background: white;
        display: grid;
        grid-template-columns: 25% 25% 25% 25%;
        background:rgb(1, 50, 99);
        padding: 5% 0 0 1%;
        
    }
    .card-sect{
        margin-top: 20px;
    }
    #services > .card-sect +.card-sect{
        margin-top: 10px;
    }
    @media screen and (max-width: 700px){
        #services{
            display: block;
        }
    }
    
</style>