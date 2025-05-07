<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8" />
  <title>Mountaintop removal mining sites in eastern Kentucky</title>
  <meta name="viewport" content="initial-scale=1,maximum-scale=1,user-scalable=no" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;800&display=swap" rel="stylesheet" />
  <style>
    /* Set margin/padding to fit border in box model */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    /* Define styles on body (and all descendants) */
    body {
      margin: 0;
      padding: 0;
      font-family: "Open Sans", sans-serif;
      font-weight: 400;
      color: rgb(32, 32, 32);
      background-color: rgb(236, 232, 228);
    }

    /* Define styles for the headings */
    h1 {
      font-size: 3rem;
      font-weight: 800;
      margin: 10px 0;
      padding: 0;
      color: rgb(0, 0, 0);
    }

    h2 {
      font-size: 2rem;
      font-weight: 800;
      margin: 0;
      padding: 0;
    }


    h3 {
      font-size: 1.5rem;
      font-weight: bold;
      margin-bottom: 10px;
    }

    /* Define styles for the paragraph */
    p {
      font-size: 1.3rem;
      font-weight: 400;
      margin: 0 0 10px 0;
      padding: 0;
    }

    a:link,
    a:visited {
      color: rgb(12, 73, 34);
    }

    a:hover {
      color: rgb(86, 86, 86);
      text-decoration: none;
    }

    section {
      width: 80%;
      margin: 0 auto;
    }

    footer {
      width: 80%;
      margin: 0 auto;
      color: rgb(100, 100, 100);
    }

    iframe {
      border: 1px solid rgb(200, 200, 200);
      border-radius: 10px;
      margin-top: 20px;
    }

    .caption {
      font-size: 0.8rem;
      font-weight: 400;
      font-style: italic;
      margin: 0;
      padding: 0;
      color: rgb(100, 100, 100);
    }

    .title {
      text-align: left;
      margin: 20px;
    }

    /* Set up a container for the two columns */
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }

    /* Define styles for the left column */
    .left-column {
      flex-basis: 40%;
      padding: 20px;
      margin-bottom: 20px;
    }

    /* Define styles for the right column */
    .right-column {
      flex-basis: 55%;
      background-color: rgba(255, 255, 255, 0.35);
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
    }

    /* Round image corners for images inside the right-column */
    .right-column img {
      border-radius: 10px;
    }

    /* Media query for small screens */
    /* For screens up to 768px, apply these rules. */
    @media (max-width: 768px) {

      /* Change to a single column layout */
      .container {
        flex-direction: column;
      }

      /* Set full width for both columns */
      .left-column,
      .right-column {
        flex-basis: 100%;
      }
    }
  </style>
</head>

<body>
  <section>
    <!-- 💡💡💡 Cesium map: paste embed code below -->
    <iframe title="GEO 409: Final Project" width="1024" height="576" src="https://ion.cesium.com/stories/viewer/?id=362a872e-b9bb-483a-affc-5f3902777ec9" frameborder="0" allow="fullscreen" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
    <!-- 💡💡💡 Cesium map: paste embed code above -->
    <p class="caption">Lidar pointcloud visualization of eastern Kentucky</p>
    <div class="title">
      <h1>Mountaintop removal mining sites in eastern Kentucky</h1>
      <h2>Ecologically destructive mining practices throughout eastern Kentucky contribute to increased flooding patterns. These maps depict terrain modification between 1990 and 2010 and lack of vegetation at one of these sites.</h2>
    </div>
    <div class="container">
      <div class="left-column">
        <h3>Background and Relevance</h3>
        <p>
          This specific mining site is just south of Robinson Forest, the University of Kentucky's pristine forest for exploring Appalachian sustainability. Several U.K. students visit for class trips and additional extracirricular activities, and the area boasts one of the cleanest watersheds in eastern Kentucky. However, as demonstrated by this project, Robinson Forest has a close proximity to coal mining sites. 
        </p>

        <p>
          The goal of this project is to measure and visualize the vegetation loss and terrain modification of a coal mining site in eastern Kentucky. Near the Cumberland Plateau especially, mountaintop removal practices have swept through and decimated forests throughout eastern Kentucky. By removing natural vegetation from the tops of mountains, water flowing downhill is able to accumulate on a vaster scale and contribute to unprecedented flooding threats, as witnessed in the summer of 2022.
        </p>

        <p>
          Visualizations created from lidar data provided by
          <a href="https://kyfromabove.ky.gov/">KyFromAbove</a> in ArcGIS Pro and
          Blender.
        </p>

        <p>
          Page and visualizations created by Sophia McKay for GEO 409, Department of
          Geography, University of Kentucky. Spring 2024.
        </p>


      </div>
      <div class="right-column">
        <h3>Right Column - Vizualizations </h3>
        <img src="Layout3.jpg" alt="Terrain modification between 1990s and 2010s" width="100%" />
        <p class="caption">Terrain modification between 1990s and 2010s</p>
        <img src="Layout4.jpg" alt="Shaded relief of mining site" width="100%" />
        <p class="caption">Shaded relief of mining site</p>
      </div>
    </div>
  </section>
  <footer>
    <hr />
    <img src="logo-color-400px.png" alt="UKy Arts and Sciences  " width="300px">

  </footer>
</body>

</html>

