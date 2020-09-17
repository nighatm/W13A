<template >
<div class="sidepanel">
        
    <div></div>
    <h3>Body container text</h3>
    <div></div>
    <h3>Body container Image</h3>
    <div></div>
    <h3>Body container links</h3>
    <div></div>
    </div>
</template>

<script>
export default {
    name:"side-panel"
    }
</script>

<style scoped>
.sidepanel{
        display: grid;
        justify-items: left;
        align-items: left;
        align-self: left;
        grid-template-columns:4fr 6fr;
        width:40%;
        background-color:rgb(90, 94, 92);
}
</style>