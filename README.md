<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>My Website</title>
  <style>
    /* CSS for the navigation menu */
    .navigation-menu {
      display: none; /* Initially hide the navigation menu */
    }
    .show-menu .navigation-menu {
      display: block; /* Display the navigation menu when the button is clicked */
    }
  </style>
</head>
<body>
  <button id="navButton">ChatGPT</button>
  <div class="navigation-menu">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </div>

  <script>
    // JavaScript to toggle the navigation menu
    document.getElementById("navButton").addEventListener("click", function() {
      document.body.classList.toggle("show-menu");
    });
  </script>
</body>
</html>
