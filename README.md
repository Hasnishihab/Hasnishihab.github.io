<html>
<head>
</head>
<body>
<div id="lat"></div>
<div id="lng"></div>
<p>the values in the client is</p>
<br>
    <script>
      document.getElementById("lat").innerHTML = localStorage.getItem("lattitude");
	  document.getElementById("lng").innerHTML = localStorage.getItem("longitude");
	  //document.write(name + "<br>");
         
     </script> 
  
  </body>
</html>

