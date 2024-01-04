<template>
    <div class="block">
        <h3>Click Here {{delay}}</h3>
    </div>
</template>

<script>
export default {
    props:['delay']
}
</script>

<style>
    .block {
        background: aqua;
        width: 400px;
        height: 300px;
        margin: 20px auto;
        padding: 30px;
        border-radius: 30px;
    }
</style>