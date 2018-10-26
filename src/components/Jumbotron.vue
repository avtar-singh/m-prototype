<template>
    <div class="jumbotron jumbotron-fluid text-left px-2">
        <div class="container">
            <h1 class="display-5 mb-3">VÄLKOMMEN TILL GAZZINE<br>
-där texter hittar sina läsare
</h1>
            <p class="lead mb-4" style="font-size: 1.5rem;"><span style="font-size: 1.2rem;">GAZZINE</span> Här bjuder Sveriges främsta skribenter<br>
på texter inom ämnen som du bryr dig om</p>
            <button type="button" class="my-black-button">KOM IGÅNG</button>
            &nbsp;&nbsp;&nbsp;
            <button type="button" class="my-white-button">UTFORSKA</button>
        </div>
    </div> 
</template>

<script>
export default {
    name: 'Jumbotron'
}
</script>

<style scoped>
.display-5{
    font-size: 2.8rem;
}
.my-black-button{
    color: white !important;
    background-color: black;
    width: 160px;
    height: 50px;
    font-family: 'Acme', sans-serif;
    font-size: 16px;
    letter-spacing: 1px;
    border-width: 0;
}
.my-white-button{
    color: white !important;
    background-color: rgb(167, 11, 50);
    width: 160px;
    height: 50px;
    font-family: 'Acme', sans-serif;
    font-size: 16px;
    letter-spacing: 1px;
    border: 1px solid white;
}
</style>

