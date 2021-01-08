<template>
    <header>
        <div class="logo">
            <h1>{{logo}}</h1>
        </div>
        <div class="nav-items">
            <a href="#">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#">Contacts</a>
        </div>
    </header>
</template>

<script>
export default {
    name:'Header',
    props:["logo"] 
}
</script>

<style>
    header{
        display: flex;
        justify-content: space-between;
        padding: 20px;
        background:linear-gradient(24deg, rgb(11, 111, 211), dodgerblue);
        color: white;
        top: 0;
        left: 0;
        width: 100%;
        position: fixed;
    }
    .logo{
        font-size: 0.8em;
    }
    .nav-items{
        margin-top: 10px;
        
    }
    .nav-items a{
        text-decoration: none;
        color: white;
        text-transform: uppercase;
        font-size: 1.2em;
    }
    .nav-items > a +a {
        margin-left: 20px;

    }
</style>