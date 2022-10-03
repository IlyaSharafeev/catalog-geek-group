<template>
  <div class="d-flex flex-row header-catalog__icons">
    <div class="header-catalog__icon">
      <div class="header-catalog__icon-badge">8</div>
      <img :src="require('@/assets/icons/core.svg')"/>
    </div>
    <div class="header-catalog__icon">
      <img :src="require('@/assets/icons/message.svg')"/>
      <div class="header-catalog__icon-badge header-catalog__icon-badge_red">3</div>
    </div>
    <div class="header-catalog__icon">
      <img :src="require('@/assets/icons/cart.svg')"/>
      <div class="header-catalog__icon-badge">3</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MenuIcons"
}
</script>

<style scoped>

</style>