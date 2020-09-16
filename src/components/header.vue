<template>
<div>
        <img alt="Vue logo" src="../assets/logo.png">
        <div></div>
        <h3>About us</h3>
        <h3>Location</h3>
        <h3>Menu</h3>
</div>
    
</template>

<script>
    export default{
        name:"page-header"
    }

</script>

<style scoped>
.header-grid{
    display: grid;
    justify-items: center;
    align-items: center;
    grid-template-columns: 1fr 2fr 1fr 1fr 1fr;
}

</style>