<template>
    <div :class="bgColor + ' ' + textColor" class="h-60 flex flex-col gap-8 justify-center items-center text-center">
        <div class="text-4xl font-bold">Small Side Project Title</div>
        <div class="text-lg font-light">Insert Small side project description</div>
    </div>
</template>

<script>
export default {
    props: {
        bgColor: {
            required: true,
            type: String
        },
        textColor: {
            required: true,
            type: String
        }
    }

}
</script>

<style>

</style>