<template>
    <div>
        <hr>
        Child counter : {{ this.$store.state.counter }} <br>
        <button>+</button>
        <button>-</button>
    </div>
</template>

<script>
export default {
    props: ['passedCounter']
}
</script>

<style>

</style>