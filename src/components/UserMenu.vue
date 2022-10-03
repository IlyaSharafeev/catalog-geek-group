<template>
  <ul class="navbar-nav">
    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
        <img :src="require('@/assets/icons/Avatar.svg')"/>
      </a>
      <ul class="dropdown-menu">
        <li><a class="dropdown-item" href="#">Eng</a></li>
        <li><a class="dropdown-item" href="#">Fr</a></li>
        <li><a class="dropdown-item" href="#">Sp</a></li>
      </ul>
    </li>
  </ul>
</template>

<script>
export default {
  name: "UserMenu"
}
</script>

<style scoped>

</style>