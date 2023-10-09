<script>
    //@ts-nocheck
    export let color;
    export let backgroundColor;
    export let image1;
    export let iconColor;
    export let count;
    export let text;
    //console.log(color);
</script>

<div class="card" style="background-color:{color} ; ">
    <div class="inner-card" style="background-color:{backgroundColor}">
        <span style="color:{iconColor}">{@html image1}</span>
    </div>
    <div class="second-item">
        <h1 class="count">{count}</h1>
        <h3 style="color:{iconColor};">{text}</h3>
    </div>
</div>

<style>
    .card {
        border-radius: 7px;
        width: 25vw;
        height: 17vh;
        display: flex;
        z-index: 0;
    }
    .inner-card {
        width: 15%;
        height: 38%;
        margin-top: 10%;
        margin-left: 5%;
        border-radius: 5px;
        z-index: 1500;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .second-item {
        margin-left: 40%;
        font-family: monospace;
    }
    .count {
        margin-left: 75%;
    }
</style>
