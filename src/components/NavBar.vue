<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top flex-md-nowrap p-0 shadow">
    <div class="container-fluid">

      <a class="navbar-brand"
         href="#">
        <img src="/docs/5.0/assets/brand/bootstrap-logo.svg"
             alt=""
             width="30"
             height="24"
             class="d-inline-block align-top">
        Bootstrap
      </a>

      <button class="navbar-toggler"
              type="button"
              data-toggle="collapse"
              data-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent"
              aria-expanded="false"
              aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse"
           id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active"
               aria-current="page"
               href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link"
               href="#">Link</a>
          </li>
        </ul>
      </div>

      <div class="collapse navbar-collapse d-flex justify-content-end"
           id="navbarNavDarkDropdown">
        <ul class="navbar-nav">
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle"
               href="#"
               id="navbarDarkDropdownMenuLink"
               role="button"
               data-toggle="dropdown"
               aria-expanded="false">
              Dropdown
            </a>
            <ul class="dropdown-menu dropdown-menu-dark"
                aria-labelledby="navbarDarkDropdownMenuLink">
              <li><a class="dropdown-item"
                   href="#">info</a></li>
              <li><a class="dropdown-item"
                   href="#">logout</a></li>
              <li><a class="dropdown-item"
                   href="#">login</a></li>
            </ul>
          </li>
        </ul>
      </div>

    </div>
  </nav>
</template>

<script>
  export default {
    name: "NavBar",
    props: {},
    data() {
      return {};
    },
  };
</script>

<style scoped>
</style>
