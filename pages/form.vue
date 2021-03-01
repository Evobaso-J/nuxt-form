<template>
    <div class="formBox">
        <form
            name="contact"
            action=""
            method="post"
        >
        <p>Insert your contact infos here</p>
        <br/>
        <inputName/>
        <inputSurname/>
        <inputSubmit/>
        <br/>
        </form> 
    </div>   
</template>

<script>
import inputName from '../components/inputName.vue'
import InputSubmit from '../components/inputSubmit.vue'
import InputSurname from '../components/inputSurname.vue'
export default {
  components: { inputName, InputSurname, InputSubmit },
        
}
</script>

<style lang="scss">
    $font-stack: Helvetica, sans-serif;
    $background-color: aquamarine;
    $font-color: #35495e; 

    .formBox {
        background-color: $background-color;
        color: $font-color;
        max-width: 400px;
        margin: 100px auto 0 auto;
        border-radius: 8px;
        text-align: center;
        padding: 20px;
    }


</style>


