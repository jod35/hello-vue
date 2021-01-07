<template>
    <main>
        <div class="intro" id="home">
            <h1>Hello to my Vue App</h1>
        </div>
    </main>
</template>

<script>
export default{
    name:'Main',
}


</script>

<style>
.intro{
    min-height: 100vh;
    margin-top: 0;
    background:repeating-linear-gradient(24deg, rgb(11, 111, 211), dodgerblue);
    color:white;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>