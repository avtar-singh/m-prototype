<template>
    <div class="container-fluid">
        <div class="mb-3">
            <div class="row">
                <div class="col-md-4 p-1">
                    <img class="img-fluid pb-1" style="width: 100%; height: 250px !important; object-fit: cover;" src="../assets/2.png" alt="Card image cap">
                    <img class="img-fluid" style="width: 100%; height: 150px !important; object-fit: cover;" src="../assets/3.png" alt="Card image cap">
                </div>
                <div class="col-md-8 p-1">
                    <img class="img-fluid" style="width: 100%; height: 400px !important; object-fit: cover;" src="../assets/1.png" alt="Card image cap">
                </div>
            </div>
            <div class="card-body pl-0 py-0 mt-3" id="postData">
            <h3 class="card-title left pl-0 pr-2 mb-1 mt-1">{{postTitle}}</h3>
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
        border: 1px dotted #343a40 !important;
    }
    .dotted{
        border: none !important;
        border-radius: 0 !important;
        border-bottom: 1px dotted #343a40 !important;
        border-width: 0 2em;
    }
</style>
