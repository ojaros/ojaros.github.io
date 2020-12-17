<template>
  <div class="card text-center mt-5">
    <div class="card-body">
      <img
        src="~/assets/images/Jaros-7.jpg"
        class="mb-3"
        alt="Me"
        width="200"
        height="400"
      />
      <h1 class="mb-3 text-dark">Oliver Jaros</h1>
      <a href="/OliverJarosResume.pdf" download = "" class="btn btn-lg"> Resume </a>
      <a href="mailto:oliverjaros214@gmail.com" class="btn btn-lg"> Contact </a>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.container-fluid {
  padding-top: 70px;
  padding-bottom: 70px;
}
.card {
  background-color: rgba(255, 255, 255, 0.8);
  border-radius: 0.25rem;
  border: none;
}
.btn {
  background-color: #97afa3;
  color: #fff;
}
img {
  border-radius: 50%;
}
</style>
