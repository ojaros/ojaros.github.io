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
              Created a model to predict the final scores of NBA games and compare point difference to Vegas spread. 
            <li>
              I first scraped stats from every game in the past 10 years using the stats.nba.com API.
            </li>
            <li>
              I cleaned and manipulated this data to include the four factos of effective field goal percentage, turnover percentage, rebound percentage, and free throw rate.
            </li>
            <li>
              I then found the correlations of these factors to final scores using sklearn with python to create a linear regression model that was able to predict final scores with a margin of error of 5.8 points.
            </li>
            <li>
              After creating the model I scraped the current NBA schedule as well as each team's average four factors from their past 10 games. 
            </li>
            <li>
              I then wrote a function to input the four factors of the teams playing in each game into the model and output the predicted final score.
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
              Recognized the problem of long lines at my high school snack bar causing students to be late to class.
            </li>
            <li>
              Developed iOS application using Xcode allowing students to order snacks from anywhere on campus by paying with their student ID number.
            </li>
            <li>
              Automated and enabled pre-orders to reduce wait time by 70%.
            </li>
            <li>
              Received over 200 downloads on the iOS App Store within a week of launch.
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
