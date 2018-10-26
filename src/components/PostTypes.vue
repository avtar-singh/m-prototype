<template>
    <form>
    <fieldset>
        <legend class="text-uppercase" style="font-size: 40px;letter-spacing: 0 !important;">&nbsp;UTVALT FÖR DIG&nbsp;</legend>
        <PostTypeBoxes/>
        <PostTypeBoxes/>
        <PostTypeBoxes/>
        <PostTypeBoxes/>
    </fieldset>
    </form>    
</template>

<script>
import PostTypeBoxes from './PostTypeBoxes'
export default {
    name: 'PostTypes',
    components: {
        PostTypeBoxes
    }
}
</script>

<style>
fieldset{
    border: 1px dashed #343a40 !important;
    /* margin-left: 20px !important; */
}
legend{
    text-align: center;
    width: unset !important;
    font-family: 'Abril Fatface', cursive;
}
</style>
