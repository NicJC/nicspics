---
title: christchurch
author: ''
date: '2024-12-19'
categories: []
tags:
  - christchurch
---

<link rel="stylesheet" href="styles.css" />

<style>

.button{
padding: 5px 5px 5px 5px  ;
}

</style>
<body>

<p>

Christchurch holiday pics:


<div class="container"
style="text-align: center;"><img style="border-radius: 6px;border: 1.0px solid black;" src="images/ChristchurchTOPO5.png" width="1300" height="800" onclick="enlargeImg()"id="img1" />
 <br><br><br>


<button id="button" onclick="resetImg()">Reset</button>
</div>

</p>

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


