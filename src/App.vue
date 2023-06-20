<template>
  <div class="container" style="display: flex;">
    <div class="x-description">
      <description />
    </div>
    <div class="x-inventory">
      <inventory />
    </div>
  </div>
</template>

<script>
import { Description } from './components/Description'
import { Inventory } from "./components/Inventory";

export default {
  name: 'App',
  components: {
    Description,
    Inventory
  }
}
</script>

<style lang="scss" src="./styles.scss">

</style>
