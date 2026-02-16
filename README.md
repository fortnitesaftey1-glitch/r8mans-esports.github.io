# r8mans-esports.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>R8MANS Esports</title>
  <meta name="description" content="Official website of R8MANS Esports" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Inter', sans-serif;
      background: #0a0a0a;
      color: #ffffff;
      line-height: 1.6;
    }
    header {
      padding: 80px 20px;
      text-align: center;
      background: linear-gradient(135deg, #111, #000);
    }
    header img {
      width: 120px;
      margin-bottom: 20px;
    }
    header h1 {
      font-size: 3rem;
      font-weight: 800;
      letter-spacing: 2px;
    }
    header p {
      margin-top: 10px;
      color: #aaa;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }
    section {
      padding: 80px 20px;
      max-width: 1100px;
      margin: auto;
    }
    h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      font-weight: 800;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #111;
      border: 1px solid #222;
      padding: 30px;
      border-radius: 16px;
    }
    .card h3 { margin-bottom: 10px; }
    .card p { color: #bbb; }
    .cta {
      text-align: center;
      background: #fff;
      color: #000;
      padding: 80px 20px;
    }
    .cta h2 { color: #000; }
    .cta a {
      display: inline-block;
      margin-top: 20px;
      padding: 14px 32px;
      background: #000;
      color: #fff;
      text-decoration: none;
      font-weight: 600;
      border-radius: 999px;
    }
    footer {
      text-align: center;
      padding: 30px;
      background: #000;
      color: #666;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
<nav style="position:fixed; top:0; width:100%; background:#000; padding:16px 30px; display:flex; justify-content:space-between; align-items:center; z-index:1000;">
  <strong style="letter-spacing:2px;">R8MANS</strong>
  <div style="display:flex; gap:20px;">
    <a href="index.html" style="color:#fff; text-decoration:none;">Home</a>
    <a href="roster.html" style="color:#fff; text-decoration:none;">Roster</a>
    <a href="jersey.html" style="color:#fff; text-decoration:none;">Jersey</a>
    <a href="apply.html" style="color:#fff; text-decoration:none;">Apply</a>
  </div>
</nav>
<div style="height:70px;"></div>

<header>
  <!-- Replace src with your uploaded logo -->
  <img src="logo.png" alt="R8MANS Logo" />
  <h1>R8MANS</h1>
  <p>Faith-driven. Competitive. Professional esports organization competing at the highest level.</p>
</header>

<section>
  <h2>About Us</h2>
  <p>
    R8MANS Esports is a competitive organization built on discipline, respect, and excellence. 
    We compete across multiple titles with a focus on long-term growth, clean branding, and professional conduct.
  </p>
</section>

<section>
  <h2>Divisions</h2>
  <div class="cards">
    <div class="card">
      <h3>Fortnite</h3>
      <p>Competitive and creative players across NA and EU.</p>
    </div>
    <div class="card">
      <h3>Upcoming Titles</h3>
      <p>Expanding into new esports titles soon.</p>
    </div>
  </div>
</section>

<section>
  <h2>Join R8MANS</h2>
  <p>We are always looking for dedicated players, creators, and staff.</p>
</section>

<section>
  <h2>Official Jersey</h2>
  <p>Our official R8MANS competition jersey — minimalist, professional, and tournament-ready.</p>
  <div class="cards">
    <div class="card">
      <img src="jersey.png" alt="R8MANS Jersey" style="width:100%; border-radius:14px;" />
      <h3>2026 Pro Jersey</h3>
      <p>White & black performance fit. Worn on stage.</p>
    </div>
  </div>
</section>

<section>
  <h2>Apply to Join R8MANS</h2>
  <p>Players, creators, and staff can apply below. We review all serious applications.</p>
  <form action="https://formspree.io/f/yourformid" method="POST" style="max-width:600px; margin-top:30px;">
    <div style="margin-bottom:15px;">
      <input type="text" name="name" placeholder="Name / IGN" required style="width:100%; padding:14px; border-radius:10px; border:none;" />
    </div>
    <div style="margin-bottom:15px;">
      <input type="email" name="email" placeholder="Email" required style="width:100%; padding:14px; border-radius:10px; border:none;" />
    </div>
    <div style="margin-bottom:15px;">
      <input type="text" name="role" placeholder="Role (Player, Creator, Staff)" required style="width:100%; padding:14px; border-radius:10px; border:none;" />
    </div>
    <div style="margin-bottom:15px;">
      <textarea name="message" placeholder="Tell us about yourself" rows="5" required style="width:100%; padding:14px; border-radius:10px; border:none;"></textarea>
    </div>
    <button type="submit" style="padding:14px 32px; border-radius:999px; border:none; font-weight:600; cursor:pointer;">Submit Application</button>
  </form>
</section>

<section class="cta">
  <h2>Contact & Partnerships</h2>
  <p>Business inquiries, sponsorships, and collaborations.</p>
  <a href="mailto:r8mansesports@gmail.com">Contact Us</a>
</section>

<footer>
  © 2026 R8MANS Esports. All rights reserved.
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>R8MANS Jersey</title>
</head>
<body>

<nav></nav>

<section>
  <h2>Official Jersey</h2>
  <img src="jersey.png" style="max-width:800px; width:100%; border-radius:20px;">
  <p>Official on-stage competition jersey.</p>
</section>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Apply | R8MANS</title>
</head>
<body>

<nav></nav>

<section>
  <h2>Apply to R8MANS</h2>
  <form action="https://formspree.io/f/mykdwaen" method="POST">
    <input type="text" name="name" placeholder="IGN / Name" required>
    <input type="email" name="email" placeholder="Email" required>
    <input type="text" name="role" placeholder="Player / Creator / Staff" required>
    <textarea name="message" placeholder="Tell us about yourself" required></textarea>
    <button type="submit">Submit</button>
  </form>
</section>

</body>
</html>
<img src="logo.png" alt="R8MANS Logo">
<img src="jersey.png" alt="R8MANS Jersey">

