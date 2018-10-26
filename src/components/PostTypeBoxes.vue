<template>
    <div class="media m-3">
    <img class="img-fluid img-thumb" src="../assets/logo.png" alt="Card image cap">
    <div class="media-body pt-0" id="postData">
        <h3 class="card-title left px-2 mb-1">{{postTitle}}</h3>
        <h6 class="text-uppercase card-title left px-2 mb-0 font-weight-bold">{{postSubTitle}}</h6>
        <div class="left px-2 pt-0 mb-1">
            <span class="font-weight-bold">{{postPlace}}</span>
            <br>
            <span class="font-weight-light">{{postDate}}</span>
            &nbsp;
            <span class="font-weight-light">{{postTime}}</span>
            &nbsp;
            <span class="font-weight-light">{{postStatus}}</span>
        </div>
        <p class="card-text left px-2">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer...<a href="#"><i class="fas fa-caret-right" id="red"></i></a></p>
    </div>
    </div>   
</template>

<script>
export default {
    name: 'PostTypeBoxes',
    data() {
    return {
            postTitle: 'Life Style',
            postSubTitle: 'Culture',
            postPlace: 'Los Vegas',
            postDate: '24 OCT',
            postTime: '4:25pm',
            postStatus: 'Reading'
        }
    }
}

</script>

<style scoped>
    .img-thumb{
        width: 120px;
        height: 120px;
    }
</style>
