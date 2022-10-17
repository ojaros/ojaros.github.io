
<template>
  <div id = "Experience" class="container">
    <h1> Experience </h1>
    <hr class = "dark mb-5">
    <div class="mb-5">
      <h3 class="mb-4 text-left"> Education </h3>

      <div class="row">
        <div class="col-12 col-sm-6 my-auto">
          <img src="~/assets/images/VerticalstackedRed.png" alt="scu" class="center">
        </div>
        <div class="col-12 col-sm-6">
          <div class="card"><h4> <strong>Santa Clara University</strong> </h4>
            <p>Expected Graduation: 2022</p>
            <p>
              <ul>
                <li>B.S. in Computer Science & Mathematics </li>
                <li>Minor in Desing Thinking and Entrepreneurship</li>
                <li>Relevant Coursework: Calculus 1-4, Discrete Mathematics, Linear Algebra, Probability and Statistics, Object Oriented Programming (C++), Data Structures, Theory of Algorithms, Embedded Systems, Logic Design, Operating Systems, Applied Entrepreneurship.</li>
              </ul>
            </p>
          </div>
        </div>
      </div>
    </div>

    <h3 class="mb-4 text-left"> Work </h3>

    <div class="row">
      <div class="col-12 col-sm-6">
        <div class="card">
          <h4>Software Engineering Intern</h4>
          <p>CMT Asset Management<br>Summer 2021</p>
          <ul>
            <li>Built a dashboard to display hundreds of our venture fund’s investments and raises by creating a PostgreSQL database and writing Django models defined as Company, Fund, Raise, and Investment.</li>
            <li>Used Django REST Framework to serialize models and create URI endpoints to display data in React frontend.</li>
            <li>Assisted with building application to display crypto trading desk’s positions, transfers, and trades by writing 3 Golang microservices and Django models for each of these.</li>
            <li>Wrote scripts to pull data from 9 crypto exchange API’s that the desk trades on and displayed on 3 separate tables in React frontend.</li>
          </ul>
        </div>
      </div>
      <div class="col-12 col-sm-6 my-auto">
        <img src="~/assets/images/CMT.jpg" alt="CMT" class="center">
      </div>
    </div>

    <div class="row">
      <div class="col-12 col-sm-6 my-auto">
        <img src="~/assets/images/bigblue.jpg" alt="bigblue" class="center">
      </div>
      <div class="col-12 col-sm-6">
        <div class="card">
          <h4>Software Engineering Intern</h4>
          <p>Big Blue Swim School <br>Summer 2020</p>
          <ul>
            <li>Rewrote several components to support migration of the company website from Angular to Vue.</li>
            <li>Improved on styling and UI of website using Tailwind CSS.</li>
            <li>Participated in daily progress report meetings with Scrum team and sprint planning meetings every 2 weeks.</li>
            <li>Fixed bugs on login and payment pages of mobile application coding in Dart with Flutter.</li>
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
