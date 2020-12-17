<template>
  <nav class="navbar navbar-expand-lg fixed-top navbar-light px-4">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">OJ</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse ml-auto" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#Introduction">About</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#Experiences">Experience</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#Projects">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.navbar {
  padding-top: 15px;
  padding-bottom: 15px;
  border: 0;
  border-radius: 0;
  margin-bottom: 0;
  font-size: 12px;
  letter-spacing: 3px;
  height: 80px;
  background: #f0f2f2;
}
.dot {
  height: 40px;
  width: 40px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  text-align: center;
}
</style>
