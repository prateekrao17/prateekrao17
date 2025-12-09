<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Prateek Rao — Product & Data Portfolio</title>
  <meta name="description" content="Product-focused portfolio for Prateek Rao — case studies, data projects, and product thinking." />
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#94a3b8; --accent:#6ee7b7; --glass: rgba(255,255,255,0.03);
      --maxw:1100px; --radius:14px; --gap:18px; --accent-2:#60a5fa;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; background:linear-gradient(180deg,#071028 0%, #081126 40%); color:#e6eef8}
    a{color:var(--accent);text-decoration:none}
    .wrap{max-width:var(--maxw);margin:36px auto;padding:28px}
    header{display:flex;align-items:center;justify-content:space-between;margin-bottom:28px}
    .brand{display:flex;gap:14px;align-items:center}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;font-weight:700;color:#042;box-shadow:0 6px 18px rgba(6,15,30,0.6)}
    .brand h1{font-size:18px;margin:0}
    nav a{margin-left:18px;color:var(--muted);font-weight:600;font-size:14px}

    .hero{display:grid;grid-template-columns:1fr 380px;gap:28px;align-items:center;margin-bottom:28px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:var(--radius);padding:22px;box-shadow:0 6px 16px rgba(2,6,23,0.6);}
    .intro h2{margin:0 0 8px 0;font-size:26px}
    .intro p{margin:0;color:var(--muted);line-height:1.5}
    .ctas{margin-top:18px;display:flex;gap:12px}
    .btn{padding:10px 14px;border-radius:10px;font-weight:700;border:0;cursor:pointer}
    .btn-primary{background:linear-gradient(90deg,var(--accent),var(--accent-2));color:#052;}
    .btn-ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--muted)}

    .profile{display:flex;flex-direction:column;gap:12px}
    .avatar{width:100%;height:220px;border-radius:10px;background:linear-gradient(180deg,#06243a 0%, #0a1b2b 100%);display:flex;align-items:center;justify-content:center;font-size:20px;color:var(--muted)}
    .meta{display:flex;gap:12px;align-items:center}
    .tags{display:flex;gap:10px;flex-wrap:wrap}
    .pill{background:var(--glass);padding:8px 10px;border-radius:999px;color:var(--muted);font-weight:600;font-size:13px}

    .projects{display:grid;grid-template-columns:repeat(2,1fr);gap:18px;margin-top:18px}
    .project-card{display:flex;gap:14px;align-items:flex-start}
    .proj-thumb{width:120px;height:80px;border-radius:8px;background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));display:flex;align-items:center;justify-content:center;color:var(--muted);font-weight:700}
    .proj-body h3{margin:0;font-size:16px}
    .proj-body p{margin:6px 0 0 0;color:var(--muted);font-size:13px}
    .metrics{margin-top:8px;color:var(--accent);font-weight:700}

    .skills{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
    .skill{background:rgba(255,255,255,0.02);padding:8px 10px;border-radius:8px;color:var(--muted);font-weight:700}

    footer{margin-top:24px;color:var(--muted);font-size:13px;display:flex;justify-content:space-between;align-items:center}

    /* responsive */
    @media(max-width:900px){
      .hero{grid-template-columns:1fr;}
      .projects{grid-template-columns:1fr}
      .wrap{padding:18px}
    }

    /* Case study modal / detailed view (simple) */
    .case{margin-top:18px;background:linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01));padding:18px;border-radius:12px}
    .case h4{margin:0 0 8px 0}
    .case .row{display:flex;gap:16px}
    .case .col{flex:1}
    pre{background:#041224;padding:12px;border-radius:8px;overflow:auto;color:#9bd6ff}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="logo">PR</div>
        <div>
          <h1>Prateek Rao</h1>
          <div style="color:var(--muted);font-size:13px">Product | Data & Analytics | APM Aspirant</div>
        </div>
      </div>
      <nav>
        <a href="#projects">Projects</a>
        <a href="#case-studies">Case Studies</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero">
      <div class="card intro">
        <h2>Product thinker who ships with data.</h2>
        <p>I build product experiences and data stories that improve activation, retention and monetization. I craft PRDs, run experiments, and use metrics to steer product decisions.</p>
        <div class="ctas">
          <a class="btn btn-primary" href="#case-studies">View Case Studies</a>
          <a class="btn btn-ghost" href="mailto:your.email@example.com">Get in touch</a>
        </div>

        <div class="case" id="case-studies">
          <h4>Quick case snapshot — Gullak (Savings Product)</h4>
          <div class="row">
            <div class="col">
              <strong>Problem</strong>
              <p style="color:var(--muted)">Low daily engagement for small-ticket savings. Users wanted an easy habit-building flow.</p>

              <strong>My role</strong>
              <p style="color:var(--muted)">Led discovery, wrote PRD, designed onboarding microflows, and tracked retention metrics.</p>
            </div>
            <div class="col">
              <strong>Impact</strong>
              <p style="color:var(--muted)">Proposed experiments increased activation by +18% (hypothetical / sample metrics). Focused on lower friction and progressive disclosure.</p>
            </div>
          </div>
        </div>

      </div>

      <aside class="card profile">
        <div class="avatar">Profile Photo</div>
        <div class="meta">
          <div>
            <div style="font-weight:700">Associate Product Manager (APM) Aspirant</div>
            <div style="color:var(--muted);font-size:13px">Currently: Product Ops Intern, Uolo</div>
          </div>
        </div>

        <div class="tags">
          <div class="pill">Product Strategy</div>
          <div class="pill">Analytics & SQL</div>
          <div class="pill">A/B Testing</div>
          <div class="pill">User Research</div>
        </div>

        <div style="margin-top:10px">
          <a class="btn btn-primary" href="#projects">Featured projects</a>
        </div>
      </aside>
    </section>

    <section id="projects">
      <h3 style="margin-bottom:12px">Featured Projects</h3>
      <div class="projects">

        <div class="card project-card">
          <div class="proj-thumb">G</div>
          <div class="proj-body">
            <h3>Gullak — Micro-savings Concept</h3>
            <p>Product concept focused on habit formation and daily savings. Designed onboarding, reward loops, and retention experiments.</p>
            <div class="metrics">Impact: +18% activation (A/B test)</div>
            <div style="margin-top:8px;color:var(--muted);font-size:13px">Tools: Figma • Miro • Mixpanel • SQL</div>
          </div>
        </div>

        <div class="card project-card">
          <div class="proj-thumb">F</div>
          <div class="proj-body">
            <h3>Credit Card Fraud Detection</h3>
            <p>Built model and dashboards to detect anomalies in transaction patterns. Focus on precision and reducing false positives.</p>
            <div class="metrics">Impact: Reduced review load by ~30% (implementation hypothesis)</div>
            <div style="margin-top:8px;color:var(--muted);font-size:13px">Tools: Python • Pandas • Scikit-learn • Dash</div>
          </div>
        </div>

        <div class="card project-card">
          <div class="proj-thumb">A</div>
          <div class="proj-body">
            <h3>Activation Funnel — News Subscription</h3>
            <p>Analyzed subscription funnel and proposed experiment to improve trial to paid conversion through onboarding and messaging changes.</p>
            <div class="metrics">Impact: +12% trial→paid (experiment design)</div>
            <div style="margin-top:8px;color:var(--muted);font-size:13px">Tools: Amplitude • SQL • Notion</div>
          </div>
        </div>

        <div class="card project-card">
          <div class="proj-thumb">D</div>
          <div class="proj-body">
            <h3>Sales Dashboard — Amazon</h3>
            <p>Created dashboards to track KPIs and uncover insights for pricing and inventory decisions. Automated weekly reports for stakeholders.</p>
            <div class="metrics">Impact: Reduced report time from 6 hrs to 30 mins</div>
            <div style="margin-top:8px;color:var(--muted);font-size:13px">Tools: Python • PowerBI • Excel</div>
          </div>
        </div>

      </div>
    </section>

    <section style="margin-top:22px">
      <div class="card">
        <h3 id="skills">Skills & How I Work</h3>
        <p style="color:var(--muted)">I combine product thinking, quantitative analysis, and clear execution. I prefer small, measurable experiments and rapid learning loops.</p>
        <div class="skills">
          <div class="skill">Product Strategy</div>
          <div class="skill">PRDs & User Stories</div>
          <div class="skill">Funnel Analytics</div>
          <div class="skill">A/B Testing</div>
          <div class="skill">SQL & Python</div>
          <div class="skill">Figma & Wireframing</div>
        </div>
      </div>
    </section>

    <section style="margin-top:18px">
      <div class="card">
        <h3>How to view full case studies & repos</h3>
        <p style="color:var(--muted)">Each project has a detailed case-study (PRD, metrics, dashboards) in the repository. To add your real repo links, replace the placeholders below in the HTML or send me your repo links and I will update them for you.</p>
        <pre>• GitHub: https://github.com/your-username
• Portfolio site: /index.html

/* Replace project descriptions, metrics and images with your real outputs */</pre>
      </div>
    </section>

    <footer id="contact">
      <div>
        <strong>Contact</strong>
        <div style="color:var(--muted)">Email: <a href="mailto:your.email@example.com">your.email@example.com</a> • LinkedIn: <a href="#">linkedin.com/in/yourprofile</a></div>
      </div>
      <div style="text-align:right;color:var(--muted)">Built for product interviewers • Last updated: <!-- update date --> </div>
    </footer>

  </div>
</body>
</html>
