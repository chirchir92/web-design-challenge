<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>landing page</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<!------------------------------------------------------------------------->
<body>
    <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
        <div class="navbar-header">
            <a class="navbar-brand" href="landing-page.html">Latitude</a>
        </div>
        <ul class="nav navbar-nav navbar-right">
            <li class="dropdown">
                <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true"
                    aria-expanded="false">Plots <span class="caret"></span></a>
                <ul class="dropdown-menu">
                    <li><a href="max-temp.html">Max Temperature</a></li>
                    <li><a href="humidity.html">Humidity</a></li>
                    <li><a href="cloudiness.html">Cloudiness</a></li>
                    <li><a href="wind-speed.html">Wind Speed</a></li>
                </ul>
            </li>
            <li><a href="comparison.html">Comparison</a></li>
            <li><a href="data-table.html">Data</a></li>
        </ul>
    </div>
    </div>
</nav>
<br>
<br>
<br>
<!------------------------------------------------------------------------>
<div class="container">
    <div class="row">
        <div class="col-lg-8 col-sm-12">
            <div style="background-color:white;">
            <h1 style="color: rgb(63, 171, 171)">Summary: Latitude vs X</h1>

            <hr>
            <img src="max_temp.png" alt="humidity" height="200" width="200" align="left">
            <p><br>The purpose of this project was to analysis how weather patterns may change and alter as one travels
                closer to the equator. An Open Weather API and the CitiPy Python Library to randomly pull 500 cities
                from around the world was to create the dataset.
                <br>
                <br>
                <br>
                After assembling the data, Pandas and Matplotlib Python libraries were used to analyze the data set.
                The four dependent variables were: Max Temperature, Humidity, Cloudiness, and Wind Speed.
                <br>
                This dashboard shows the source data and the visualizations based on the four dependent variables.</p>
            </div>
        </div>

        <div class="col-md-4 col-sm-12 offset-md-1" style="background-color:white;" id="viz">
            <h2 style="color: rgb(63, 171, 171)">Visualizations</h2>
            <hr>

            <div class="col-md-6 col-sm-3">
                <img src="max_temp.png" alt="maxtemp" height="150" width="150">
            </div>

            <div class="col-md-6 col-sm-3">
                <img src="humidity.png" alt="humidity" height="150" width="150">
            </div>

            <div class="col-md-6 col-sm-3">
                <img src="cloudiness.png" alt="cloudiness" height="150" width="150">
            </div>
            
            <div class="col-md-6 col-sm-3">
                <img src="wind_speed.png" alt="windspeed" height="150" width="150">
            </div>
        </div>
    </div>
</div>
</body>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/js/bootstrap.min.js"></script>
</html>
