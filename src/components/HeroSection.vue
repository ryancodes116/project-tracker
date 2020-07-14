<template>
  <div class="hero container">
    <img
      src="../assets/images/illustration-devices.svg"
      alt="phone and laptop illustration"
      class="devices"
    />
    <div class="hero-text">
      <div class="heading">
        <p class="new">New</p>
        <p class="dashboard">Monograph Dashboard</p>
      </div>
      <h1 class="title">Powerful Insights Into Your Team</h1>
      <p class="subtitle">Project planning and time tracking for agile teams</p>
      <div class="cta">
        <button class="cta-btn">Schedule a Demo</button>
        <p class="cta-text">To See A Preview</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.hero {
  display: flex;
  flex-direction: column;
}

.devices {
  width: 161%;
  margin-left: -1.9rem;
  margin-bottom: 7rem;
}

.hero-text {
  text-transform: uppercase;
}

.heading {
  display: flex;
  align-items: center;
  margin-bottom: 1.5rem;
}

.new {
  font-weight: 700;
  background-color: #000;
  color: #fff;
  padding: 0.2rem 0.9rem;
  border-radius: 2rem;
  margin-right: 1rem;
}

.dashboard {
  color: hsl(231, 7%, 65%);
  letter-spacing: 0.2rem;
}

.title {
  font-size: 3.1rem;
  line-height: 3rem;
  margin-bottom: 2rem;
}

.subtitle {
  color: hsl(230, 11%, 40%);
  width: 75%;
  line-height: 1.5;
  text-transform: none;
  margin-bottom: 2rem;
}

.cta {
  display: flex;
  align-items: center;
}

.cta-btn {
  width: 50%;
  padding: 0.7rem 0;
  background-color: hsl(0, 100%, 68%);
  color: #fff;
  border: none;
  border-radius: 0.3rem;
  font-size: 18px;
  font-weight: 700;
  text-transform: uppercase;
  margin-right: 1.2rem;
  cursor: pointer;
}

.cta-text {
  font-size: 0.9rem;
  letter-spacing: 0.2rem;
  color: hsl(231, 7%, 65%);
}
</style>