<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <nuxt-link
      to="/"
      class="navbar-brand"
    >
      FrontEnd
    </nuxt-link>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon" />
    </button>

    <div
      id="navbarSupportedContent"
      class="collapse navbar-collapse"
    >
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <nuxt-link
            to="/"
            class="nav-link"
          >
            Home
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link
            to="/"
            class="nav-link"
          >
            Posts
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link
            to="/login"
            class="nav-link"
          >
            Login
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link
            to="/register"
            class="nav-link"
          >
            Register
          </nuxt-link>
        </li>
      </ul>
    </div>
  </nav>
</template>
