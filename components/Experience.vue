
<template>
  <div id = "Experiences" class="container">
    <h1> Experience </h1>
    <hr class = "dark mb-5">
    <div class="mb-5">
      <h3 class="mb-4 text-left"> Education </h3>

      <div class="row">
        <div class="col-12 col-sm-6">
          <div class="card"><h4> <strong>Santa Clara University</strong> </h4>
            <p>Expected Graduation: 2022</p>
            <p>
              <strong>B.S. in Computer Science & Mathematics </strong>
              <ul>
                <li>Minor in Desing Thinking and Entrepreneurship</li>
                <li>Related Coursework: Object Oriented Programming (C++), Data Structures, Algorithms, Discrete Mathematics, Logic Design, Linear Algebra</li>
              </ul>
            </p>
          </div>
        </div>
        <div class="col-12 col-sm-6 my-auto">
          <img src="~/assets/images/VerticalstackedRed.png" alt="scu" class="center">
        </div>
      </div>
    </div>

    <h3 class="mb-4 text-left"> Work </h3>

    <div class="row">
      <div class="col-12 col-sm-6 my-auto">
        <img src="~/assets/images/bigblue.jpg" alt="bigblue" class="center">
      </div>
      <div class="col-12 col-sm-6">
        <div class="card">
          <h4>Software Engineering Intern</h4>
          <p>Big Blue Swim School <br>Summer 2020</p>
          <ul>
            <li>Worked on both front end and back end of website using frameworks such as Vue and Tailwind</li>
            <li>Participated in daily meetings sharing progress reports with Agile team</li>
            <li>Assisted in the development of mobile application coding in Flutter</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-12 col-sm-6">
        <div class="card">
          <h4>Bartender</h4>
          <p>The Sports Hall <br>Summer 2019</p>
          <ul>
            <li>Provided excellent customer service by catering to the needs of all patrons.</li>
            <li>Learned to handle pressure by serving over 100 customers every fast-paced Saturday night.</li>
          </ul>
        </div>
      </div>
      <div class="col-12 col-sm-6 my-auto">
        <img src="~/assets/images/sportshall.png" alt="sportshall" class="center">
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.card {
  border: none;
  padding: 1.25rem;
  background-color: #f0f2f2;
}
.row {
  margin-bottom: 2rem;
}
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}
</style>
