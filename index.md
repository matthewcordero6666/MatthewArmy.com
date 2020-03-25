<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: green;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: tan;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}

/* Clear floats after the columns */
section:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: black;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>
<header>
  <h2>Matthew Empire Army and Horde</h2>
</header>

<section>
  <nav>
    <ul>
      <li><a href="#">about the matthew army</a></li>
      <li><a href="https://matthewcordero6666.github.io/MatthewArmy.com/join_now">join now</a></li>
      <li><a href="https://matthewcordero6666.github.io/MatthewArmy.com/">home</a></li>
    </ul>
  </nav>
  
  <article>
    <h1>Matthew Army</h1>
    <p>The main fighting force of the matthew empire</p>
  <p>second only to genghis khan</p>
  </article>
</section>

<footer>
  <p>Matthew Army: enlist now defeat the enemies of matthew</p>
  <p>"Those who are annoyed by General Matthew, are only jealous of his intelect and fighting skill" - General Davis Gulley</p>
</footer>

</body>
</html>
