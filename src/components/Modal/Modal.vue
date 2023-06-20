<template>
    <div class="modal">
        <div class="modal__content">
            <button class="modal__close">
                <icon name="Close" class="modal__icon"/>
            </button>
            <img src="../../assets/slot-b.png" alt="slot" class="modal__img">
            <div class="description">
                <skeleton :heightProp="26" />
                <skeleton />
                <skeleton />
                <skeleton />
                <skeleton />
                <skeleton :widthProp="40" />
            </div>
            <button class="modal__btn">Удалить предмет</button>
        </div>
    </div>
</template>

<script>
import { Skeleton } from '../Skeleton'
import { Icon } from '../../icons'

    export default {
        name: 'Modal',
        components: {
            Skeleton,
            Icon
        }
    }
</script>

<style lang="scss" scoped src="./modal.scss">

</style>