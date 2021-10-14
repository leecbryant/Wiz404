<template>
  <nav class="navbar navbar-dark justify-content-between" style="background-color: #3d2566;">
    <a class="navbar-brand" href="#">
      <img src="./assets/logo.png" width="30" height="30" class="d-inline-block align-top" alt="">
      Wizard404 <i class="subtitle"> A Modern Wizard101 Wiki </i>
    </a>
    <!-- Search Will Definitely Be a Necessity in the Future -->
    <!-- <form class="form-inline">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-light my-2 my-sm-0" type="submit">Search</button>
    </form> -->
  </nav>
  <router-view />
</template>

<style>
  body {
    background-color: #383838;
  }
  .subtitle {
    font-size: 0.75em;
    margin-left: 0.5em;
  }
</style>