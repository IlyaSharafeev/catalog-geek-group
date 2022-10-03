<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-12">
        <Breadcrumb />
      </div>
    </div>
    <div class="row">
      <div class="col-sm-12">
        Каталог одягу
      </div>
    </div>
  </div>
</template>

<script>
import Breadcrumb from "@/components/Breadcrumb";

export default {
  name: "ClothingCatalogPage",
  components: {
    Breadcrumb,
  }

}
</script>

<style scoped>

</style>