<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Islamic Thoughts</title>

  <!-- Font Awesome for social icons -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

  <style>
    /* General Styles */
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #f4f4f4;
      color: white;
    }

    a { text-decoration: none; }

    /* NAVBAR */
    nav {
      background: #0f3d3e;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    nav h2 { color: #d4af37; margin: 0; }
    nav ul { list-style: none; display: flex; gap: 20px; margin: 0; padding: 0; }
    nav ul li a { color: white; transition: 0.3s; }
    nav ul li a:hover { color: #d4af37; }

    /* HERO */
    .hero {
      height: 85vh;
      background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)),
                  url("https://images.unsplash.com/photo-1531497417581-f6d7b04e6197?crop=entropy&cs=tinysrgb&w=1600&fit=max")
                  center/cover no-repeat;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }
    .hero h1 { font-size: 50px; color: #d4af37; margin: 0; }
    .hero p { font-size: 20px; color: #ccc; }
    .btn { display: inline-block; margin-top: 20px; padding: 12px 30px; background: #d4af37; color: #0f3d3e; border-radius: 5px; font-weight: 600; transition: 0.3s; }
    .btn:hover { color: #fff; }

    /* SECTION TITLES */
    section h2 { color: #d4af37; margin-bottom: 20px; text-align: center; }

    /* LIBRARY */
    #library { padding: 70px 20px; text-align: center; }
    .cards { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; }
    .card {
      background: #2a2a2a; padding: 30px; width: 250px; border-radius: 10px; transition: 0.3s;
    }
    .card:hover { transform: translateY(-10px); background: #0f3d3e; }
    .card a { color: #d4af37; font-weight: 600; }
    .card a:hover { color: #fff; }

    /* TikTok */
    #tiktok { background: #0f3d3e; padding: 50px 20px; text-align: center; }
    #tiktok .btn { margin-top: 15px; }

    /* YouTube */
    #youtube { padding: 50px 20px; text-align: center; }
    #youtube .btn { margin-top: 15px; }

    /* About */
    #about { padding: 70px 20px; background: #2a2a2a; text-align: center; }
    #about p { color: #ccc; font-size: 18px; max-width: 700px; margin: 0 auto 20px auto; }

    /* Contact */
    #contact { background: #1e2a2f; color: #fff; padding: 50px 20px; text-align: center; border-radius: 10px; margin: 30px 0; }
    #contact a { color: #d4af37; }
    #contact a:hover { color: #fff; text-decoration: underline; }

    /* Footer */
    footer { background: #111; padding: 30px 20px; text-align: center; border-top: 3px solid #d4af37; }
    footer p { margin: 5px; }
    .social-icons { display: flex; justify-content: center; margin-top: 15px; }
    .social-icons a { color: white; font-size: 28px; margin: 0 12px; transition: 0.3s; }
    .social-icons a:hover { color: #d4af37; }

    /* Mobile */
    @media(max-width:768px){
      .hero h1 { font-size: 32px; }
      .cards { flex-direction: column; align-items: center; }
    }

  </style>
</head>

<body>

  <!-- NAVBAR -->
  <nav>
    <h2>Islamic Thoughts</h2>
    <ul>
      <li><a href="#library">Library</a></li>
      <li><a href="#tiktok">TikTok</a></li>
      <li><a href="#youtube">YouTube</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <div>
      <h1>Inspirational Quran & Sunnah Guidance</h1>
      <p>Explore Islamic knowledge and wisdom</p>
      <a href="#library" class="btn">Explore Library</a>
    </div>
  </section>

  <!-- LIBRARY -->
  <section id="library">
    <h2>Islamic Library</h2>
    <div class="cards">
      <div class="card">
        <a href="https://quran.com/ayaat" target="_blank">Quran & Ayyat</a>
        <p>Read verses from the Holy Quran online.</p>
      </div>
      <div class="card">
        <a href="https://www.al-islam.org/seerah-ahlul-bayt" target="_blank">Seerat Ahl e Bait</a>
        <p>Learn about the lives of Ahlul Bayt.</p>
      </div>
      <div class="card">
        <a href="#">Hadith</a>
        <p>Authentic sayings of Prophet Muhammad ﷺ.</p>
      </div>
    </div>
  </section>

  <!-- TIKTOK SECTION -->
  <section id="tiktok">
    <h2>Follow Us on TikTok</h2>
    <p>Watch short Islamic reminders.</p>
    <a href="https://www.tiktok.com/@imranshahs0" class="btn" target="_blank"><i class="fab fa-tiktok"></i> Visit TikTok</a>
  </section>

  <!-- YOUTUBE SECTION -->
  <section id="youtube">
    <h2>YouTube Channel</h2>
    <a href="https://youtube.com/@islamicthoughts-o3f?si=b4BMtcciwST0wSGv" class="btn" target="_blank"><i class="fab fa-youtube"></i> Visit YouTube</a>
  </section>

  <!-- ABOUT SECTION -->
  <section id="about">
    <h2>About Us</h2>
    <p>Welcome to Islamic Thoughts. We aim to inspire people with the teachings of Islam and provide guidance through the Quran, Sunnah, and the lives of the Prophet ﷺ and Ahlul Bayt. Stay connected with us on our social media platforms and explore Islamic content that can help guide you in daily life.</p>
    <a href="https://wa.me/923448556074" class="btn" target="_blank"><i class="fab fa-whatsapp"></i> Contact Us on WhatsApp</a>
  </section>

  <!-- CONTACT SECTION -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Phone: <a href="tel:+923448256074">03448256074</a></p>
    <p>Email: <a href="mailto:islamiswal51214@gmail.com">islamiswal51214@gmail.com</a></p>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>© 2026 Islamic Thoughts. All Rights Reserved.</p>
    <div class="social-icons">
      <a href="#"><i class="fab fa-facebook"></i></a>
      <a href="#"><i class="fab fa-twitter"></i></a>
      <a href="#"><i class="fab fa-youtube"></i></a>
      <a href="#"><i class="fab fa-tiktok"></i></a>
      <a href="#"><i class="fab fa-whatsapp"></i></a>
    </div>
  </footer>

</body>
</html>
