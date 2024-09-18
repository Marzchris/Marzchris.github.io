<!DOCTYPE html>
<html>
<head>
  <title>Images</title>
  <style type="text/css">
    body {
      color: #665544;
      background-color: #d4d0c6;
      background-image: url("images/backdrop.gif");
      font-family: Georgia, "Times New Roman", serif;
      text-align: center;
    }
    .wrapper {
      width: 720px;
      margin: 0px auto;
    }
    header {
      margin: 40px 0px 20px 0px;
    }
    .entry {
      width: 220px;
      float: left;
      margin: 10px;
      height: auto; /* Adjust height to auto */
      background-image: url("images/shadow.png");
      background-repeat: no-repeat;
      background-position: bottom;
    }
    figure {
      display: block;
      width: 100%; /* Make figure take up the full width of its container */
      background-color: #e7e3d8;
      margin: 0px;
      padding: 9px;
      text-align: left;
    }
    figure img {
      width: 100%; /* Scale the image to fit the figure width */
      height: auto; /* Maintain the aspect ratio */
      border: 1px solid #d6d6d6;
      object-fit: cover; /* Cover the area while maintaining aspect ratio */
    }
    figcaption {
      background-image: url("images/icon.png");
      padding-left: 20px;
    }
  </style>
</head>
<body>
  <div class="wrapper">
    <header>
      <img src="IMG_0271.JPG" alt="Galerie Botanique" width="456" height="122" />
      <p>Here are some pictures of my beautiful girlfriend.</p>
    </header>

    <div class="entry">
      <figure>
        <img src="01HN6ZFTJ06279CHTVAC80JXZP-low-res-branded-.jpeg" alt="Helianthus" />
        <figcaption>Helianthus</figcaption>
      </figure>
    </div>

    <div class="entry">
      <figure>
        <img src="IMG_4345.JPG" alt="Passiflora" />
        <figcaption>Passiflora</figcaption>
      </figure>
    </div>

    <div class="entry">
      <figure>
        <img src="IMG_4897.jpeg" alt="Nyctocalos" />
        <figcaption>Nyctocalos</figcaption>
      </figure>
    </div>

    <div class="entry">
      <figure>
        <img src="IMG_5018.jpeg" alt="Polianthes" />
        <figcaption>Polianthes</figcaption>
      </figure>
    </div>

    <div class="entry">
      <figure>
        <img src="IMG_5036.jpeg" alt="Ficus" />
        <figcaption>Ficus</figcaption>
      </figure>
    </div>

    <div class="entry">
      <figure>
        <img src="IMG_6553.jpeg" alt="Dendrobium" />
        <figcaption>Dendrobium</figcaption>
      </figure>
    </div>
  </div>
</body>
</html>
