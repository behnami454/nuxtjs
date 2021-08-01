<template>
  <b-navbar toggleable type="dark" variant="dark">
    <b-navbar-brand href="#">Skull</b-navbar-brand>

    <b-navbar-toggle target="navbar-toggle-collapse" class="text-light">
      <template #default="{ expanded }">
        <b-icon v-if="expanded" icon="chevron-bar-up"></b-icon>
        <b-icon v-else icon="chevron-bar-down"></b-icon>
      </template>
    </b-navbar-toggle>

    <b-collapse id="navbar-toggle-collapse" class="light" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="/contact">contact</b-nav-item>
        <b-nav-item href="/detail">detail</b-nav-item>
        
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>