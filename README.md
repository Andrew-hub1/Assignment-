<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Learn the basics of HTML5 with accessibility and SEO-friendly practices.">
  <title>My First Accessible & SEO-Friendly Webpage</title>
</head>
<body>
  <header>
<hi> Welcome to my First web page</hi>
  <ul>
        <li><a href="#about" aria-label="About section">About</a></li>
        <li><a href="#services" aria-label="Services section">Services</a></li>
        <li><a href="#contact" aria-label="Contact section">Contact</a></li>
      </ul>
    </header>
<main>
    <section id="about">
        <h2>About me</h2>
        <p> Hello! my name is Elvis Omondi and am a beginer in web development and am realy into creating great workable and esthetic websites </p>

    </section>
     <section id="services">
      <h2>What I Do</h2>
      <article>
        <h3>Web Design</h3>
        <p>I create simple, user-friendly websites using HTML5 and CSS.</p>
      </article>
      <article>
        <h3>Accessibility Tips</h3>
        <p>I focus on making websites usable for everyone, including those with disabilities.</p>
      </article>
    </section>

        <section id="contact">
      <h2>Contact Me</h2>
      <form>
        <label for="name">Elvis Omondi:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Babjiagoro@gmail.com:</label>
        <input type="email" id="email" name="email" required>

        <label for="message"> send an email:</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Send</button>
      </form>
    </section>
<footer>
    <p>&copy; 2025 My Web Page. All rights reserved. Elvis Omondi</p>
  </footer>
</body>
</html>
</main>
</header># Assignment-
