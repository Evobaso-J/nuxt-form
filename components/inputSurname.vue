<template>
    <fieldset>
        <input 
            type="text"
            name="surname"
            id="surname"
            placeholder="Insert your surname here"
        >
    </fieldset>
</template>

<script>
export default {  
}
</script>

<style>
    input[type="text"] {
        width: 100%;
        height: 100%;
        border: none;
    }

    fieldset {
        border: medium none !important;
        margin: 0 0 10px;
        min-width: 100%;
        padding: 0;
        width: 100%;
    }
</style>