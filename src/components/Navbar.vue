<template>
  <div >
    <b-navbar toggleable type="dark" variant="dark">
      <b-navbar-brand href="#">Tanya Portfolio</b-navbar-brand>

      <b-navbar-toggle target="navbar-toggle-collapse">
        <template #default="{ expanded }">
          <b-icon v-if="expanded" icon="chevron-bar-up"></b-icon>
          <b-icon v-else icon="chevron-bar-down"></b-icon>
        </template>
      </b-navbar-toggle>

      <b-collapse id="navbar-toggle-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">Linkedin</b-nav-item>
          <b-nav-item href="https://github.com/singhtanya123" target="_blank"
            >Github</b-nav-item
          >
          <b-nav-item href="#">HackerRank</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
   
  </div>
</template>

<style scoped>
  .title{
    text-align: center;
    font-size: 1.2em;
  }
</style>
