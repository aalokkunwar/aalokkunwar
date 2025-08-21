<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aalok Kunwar's README</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #1e1e2f 0%, #2a2a4e 100%);
      color: #ffffff;
      line-height: 1.6;
      padding: 20px;
      min-height: 100vh;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    .header {
      text-align: center;
      padding: 40px 0;
      animation: fadeIn 1s ease-in-out;
    }

    .header img {
      width: 50px;
      vertical-align: middle;
    }

    .header h1 {
      font-size: 3rem;
      color: #ffffff;
      margin: 10px 0;
      text-shadow: 0 0 10px rgba(127, 63, 191, 0.7);
    }

    .badges a {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      border-radius: 25px;
      text-decoration: none;
      font-weight: 600;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .badges a:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    }

    .portfolio { background: #7F3FBF; color: white; }
    .linkedin { background: #0A66C2; color: white; }
    .email { background: #D14836; color: white; }

    .typing-svg {
      text-align: center;
      margin: 20px 0;
    }

    .typing-svg img {
      max-width: 100%;
      border-radius: 10px;
    }

    .section {
      margin: 40px 0;
      padding: 30px;
      background: rgba(255, 255, 255, 0.05);
      border-radius: 15px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s;
    }

    .section:hover {
      transform: translateY(-10px);
    }

    .section h2 {
      font-size: 2rem;
      color: #7F3FBF;
      margin-bottom: 20px;
      position: relative;
    }

    .section h2::after {
      content: '';
      width: 50px;
      height: 3px;
      background: #7F3FBF;
      position: absolute;
      bottom: -5px;
      left: 0;
    }

    .skills-grid, .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .skills-grid span, .projects-grid a {
      background: rgba(255, 255, 255, 0.1);
      padding: 10px;
      border-radius: 10px;
      text-align: center;
      transition: background 0.3s, transform 0.3s;
    }

    .skills-grid span:hover, .projects-grid a:hover {
      background: #7F3FBF;
      transform: scale(1.05);
    }

    .projects-grid a {
      color: #ffffff;
      text-decoration: none;
      display: block;
    }

    .blog-posts ul {
      list-style: none;
      padding: 0;
    }

    .blog-posts li {
      margin: 10px 0;
      padding: 15px;
      background: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
      transition: background 0.3s;
    }

    .blog-posts li:hover {
      background: #7F3FBF;
    }

    .blog-posts a {
      color: #ffffff;
      text-decoration: none;
      font-weight: 500;
    }

    .github-stats {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      margin-top: 20px;
    }

    .github-stats img {
      max-width: 100%;
      border-radius: 10px;
    }

    .connect {
      text-align: center;
      margin: 40px 0;
    }

    .connect a {
      color: #7F3FBF;
      text-decoration: none;
      font-weight: 600;
      margin: 0 10px;
    }

    .connect a:hover {
      text-decoration: underline;
    }

    .footer img {
      max-width: 100%;
      margin-top: 20px;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 768px) {
      .header h1 { font-size: 2rem; }
      .section h2 { font-size: 1.5rem; }
      .badges a { padding: 8px 15px; font-size: 0.9rem; }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <img src="https://raw.githubusercontent.com/aalokkunwar/aalokkunwar/main/wave.gif" alt="Wave">
      <h1>Hello, World! I'm Aalok Kunwar</h1>
      <p>Full Stack Developer | AI Enthusiast | Tech Educator | Open Source Contributor</p>
      <div class="badges">
        <a href="https://aalokkunwar.com.np" class="portfolio">Portfolio</a>
        <a href="https://www.linkedin.com/in/aalok-kunwar-554a562a8" class="linkedin">LinkedIn</a>
        <a href="mailto:aalokjungkunwar@gmail.com" class="email">Email</a>
      </div>
    </div>

    <div class="typing-svg">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=7F3FBF&width=435&lines=Full+Stack+Web+Developer;Passionate+AI+%26+ML+Explorer;Open+Source+Contributor;Building+Digital+Solutions" alt="Typing SVG" />
    </div>

    <div class="section about">
      <h2>🚀 About Me</h2>
      <p>I'm a <strong>dynamic IT professional</strong> with 2+ years of experience transitioning into <strong>full-stack web development</strong>. Currently contributing at <a href="https://www.sequoia.codes/">SequoiaCodes</a>, I've previously worked as an IT Assistant and interned at <strong>Nepal Telecom</strong>. I build scalable applications, love solving problems, and contribute to community tech initiatives in Nepal.</p>
    </div>

    <div class="section skills">
      <h2>🧠 Skills & Technologies</h2>
      <h3>Languages & Frameworks</h3>
      <div class="skills-grid">
        <span>JavaScript</span>
        <span>React</span>
        <span>Node.js</span>
        <span>Next.js</span>
        <span>Python</span>
      </div>
      <h3>Databases & Cloud</h3>
      <div class="skills-grid">
        <span>MongoDB</span>
        <span>PostgreSQL</span>
        <span>Firebase</span>
        <span>AWS</span>
      </div>
      <h3>Tools & Platforms</h3>
      <div class="skills-grid">
        <span>Git</span>
        <span>Docker</span>
        <span>VS Code</span>
        <span>Photoshop</span>
      </div>
    </div>

    <div class="section projects">
      <h2>🌟 Featured Projects</h2>
      <div class="projects-grid">
        <a href="https://github.com/aalokkunwar/nepali-nlp">Nepali NLP Toolkit<br><small>Natural Language Processing toolkit for Nepali language processing.</small></a>
        <a href="https://www.yhhfn.org.np">Yakumaya Helping Hands Foundation<br><small>Tech support & web presence for a non-profit focused on Nepal’s rural development.</small></a>
      </div>
    </div>

    <div class="section blog-posts">
      <h2>✍️ Recent Blog Posts</h2>
      <ul>
        <li><a href="https://aalokkunwar.com.np/blog/microservices-nodejs">Building Scalable Microservices with Node.js</a></li>
        <li><a href="https://aalokkunwar.com.np/blog/nepali-text-classification">Machine Learning for Nepali Text Classification</a></li>
        <li><a href="https://aalokkunwar.com.np/blog/ai-developing-countries">The Future of AI in Developing Countries</a></li>
      </ul>
    </div>

    <div class="section github-stats">
      <h2>📊 GitHub Stats</h2>
      <div class="github-stats">
        <img src="https://github-readme-stats.vercel.app/api?username=aalokkunwar&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub Stats" width="49%">
        <img src="https://github-readme-streak-stats.herokuapp.com?user=aalokkunwar&theme=radical&hide_border=true" alt="GitHub Streak" width="49%">
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=aalokkunwar&theme=react-dark&hide_border=true&area=true" alt="GitHub Activity" width="100%">
      </div>
    </div>

    <div class="section connect">
      <h2>🤝 Let's Connect</h2>
      <p>Feel free to reach out via <a href="mailto:aalokjungkunwar@gmail.com">email</a>, connect on <a href="https://www.linkedin.com/in/aalok-kunwar-554a562a8">LinkedIn</a>, or visit my <a href="https://aalokkunwar.com.np">website</a> for more.</p>
    </div>

    <div class="footer">
      <img src="https://raw.githubusercontent.com/aalokkunwar/aalokkunwar/main/footer.svg" alt="Footer">
    </div>
  </div>
</body>
</html>
