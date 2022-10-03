<template>
  <div class="input-group">
        <span class="input-group-text background_none" id="basic-addon1">
          <img :src="require('@/assets/icons/search.svg')"/>
        </span>
    <input
        type="text"
        class="form-control border-left_none header-catalog__search-input"
        placeholder="Знайти речі або бренди"
        aria-label="Знайти речі або бренди"
        aria-describedby="basic-addon1"
    />
  </div>
</template>

<script>
export default {
  name: "SearchInput"
}
</script>

<style scoped>

</style>