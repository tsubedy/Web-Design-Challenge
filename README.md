<!DOCTYPE html>
<html lang="en-us">
<head>
    <meta charset="UTF-8">
    <title>Comparison</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="Resources/assets/images/equatorsign.png" type="image/x-icon">
  </head>
  
  <body>
  <nav class="navbar navbar-default">
    <div class="container-fluid">
      <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="index.html">Home</a>
      </div>
    
  
      <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      
        <ul class="nav navbar-nav navbar-right">
            <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Plots <span class="caret"></span></a>
            <li class="dropdown"></li>
            <li><a href="Comparison.html">Comparison</a></li>
            <li><a href="Dataset.html">Dataset</a></li>
            <ul class="dropdown-menu">
              <li><a href="temperature.html">Max Temperature</a></li>
              <li><a href="Humidity.html">Humidity</a></li>
              <li role="separator" class="divider"></li> 
              <li><a href="Cloudiness.html">Cloudiness</a></li>
              <li><a href="Wind_speed.html">Wind Speed</a></li>
        </li>
      </ul>
      </div>
    </div>
  </nav>

<!-- Contents-->              

    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <h1>Weather Analysis Project</h1>
        </div>  
                  
        <div class="col-md-8">
            <p>The purpose of this project was to analyse how weather changes as you get close to the equator. To
            accomplish this we first pulled data from 500 randomly chosen city around the world, using an OpenWeatherMap
            API.</p>
              
            <p>After composing the dataset, we used MatPlotLib to plot various aspects of the weather latitute. Factors we
            looked at were temperature, cloudiness, wind speed and humidity. This website provides the source data and
            visualisations created as part of the analysis, as well as explanations and trends or
            correlations witnessed </p>

          </div>    

          <!-- Sidebar -->

          <div class="col-md-4 sidebar">
            <div class="row">
            
              <div class="col-md-12">
                <h1>Visualizations</h1>
              </div>
            </div>
            
            <hr>
              <p class = "i"> For details of each individual variables, please click the graphs below</p> 
            <hr>

          <div class="row">
            <div class="col-md-6">    
              <a href="temperature.html"> Max Temperature<img src="Resources/assets/images/Fig_1_temperature.png" class="img-thumbnail"></a>
            </div>
          
            <div class="col-md-6">  
              <a href="Humidity.html"> Humidity<img src="Resources/assets/images/Fig_2_Humidity.png" class="img-thumbnail"></a>
            </div>
          </div>   

          <div class ="row"> 
            <div class="col-md-6">  
              <a href="Cloudiness.html"> Cloudiness<img src="Resources/assets/images/Fig_3_Cloudiness.png" class="img-thumbnail"></a>
            </div>
            
            <div class="col-md-6">     
              <a href="Wind_speed.html"> Wind Speed<img src="Resources/assets/images/Fig_4_Wind_speed.png" class="img-thumbnail"></a>
            </div>
          </div>    
          </div>         
      </div>      
    </div>	 	

<!-- footer -->

<footer>
  <div class="footer">&copy; Copyright: T Subedy, Sept 2021.</div>
</footer>

<!-- Scripts: -->
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  
</body>
</html>
