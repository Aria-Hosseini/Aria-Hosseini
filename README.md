
<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Syne:wght@400;600;700;800&display=swap');

:root {
  --aria-accent: #6EE7B7;
  --aria-accent2: #818CF8;
  --aria-bg: #0D1117;
  --aria-surface: #161B22;
  --aria-border: #30363D;
  --aria-text: #E6EDF3;
  --aria-muted: #8B949E;
  --aria-tag-bg: #1C2128;
}

* { box-sizing: border-box; margin: 0; padding: 0; }

.readme {
  font-family: 'Syne', sans-serif;
  background: var(--aria-bg);
  color: var(--aria-text);
  padding: 2.5rem 2rem;
  border-radius: 12px;
  border: 1px solid var(--aria-border);
  max-width: 680px;
  margin: 0 auto;
}

.header {
  margin-bottom: 2.5rem;
  position: relative;
}

.greeting {
  font-size: 13px;
  font-family: 'Space Mono', monospace;
  color: var(--aria-accent);
  letter-spacing: 0.12em;
  text-transform: uppercase;
  margin-bottom: 0.5rem;
}

.name {
  font-size: 2.8rem;
  font-weight: 800;
  line-height: 1.1;
  background: linear-gradient(135deg, var(--aria-text) 40%, var(--aria-accent2));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 0.6rem;
}

.title {
  font-size: 1rem;
  color: var(--aria-muted);
  font-weight: 400;
  font-family: 'Space Mono', monospace;
}

.divider {
  border: none;
  border-top: 1px solid var(--aria-border);
  margin: 2rem 0;
}

.section-label {
  font-size: 11px;
  font-family: 'Space Mono', monospace;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: var(--aria-accent);
  margin-bottom: 1rem;
}

.tech-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 0.5rem;
}

.tech-group {
  margin-bottom: 1.5rem;
}

.group-title {
  font-size: 11px;
  color: var(--aria-muted);
  font-family: 'Space Mono', monospace;
  letter-spacing: 0.08em;
  margin-bottom: 8px;
  padding-left: 2px;
}

.badge {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--aria-tag-bg);
  border: 1px solid var(--aria-border);
  border-radius: 6px;
  padding: 5px 10px;
  font-size: 12.5px;
  font-weight: 600;
  color: var(--aria-text);
  letter-spacing: 0.02em;
  transition: border-color 0.15s, background 0.15s;
  cursor: default;
}

.badge:hover {
  border-color: var(--aria-accent2);
  background: #1a1f2e;
}

.badge .dot {
  width: 6px;
  height: 6px;
  border-radius: 50%;
  flex-shrink: 0;
}

.dot-js { background: #F7DF1E; }
.dot-ts { background: #3178C6; }
.dot-react { background: #61DAFB; }
.dot-next { background: #E6EDF3; }
.dot-html { background: #E34F26; }
.dot-css { background: #1572B6; }
.dot-tw { background: #06B6D4; }
.dot-mat { background: #757575; }
.dot-electron { background: #47848F; }
.dot-strapi { background: #4945FF; }
.dot-cs { background: #953DAC; }
.dot-zustand { background: #6EE7B7; }
.dot-jest { background: #C21325; }
.dot-rtl { background: #E33332; }

.contact {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
}

.contact-link {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  background: var(--aria-tag-bg);
  border: 1px solid var(--aria-border);
  border-radius: 8px;
  padding: 8px 14px;
  font-size: 13px;
  font-weight: 600;
  color: var(--aria-muted);
  text-decoration: none;
  font-family: 'Space Mono', monospace;
  transition: all 0.15s;
}

.contact-link:hover {
  border-color: var(--aria-accent);
  color: var(--aria-accent);
}

.contact-icon {
  font-size: 15px;
}

.status-bar {
  display: flex;
  align-items: center;
  gap: 8px;
  margin-bottom: 2rem;
}

.status-dot {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: var(--aria-accent);
  box-shadow: 0 0 0 3px rgba(110, 231, 183, 0.18);
  animation: pulse 2s ease-in-out infinite;
}

@keyframes pulse {
  0%, 100% { box-shadow: 0 0 0 3px rgba(110,231,183,0.18); }
  50% { box-shadow: 0 0 0 6px rgba(110,231,183,0.08); }
}

.status-text {
  font-size: 12px;
  font-family: 'Space Mono', monospace;
  color: var(--aria-muted);
}

.copy-notice {
  margin-top: 2.5rem;
  padding: 1rem 1.2rem;
  background: var(--aria-tag-bg);
  border: 1px solid var(--aria-border);
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
}

.copy-notice p {
  font-size: 12px;
  font-family: 'Space Mono', monospace;
  color: var(--aria-muted);
  line-height: 1.5;
}

.copy-btn {
  flex-shrink: 0;
  background: none;
  border: 1px solid var(--aria-border);
  border-radius: 6px;
  padding: 6px 12px;
  color: var(--aria-accent);
  font-family: 'Space Mono', monospace;
  font-size: 11px;
  cursor: pointer;
  letter-spacing: 0.08em;
  transition: background 0.15s;
}

.copy-btn:hover { background: rgba(110,231,183,0.08); }
</style>

<div class="readme">
  <h2 class="sr-only" style="position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)">GitHub profile README for Aria, a front-end web developer</h2>

  <div class="header">
    <p class="greeting">// hello world</p>
    <h1 class="name">I'm Aria.</h1>
    <p class="title">Front-end developer — building for the web</p>
  </div>

  <div class="status-bar">
    <span class="status-dot"></span>
    <span class="status-text">open to new opportunities</span>
  </div>

  <p class="section-label">// tech stack</p>

  <div class="tech-group">
    <p class="group-title">languages</p>
    <div class="tech-grid">
      <span class="badge"><span class="dot dot-js"></span>JavaScript</span>
      <span class="badge"><span class="dot dot-ts"></span>TypeScript</span>
      <span class="badge"><span class="dot dot-html"></span>HTML5</span>
      <span class="badge"><span class="dot dot-css"></span>CSS3</span>
      <span class="badge"><span class="dot dot-cs"></span>C#</span>
    </div>
  </div>

  <div class="tech-group">
    <p class="group-title">frameworks & libraries</p>
    <div class="tech-grid">
      <span class="badge"><span class="dot dot-react"></span>React</span>
      <span class="badge"><span class="dot dot-next"></span>Next.js</span>
      <span class="badge"><span class="dot dot-electron"></span>Electron.js</span>
      <span class="badge"><span class="dot dot-mat"></span>Materialize</span>
    </div>
  </div>

  <div class="tech-group">
    <p class="group-title">styling</p>
    <div class="tech-grid">
      <span class="badge"><span class="dot dot-tw"></span>Tailwind CSS</span>
    </div>
  </div>

  <div class="tech-group">
    <p class="group-title">state & backend</p>
    <div class="tech-grid">
      <span class="badge"><span class="dot dot-zustand"></span>Zustand</span>
      <span class="badge"><span class="dot dot-strapi"></span>Strapi</span>
    </div>
  </div>

  <div class="tech-group">
    <p class="group-title">testing</p>
    <div class="tech-grid">
      <span class="badge"><span class="dot dot-jest"></span>Jest</span>
      <span class="badge"><span class="dot dot-rtl"></span>Testing Library</span>
    </div>
  </div>

  <hr class="divider">

  <p class="section-label">// contact</p>
  <div class="contact">
    <a class="contact-link" href="https://linkedin.com/in/aria-hosseini" target="_blank">
      <i class="ti ti-brand-linkedin contact-icon" aria-hidden="true"></i>LinkedIn
    </a>
    <a class="contact-link" href="https://t.me/misty_enigma" target="_blank">
      <i class="ti ti-brand-telegram contact-icon" aria-hidden="true"></i>Telegram
    </a>
    <a class="contact-link" href="mailto:ariahosseini.dev@gmail.com" target="_blank">
      <i class="ti ti-mail contact-icon" aria-hidden="true"></i>Email
    </a>
  </div>

  <div class="copy-notice">
    <p>This is a live preview of your new README design. Copy the markdown below to your GitHub profile repo.</p>
    <button class="copy-btn" onclick="copyMarkdown()">COPY MD ↗</button>
  </div>
</div>

<script>
function copyMarkdown() {
  const md = `<div align="center">

<!-- greeting -->
\`\`\`
// hello world
\`\`\`

# I'm Aria.
### Front-end developer — building for the web

</div>

---

## // tech stack

**Languages**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![C#](https://img.shields.io/badge/C%23-953DAC?style=flat-square&logo=csharp&logoColor=white)

**Frameworks & Libraries**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Materialize](https://img.shields.io/badge/Materialize-757575?style=flat-square&logo=material-design&logoColor=white)

**Styling**
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**State & Backend**
![Zustand](https://img.shields.io/badge/Zustand-6EE7B7?style=flat-square&logoColor=black)
![Strapi](https://img.shields.io/badge/Strapi-4945FF?style=flat-square&logo=strapi&logoColor=white)

**Testing**
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white)

---

## // contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/aria-hosseini)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/misty_enigma)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ariahosseini.dev@gmail.com)

</div>`;

  navigator.clipboard.writeText(md).then(() => {
    const btn = document.querySelector('.copy-btn');
    btn.textContent = 'COPIED ✓';
    btn.style.color = '#6EE7B7';
    setTimeout(() => { btn.textContent = 'COPY MD ↗'; btn.style.color = ''; }, 2000);
  });
}
</script>
