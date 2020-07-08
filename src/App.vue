<template>
    <div id="app">
        <canvas id="canvas"></canvas>
    </div>
</template>

<script>
    import hack from "./common/hack";
    // import rains from "./common/rains";

    export default {
        name: 'App',
        components: {},
        mounted() {
            hack()
            // rains()
        }
    }
</script>

<style>
    @import "./assets/css/base.css";

    body {
        margin: 0;
        padding: 0;
        overflow: hidden;
    }
    /*#app {*/
    /*    background-color: black;*/
    /*}*/
    canvas {
        height: 100%;
        width: 100%;
        position: absolute;
        background: #000 url("./assets/img/67078.jpg");
        background-size: cover;
    }
</style>
