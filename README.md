<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yoni’s Sports Training | Lawrence, NY</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet" />

  <!-- SEO Meta Tags -->
  <meta name="description" content="All sports. All ages. Book 1-on-1 or group coaching with Yoni in Lawrence, NY. Football, basketball, and more!" />
  <meta name="keywords" content="sports training, kids sports, private coach, Lawrence NY, Yoni, basketball training, football training" />
  <meta name="author" content="Yoni’s Sports Training" />
  <meta name="robots" content="index, follow" />
  <link rel="canonical" href="https://www.yonissportstraining.com" />
  <link rel="icon" href="favicon.ico" type="image/x-icon" />

  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #F4F7FA;
      color: #212121;
      margin: 0;
      padding: 0;
    }

    header {
      background: linear-gradient(to right, #0D47A1, #1976D2);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    header h1 {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 64px;
      margin: 0 0 10px;
      letter-spacing: 2px;
    }

    header p {
      font-size: 22px;
    }

    nav {
      background-color: #0D47A1;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 40px;
      padding: 15px;
      margin: 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: 500;
      font-size: 18px;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #FF6F00;
    }

    section {
      max-width: 900px;
      margin: auto;
      padding: 50px 20px;
    }

    section:nth-of-type(even) {
      background-color: #ffffff;
    }

    section:nth-of-type(odd) {
      background-color: #F0F3F7;
    }

    h2 {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 36px;
      color: #0D47A1;
      margin-bottom: 20px;
      text-align: center;
    }

    p, li {
      font-size: 18px;
      line-height: 1.6;
    }

    img {
      width: 100%;
      max-width: 500px;
      display: block;
      margin: 30px auto;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    form {
      background: #ffffff;
      padding: 30px;
      border: 1px solid #ddd;
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.05);
    }

    label {
      font-weight: 500;
      display: block;
      margin-bottom: 5px;
    }

    input, select {
      font-size: 16px;
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border-radius: 8px;
      border: 1px solid #ccc;
    }

    button {
      background-color: #FF6F00;
      color: white;
      border: none;
      padding: 14px 24px;
      font-size: 16px;
      font-weight: bold;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s ease, transform 0.2s ease;
    }

    button:hover {
      background-color: #e65c00;
      transform: scale(1.02);
    }

    ul {
      list-style-type: square;
      padding-left: 20px;
    }

    a {
      color: #0D47A1;
    }

    footer {
      background-color: #0D47A1;
      color: white;
      text-align: center;
      padding: 30px 10px;
      font-size: 16px;
    }
  </style>
</head>

<body>

  <header>
    <h1>Yoni’s Sports Training</h1>
    <p>All Sports. All Ages. Based in Lawrence, NY</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#programs">Programs</a></li>
      <li><a href="#book">Book</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about">
    <h2>About Yoni</h2>
    <p>Train like a champion! Yoni works with athletes of all levels in football, basketball, speed training and more.</p>
    <img src="https://images.unsplash.com/photo-1579980757556-3d7f3a1223b9" alt="Young athlete playing basketball outdoors" />
  </section>

  <section id="programs">
    <h2>Programs Offered</h2>
    <ul>
      <li>Basketball Training</li>
      <li>Football Skills</li>
      <li>Speed & Agility</li>
      <li>Private 1-on-1 Coaching</li>
      <li>Group Clinics & Camps</li>
    </ul>
  </section>

  <section id="book">
    <h2>Book a Session</h2>
    <form action="book_session.php" method="POST">
      <label for="session-type">Session Type:</label>
      <select id="session-type" name="session-type" required>
        <option value="">Choose an option</option>
        <option value="1-on-1">$75 – 1-on-1 Session</option>
        <option value="2-kids">$90 – 2 Kids</option>
        <option value="extra">$15 – Each Additional Kid (up to 6)</option>
      </select>

      <label for="date">Choose a Date:</label>
      <input type="date" id="date" name="date" required />

      <label for="time">Choose a Time:</label>
      <input type="time" id="time" name="time" required />

      <button type="submit">Book Now</button>
    </form>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:yonibobker@gmail.com">yonibobker@gmail.com</a></p>
    <p>Phone: <a href="tel:+15166660292">+1 516-666-0292</a></p>
    <p>Lawrence, NY 11559</p>
  </section>

  <footer>
    <p>&copy; 2025 Yoni’s Sports Training. All rights reserved.</p>
  </footer>

</body>
</html>
