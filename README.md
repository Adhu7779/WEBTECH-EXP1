<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Simple Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fdfdfd;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header, footer {
      background-color: #007acc;
      color: white;
      text-align: center;
      padding: 15px;
    }
    main {
      padding: 20px;
    }
    img {
      max-width: 100%;
      height: auto;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }
    table, th, td {
      border: 1px solid #444;
    }
    th, td {
      padding: 10px;
      text-align: left;
    }
    nav a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Simple Website</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="home">
      <h2>Home</h2>
      <p>This is a basic, clean web page built with HTML. It's responsive and easy to edit. Great for beginners.</p>
      <img src="https://via.placeholder.com/600x300" alt="Placeholder Image">
    </section>

    <section id="about">
      <h2>About</h2>
      <p>We help beginners learn web development. This website is made using just HTML and a bit of CSS for styling.</p>

      <h3>Quick Links</h3>
      <ul>
        <li><a href="https://www.w3schools.com" target="_blank">Learn HTML</a></li>
        <li><a href="adwaith0363@gmail.com">Send us an Email</a></li>
        <li><a href="tel:+918089867566">Call Us</a></li>
      </ul>

      <h3>Our Team</h3>
      <table>
        <tr>
          <th>Name</th>
          <th>Role</th>
        </tr>
        <tr>
          <td>Adwaith</td>
          <td>Developer</td>
        </tr>
        <tr>
          <td>Ruth</td>
          <td>Designer</td>
        </tr>
      </table>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Feel free to reach out to us anytime!</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Simple Website. All rights reserved.</p>
  </footer>

</body>
</html>
