<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-6 my-custom-col-pad">
                <div class="media mx-3 mb-3">
                <div class="media-body pt-0" id="postData">
                    <h3 class="card-title left pr-2 mb-1">{{postTitle}}</h3>
                    <h6 class="text-uppercase card-title left pr-2 mb-0 font-weight-bold">{{postSubTitle}}</h6>
                    <div class="left pr-2 pt-0 mb-1">
                        <span class="font-weight-bold">{{postPlace}}</span>
                        &nbsp;
                        <span class="font-weight-light">{{postDate}}</span>
                        &nbsp;
                        <span class="font-weight-light">{{postTime}}</span>
                        &nbsp;
                        <span class="font-weight-light">{{postStatus}}</span>
                    </div>
                    <p class="card-text left pr-2">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer...<a href="#"><i class="fas fa-caret-right" id="red"></i></a></p>
                </div>
                </div>               
            </div>
            <div class="col-md-6 my-custom-col-pad">
                <div class="media mx-3 mb-3">
                <div class="media-body pt-0" id="postData">
                    <h3 class="card-title left pr-2 mb-1">{{postTitle}}</h3>
                    <h6 class="text-uppercase card-title left pr-2 mb-0 font-weight-bold">{{postSubTitle}}</h6>
                    <div class="left pr-2 pt-0 mb-1">
                        <span class="font-weight-bold">{{postPlace}}</span>
                        &nbsp;
                        <span class="font-weight-light">{{postDate}}</span>
                        &nbsp;
                        <span class="font-weight-light">{{postTime}}</span>
                        &nbsp;
                        <span class="font-weight-light">{{postStatus}}</span>
                    </div>
                    <p class="card-text left pr-2">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer...<a href="#"><i class="fas fa-caret-right" id="red"></i></a></p>
                </div>
                </div>   
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'SubPostBox',
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
