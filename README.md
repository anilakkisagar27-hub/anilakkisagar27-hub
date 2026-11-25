<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#080808">
<title>Anil Akkisagar — Developer Portfolio</title>
<style>
:root{--bg:#080808;--panel:#171717;--panel2:#202020;--text:#f4f4f4;--muted:#aaa;--line:#303030;--accent:#c7f36b;--max:1180px}
*{box-sizing:border-box}html{scroll-behavior:smooth;scroll-padding-top:90px}body{margin:0;background:var(--bg);color:var(--text);font-family:Inter,ui-sans-serif,system-ui,-apple-system,Segoe UI,Arial,sans-serif;line-height:1.6;overflow-x:hidden}a{color:inherit;text-decoration:none}button{font:inherit;color:inherit;cursor:pointer}
.cursor{position:fixed;z-index:1000;left:0;top:0;width:13px;height:13px;border:1px solid var(--accent);border-radius:50%;pointer-events:none;transform:translate(-50%,-50%);transition:width .18s,height .18s,background .18s;mix-blend-mode:difference}.cursor.big{width:42px;height:42px;background:#c7f36b22}
.wrap{width:min(var(--max),calc(100% - 48px));margin:auto}.topbar{position:fixed;top:16px;left:50%;transform:translateX(-50%);width:min(var(--max),calc(100% - 32px));z-index:100;display:flex;align-items:center;justify-content:space-between;padding:10px 12px 10px 16px;border:1px solid #ffffff18;border-radius:18px;background:#111c;backdrop-filter:blur(18px)}.brand{width:36px;height:36px;border-radius:50%;display:grid;place-items:center;background:#eee;color:#111;font-weight:850;font-size:12px;letter-spacing:-1px}.nav{display:flex;gap:5px;align-items:center}.nav a{font-size:12px;color:#c6c6c6;padding:9px 12px;border-radius:10px;transition:.2s}.nav a:hover,.nav a.active{background:#292929;color:#fff}.talk{font-size:12px;padding:9px 14px;border:1px solid #555;border-radius:10px;background:#292929}.hero{min-height:720px;padding:180px 0 90px;display:grid;grid-template-columns:1.1fr .9fr;align-items:center;gap:40px}.eyebrow{color:var(--muted);font-size:14px;letter-spacing:.04em}.hero h1{font-size:clamp(44px,6vw,76px);line-height:1.02;letter-spacing:-.065em;margin:16px 0 22px;max-width:700px}.hero h1 span{color:var(--accent)}.lead{max-width:570px;color:#b8b8b8;font-size:16px}.actions{display:flex;gap:12px;margin-top:30px;flex-wrap:wrap}.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;padding:12px 18px;border:1px solid #4a4a4a;border-radius:11px;background:#1b1b1b;font-size:13px;transition:transform .2s,border .2s}.btn:hover{transform:translateY(-3px);border-color:var(--accent)}.btn.primary{background:var(--accent);border-color:var(--accent);color:#111;font-weight:750}.socials{display:flex;gap:20px;margin-top:30px;color:#bbb;font-size:13px}.socials a:hover{color:var(--accent)}.portrait-wrap{display:grid;place-items:center;position:relative;min-height:380px}.portrait{width:min(350px,80%);aspect-ratio:1;border-radius:44% 56% 48% 52%;background:radial-gradient(circle at 35% 25%,#454545,#191919 60%,#101010);border:1px solid #ffffff20;display:grid;place-items:center;position:relative;overflow:hidden;box-shadow:0 0 100px #c7f36b0c}.portrait:before{content:"";position:absolute;inset:12%;border:1px solid #ffffff20;border-radius:50%}.portrait strong{font-size:clamp(70px,10vw,120px);letter-spacing:-.1em;color:#eee;z-index:1}.orbit{position:absolute;width:410px;height:410px;border:1px dashed #ffffff22;border-radius:50%;animation:spin 35s linear infinite}.orbit:after{content:"";position:absolute;width:9px;height:9px;border-radius:50%;background:var(--accent);top:50px;left:45px}@keyframes spin{to{transform:rotate(360deg)}}
section{padding:90px 0}.section-head{text-align:center;margin-bottom:38px}.kicker{font-size:11px;letter-spacing:.2em;text-transform:uppercase;color:var(--accent)}h2{font-size:clamp(34px,4vw,48px);letter-spacing:-.055em;line-height:1.1;margin:10px 0}.section-head p{color:var(--muted);font-size:14px}.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}.card{background:linear-gradient(145deg,#1b1b1b,#121212);border:1px solid #ffffff13;border-radius:18px;padding:25px;transition:transform .25s,border .25s}.card:hover{transform:translateY(-6px);border-color:#c7f36b66}.card h3{margin:0 0 12px;font-size:19px;letter-spacing:-.03em}.card p{margin:0;color:#aaa;font-size:14px}.tags{display:flex;flex-wrap:wrap;gap:7px;margin-top:20px}.tag{font-size:11px;color:#d6d6d6;border:1px solid #ffffff1c;background:#222;padding:6px 10px;border-radius:99px}.about-copy{max-width:850px;text-align:center;margin:0 auto 35px;color:#b9b9b9}.steps{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}.step{display:flex;gap:14px;align-items:center;background:#202020;border:1px solid #ffffff12;border-radius:14px;padding:18px;font-size:13px}.num{width:34px;height:34px;flex:0 0 34px;border-radius:9px;background:#eee;color:#111;display:grid;place-items:center;font-weight:800}.stats{display:flex;justify-content:center;gap:65px;margin-top:35px;text-align:center}.stats strong{display:block;font-size:28px;letter-spacing:-.05em}.stats span{font-size:12px;color:#999}.project-card{min-height:250px;display:flex;flex-direction:column;justify-content:space-between}.project-top{display:flex;justify-content:space-between;align-items:center;color:var(--accent);font-size:12px}.project-link{margin-top:22px;font-size:13px;color:var(--accent)}.skill-grid{grid-template-columns:repeat(4,1fr)}.contact-box{border:1px solid #ffffff18;border-radius:22px;padding:45px;background:radial-gradient(circle at 80% 10%,#c7f36b16,transparent 40%),#141414;text-align:center}.contact-box p{color:#aaa}.footer{padding:30px 0 45px;border-top:1px solid #ffffff12;color:#888;font-size:12px;display:flex;justify-content:space-between;gap:20px}
.reveal{opacity:0;transform:translateY(26px);transition:opacity .8s ease,transform .8s cubic-bezier(.2,.7,.2,1)}.reveal.visible{opacity:1;transform:translateY(0)}.word{display:inline-block;opacity:0;transform:translateY(14px);transition:opacity .55s ease,transform .55s cubic-bezier(.2,.7,.2,1);transition-delay:var(--d)}.visible .word{opacity:1;transform:translateY(0)}
.modal-backdrop{position:fixed;inset:0;z-index:200;background:#000b;backdrop-filter:blur(10px);display:none;place-items:center;padding:20px}.modal-backdrop.open{display:grid}.modal{width:min(620px,100%);max-height:85vh;overflow:auto;background:#171717;border:1px solid #ffffff25;border-radius:22px;padding:28px;position:relative;animation:pop .25s ease}.modal h2{font-size:30px}.modal p,.modal li{color:#aaa;font-size:14px}.close{position:absolute;right:18px;top:16px;width:34px;height:34px;border-radius:50%;background:#292929;border:1px solid #444}.modal-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-top:18px}.modal-item{padding:15px;background:#222;border-radius:12px}.modal-item b{display:block;font-size:13px}.modal-item span{color:#aaa;font-size:12px}
.toast{position:fixed;bottom:25px;left:50%;transform:translate(-50%,20px);opacity:0;pointer-events:none;background:#eee;color:#111;padding:11px 16px;border-radius:10px;font-size:13px;z-index:300;transition:.25s}.toast.show{opacity:1;transform:translate(-50%,0)}
@media(max-width:800px){.hero{grid-template-columns:1fr;padding-top:145px;text-align:center;gap:10px}.hero .lead{margin:auto}.actions,.socials{justify-content:center}.portrait-wrap{min-height:300px}.portrait{width:250px}.orbit{width:300px;height:300px}.grid{grid-template-columns:repeat(2,1fr)}.skill-grid{grid-template-columns:repeat(2,1fr)}.steps{grid-template-columns:1fr}.stats{gap:28px}.nav a{padding:8px 7px;font-size:11px}.topbar{padding:8px}.brand{width:32px;height:32px}.talk{padding:8px 10px;font-size:11px}}
@media(max-width:520px){.wrap{width:calc(100% - 32px)}.topbar{top:8px;width:calc(100% - 16px)}.nav{gap:0}.nav a{font-size:10px;padding:8px 6px}.talk{display:none}.hero{min-height:auto;padding:140px 0 60px}.hero h1{font-size:47px}.grid,.skill-grid{grid-template-columns:1fr}.section{padding:65px 0}.stats{gap:18px}.stats strong{font-size:23px}.stats span{font-size:10px}.contact-box{padding:30px 18px}.footer{flex-direction:column}.modal-grid{grid-template-columns:1fr}.cursor{display:none}}
@media(prefers-reduced-motion:reduce){*,*:before,*:after{scroll-behavior:auto!important;animation:none!important;transition:none!important}.reveal{opacity:1;transform:none}.word{opacity:1;transform:none}}
</style>
</head>
<body>
<div class="cursor" id="cursor"></div>
<header class="topbar">
  <button class="brand" id="profileBtn" aria-label="Open profile details" title="Open profile">AA</button>
  <nav class="nav" aria-label="Main navigation">
    <a href="#home" class="active">Home</a><a href="#services">Services</a><a href="#about">About</a><a href="#skills">Skills</a><a href="#projects">Projects</a>
  </nav>
  <a class="talk" href="#contact">Let's Talk ↗</a>
</header>

<main>
<section class="hero wrap" id="home">
  <div>
    <div class="eyebrow reveal">Hello, I'm Anil Akkisagar</div>
    <h1 class="reveal words">Java Developer <span>&</span><br>Full-Stack Enthusiast.</h1>
    <p class="lead reveal words">I build practical software experiences with Java, backend technologies and modern web tools. I enjoy turning real problems into clean, useful applications.</p>
    <div class="actions reveal"><a class="btn primary" href="#projects">Explore my work ↘</a><button class="btn" id="cvBtn">Download CV ↓</button></div>
    <div class="socials reveal"><a href="#" data-link="linkedin">LinkedIn ↗</a><a href="#" data-link="github">GitHub ↗</a><button class="btn" id="heroProfile" style="padding:3px 10px">Profile details +</button></div>
  </div>
  <div class="portrait-wrap reveal"><div class="orbit"></div><div class="portrait"><strong>AA</strong></div></div>
</section>

<section id="services">
  <div class="wrap">
    <div class="section-head reveal"><div class="kicker">What I work on</div><h2 class="words">Services & Focus</h2><p>Building reliable applications from interface to backend.</p></div>
    <div class="grid">
      <article class="card reveal"><h3>Backend Development</h3><p>Building application logic, REST APIs and structured backend services using Java and Spring Boot.</p><div class="tags"><span class="tag">Java</span><span class="tag">Spring Boot</span></div></article>
      <article class="card reveal"><h3>Full-Stack Web Apps</h3><p>Connecting responsive user interfaces with backend services to create complete web experiences.</p><div class="tags"><span class="tag">React</span><span class="tag">JavaScript</span></div></article>
      <article class="card reveal"><h3>Microservices</h3><p>Exploring independent services, API communication and scalable application architecture.</p><div class="tags"><span class="tag">Spring Cloud</span><span class="tag">REST API</span></div></article>
    </div>
  </div>
</section>

<section id="about">
  <div class="wrap">
    <div class="section-head reveal"><div class="kicker">A little about me</div><h2 class="words">About Me</h2></div>
    <p class="about-copy reveal words">I'm a Computer Science and Engineering student focused on becoming a software engineer. I enjoy learning by building projects, solving problems and improving my development skills step by step.</p>
    <div class="section-head reveal"><h3 style="font-size:20px;margin:0">My Approach</h3></div>
    <div class="steps">
      <div class="step reveal"><span class="num">01</span><span>Understand the problem and user needs</span></div>
      <div class="step reveal"><span class="num">02</span><span>Design a clean and maintainable solution</span></div>
      <div class="step reveal"><span class="num">03</span><span>Build, test and improve continuously</span></div>
    </div>
    <div class="stats reveal"><div><strong>Java</strong><span>Primary language</span></div><div><strong>2</strong><span>Featured projects</span></div><div><strong>Always</strong><span>Learning mindset</span></div></div>
  </div>
</section>

<section id="skills">
  <div class="wrap">
    <div class="section-head reveal"><div class="kicker">Tools of the trade</div><h2 class="words">Skills</h2><p>Technologies I'm learning and using in projects.</p></div>
    <div class="grid skill-grid">
      <article class="card reveal"><h3>Programming</h3><div class="tags"><span class="tag">Java</span><span class="tag">JavaScript</span><span class="tag">C</span></div></article>
      <article class="card reveal"><h3>Backend</h3><div class="tags"><span class="tag">Spring Boot</span><span class="tag">Spring Cloud</span><span class="tag">REST APIs</span><span class="tag">Microservices</span></div></article>
      <article class="card reveal"><h3>Frontend</h3><div class="tags"><span class="tag">HTML</span><span class="tag">CSS</span><span class="tag">React</span></div></article>
      <article class="card reveal"><h3>Tools & Concepts</h3><div class="tags"><span class="tag">Git</span><span class="tag">GitHub</span><span class="tag">MySQL</span><span class="tag">JWT</span></div></article>
      <article class="card reveal"><h3>AI & Emerging Tech</h3><div class="tags"><span class="tag">AI/ML Fundamentals</span><span class="tag">Prompt Engineering</span><span class="tag">AI Integration</span><span class="tag">Intelligent Dashboards</span><span class="tag">Python (Learning)</span></div></article>
    </div>
  </div>
</section>

<section id="projects">
  <div class="wrap">
    <div class="section-head reveal"><div class="kicker">Selected work</div><h2 class="words">Featured Projects</h2><p>A couple of projects that demonstrate what I like building.</p></div>
    <div class="grid">
      <a class="card project-card reveal project-live" href="#" data-project="icu" target="_blank" rel="noopener noreferrer"><div><div class="project-top"><span>01 / AI WEB APPLICATION</span><span>↗</span></div><h3 style="margin-top:25px">AI ICU Monitoring Dashboard</h3><p>A monitoring dashboard concept with patient vitals, AI-based risk indicators, alerts and real-time updates.</p><div class="tags"><span class="tag">React</span><span class="tag">Node.js</span><span class="tag">Socket.IO</span><span class="tag">AI Risk Analysis</span></div></div><span class="project-link">Open live project ↗</span></a>
      <a class="card project-card reveal project-live" href="#" data-project="parking" target="_blank" rel="noopener noreferrer"><div><div class="project-top"><span>02 / SMART PARKING</span><span>↗</span></div><h3 style="margin-top:25px">Pay Parking Web Application</h3><p>A web-based parking project designed to make parking discovery and payment workflows easier for users.</p><div class="tags"><span class="tag">Web Development</span><span class="tag">UI</span><span class="tag">Parking</span></div></div><span class="project-link">Open live project ↗</span></a>
      <a class="card project-card reveal project-live" href="#" data-project="ecommerce" target="_blank" rel="noopener noreferrer"><div><div class="project-top"><span>03 / BACKEND ARCHITECTURE</span><span>↗</span></div><h3 style="margin-top:25px">Microservices E-Commerce</h3><p>An e-commerce platform concept using independent services and API communication, designed with scalability in mind.</p><div class="tags"><span class="tag">Java</span><span class="tag">Spring Boot</span><span class="tag">Spring Cloud</span><span class="tag">REST APIs</span></div></div><span class="project-link">Open live project ↗</span></a>
    </div>
  </div>
</section>

<section id="contact">
  <div class="wrap">
    <div class="contact-box reveal"><div class="kicker">Have an opportunity?</div><h2 class="words">Let's build something useful.</h2><p>Open to connecting about software development, projects and entry-level opportunities.</p><button class="btn primary" id="contactBtn">Contact me ↗</button></div>
  </div>
</section>
</main>
<footer class="footer wrap"><span>© <span id="year"></span> Anil Akkisagar</span><span>Designed with curiosity & code.</span><a href="#home">Back to top ↑</a></footer>

<div class="modal-backdrop" id="profileModal" role="dialog" aria-modal="true" aria-labelledby="modalTitle">
  <div class="modal"><button class="close" id="closeModal" aria-label="Close profile">×</button><div class="kicker">Profile card</div><h2 id="modalTitle">Anil Akkisagar</h2><p>Computer Science & Engineering student · Aspiring Software Engineer</p>
    <div class="modal-grid">
      <div class="modal-item"><b>Primary language</b><span>Java</span></div><div class="modal-item"><b>Career focus</b><span>Software / Backend Development</span></div>
      <div class="modal-item"><b>Backend interests</b><span>Spring Boot · Microservices · REST APIs</span></div><div class="modal-item"><b>Project interests</b><span>Web apps · Real-time dashboards</span></div>
    </div>
    <p style="margin-top:20px">Use the contact section to connect. Add your verified links and resume file in the configuration before publishing.</p>
  </div>
</div>
<div class="toast" id="toast" role="status"></div>
<script>
// PERSONALISE THESE VALUES before publishing.
const PROFILE = {
  linkedin: "", // e.g. https://www.linkedin.com/in/your-profile/
  github: "",   // e.g. https://github.com/your-username
  email: "",    // your professional email address
  cvFile: "",   // e.g. assets/Anil-Akkisagar-CV.pdf
  projects: {
    icu: "",       // live URL for AI ICU Monitoring Dashboard
    parking: "",   // live URL for Pay Parking Web Application
    ecommerce: ""  // live URL for Microservices E-Commerce
  }
};

const $ = (s) => document.querySelector(s);
const toast = (message) => { const el=$("#toast"); el.textContent=message; el.classList.add("show"); clearTimeout(window.toastTimer); window.toastTimer=setTimeout(()=>el.classList.remove("show"),2600); };

// Profile modal opens from the round initials avatar and the hero shortcut.
const modal=$("#profileModal");
function openProfile(){modal.classList.add("open");document.body.style.overflow="hidden";$("#closeModal").focus();}
function closeProfile(){modal.classList.remove("open");document.body.style.overflow="";}
$("#profileBtn").addEventListener("click",openProfile);
$("#heroProfile").addEventListener("click",openProfile);
$("#closeModal").addEventListener("click",closeProfile);
modal.addEventListener("click",e=>{if(e.target===modal)closeProfile();});
document.addEventListener("keydown",e=>{if(e.key==="Escape")closeProfile();});

// Smooth section navigation and active menu state.
document.querySelectorAll('.nav a').forEach(a=>a.addEventListener('click',()=>{document.querySelectorAll('.nav a').forEach(x=>x.classList.remove('active'));a.classList.add('active');}));
const sections=[...document.querySelectorAll('main section[id]')];
const navObserver=new IntersectionObserver(entries=>entries.forEach(entry=>{if(entry.isIntersecting){document.querySelectorAll('.nav a').forEach(a=>a.classList.toggle('active',a.getAttribute('href')==='#'+entry.target.id));}}),{rootMargin:"-35% 0px -55% 0px"});
sections.forEach(s=>navObserver.observe(s));

// Scroll reveal: each word fades upward with a tiny stagger.
document.querySelectorAll('.words').forEach(el=>{
  const parts=el.innerHTML.split(/(\s+)/);
  el.innerHTML=parts.map((part,i)=>part.trim()?`<span class="word" style="--d:${Math.min(i*35,700)}ms">${part}</span>`:part).join('');
});
const revealObserver=new IntersectionObserver(entries=>entries.forEach(entry=>{if(entry.isIntersecting){entry.target.classList.add('visible');revealObserver.unobserve(entry.target);}}),{threshold:.12});
document.querySelectorAll('.reveal').forEach(el=>revealObserver.observe(el));

// Custom cursor follows the pointer and grows over interactive elements.
const cursor=$("#cursor");
if(matchMedia("(pointer:fine)").matches){document.addEventListener("mousemove",e=>{cursor.style.left=e.clientX+"px";cursor.style.top=e.clientY+"px";});document.querySelectorAll("a,button,.card").forEach(el=>{el.addEventListener("mouseenter",()=>cursor.classList.add("big"));el.addEventListener("mouseleave",()=>cursor.classList.remove("big"));});}

// Project cards open their deployed live websites in a new tab.
document.querySelectorAll('.project-live').forEach(card=>card.addEventListener('click',e=>{
  e.preventDefault();
  const url=PROFILE.projects[card.dataset.project];
  if(url){window.open(url,'_blank','noopener,noreferrer');}
  else{toast(`Add the live website URL for ${card.querySelector('h3').textContent} in PROFILE.projects.`);}
}));

// External links only open when a real URL has been configured.
document.querySelectorAll('[data-link]').forEach(a=>a.addEventListener('click',e=>{e.preventDefault();const url=PROFILE[a.dataset.link];if(url)window.open(url,'_blank','noopener,noreferrer');else toast(`Add your ${a.dataset.link} URL in the PROFILE settings.`);}));
$("#cvBtn").addEventListener("click",()=>{if(PROFILE.cvFile){const a=document.createElement("a");a.href=PROFILE.cvFile;a.download="Anil-Akkisagar-CV";a.click();}else toast("Add your CV file path in PROFILE.cvFile first.");});
$("#contactBtn").addEventListener("click",()=>{if(PROFILE.email)window.location.href=`mailto:${PROFILE.email}?subject=Portfolio%20contact`;else toast("Add your professional email in PROFILE.email first.");});
$("#year").textContent=new Date().getFullYear();
</script>
</body>
</html>
