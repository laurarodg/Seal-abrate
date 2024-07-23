<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Seal World</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Oxygen:wght@300;400&display=swap" rel="stylesheet">
  </head>

  <body>
    <main>
      <section class="inicio">
        <video class="inicio__background" autoplay muted loop>
        <source src="video/pexels-zlatin-georgiev-5607740_2160p.mp4"></video>
        <div class="inicio__foreground">
          <h1 class="inicio__title">Get Ready to Seal-abrate</h1>
          <p class="inicio__text">
            Dive in and Descover the Charm of These Aquatic Wonders
          </p>
        </div>
      </section>
    </main>

    <section class="section">
      <h2 class="section__title">Exploring the World of Seals</h2>
      <img class="section__img" src="img/pexels-minsu-b-11932453.jpg">
      <p class="section__text">
        Hold onto your flippers, because we're about to embark on a journey into
        the lives of seals! These adorable aquatic mammals are real stars of the
        ocean, and they've got some seal-iously cool tales to tell. From Arctic
        cold to sunny shores, seals have mastered the art of enjoying life both
        above and below the waves. Let's splash into the deep waters of seal
        knowledge!
      </p>
      
    </section>

* {
    box-sizing: border-box;
    font-family: 'Oxygen', system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    margin: 0;
    padding: 0;
    scroll-snap-type: mandatory;
}

:root {
    --color-backgroud: #030207;
    --color-white: #fff;
    --color-blue: #1474b4;

}

body {
    background-color: var(--color-backgroud);
    color: var(--color-white);

}


.inicio {
    background: linear-gradient(rgba(0, 0, 0 ,0.1), var(--color-backgroud));
    position: relative;
    min-height: 100vh;

}

.inicio__background {
    object-fit: cover;
    position: absolute;
    top: 0;
    height: 100vh;
    width: 100%;
    z-index: -10;
}
