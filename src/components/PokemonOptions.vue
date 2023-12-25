<template>
    <div class="options-container">
        <option value="">Opcion 1</option>
        <option value="">Opcion 2</option>
        <option value="">Opcion 3</option>
        <option value="">Opcion 4</option>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>

    .options-container{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    option{
        width: 300px;
        height: 10px;
        padding: 10px;
        background: red;
        margin: 10px;
    }

</style>