<template>
    <div class="media m-3">
    <img class="img-fluid img-thumb" src="../assets/4.png" alt="Card image cap">
    <div class="media-body pt-0" id="postData">
        <h6 class="card-title left px-2 mb-0 font-weight-bold" style="font-size: 18px;">{{postSubTitle}}</h6>
        <div class="left px-2 pt-0 mb-1">
            <span class="font-weight-bold" style="font-size: 13px;">{{postPlace}}</span>
            <br>
            <span class="font-weight-light" style="font-size: 12px;">{{postDate}}</span>
            &nbsp;
            <span class="font-weight-light" style="font-size: 12px;">{{postTime}}</span>
            &nbsp;
            <span class="font-weight-light" style="font-size: 12px;">{{postStatus}}</span>
        </div>
        <p class="card-text left px-2">16 saker du får
panik över om du
har kontrollb… <a href="#"><i class="fas fa-caret-right" id="red"></i></a></p>
    </div>
    </div>   
</template>

<script>
export default {
    name: 'PostBox',
    data() {
    return {
            postSubTitle: 'LIVSSTIL',
            postPlace: 'Lowe Andersson',
            postDate: '12 SEPT',
            postTime: '13 MIN',
            postStatus: 'LÄSNING'
        }
    }
}

</script>

<style scoped>
    .img-thumb{
        width: 150px;
        height: 150px;
    }
    #red{
        color: darkred;
        font-size: 15px;
    }
    p.card-text.left.px-2{
        font-weight: 500;
        font-size: 18px !important;
        line-height: 20px !important;
    }
</style>
