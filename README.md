<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Interactive Name</title>
<style>
  @keyframes move {
    0% { transform: translateY(0); }
    50% { transform: translateY(-5px); }
    100% { transform: translateY(0); }
  }
  
  .name-letter {
    animation: move 1s infinite;
  }

  .green-text {
    color: green;
  }
</style>
</head>
<body>
  <h1>
    <span class="name-letter">J</span>
    <span class="name-letter">o</span>
    <span class="name-letter">s</span>
    <span class="name-letter">é</span>
    <span class="name-letter"> </span>
    <span class="name-letter">M</span>
    <span class="name-letter">u</span>
    <span class="name-letter">l</span>
    <span class="name-letter">l</span>
    <span class="name-letter">e</span>
    <span class="name-letter">r</span>
  </h1>
  <p class="green-text">Profissão: Data Scientist</p>
</body>
</html>


