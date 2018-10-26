<template>
    <div class="media m-3">
    <img class="img-fluid img-thumb" src="../assets/7.png" alt="Card image cap">
    <div class="media-body pt-0" id="postData">
        <h6 class="text-uppercase card-title left px-2 mb-0" style="font-size: 20px;">{{postSubTitle}}</h6>
        <div class="left px-2 pt-0 mb-1">
            <span class="font-weight-bold" style="font-size: 13px;">{{postPlace}}</span>
            <br>
            <span class="font-weight-light" style="font-size: 12px;">{{postDate}}</span>
            &nbsp;
            <span class="font-weight-light" style="font-size: 12px;">{{postTime}}</span>
            &nbsp;
            <span class="font-weight-light" style="font-size: 12px;">{{postStatus}}</span>
        </div>
        <p class="card-text left px-2"><span style="font-weight: bold;">I huvudet på en seriemördare Seriemördare</span> finns i alla länder
i världen. Och när dr Helen Morrison började forska i
vad som driver en människa att mörda fann hon överraskande
nog mängder av likheter mellan seriemördare ö…<a href="#"><i class="fas fa-caret-right" id="red"></i></a></p>
    </div>
    </div>   
</template>

<script>
export default {
    name: 'PostTypeBoxes',
    data() {
    return {
            postSubTitle: 'PSYKOLOGI',
            postPlace: 'Anders Ljungstedt',
            postDate: '10 SEPT',
            postTime: '11 MIN',
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
p.card-text{
    font-size: 17px;
    line-height: 20px;
}   
</style>
