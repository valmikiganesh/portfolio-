[Valmiki Ganesha – Data Analyst portfolio.html](https://github.com/user-attachments/files/35504727/Valmiki.Ganesha.Data.Analyst.portfolio.html)

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Valmiki Ganesha – Data Analyst</title>
<link href="https://fonts.googleapis.com/css2?family=Anton&family=Space+Grotesk:wght@400;500;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#f9e6d3;--ink:#3b1f1a;--card:#fffaf4;--blue:#1450ff;--sky:#4cb8e8;--yellow:#ffd91a;--red:#ff3b3b;--shadow:#3b1f1a;--line:#1450ff}
html[data-theme="dark"]{--bg:#17171a;--ink:#f5ece2;--card:#26262b;--shadow:#000;--line:#ffd91a}
,::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-padding-top:70px}
body{background:var(--bg);color:var(--ink);font:400 1.05rem/1.6 'Space Grotesk',system-ui,sans-serif;overflow-x:hidden;padding-bottom:env(safe-area-inset-bottom,0px)}
h1,h2,h3{font-family:'Anton',Impact,sans-serif;text-transform:uppercase;line-height:1}
h3{font-size:1.4rem;letter-spacing:.02em;margin-bottom:8px}
section{padding:80px 6vw;position:relative}
:focus-visible{outline:3px solid var(--blue);outline-offset:3px}

nav{position:sticky;top:0;z-index:20;display:flex;justify-content:space-between;align-items:center;padding:calc(12px + env(safe-area-inset-top,0px)) 6vw 12px;background:var(--bg);}
.logo{font-family:'Anton';font-size:1.2rem}
.logo small{background:var(--yellow);color:#000;font:700 .6rem 'Space Grotesk';padding:3px 7px;border-radius:3px;margin-left:8px;vertical-align:middle}
.nav-r{display:flex;gap:22px;align-items:center}
.nav-r a{color:var(--ink);text-decoration:none;font-weight:700}
.toggle{width:72px;height:36px;border-radius:6px;border:0;cursor:pointer;background:#fff;box-shadow:inset 0 2px 6px rgba(0,0,0,.25),0 3px 0 var(--shadow);position:relative}
.toggle::after{content:"";position:absolute;top:4px;left:4px;width:28px;height:28px;border-radius:3px;background:var(--blue);}
html[data-theme="dark"] .toggle{background:#333}
html[data-theme="dark"] .toggle::after{transform:translateX(36px);background:#fff;box-shadow:0 0 0 3px #2ee06a}

.hero{text-align:center;display:flex;flex-direction:column;align-items:center;gap:24px;padding-top:60px}
.hero h1{font-size:clamp(3.2rem,12vw,9rem);text-shadow:4px 4px 0 rgba(59,31,26,.18)}
.lede{max-width:600px;font-size:1.2rem;opacity:.85}
.btn{display:inline-block;padding:14px 28px;border-radius:12px;font-weight:700;text-decoration:none;color:#000;background:var(--yellow);border:2px solid var(--shadow);box-shadow:5px 5px 0 var(--shadow);}
.btn:hover{background:#fff}
.btn.red{background:var(--red);color:#fff}

.chart{width:100%;max-width:640px;background:var(--card);border:2px solid var(--shadow);box-shadow:7px 7px 0 var(--shadow);border-radius:14px;padding:16px 16px 6px;}
.chart svg{width:100%;height:auto;display:block}
.chart figcaption{font-size:.85rem;opacity:.7;padding:4px 0 8px;text-align:left}
.axis{stroke:currentColor;opacity:.25;stroke-width:1}
.line{fill:none;stroke:var(--line);stroke-width:4;stroke-linejoin:round;stroke-linecap:round;}
.peak{fill:var(--red);stroke:#000;stroke-width:2}

h2{font-size:clamp(2.4rem,7vw,5rem);text-align:center;margin-bottom:50px;text-shadow:3px 3px 0 rgba(59,31,26,.2)}
.projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:40px;max-width:1000px;margin:auto}
.proj{background:var(--card);border:2px solid var(--shadow);border-radius:14px;box-shadow:7px 7px 0 var(--shadow);padding:24px}
.proj > p{margin-bottom:14px;opacity:.85}
.stages{list-style:none;counter-reset:s;margin-bottom:16px}
.stages li{counter-increment:s;position:relative;padding-left:44px;margin-bottom:14px;font-size:.95rem}
.stages li::before{content:counter(s);position:absolute;left:0;top:0;width:30px;height:30px;display:grid;place-items:center;background:var(--yellow);color:#000;font:1rem 'Anton';border:2px solid var(--shadow);border-radius:8px;box-shadow:2px 2px 0 var(--shadow)}
.stages strong{display:block}
.tags{display:flex;flex-wrap:wrap;gap:6px;list-style:none;margin-bottom:16px}
.tags li{font-size:.75rem;font-weight:700;background:var(--yellow);color:#000;border-radius:4px;padding:3px 10px}

.skills{background:var(--blue);color:#fff;clip-path:ellipse(120% 100% at 50% 100%);padding-top:120px;padding-bottom:110px;margin-top:50px}
.skills h2{color:#fff;text-shadow:3px 3px 0 rgba(0,0,0,.25)}
.skill-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:28px;max-width:960px;margin:auto}
.skill{background:var(--card);color:#14232e;border:2px solid #111;box-shadow:6px 6px 0 #111;border-radius:12px;padding:20px}
html[data-theme="dark"] .skill{color:#f5ece2}
.skill:nth-child(1){transform:rotate(-1.5deg)}.skill:nth-child(2){transform:rotate(1deg)}.skill:nth-child(3){transform:rotate(-1deg)}

.contact{text-align:center}
.contact .sticker{display:inline-block;font:1.5rem 'Anton';text-transform:uppercase;padding:14px 22px;background:var(--red);color:#fff;border:2px solid var(--shadow);box-shadow:5px 5px 0 var(--shadow);transform:rotate(-2deg);margin-bottom:24px}
.contact p{max-width:520px;margin:0 auto 28px}
footer{text-align:center;padding:30px;font-size:.85rem;opacity:.7}
@media(max-width:700px){.nav-r a{display:none}.chart{transform:none}}
@media(prefers-reduced-motion:reduce){*{transition:none!important}}
</style>
</head>
<body>

<nav>
  <div class="logo">VALMIKI GANESHA<small>DATA ANALYST</small></div>
  <div class="nav-r">
    <a href="#work">Projects</a><a href="#skills">Skills</a><a href="#contact">Contact</a>
    <button class="toggle" id="theme" aria-label="Toggle light and dark theme"></button>
  </div>
</nav>

<header class="hero">
  <h1>Valmiki Ganesha</h1>
  <p class="lede">Data analyst who turns messy sales data into clear answers, using SQL, Python and Power BI.</p>
  <figure class="chart" aria-labelledby="cap">
    <svg viewBox="0 0 600 220" role="img" aria-label="Illustrative line chart of monthly sales rising through the year with a peak in November">
      <line class="axis" x1="30" y1="190" x2="590" y2="190"/>
      <line class="axis" x1="30" y1="120" x2="590" y2="120" stroke-dasharray="4 6"/>
      <line class="axis" x1="30" y1="50" x2="590" y2="50" stroke-dasharray="4 6"/>
      <polyline class="line" points="30,150 80,138 130,145 180,120 230,126 280,104 330,112 380,92 430,98 480,70 530,36 580,62"/>
      <circle class="peak" cx="530" cy="36" r="7"/>
      <text x="30" y="212" font-size="12" fill="currentColor" opacity=".6">Jan</text>
      <text x="560" y="212" font-size="12" fill="currentColor" opacity=".6">Dec</text>
    </svg>
    <figcaption id="cap">Illustrative monthly sales trend. Replace with a real chart from your project.</figcaption>
  </figure>
  <a class="btn" href="#work">See my projects</a>
</header>

<section id="work" aria-labelledby="work-h">
  <h2 id="work-h">Projects</h2>
  <div class="projects">
    <article class="proj">
      <h3>Superstore Sales Dashboard</h3>
      <p>Explore sales performance, trends and business metrics with a dashboard built from retail sales data.</p>
      <ul class="tags" aria-label="Tools used"><li>Power BI</li><li>Data Visualization</li><li>Sales</li></ul>
      <a class="btn red" href="https://github.com/valmikiganesha" style="padding:8px 16px;font-size:.85rem">View on GitHub</a>
    </article>
    <article class="proj">
      <h3>Crop Management System</h3>
      <p>Academic project exploring machine learning concepts for crop-related management and recommendations.</p>
      <ul class="tags" aria-label="Tools used"><li>Machine Learning</li><li>Python</li></ul>
      <a class="btn red" href="https://github.com/valmikiganesha" style="padding:8px 16px;font-size:.85rem">View on GitHub</a>
    </article>
    <article class="proj">
      <h3>Water Quality Monitoring</h3>
      <p>Project concept focused on monitoring water quality indicators and presenting useful information.</p>
      <ul class="tags" aria-label="Tools used"><li>Data Analysis</li></ul>
      <a class="btn red" href="https://github.com/valmikiganesha" style="padding:8px 16px;font-size:.85rem">View on GitHub</a>
    </article>
    <article class="proj">
      <h3>Groundwater Level Prediction</h3>
      <p>Exploring groundwater level prediction using machine learning methods.</p>
      <ul class="tags" aria-label="Tools used"><li>Machine Learning</li><li>Python</li></ul>
      <a class="btn red" href="https://github.com/valmikiganesha" style="padding:8px 16px;font-size:.85rem">View on GitHub</a>
    </article>
    <article class="proj">
      <h3>Blood Bank Management System</h3>
      <p>Database-oriented academic project for organizing blood bank records and operations.</p>
      <ul class="tags" aria-label="Tools used"><li>Database</li><li>SQL</li></ul>
      <a class="btn red" href="https://github.com/valmikiganesha" style="padding:8px 16px;font-size:.85rem">View on GitHub</a>
    </article>
  </div>
</section>

<section class="skills" id="skills" aria-labelledby="skills-h">
  <h2 id="skills-h">Skills</h2>
  <div class="skill-grid">
    <div class="skill"><h3>Querying</h3><p>SQL Server, data cleaning, validation checks.</p></div>
    <div class="skill"><h3>Analysis</h3><p>Python, pandas, exploratory analysis, KPIs.</p></div>
    <div class="skill"><h3>Reporting</h3><p>Power BI dashboards, charts, written summaries.</p></div>
  </div>
</section>

<section class="contact" id="contact" aria-labelledby="contact-h">
  <h2 id="contact-h">Get in touch</h2>
  <span class="sticker">Open to work</span>
  <p>Open to data analyst roles and freelance projects.</p>
  <a class="btn" href="mailto:ganeshganesh39678@gmail.com">Email me</a>
  <a class="btn" href="https://github.com/valmikiganesha" style="margin-left:12px">GitHub</a>
</section>


<script>
const root=document.documentElement,btn=document.getElementById('theme');
try{const s=localStorage.getItem('theme');if(s)root.dataset.theme=s;}catch(e){}
btn.addEventListener('click',()=>{
  const t=root.dataset.theme==='dark'?'light':'dark';
  root.dataset.theme=t;
  try{localStorage.setItem('theme',t)}catch(e){}
});
</script>
</body>
</html>
