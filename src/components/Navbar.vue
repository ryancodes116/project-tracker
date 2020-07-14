<template>
  <div class="navbar container">
    <img src="../assets/images/logo.svg" alt="product logo" />
    <img src="../assets/images/icon-hamburger.svg" alt="nav menu" class="nav-icon" />
    <ul class="nav-list">
      <li class="nav-item">
        <a class="nav-link" href="#">Product</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Features</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Pricing</a>
      </li>
      <li class="nav-item bullet">∙</li>
      <li class="nav-item login">
        <a class="nav-link login" href="#">Login</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 5rem;
}

.nav-icon {
  cursor: pointer;
}

.nav-list {
  display: none;
}

/* Media Queries */
@media (min-width: 990px) {
  .nav-icon {
    display: none;
  }

  .nav-list {
    display: flex;
  }

  .nav-item {
    margin-right: 2rem;
    text-transform: uppercase;
  }

  .nav-item:last-of-type {
    margin-right: 0;
  }

  .login {
    color: hsl(207, 33%, 95%);
  }

  .nav-link {
    color: #000;
    font-weight: 700;
  }
}
</style>