<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
      <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
</head>
<body>
    <img class="image_gradient" src="gradient.png" alt="gradient"> 
    <div class="layer_blur"></div>
    <div class="container">
        <header class="nav_box">
            <h1 data-aos="fade-down" data-aos-duration= "1500" class="logo">Kesh_v</h1>
            <nav>
                <a data-aos="fade-down" data-aos-duration= "1500"  href="#">Projects</a>
                <a data-aos="fade-down" data-aos-duration= "2000"  href="#">About</a>
                <a data-aos="fade-down" data-aos-duration= "2500"  href="#">Skills</a>
                <a data-aos="fade-down" data-aos-duration= "3000"  href="#">Contact</a>
            </nav>
        </header>
       <main>
        <div class="content">
              <h1 data-aos="fade-zoom-in"
     data-aos-easing="ease-in-back"
     data-aos-delay="300"
     data-aos-offset="0" data-aos-duration= "2000">I'm<br>Keshav</h1>
                <p data-aos="fade-zoom-in"
     data-aos-easing="ease-in-back"
     data-aos-delay="300"
     data-aos-offset="0" data-aos-duration= "2000" class="description">A 2nd-year Computer Science Engineering student at Kurukshetra University with a passion for programming, problem-solving, and emerging technologies. Focused on core CS subjects and gaining hands-on experience in web development, AI, and software engineering.
        </div>
       </div>
       </main>
        <spline-viewer data-aos="fade-zoom-in"
     data-aos-easing="ease-in-back"
     data-aos-delay="300"
     data-aos-offset="0" data-aos-duration= "2500" class="robo_3d" loading-anim-type="spinner-small-dark" url="https://prod.spline.design/llawedKZD4FPrQHM/scene.splinecode"></spline-viewer>
    </div>
    <script type="module" src="https://unpkg.com/@splinetool/viewer@1.10.22/build/spline-viewer.js"></script>


  <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
</body>
</html>
