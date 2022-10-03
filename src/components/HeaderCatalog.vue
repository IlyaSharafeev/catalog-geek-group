<template>
  <div class="row header-catalog flex-wrap">
    <MainLogo class="col-sm-12 col-lg-2"/>
    <div class="col-sm-12 col-lg-10 header-catalog__menu">
      <div class="header-catalog__menu-search-form">
        <SearchInput/>
        <button type="button" class="btn btn-dark header-catalog__menu-button">
          Додати товар
        </button>
      </div>
      <div class="header-catalog__menu-icons">
        <LangSwitch/>
        <MenuIcons/>
        <UserMenu/>
      </div>
    </div>
  </div>
</template>

<script>
import MainLogo from "@/components/MainLogo";
import LangSwitch from "@/components/LangSwitch";
import UserMenu from "@/components/UserMenu";
import SearchInput from "@/components/SearchInput";
import MenuIcons from "@/components/MenuIcons";

export default {
  name: "HeaderCatalog",
  components: {
    MenuIcons,
    SearchInput,
    UserMenu,
    LangSwitch,
    MainLogo
  }
}
</script>

<style scoped>

</style>