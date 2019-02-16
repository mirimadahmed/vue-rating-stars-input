<template>
    <div>

    </div>
</template>

<script>
    export default {
        props: {
            mode: {
                type: String,
                required: false,
                default: 'input',
                validator: value => ['input', 'show'].includes(value)
            }
        }
    }
</script>

<style scoped>

</style>