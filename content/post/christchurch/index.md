---
title: christchurch
author: ''
date: '2024-12-19'
categories: []
tags:
  - christchurch
---

library(leaflet)

<link rel="stylesheet" href="styles.css" />

m <- leaflet()
m <- addTiles(m)
m <- addMarkers(m, lng=174.71625, lat=-37.1394, popup="Our Home") 
# %>% addPopups(lng=174.71625,lat= -37.1394, "Here is our Home")  https://rstudio.github.io/leaflet/reference/leaflet.html#ref-examples
m



<body>

<style>

#button {
   position: relative;
   float: left;
   font-weight: bold;
   margin: margin: 0px 0px 0px 0px;
   padding:5px 5px;
   color: #e30b0b;
   background-color: transparent;
   border-width: 1;
        }
        
#button:hover {
        cursor: pointer;
        background: #1e1d25;
      }
      
      
      
</style>



<p>
Christchurch holiday pics:
</p>

<div class="container"
style="text-align: center;"><img style="text-align: center;
                margin-top: 5em;" src="images/ChristchurchTOPO5.png" width="1300" max-height: 800px; onclick="enlargeImg()"id="img1" />
 


<button id="button" onclick="resetImg()">Reset map</button>
</div>

<br>

<center>
<img style="float: right; margin: 10px 10px 15px 15px;border-radius: 6px;border: 1.0px solid black;" src="images/chch.jpg" width="500" height="500"/>

</center>

<script>
img = document.getElementById("img1");
      
        function enlargeImg() {
            img.style.transform = "scale(1.5)";
            img.style.transition = "transform 0.25s ease";
        }
      
        // Function to reset image size
        function resetImg() {
            img.style.transform = "scale(1)";
            img.style.transition = "transform 0.25s ease";
        }


</script>


</body>

</html>


