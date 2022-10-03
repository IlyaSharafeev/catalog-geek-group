<template>
  <div class="container-lg text-center">
    <HeaderCatalog/>
    <Divider/>
    <NavigationPanel/>
  </div>
</template>

<script>
import HeaderCatalog from "@/components/HeaderCatalog";
import Divider from "@/components/Divider";
import NavigationPanel from "@/components/Navigation/NavigationPanel";

export default {
  name: "Header",
  components: {
    NavigationPanel,
    Divider,
    HeaderCatalog,
  }
}
</script>

<style scoped>

</style>