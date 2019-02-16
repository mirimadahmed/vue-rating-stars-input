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
            },
            value: {
                type: Number,
                required: false,
                default: 0,
            }
        }
    }
</script>

<style scoped>

</style>