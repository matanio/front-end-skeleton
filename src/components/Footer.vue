<template>
    <div :class="bgColor + ' ' + textColor" class="h-32 flex justify-center items-center">
        <div>Made by Matan 🤙</div>
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