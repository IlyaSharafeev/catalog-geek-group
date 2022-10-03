<template>
  <div class="navigation-item fw-bold">
    {{item.title}}
  </div>
</template>

<script>
export default {
  name: "NavigationItem",
  props: {
    item: {
      default: String
    }
  }
}
</script>

<style scoped>

</style>