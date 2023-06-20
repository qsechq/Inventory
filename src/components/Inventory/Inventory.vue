<template>
    <div class="c-inventory">
        <table class="inventory__table">
            <tbody class="inventory__tbody">
                <tr class="inventory__list">
                    <td class="inventory__item">
                        <inventory-slot />
                    </td>
                    <td class="inventory__item">
                        <inventory-slot />
                    </td>
                    <td class="inventory__item">
                        <inventory-slot />
                    </td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                </tr>
                <tr class="inventory__list">
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                </tr>
                <tr class="inventory__list">
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                </tr>
                <tr class="inventory__list">
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                </tr>
                <tr class="inventory__list">
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                    <td class="inventory__item"></td>
                </tr>
            </tbody>
        </table>
        <modal></modal>
    </div>
</template>

<script>
import { InventorySlot } from "../InventorySlot";
import { Modal } from "../Modal";

    export default {
        name: 'Inventory',
        components: {
            InventorySlot,
            Modal
        }
    }
</script>

<style lang="scss" scoped src="./inventory.scss">

</style>