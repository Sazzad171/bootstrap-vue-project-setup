<template>
  <div>
  <b-navbar toggleable="md" type="dark" variant="success">
    <b-navbar-brand>Food Palace</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">

        <b-navbar-nav class="text-white">
          <b-nav-item> <b-link to="/home">Home</b-link> </b-nav-item>
          <b-nav-item> <b-link to="/blogs">Blogs</b-link> </b-nav-item>
          <b-nav-item> <b-link to="/ourTeam">Our Team</b-link> </b-nav-item>
        </b-navbar-nav>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<style>
.navbar-dark .navbar-nav .nav-link {
  color: #fff !important;
}
a {
  color: #fff !important;
}
a:hover {
  text-decoration: none !important;
}
</style>