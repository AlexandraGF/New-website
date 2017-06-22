
<html>
  <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css"/>
  <link rel="stylesheet" class="text/css" href="https://codepen.io/AlexandraGF/pen/weddOr.css"/>
  <link rel="stylesheet" class="text/javascript" href="https://codepen.io/AlexandraGF/pen/weddOr.js"/>

  <h1 class="text-heading">And your journey begins today...</h1>
  <a href="https://unnoticed.blog"><h2 class="text-2">by Alexandra F.</h2></a>
  
    <button class="Instagram"><a href="https://www.instagram.com/unnoticedblog/">Instagram</a></button>
 
   <button class="Twitter">
              <a href="https://twitter.com/unnoticedblog">Twitter</a></button><br>
  <br><br>
  
  <p class="Paragraph">If we would have to wait until we're ready, we might wait a long time...so why not today?</p><br>
 
  <div id="myDiv">
  Image selection<br>
  <img id="myImage" src="https://unnoticeddotblog.files.wordpress.com/2017/04/img_3525-2.jpg?w=2000&h=1500&crop=1">
</div>
<br><br>
<input type="button" onclick="randomImg()" value="-------> Click Me! <--------">
  
  
  
  <script>
  window.randomImg = function() {
    var myImage = new Array();
    myImage[0] = "https://unnoticeddotblog.files.wordpress.com/2017/04/img_4042.jpg?w=2000&h=1500&crop=1";
    myImage[1] = "https://unnoticeddotblog.files.wordpress.com/2017/06/img_3806.jpg?w=2000&h=1500&crop=1";
    myImage[2] = "https://unnoticeddotblog.files.wordpress.com/2017/05/img_4082.jpg?w=2000&h=1500&crop=1";
    var random = Math.floor(Math.random() * myImage.length);
    document.getElementById("myImage").src = myImage[random];
  }
  </script>
  
</html>
