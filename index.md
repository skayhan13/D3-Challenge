<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>D3Times</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
  <link rel="stylesheet" href="assets/css/style.css">
  <link rel="stylesheet" href="assets/css/d3Style.css">

</head>

<body>
  <div class="container">
    <div class="row">
      <div class="col-xs-12 col-md-12">
        <h1>D3Times</h1>
      </div>
    </div>
    <div class="row">
      <div class="col-xs-12  col-md-9">
        <div id="scatter">
          <!-- We append our chart here. -->
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-xs-12  col-md-9">
        <div class="article">
          <h2>Correlations Discovered Between Health Risks and Age, Income</h2>
          <p> The D3 enabled interactive scatterplot above allows you to click through multiple variables to compare and contrast their relationships with each other with respect to U.S. states. Click through each variable combination to see how they relate.</p>

          <p>Here are the noteworthy findings: there appears to be a positive correlation between the Lacks Healthcare and In Poverty. Southern states tend to have the highest rates of poverty and less healthcare coverage (with Texas being an outlier as it has the highest % lacking healthcare) while some New England states have the lowest rates of poverty and lack of healthcare.</p>

          <p>The age demographic is squarely within the middle age range from age 30-45.  Furthermore, there is a negative correlation between Lacks Healthcare and Household Income, so wealthier states tend to have more healthcare coverage. Smoking has a positive correlation with poverty, none with age, and a negative correlation with household income.  Finally, obesity also has a positive correlation with poverty, none with age, and a negative correlation with household income.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer-->
  <div id="footer">
    <p>Sara Kayhan&copy;2021</p>
  </div>
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  <script src="https://d3js.org/d3.v5.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/d3-tip/0.9.1/d3-tip.js"></script>
  <script type="text/javascript" src="assets/js/app.js"></script>

</body>

</html>
