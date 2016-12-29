<template>
  <div id="app">
    <item-image />
    <item-title />
    <item-description />
  </div>
</template>

<script>
  import ItemImage from './components/ItemImage.vue'
  import ItemTitle from './components/ItemTitle.vue'
  import ItemDescription from './components/ItemDescription.vue'

  export default {
    components: {
      ItemImage,
      ItemTitle,
      ItemDescription
    }
  }
</script>

<style>
#app {
  text-align: center;
}
</style>
