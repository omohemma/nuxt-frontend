<template>
  <div class="container col-md-5 col-lg-4 mt-5">
    <h3>Login Form</h3>
    <br />
    <form>
      <div class="form-group">
        <label for="email">Email address</label>
        <input type="email" class="form-control" id="email" aria-describedby="emailHelp" />
        <small id="emailHelp" class="form-text text-danger">Show Errors Here</small>
      </div>
      <div class="form-group">
        <label for="password">Password</label>
        <input type="password" class="form-control" id="password" aria-describedby="passwordHelp" />
        <small id="passwordHelp" class="form-text text-danger">Show errors Here</small>
      </div>
      <div class="form-group form-check">
        <input type="checkbox" class="form-check-input" id="remember" />
        <label class="form-check-label" for="remember">Rememember me</label>
      </div>
      <button type="submit" class="btn btn-primary">Login</button>
    </form>
    <p class="mt-3">
      Don't have an account?
      <nuxt-link to="/register">Register</nuxt-link>
    </p>
  </div>
</template>