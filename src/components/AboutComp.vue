<template>
    <div class="aboutcomp">
        <h1>
            Hi my name is {{asd}}
        </h1>
        <h3>
            I Need to stop this.
        </h3>
        <img src="../assets/backg2.jpg" alt="Kep">

    </div>
</template>

<script>
export default {
    name:"szoveg",
    props: {
        asd: String
    }
}
</script>

<style scoped>
    h1{
        color:red;
    }
    .aboutcomp{
        background-image: url("../assets/backg1.jpg");
        padding-top:50px;
        width:100%;
        margin:0;
    }
    img{
        max-width:100%;
        max-height: 800px;
    }
</style>