<script>
export default {
    props:{
        input: Object
    }
}
</script>


<template>
    <div class="max-w-xs flex justify-center p-2 border-solid border-2 border-red-600 rounded">
        <img v-bind:src="input.src"/> <a class="ml-2" v-bind:href="input.url">{{ input.text }}</a>
    </div>
</template>


<style>


</style>