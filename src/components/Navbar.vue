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
    <div class="bg-image"></div>
  </div>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style scoped>
.bg-image {
  background-color: hsl(207, 33%, 95%);
  position: absolute;
  top: -6%;
  right: -15%;
  width: 65%;
  height: 73%;
  border-radius: 3.5rem;
  z-index: -1;
  overflow: hidden;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 5rem;
  overflow: hidden;
}

.nav-icon {
  cursor: pointer;
}

.nav-list {
  display: none;
}

/* Media Queries */
@media (min-width: 990px) {
  .bg-image {
    right: -2%;
    width: 65%;
    height: 58%;
  }

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