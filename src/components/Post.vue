<template>
    <div class="container-fluid">
        <div class="mb-3">
            <div class="row">
                <div class="col-md-4 py-1 pl-1 pr-0">
                    <img class="img-fluid pb-1" style="width: 100%; height: 250px !important;" src="../assets/2.png" alt="Card image cap">
                    <img class="img-fluid" style="width: 100%; height: 150px !important; object-fit: cover;" src="../assets/3.png" alt="Card image cap">
                </div>
                <div class="col-md-8 p-1">
                    <img class="img-fluid" style="width: 100%; height: 400px !important; object-fit: cover;" src="../assets/1.png" alt="Card image cap">
                </div>
            </div>
            <div class="card-body pl-0 py-0 mt-3" id="postData">
            <h3 class="card-title card-main-title left pl-0 pr-2 mb-0 mt-1">{{postTitle}}</h3>
            <h6 class="text-uppercase card-title left pr-2 mb-0 font-weight-bold" style="font-size: 14px; font-family: 'Work Sans', sans-serif;">{{postSubTitle}}</h6>
            <div class="left pr-2 pt-0 mb-1">
                <span class="font-weight-bold" style="font-size: 13px;">{{postPlace}}</span>
                &nbsp;&nbsp;
                <span class="font-weight-light" style="font-size: 12px;">{{postDate}}</span>
                &nbsp;&nbsp;
                <span class="font-weight-light" style="font-size: 12px;">{{postTime}}</span>
                &nbsp;&nbsp;
                <span class="font-weight-light" style="font-size: 12px;">{{postStatus}}</span>
            </div>
            <p class="card-text left pr-2">Spill inte tid på dåliga filmmanus och slött slentrian-zappande. Här är
listan med 30 fantastiska dokumentärer som bkräftar att…<a href="#"><i class="fas fa-caret-right" id="red"></i></a></p>
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
            postTitle: 'Dokumentärerna du inte får missa',
            postSubTitle: 'KULTUR',
            postPlace: 'Lowe Andersson',
            postDate: '12 SEPT',
            postTime: '13 MIN',
            postStatus: 'LÄSNING'
        }
    }
}

</script>

<style scoped>
    hr { 
        display: block;
        /* margin-left: 0.5em;
        margin-right: 1.5em; */
        border: 1px dashed #343a40 !important;
    }
    .dotted{
        border: none !important;
        border-radius: 0 !important;
        border-bottom: 1px dotted #343a40 !important;
        border-width: 0 2em;
    }
    .card-main-title{
        font-family: -webkit-body;
        color: #000;
        font-size: 50px;
        font-weight: 800;
        letter-spacing: -2px;        
    }
</style>
