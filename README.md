# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Chandradeep Singh Rathore — Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Portfolio of Chandradeep Singh Rathore — Coder, Developer, Entrepreneur, Editor, Gamer, Photographer." />
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@500&display=swap" />
  <style>
    body {
      background: url('5823589-2920x1640-desktop-hd-boy-programmer-wallpaper-image.jpg') no-repeat center center fixed;
      background-size: cover;
      background-color: #0a0a0f;
      color: #e3e3e3;
      font-family: "Fira Code", monospace;
      margin: 0;
      padding: 0;
      min-height: 100vh;
    }
    header,
    main,
    footer {
      max-width: 800px;
      margin: auto;
      padding: 2rem;
      background: rgba(10, 10, 15, 0.85);
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0, 255, 150, 0.4);
    }
    header {
      text-align: center;
    }
    .profile-pic {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #25e89e;
      margin-bottom: 1rem;
      box-shadow: 0 0 8px #25e89e;
      background-color: #111;
    }
    nav {
      margin: 1rem 0;
    }
    nav a {
      color: #25e89e;
      margin: 0 1em;
      text-decoration: none;
      transition: color 0.2s;
      font-weight: 600;
    }
    nav a:hover {
      color: #ea3ec8;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 0.2em;
      text-shadow: 0 0 7px #25e89e;
    }
    .tagline {
      color: #25e89e;
      font-size: 1.3rem;
      text-shadow: 0 0 6px #25e89e;
    }
    section {
      margin: 2em 0;
    }
    .skills span,
    .roles span {
      display: inline-block;
      background: rgba(21, 21, 32, 0.8);
      color: #e3e3e3;
      padding: 0.3em 0.7em;
      border-radius: 6px;
      margin: 0.3em 0.5em 0.3em 0;
      font-size: 1em;
      border: 1px solid #25e89e;
      box-shadow: 0 0 5px #25e89e;
      user-select: none;
    }
    .work-block {
      background: rgba(24, 24, 54, 0.9);
      border-radius: 10px;
      padding: 1em;
      margin: 1em 0;
      border-left: 5px solid #25e89e;
      box-shadow: 0 0 10px #25e89e;
      font-weight: 600;
    }
    a.link-icon {
      color: #ea3ec8;
      text-decoration: underline;
      font-weight: 600;
    }
    .contact-list {
      list-style: none;
      padding: 0;
    }
    .contact-list li {
      margin-bottom: 0.7em;
      font-weight: 600;
      font-size: 1.05em;
    }
    .contact-list a {
      color: #25e89e;
      text-decoration: none;
    }
    .contact-list a:hover {
      text-decoration: underline;
    }
    .footer {
      position: relative;
      color: #888;
      text-align: center;
      font-size: 0.9em;
      letter-spacing: 1px;
      overflow: hidden;
      background-color: rgba(10, 10, 15, 0.85);
      padding: 1.5rem 2rem;
      margin-top: 4rem;
      border-radius: 10px;
      box-shadow: 0 0 12px rgba(37, 232, 158, 0.7);
    }
    .footer::before {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: repeating-linear-gradient(
        0deg,
        rgba(10, 10, 15, 0.85),
        rgba(10, 10, 15, 0.85) 2px,
        #25e89e 3px,
        rgba(10, 10, 15, 0.85) 4px
      );
      animation: scrollLines 1.5s linear infinite;
      opacity: 0.2;
      z-index: -1;
      border-radius: 10px;
    }
    @keyframes scrollLines {
      0% { background-position: 0 0; }
      100% { background-position: 0 10px; }
    }
  </style>
</head>
<body>
  <header>
    <img src="Snapchat-1540699169.jpg" alt="Chandradeep Profile Picture" class="profile-pic" />
    <h1>Chandradeep Singh Rathore</h1>
    <div class="tagline">
      I build, create, and disrupt.<br />
      <span>Coder · Developer · Gamer · Editor · Entrepreneur · Photographer</span>
    </div>
    <nav>
      <a href="#about">About</a>
      <a href="#work">Work</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <main>
    <section id="about">
      <h2>~ About Me</h2>
      <p>
        Hi! I'm Chandradeep, a multi-passionate <strong>coder, developer, entrepreneur, editor, gamer, and photographer</strong> constantly pushing the
        envelope in tech and creativity.<br />
        Founder of <strong>Techformers</strong> (since 2022), and currently working at <strong>T.W.C</strong> (The Waiter Company, since 2024). Tech is my playground.<br />
        I love building cool things, whether that means shipping software, leading teams, editing videos, or capturing moments through a lens.
      </p>
      <div class="roles">
        <span>Developer</span>
        <span>Entrepreneur</span>
        <span>Editor</span>
        <span>Gamer</span>
        <span>Photographer</span>
      </div>
    </section>

    <section id="work">
      <h2>~ My Work</h2>
      <div class="work-block">
        <strong>Techformers</strong> &nbsp;(<span>Since 2022</span>)<br />
        Founder & Team Leader — Building a collaborative tech community, running projects, events, and hackathons. <br />
        <code>#Leadership #Teamwork #Innovation</code>
      </div>
      <div class="work-block">
        <strong>T.W.C (The Waiter Company)</strong> &nbsp;(<span>Since 2024</span>)<br />
        Tech Lead, Startup Innovator — Working in core product development and startup operations.<br />
        <code>#Startup #ProductDevelopment #Strategy</code>
      </div>
    </section>

    <section id="projects">
      <h2>~ Side Projects</h2>
      <ul>
        <li><strong>Coding:</strong> Check out my code, bots, or fun scripts on request!</li>
        <li><strong>Gaming:</strong> Stream clips and tournaments shared on Instagram</li>
        <li><strong>Photography:</strong> Selected event galleries, DM on Instagram for shoots!</li>
        <li><strong>Tech Communities:</strong> Running contests and hosting events with <b>Techformers</b></li>
      </ul>
    </section>

    <section id="contact">
      <h2>~ Contact Me</h2>
      <ul class="contact-list">
        <li><strong>Mobile:</strong> <a href="tel:7877185240">+91 78771 85240</a></li>
        <li><strong>Email:</strong> <a href="mailto:chandradeep7340@gmail.com">chandradeep7340@gmail.com</a></li>
        <li><strong>Instagram:</strong> <a href="https://instagram.com/aj_moon007" target="_blank">@aj_moon007</a></li>
        <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/chandradeep-singh-rathore-0b9a6637b/" target="_blank">Chandradeep Singh Rathore</a></li>
      </ul>
    </section>
  </main>
  <footer class="footer">
    @2025 Chandradeep Singh Rathore &middot; Built by me with ❤️
  </footer>
</body>
</html>
