<template>
    <div class="container">
        <div class="content-box">
            <h1></h1>
        </div>
    </div>
</template>

<script>
export default {
    name: "MenSection"
}
</script>

<style>
.container {
    background-color: rgb(90, 93, 255);
    height: 100vh;
    width: 100%;
    max-height: 50%;
}
.content-box {
    border-radius: 1vh;
    position: absolute;
    left: 50%;
    bottom: 20%;
    transform: translate(-50%,25%);
    width: 90%;
    max-width: 750px;
    height: 520px;
    background-color: rgb(255, 255, 255);
}
</style>