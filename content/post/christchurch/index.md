---
title: christchurch
author: ''
date: '2024-12-19'
categories: []
tags:
  - christchurch
---

<link rel="stylesheet" href="styles.css" />


<body>

<style>
#button {
  position: sticky
  bottom: 5px;
  padding: 100px 50px;
        }
</style>

<p>
Christchurch holiday pics:
</p>

<div class="container"
style="text-align: center;"><img style="text-align: center;
                margin-top: 5em;" src="images/ChristchurchTOPO5.png" width="1300" height="800" onclick="enlargeImg()"id="img1" />
 <br><br><br>


<button id="button" onclick="resetImg()">Reset</button>
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


