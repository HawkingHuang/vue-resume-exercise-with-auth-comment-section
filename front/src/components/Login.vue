<template>
  <section class="section section-login">
    <nav>
      <ul class="login-lists">
        <li><h1>My Resume</h1></li>
        <li><a href="http://localhost:5001" class="login-btn">Log In</a></li>
      </ul>
    </nav>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.section-login {
  max-width: 150rem;
  margin: 2rem auto 0 auto;
}

.login-lists {
  display: flex;
  justify-content: space-between;
  align-items: center;
  list-style: none;
}

.login-btn {
  font-size: 2rem;
  font-weight: 700;
  color: black;
  text-align: center;
  width: 8rem;
  height: 2.4rem;
  padding: 1rem 2rem;
  background-color: #fee996;
  border-radius: 36px;
  margin: 0 auto;
  text-decoration: none;
}

h1 {
  font-size: 4rem;
}
</style>
