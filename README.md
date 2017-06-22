
<html>
  <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css"/>
  <link rel="stylesheet" class="text/css" href="https://codepen.io/AlexandraGF/pen/weddOr.css"/>

  <h1 class="text-heading">And your journey begins today...</h1>
  <a href="https://unnoticed.blog"><h2 class="text-2">by Alexandra F.</h2></a>
  
    <button class="Instagram"><a href="https://www.instagram.com/unnoticedblog/">Instagram</a></button>
 
   <button class="Twitter">
              <a href="https://twitter.com/unnoticedblog">Twitter</a></button><br>
  <br><br>
  
  <p class="Paragraph">If we would have to wait until we're ready, we might wait a long time...so why not today?</p><br>
  
  <script>
  $(document).ready(function() {

    $("#getMessage").on("click", function() {
      $.getJSON("https://unnoticed.blog/2017/06/21/beautiful-day-in-london/", function(json) {

        var html = "";

        json.forEach(function(val) {

          html += "<div class = 'cat'>";

          // Only change code below this line.
          
          html += "<img src = '" + val.imageLink + "' " + "alt='" + val.altText + "'>";
          

          html += "</div>";

        });

        $(".message").html(html);

      });
    });
  });
</script>

<div class="container-fluid">
  <div class = "row text-center">
    <h2>Cat Photo Finder</h2>
  </div>
  <div class = "row text-center">
    <div class = "col-xs-12 well message">
      The message will go here
    </div>
  </div>
  <div class = "row text-center">
    <div class = "col-xs-12">
      <button id = "getMessage" class = "btn btn-primary">
        Get Message
      </button>
  
 
</html>

