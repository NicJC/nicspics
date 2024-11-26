<!DOCTYPE html>
<html>
<head>
<style> 
#main {
  width: 140px;
  height: 300px;
  border: 1px solid #000000;
  display: flex;
  flex-wrap: wrap;
  align-content: space-around; 
}

#main div {
  width: 70px;
  height: 70px;
}
</style>
</head>
<body>

<h1>Change align-content with JavaScript</h1>

<div id="main">
  <div style="background-color:coral;"></div>
  <div style="background-color:lightblue;"></div>
  <div style="background-color:khaki;"></div>
  <div style="background-color:pink;"></div>
  <div style="background-color:lightgrey;"></div>
  <div style="background-color:lightgreen;"></div>
</div>



<script>
function myFunction() {
  document.getElementById("main").style.alignContent = "space-between";
}
</script>

</body>
</html>