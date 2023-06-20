<template>
    <div class="c-skeleton">
        <div :style="{ width: widthProp + '%', height: heightProp + 'px' }" class="skeleton__item"></div>
    </div>
</template>

<script>
export default {
    name: 'Skeleton',
    props: {
        widthProp: {
            type: Number,
            default: 100 
        },
        heightProp: {
            type: Number,
            default: 10
        }
    }
}
</script>

<style lang="scss" scoped src="./skeleton.scss"></style>