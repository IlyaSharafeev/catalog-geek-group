<template>
  <div class="row">
    <div class="col-lg-12 navigation-panel flex-wrap">
      <NavigationItem
         v-for="(item, key) in panelItems"
         :key="key"
         :item="item"
         :class="{'navigation-item_active': item.active}"
      />
    </div>
  </div>
</template>

<script>
import NavigationItem from "@/components/Navigation/NavigationItem";
export default {
  name: "NavigationPanel",
  components: {NavigationItem},
  data() {
    return {
      panelItems: [
        {
          title: "Головна",
        },
        {
          title: "Каталог",
          active: true
        },
        {
          title: "Жінкам",
        },
        {
          title: "Чоловікам",
        },
        {
          title: "дИТЯЧі речі",
        },
        {
          title: "Аукціон",
        },
        {
          title: "Бренди",
        },
        {
          title: "Акції",
        },
        {
          title: "Аутентифікація",
        },
        {
          title: "Блог",
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>