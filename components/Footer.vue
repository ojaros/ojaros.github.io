<template>
  <footer id="Contact" class="container-fluid bg-5 text-center">
    <h1 class="text-white">Contact</h1>
    <hr class="light" />

    <div class="row">
      <div class="col-4">
        <a
          href="mailto:oliverjaros214@gmail.com"
          title="oliverjaros214@gmail.com"
        >
          <img class="contactIcons" src="images/gmail.png" />
          <div class="contactTxt">Email</div>
        </a>
      </div>

      <div class="col-4">
        <a href="https://github.com/ojaros" title="github.com/ojaros">
          <img class="contactIcons" src="images/git1.png" />
          <div class="contactTxt">Github</div>
        </a>
      </div>

      <div class="col-4">
        <a
          href="https://www.linkedin.com/in/oliver-jaros-256382156/"
          title="linkedin.com/in/oliver-jaros-256382156/"
        >
          <img class="contactIcons" src="images/linkedin1.png" />
          <div class="contactTxt">Linkedin</div>
        </a>
      </div>
    </div>
  </footer>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.container-fluid {
  padding-top: 70px;
  padding-bottom: 70px;
}
.contactIcons {
  height: 100px;
  width: 100px;
  display: inline-block;
  margin-right: 10px;
  margin-left: 10px;
  margin-top: 10px;
  margin-bottom: 10px;
}
@media (min-width: 768px) {
  .contactIcons {
    height: 125px;
    width: 125px;
  }
}
.contactTxt {
  font-family: 'Lato', sans-serif;
  line-height: 1.8;
  color: #f5f6f7;
}

.bg-5 {
  background-color: #64646d;
}
</style>
