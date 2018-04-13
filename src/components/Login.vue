<template>
  <div class="login">
    <title>Login Page</title>
    <h1>LOGUEO</h1>
    <form id="login" name="login">
      <label for="email">Email Address</label>
      <input class="text" name="email" type="text" />
      <label for="password">Password</label>
      <input class="password" name="password" type="text" />
      <input class="btn" type="submit" value="Login" />
    </form>
  </div>
</template>

<script>
export default {
  name: 'Login'
}
</script>
