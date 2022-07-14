<template>
  <!-- Navbar -->

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Navbar</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li>
          <router-link class="nav-link" to="/Home">Home</router-link>
        </li>

        <li>
          <router-link class="nav-link" to="/carService"
            >Car Services</router-link
          >
        </li>

        <li>
          <router-link class="nav-link" to="/BookedCars"
            >Booked Cars</router-link
          >
        </li>

        <li>
          <router-link class="nav-link" to="/#">Contact</router-link>
        </li>

        <li class="nav-item"></li>
      </ul>
      <!-- Hello
      <script>
        {
          document.write(localStorage.getItem("name"));
        }
      </script> -->
      &nbsp;
      <a class="nav-link" href="#">Logout</a>
      <form class="d-flex">
        <input
          class="form-control me-2"
          type="search"
          placeholder="Search"
          aria-label="Search"
        />
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </nav>
  <body></body>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style>
body {
  background-color: #cccccc;
  /* background-image: url(../assets/images/car12.png);
  background-repeat: no-repeat, repeat; */
}
a:link {
  text-decoration: none;
  padding-left: 15px;
}
</style>
