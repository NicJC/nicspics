---
title: "christchurch"
author: ''
date: "2024-12-19"
categories: []
tags: christchurch
---

<link href="{{< blogdown/postref >}}index_files/htmltools-fill/fill.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/htmlwidgets/htmlwidgets.js"></script>
<script src="{{< blogdown/postref >}}index_files/jquery/jquery-3.6.0.min.js"></script>
<link href="{{< blogdown/postref >}}index_files/leaflet/leaflet.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/leaflet/leaflet.js"></script>
<link href="{{< blogdown/postref >}}index_files/leafletfix/leafletfix.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/proj4/proj4.min.js"></script>
<script src="{{< blogdown/postref >}}index_files/Proj4Leaflet/proj4leaflet.js"></script>
<link href="{{< blogdown/postref >}}index_files/rstudio_leaflet/rstudio_leaflet.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/leaflet-binding/leaflet.js"></script>

``` r
library(leaflet)
```

    ## Warning: package 'leaflet' was built under R version 4.4.2

``` r
m <- leaflet()
m <- addTiles(m)
m <- addMarkers(m, lng=174.71625, lat=-37.1394, popup="Christchurch") 
# %>% addPopups(lng=172.733211,lat= -43.486805,  "Christchurch")  https://rstudio.github.io/leaflet/reference/leaflet.html#ref-examples
m
```

<div class="leaflet html-widget html-fill-item" id="htmlwidget-1" style="width:672px;height:480px;"></div>
<script type="application/json" data-for="htmlwidget-1">{"x":{"options":{"crs":{"crsClass":"L.CRS.EPSG3857","code":null,"proj4def":null,"projectedBounds":null,"options":{}}},"calls":[{"method":"addTiles","args":["https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",null,null,{"minZoom":0,"maxZoom":18,"tileSize":256,"subdomains":"abc","errorTileUrl":"","tms":false,"noWrap":false,"zoomOffset":0,"zoomReverse":false,"opacity":1,"zIndex":1,"detectRetina":false,"attribution":"&copy; <a href=\"https://openstreetmap.org/copyright/\">OpenStreetMap<\/a>,  <a href=\"https://opendatacommons.org/licenses/odbl/\">ODbL<\/a>"}]},{"method":"addMarkers","args":[-37.1394,174.71625,null,null,null,{"interactive":true,"draggable":false,"keyboard":true,"title":"","alt":"","zIndexOffset":0,"opacity":1,"riseOnHover":false,"riseOffset":250},"Christchurch",null,null,null,null,{"interactive":false,"permanent":false,"direction":"auto","opacity":1,"offset":[0,0],"textsize":"10px","textOnly":false,"className":"","sticky":true},null]}],"limits":{"lat":[-37.1394,-37.1394],"lng":[174.71625,174.71625]}},"evals":[],"jsHooks":[]}</script>

<link rel="stylesheet" href="styles.css" />

<body>
<style>
&#10;#button {
   position: relative;
   float: left;
   font-weight: bold;
   margin: margin: 0px 0px 0px 0px;
   padding:5px 5px;
   color: #e30b0b;
   background-color: transparent;
   border-width: 1;
        }
        &#10;#button:hover {
        cursor: pointer;
        background: #1e1d25;
      }
      &#10;      
      &#10;</style>
<p>
Christchurch holiday pics:
</p>

<div class="container" style="text-align: center;">

\<img style=“text-align: center;
margin-top: 5em;” src=“images/ChristchurchTOPO5.png” width=“1300” max-height: 800px; onclick=“enlargeImg()”id=“img1” /\>

<button id="button" onclick="resetImg()">
Reset map
</button>

</div>

<br>

<center>

<img style="float: right; margin: 10px 10px 15px 15px;border-radius: 6px;border: 1.0px solid black;" src="images/chch.jpg" width="500" height="500"/>

</center>
<script>
img = document.getElementById("img1");
      &#10;        function enlargeImg() {
            img.style.transform = "scale(1.5)";
            img.style.transition = "transform 0.25s ease";
        }
      &#10;        // Function to reset image size
        function resetImg() {
            img.style.transform = "scale(1)";
            img.style.transition = "transform 0.25s ease";
        }
&#10;
</script>
</body>
</html>
