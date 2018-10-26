<template>
    <div class="jumbotron">
    <h1 class="display-4">
        7<center>FÖRDELAR</center>
        <center>FÖR</center>
        <center>SKRIBNTER</center>
    </h1>
    <p class="lead">
        <a href="#"><i class="fas fa-caret-right" id="red"></i></a>&nbsp;&nbsp;&nbsp;
        <button class="my-custom-white-bt">TIPS HÄR</button>
    </p>
    </div>
</template>

<script>
export default {
    name: 'Jumbotron2'
}
</script>

<style scoped>

.jumbotron{
    font-family: 'Abril Fatface', cursive;
}

.my-custom-white-bt{
    color: rgba(0,0,0,0.1);
    background-color: white;
    width: 130px !important;
    height: 50px !important;
    font-family: 'Acme', sans-serif;
    font-size: 18px;
    letter-spacing: 1px;
    border-width: 0;    
}

</style>

