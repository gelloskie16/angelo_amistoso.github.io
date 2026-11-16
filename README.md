# angelo_amistoso.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio | Angelo Amistoso</title>
  <style>
    :root {
      --bg: #0f172a;
      --surface: #1e293b;
      --text: #f8fafc;
      --muted: #94a3b8;
      --accent: #38bdf8;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
      padding: 2rem 1.25rem;
    }
    .container { max-width: 860px; margin: 0 auto; }
    header { padding: 3rem 0 2rem; border-bottom: 1px solid #334155; }
    h1 { font-size: 2.25rem; margin-bottom: 0.5rem; }
    .subtitle { color: var(--accent); font-weight: 600; margin-bottom: 1rem; }
    .bio { color: var(--muted); max-width: 650px; margin-bottom: 1.5rem; }
    .links a {
      display: inline-block;
      margin-right: 1rem;
      color: var(--text);
      text-decoration: none;
      border: 1px solid #334155;
      padding: 0.45rem 0.9rem;
      border-radius: 6px;
      font-size: 0.9rem;
    }
    .links a:hover { border-color: var(--accent); color: var(--accent); }
    section { padding: 2.5rem 0; }
    h2 { font-size: 1.4rem; margin-bottom: 1.25rem; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 1.25rem; }
    .card {
      background: var(--surface);
      padding: 1.5rem;
      border-radius: 10px;
      border: 1px solid #334155;
    }
    .card h3 { margin-bottom: 0.5rem; font-size: 1.15rem; }
    .card p { color: var(--muted); font-size: 0.95rem; margin-bottom: 1rem; }
    .tags span {
      display: inline-block;
      background: #0f172a;
      color: var(--accent);
      font-size: 0.78rem;
      padding: 0.2rem 0.55rem;
      border-radius: 4px;
      margin: 0 0.35rem 0.35rem 0;
    }
    footer { text-align: center; color: var(--muted); font-size: 0.85rem; padding-top: 2rem; border-top: 1px solid #334155; }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Angelo Amistoso</h1>
      <div class="subtitle">Computer Engineer / CCTV Engineer</div>
      <p class="bio">
        Brief 2-sentence summary highlighting your core expertise, key technical domains, and the types of systems or solutions you build.
      </p>
      <div class="links">
        <a href="mailto:you@example.com">Email</a>
        <a href="https://github.com/yourusername" target="_blank">GitHub</a>
        <a href="https://linkedin.com/in/yourusername" target="_blank">LinkedIn</a>
        <a href="resume.pdf" target="_blank">Resume (PDF)</a>
      </div>
    </header>

    <section>
      <h2>Featured Projects</h2>
      <div class="grid">
        <div class="card">
          <h3>Project Title One</h3>
          <p>Short description of the problem solved, system architecture, and measurable outcome or impact.</p>
          <div class="tags">
            <span>Python</span>
            <span>System Design</span>
            <span>Hardware</span>
          </div>
        </div>
        <div class="card">
          <h3>Project Title Two</h3>
          <p>Short description of the problem solved, system architecture, and measurable outcome or impact.</p>
          <div class="tags">
            <span>Networking</span>
            <span>Security</span>
            <span>Automation</span>
          </div>
        </div>
      </div>
    </section>

    <footer>
      © 2026 Your Name · Built and hosted on GitHub Pages
    </footer>
  </div>
</body>
</html>
