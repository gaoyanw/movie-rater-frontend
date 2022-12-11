<template>
    <div class="layout">
        <div> 
            <h4 v-for="movie in movies" :key="movie"> {{movie}}  </h4>
        </div>
        <h1> Movie Details </h1>
    </div>
</template>
<script>
    export default{
        name: "MoviesList",
        data(){
            return {
                movies:["singler","American Beauty","Seven litte guys"]
            }
        }
    }
</script>
<style scoped>
.layout{
    display:grid;
    grid-template-columns: 1fr 1fr;
}
</style>