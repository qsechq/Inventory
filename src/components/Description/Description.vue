<template>
    <div class="c-description">
        <img src="../../assets/decor.png" alt="decor" class="description__img">
        <div class="x-skeleton">
            <skeleton :widthProp="100" :heightProp="26" />
            <skeleton :widthProp="60"/>
            <skeleton :widthProp="100"/>
            <skeleton :widthProp="90"/>
            <skeleton :widthProp="80"/>
            <skeleton :widthProp="70"/>
            <skeleton :widthProp="40"/>
        </div>
    </div>
</template>

<script>
import { Skeleton } from '../Skeleton'

export default {
    name: 'Description',
    components: {
        Skeleton
    }
}
</script>

<style lang="scss" scoped src="./description.scss"></style>