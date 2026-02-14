<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Islamic Thoughts</title>
  
  <!-- Font Awesome for icons -->
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

    /* NAVBAR */
    nav {
      background: #0f3d3e;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    nav h2 {
      color: #d4af37;
      margin: 0;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      margin: 0;
      padding: 0;
    }
    nav ul li a {
      text-decoration: none;
      color: white;
      transition: 0.3s;
    }
    nav ul li a:hover {
      color: #d4af37;
    }

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
    .hero h1 {
      font-size: 50px;
      color: #d4af37;
      margin: 0;
    }
    .hero p {
      font-size: 20px;
      color: #ccc;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 30px;
      background: #d4af37;
      color: #0f3d3e;
      text-decoration: none;
      border-radius: 5px;
      font-weight: 600;
    }

    /* LIBRARY SECTION */
    section#library {
      padding: 70px 20px;
      text-align: center;
    }
    section#library h2 {
      color: #d4af37;
      margin-bottom: 30px;
    }
    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .card {
      background: #2a2a2a;
      padding: 30px;
      width: 250px;
      border-radius: 10px;
      transition: 0.3s;
    }
    .card:hover {
      transform: translateY(-10px);
      background: #0f3d3e;
    }
    .card a {
      text-decoration: none;
      color: #d4af37;
      font-weight: 600;
    }
    .card a:hover {
      color: #fff;
    }

    /* MOBILE */
    @media(max-width:768px){
      .hero h1 {
        font-size: 32px;
      }
      .cards {
        flex-direction: column;
        align-items: center;
      }
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

  <!-- You can add other sections like TikTok, YouTube, About, Contact here -->

</body>
</html>
