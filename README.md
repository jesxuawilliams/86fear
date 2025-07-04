# 86fear
86fear Media
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mr. Williams – Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="container">
    <header>
      <h1>Mr. Williams</h1>
      <p class="tagline">Culinary Specialist · Poet · Sound Alchemist</p>
    </header>

    <section id="about">
      <h2>About Me</h2>
      <p>
        I blend the sacred and streetwise into rhythm, ritual, and recipe. Whether in the kitchen, the studio, or on the page, I distill raw experience into crafted expression.
      </p>
    </section>

    <section id="music">
      <h2>Listen</h2>
      <ul>
        <li><a href="https://your-link.com" target="_blank">🎵 Album: Dark Swarm</a></li>
        <li><a href="https://your-link.com" target="_blank">🔊 SoundCloud</a></li>
        <li><a href="https://your-link.com" target="_blank">📀 Bandcamp</a></li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <form action="https://formspree.io/f/YOUR_ID" method="POST">
        <input type="text" name="name" placeholder="Your Name" required />
        <input type="email" name="_replyto" placeholder="Your Email" required />
        <textarea name="message" placeholder="Your Message" required></textarea>
        <button type="submit">Send</button>
      </form>
    </section>

    <footer>
      <p>© 2025 Mr. Williams · All rights reserved.</p>
    </footer>
  </div>
</body>
</html>
/* Reset and base styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Helvetica Neue', sans-serif;
  background: #fdfdfd;
  color: #222;
  line-height: 1.6;
  font-size: 16px;
  padding: 1rem;
}

.container {
  max-width: 800px;
  margin: 0 auto;
}

header {
  text-align: center;
  margin-bottom: 2rem;
  padding-top: 2rem;
}

header h1 {
  font-size: 2.5rem;
  margin-bottom: 0.25rem;
}

.tagline {
  color: #555;
  font-size: 1.1rem;
}

section {
  margin-bottom: 3rem;
}

h2 {
  font-size: 1.5rem;
  margin-bottom: 1rem;
  border-bottom: 2px solid #eee;
  padding-bottom: 0.25rem;
}

ul {
  list-style: none;
  padding-left: 0;
}

ul li a {
  text-decoration: none;
  color: #0077cc;
  font-weight: bold;
  display: block;
  margin-bottom: 0.5rem;
  transition: color 0.2s ease-in-out;
}

ul li a:hover {
  color: #004499;
}

form {
  display: flex;
  flex-direction: column;
}

input, textarea {
  padding: 0.75rem;
  margin-bottom: 1rem;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-family: inherit;
}

textarea {
  resize: vertical;
  min-height: 100px;
}

button {
  background-color: #0077cc;
  color: white;
  border: none;
  padding: 0.75rem;
  font-size: 1rem;
  border-radius: 5px;
  cursor: pointer;
  transition: background 0.2s ease;
}

button:hover {
  background-color: #005fa3;
}

footer {
  text-align: center;
  font-size: 0.875rem;
  color: #888;
  margin-bottom: 2rem;
}

/* Mobile Optimization */
@media (max-width: 600px) {
  body {
    font-size: 15px;
  }

  header h1 {
    font-size: 2rem;
  }
}
