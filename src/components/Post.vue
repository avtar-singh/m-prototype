<template>
    <div class="container-fluid">
        <div class="mb-3">
            <img class="img-fluid" src="../assets/logo.png" alt="Card image cap">
            <div class="card-body pl-0 py-0" id="postData">
            <h3 class="card-title left pr-2 mb-1">{{postTitle}}</h3>
            <h6 class="text-uppercase card-title left pr-2 mb-0 font-weight-bold">{{postSubTitle}}</h6>
            <div class="left pr-2 pt-0 mb-1">
                <span class="font-weight-bold">{{postPlace}}</span>
                &nbsp;&nbsp;
                <span class="font-weight-light">{{postDate}}</span>
                &nbsp;&nbsp;
                <span class="font-weight-light">{{postTime}}</span>
                &nbsp;&nbsp;
                <span class="font-weight-light">{{postStatus}}</span>
            </div>
            <p class="card-text left pr-2">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer... <a href="#"><i class="fas fa-caret-right" id="red"></i></a></p>
            <hr>
            </div>
        </div>   
    </div>
</template>

<script>
export default {
    name: 'Post',
    data() {
    return {
            postTitle: 'The documentaries you can not miss',
            postSubTitle: 'Culture',
            postPlace: 'Los Angels',
            postDate: '24 OCT',
            postTime: '3:05pm',
            postStatus: 'Reading'
        }
    }
}

</script>

<style scoped>
    hr { 
        display: block;
        /* margin-left: 0.5em;
        margin-right: 1.5em; */
        border: 1px dotted black !important;
    }
    .dotted{
        border: none !important;
        border-radius: 0 !important;
        border-bottom: 1px dotted black !important;
        border-width: 0 2em;
    }
</style>
