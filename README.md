
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yoni’s Sports Training | Lawrence, NY</title>

  <!-- SEO Meta Tags -->
  <meta name="description" content="All sports. All ages. Book 1-on-1 or group coaching with Yoni in Lawrence, NY. Football, basketball, and more!" />
  <meta name="keywords" content="sports training, kids sports, private coach, Lawrence NY, Yoni, basketball training, football training" />
  <meta name="author" content="Yoni’s Sports Training" />
  <meta name="robots" content="index, follow" />
  <link rel="canonical" href="https://www.yonissportstraining.com" />
  <link rel="icon" href="favicon.ico" type="image/x-icon" />

  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #e0f7fa;
      color: #333;
      margin: 0;
      padding: 0;
    }

    header, footer {
      background-color: #007acc;
      color: white;
      text-align: center;
      padding: 30px 10px;
    }

    nav {
      background-color: #005a9c;
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
      font-weight: bold;
      font-size: 18px;
    }

    section {
      max-width: 900px;
      margin: auto;
      padding: 30px 20px;
    }

    img {
      width: 100%;
      max-width: 500px;
      display: block;
      margin: 20px auto;
      border-radius: 10px;
    }

    form {
      background: #ffffff;
      padding: 20px;
      border: 2px solid #007acc;
      border-radius: 10px;
    }

    label, input, select {
      font-size: 16px;
      width: 100%;
      margin-bottom: 15px;
      padding: 8px;
    }

    button {
      background-color: #ff7043;
      color: white;
      border: none;
      padding: 12px 20px;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
    }

    ul {
      list-style-type: square;
      padding-left: 20px;
    }

    a {
      color: #007acc;
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
    <img src="https://images.unsplash.com/photo-1579980757556-3d7f3a1223b9" alt="Kid playing basketball">
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
        <option value="extra">$15 – Each Additional Kid</option>
      </select>

      <label for="date">Choose a Date:</label>
      <input type="date" id="date" name="date" required>

      <label for="time">Choose a Time:</label>
      <input type="time" id="time" name="time" required>

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