# MODULE-44


<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Module 4 Solution Starter</title>
  <script src="SpeakHello.js"></script>
  <script src="SpeakGoodBye.js"></script>
  <script src="script.js"></script>
</head>
<body>
  <h1>Module 4 Solution Starter</h1>
  <p>open console to see the output</p>
</body>
</html>

(function(window) {
	var speakWord = "Hello";
	var helloSpeaker = function (name) {
		console.log(speakWord + " " + name);
	}

	window.helloSpeaker = helloSpeaker;

})(window);
(function(window) {
	var speakWord = "Good Bye";
	var byeSpeaker = function (name) {
  		console.log(speakWord + " " + name);
	}
	
	window.byeSpeaker = byeSpeaker;

})(window);
