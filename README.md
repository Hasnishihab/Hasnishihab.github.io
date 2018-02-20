<html>
<head>
<title>firebase_demo</html>
<body>
<h1 id="bigone"></h1>
<script src="https://www.gstatic.com/firebasejs/4.10.0/firebase.js"></script>
<script>
  // Initialize Firebase
  var config = {
    apiKey: "AIzaSyDDbKNNMA3EpNHOBaHVtEAyFVa80dqVpPI",
    authDomain: "fir-95a38.firebaseapp.com",
    databaseURL: "https://fir-95a38.firebaseio.com",
    projectId: "fir-95a38",
    storageBucket: "",
    messagingSenderId: "209626512374"
  };
  firebase.initializeApp(config);
  var bigone=document.getElementById("bigone");
  var dbref=firebase.database().ref().child('text');
  dbref.on('value',snap=>bigone.innerText=snap.val());
</script>
</body>
</html>
