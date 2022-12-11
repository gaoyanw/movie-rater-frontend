<template>
    <div class="layout"> 
        <h1> List of movies </h1>
                <h1> Movie Details </h1>
    </div>
</template>
<script>
    export default{
        name: "MoviesList"
    }
</script>
<style scoped>
.layout{
    display:grid;
    grid-template-columns: 1fr 1fr;
}
</style>