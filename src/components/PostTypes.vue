<template>
    <form>
    <fieldset>
        <legend class="text-uppercase">&nbsp;SELECTED FOR YOU&nbsp;</legend>
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
    border: 1px dotted #343a40 !important;
    /* margin-left: 20px !important; */
}
legend{
    text-align: center;
    width: unset !important;
}
</style>
