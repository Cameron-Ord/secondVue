<template>
 
        <nav class="navigation">
    <span class="footer_span">
        <a href="">Link</a>

        <a href="">Link</a>

        <a href="">Link</a>
    </span>
    <span class="footer_span">
        <a href="">Link</a>

        <a href="">Link</a>

        <a href="">Link</a>
    </span>
</nav>

</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.navigation{

display: grid;

grid-template-columns: 1fr 1fr;

align-items: center;

justify-items: center;

height: 100%;



}

.footer_span{


}
</style>