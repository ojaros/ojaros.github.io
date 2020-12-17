<template>
  <div id="Projects" class="container">
    <h1>Projects</h1>
    <hr class="dark mb-5" />

    <div class="row">
      <div class="col-12 col-sm-6 my-auto">
        <img src="~/assets/images/nba.jpg" alt="nba" class="center rounded" />
      </div>
      <div class="col-12 col-sm-6 my-auto">
        <div class="card">
          <h4>NBA Prediction Model</h4>
          <p>2020</p>
          <ul>
            <li>
              Created a model to predict the final score of NBA games and compare them to the vegas point spread.
            </li>
            <li>
              Used Python packages such as selenium, pandas, matplotlib, numpy, and sklearn to scrape data and store it efficiently.
            </li>
            <li>
              Based linear regression model off of data from every game in the past 10 years.
            </li>
            <li>
              Predict the final score of a given NBA game based on their current form by inputting average four factors of each teams last 10 games
            </li>
          </ul>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="col-12 col-sm-6">
        <div class="card">
          <h4>Sonia's Snack Bar</h4>
          <p>2018</p>
          <ul>
            <li>
              Recognized an existing problem of long lines at my high school’s
              snack bar, not allowing time for students to get snacks in between
              class.
            </li>
            <li>
              Developed an application using Xcode to allow students to
              pre-order snacks from anywhere on campus, paying with their
              student ID number.
            </li>
            <li>
              Reduced lines as orders were automated, allowed students to avoid
              lines and pick up items between classes.
            </li>
            <li>
              Received over 200 downloads on the iOS App Store within the first
              week.
            </li>
          </ul>
        </div>
      </div>
      <div class="col-12 col-sm-6">
        <img src="~/assets/images/lfa.png" alt="lfa" class="center" />
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.card {
  border: none;
  padding: 1.25rem;
  background-color: #fff;
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
