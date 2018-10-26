<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-6 my-custom-col-pad">
                <div class="media mx-3 mb-3">
                <div class="media-body pt-0" id="postData">
                    <h3 class="card-title left pr-2 mb-1">{{postTitle}}</h3>
                    <h6 class="text-uppercase card-title left pr-2 mb-0 font-weight-bold" style="font-size: 14px;">{{postSubTitle}}</h6>
                    <div class="left pr-2 pt-0 mb-1">
                        <span class="font-weight-bold" style="font-size: 13px;">{{postPlace}}</span>
                        &nbsp;
                        <span class="font-weight-light" style="font-size: 12px;">{{postDate}}</span>
                        &nbsp;
                        <span class="font-weight-light" style="font-size: 12px;">{{postTime}}</span>
                    </div>
                    <p class="card-text left pr-2">Världens bästa vandringar - 15 enastående
leder att vandra innan du
dör nist, ut quia quidlent, etum…<a href="#"><i class="fas fa-caret-right" id="red"></i></a></p>
                </div>
                </div>               
            </div>
            <div class="col-md-6 my-custom-col-pad">
                <div class="media mx-3 mb-3">
                <div class="media-body pt-0" id="postData">
                    <h3 class="card-title left pr-2 mb-1">{{postTitle}}</h3>
                    <h6 class="text-uppercase card-title left pr-2 mb-0 font-weight-bold" style="font-size: 14px;">{{postSubTitle}}</h6>
                    <div class="left pr-2 pt-0 mb-1">
                        <span class="font-weight-bold" style="font-size: 13px;">{{postPlace}}</span>
                        &nbsp;
                        <span class="font-weight-light" style="font-size: 12px;">{{postDate}}</span>
                        &nbsp;
                        <span class="font-weight-light" style="font-size: 12px;">{{postTime}}</span>
                    </div>
                    <p class="card-text left pr-2">Världens bästa vandringar - 15 enastående
leder att vandra innan du
dör nist, ut quia quidlent, etum…<a href="#"><i class="fas fa-caret-right" id="red"></i></a></p>
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
            postTitle: '15 BÄSTA VANDRINGARNA',
            postSubTitle: 'LIVSSTIL',
            postPlace: 'Lowe Andersson',
            postDate: '12 SEPT',
            postTime: '13 MIN'
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
