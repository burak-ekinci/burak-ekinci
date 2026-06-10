
<style>
@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
:root{--teal-50:#E1F5EE;--teal-400:#1D9E75;--teal-600:#0F6E56;--teal-800:#085041;--purple-50:#EEEDFE;--purple-400:#7F77DD;--purple-600:#534AB7;--purple-800:#3C3489}
body{font-family:var(--font-sans);background:transparent}
.wrapper{max-width:680px;padding:0.5rem 0 2rem}
.hero{border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);background:var(--color-background-primary);padding:2rem 1.75rem 1.5rem;margin-bottom:1rem;position:relative;overflow:hidden}
.hero::before{content:'0x4275726163';position:absolute;top:-8px;right:1.5rem;font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--color-text-tertiary);letter-spacing:0.05em}
.hex-badge{display:inline-flex;align-items:center;gap:6px;background:var(--teal-50);color:var(--teal-600);font-family:'JetBrains Mono',monospace;font-size:11px;padding:3px 10px;border-radius:4px;margin-bottom:1rem;border:0.5px solid var(--teal-400)}
.hero-name{font-family:'JetBrains Mono',monospace;font-size:22px;font-weight:600;color:var(--color-text-primary);line-height:1.2;margin-bottom:0.5rem}
.hero-name span{color:var(--teal-400)}
.hero-sub{font-size:14px;color:var(--color-text-secondary);line-height:1.7;max-width:500px}
.social-row{display:flex;gap:8px;margin-top:1.25rem;flex-wrap:wrap}
.social-btn{display:inline-flex;align-items:center;gap:6px;padding:6px 14px;border:0.5px solid var(--color-border-secondary);border-radius:var(--border-radius-md);font-size:12px;color:var(--color-text-secondary);text-decoration:none;background:var(--color-background-secondary);transition:all .15s}
.social-btn:hover{border-color:var(--teal-400);color:var(--teal-600)}
.social-btn i{font-size:15px}
.section{margin-bottom:1rem}
.section-label{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--teal-400);letter-spacing:0.08em;text-transform:uppercase;margin-bottom:0.75rem;display:flex;align-items:center;gap:8px}
.section-label::after{content:'';flex:1;height:0.5px;background:var(--color-border-tertiary)}
.focus-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.focus-card{background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-md);padding:0.875rem 1rem;display:flex;gap:10px;align-items:flex-start}
.focus-card i{font-size:18px;color:var(--teal-400);flex-shrink:0;margin-top:1px}
.focus-card-title{font-size:13px;font-weight:500;color:var(--color-text-primary);margin-bottom:2px}
.focus-card-sub{font-size:12px;color:var(--color-text-secondary);line-height:1.5}
.stack-grid{display:flex;flex-wrap:wrap;gap:8px}
.stack-tag{display:inline-flex;align-items:center;gap:5px;padding:5px 12px;border:0.5px solid var(--color-border-tertiary);border-radius:20px;font-size:12px;color:var(--color-text-secondary);background:var(--color-background-secondary)}
.stack-tag.highlight{border-color:var(--purple-400);color:var(--purple-600);background:var(--purple-50)}
.stack-tag i{font-size:14px}
.open-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.open-item{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:0.75rem 1rem;font-size:13px;color:var(--color-text-secondary);display:flex;align-items:center;gap:8px}
.open-item i{font-size:15px;color:var(--purple-400)}
.counter{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--color-text-tertiary);text-align:center;margin-top:1rem;letter-spacing:0.05em}
</style>
<h2 class="sr-only" style="position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)">Burak Ekinci – Blockchain & Full-Stack Developer profile</h2>
<div class="wrapper">
  <div class="hero">
    <div class="hex-badge"><i class="ti ti-hexagon" aria-hidden="true"></i>burak.eth</div>
    <div class="hero-name">Burak <span>Ekinci</span></div>
    <div class="hero-name" style="font-size:15px;font-weight:400;color:var(--color-text-secondary);margin-bottom:0.75rem;font-family:var(--font-sans)">Blockchain & Full-Stack Developer</div>
    <div class="hero-sub">Production-ready smart contracts, Web3 apps, and scalable Web2 systems. Currently leading projects across Web3, AI-powered automation, and full-stack product development.</div>
    <div class="social-row">
      <a class="social-btn" href="mailto:bltycxkk@gmail.com"><i class="ti ti-mail" aria-hidden="true"></i>Email</a>
      <a class="social-btn" href="https://www.linkedin.com/in/burak-ekinci-5a592521a/"><i class="ti ti-brand-linkedin" aria-hidden="true"></i>LinkedIn</a>
      <a class="social-btn" href="https://x.com/Leviathan_js"><i class="ti ti-brand-x" aria-hidden="true"></i>@Leviathan_js</a>
      <a class="social-btn" href="https://discord.gg/ubj9EfUe"><i class="ti ti-brand-discord" aria-hidden="true"></i>Discord</a>
      <a class="social-btn" href="https://www.instagram.com/lambdavnc/"><i class="ti ti-brand-instagram" aria-hidden="true"></i>Instagram</a>
    </div>
  </div>

  <div class="section">
    <div class="section-label">// focus</div>
    <div class="focus-grid">
      <div class="focus-card">
        <i class="ti ti-lock" aria-hidden="true"></i>
        <div>
          <div class="focus-card-title">Smart Contracts</div>
          <div class="focus-card-sub">Solidity, ERC721 / ERC20, security-aware design</div>
        </div>
      </div>
      <div class="focus-card">
        <i class="ti ti-world" aria-hidden="true"></i>
        <div>
          <div class="focus-card-title">Web3 Frontend</div>
          <div class="focus-card-sub">Ethers.js, Web3.js, wallet integrations</div>
        </div>
      </div>
      <div class="focus-card">
        <i class="ti ti-layers-intersect" aria-hidden="true"></i>
        <div>
          <div class="focus-card-title">Full-Stack Web2</div>
          <div class="focus-card-sub">Next.js, Node.js, MongoDB</div>
        </div>
      </div>
      <div class="focus-card">
        <i class="ti ti-robot" aria-hidden="true"></i>
        <div>
          <div class="focus-card-title">AI & Automation</div>
          <div class="focus-card-sub">n8n workflows, system integrations</div>
        </div>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="section-label">// stack</div>
    <div class="stack-grid">
      <div class="stack-tag highlight"><i class="ti ti-file-code" aria-hidden="true"></i>Solidity</div>
      <div class="stack-tag highlight"><i class="ti ti-hexagon-letter-e" aria-hidden="true"></i>Ethers.js</div>
      <div class="stack-tag highlight"><i class="ti ti-currency-ethereum" aria-hidden="true"></i>Web3.js</div>
      <div class="stack-tag"><i class="ti ti-brand-nextjs" aria-hidden="true"></i>Next.js</div>
      <div class="stack-tag"><i class="ti ti-brand-react" aria-hidden="true"></i>React</div>
      <div class="stack-tag"><i class="ti ti-brand-nodejs" aria-hidden="true"></i>Node.js</div>
      <div class="stack-tag"><i class="ti ti-brand-typescript" aria-hidden="true"></i>TypeScript</div>
      <div class="stack-tag"><i class="ti ti-brand-javascript" aria-hidden="true"></i>JavaScript</div>
      <div class="stack-tag"><i class="ti ti-database" aria-hidden="true"></i>MongoDB</div>
      <div class="stack-tag"><i class="ti ti-settings-automation" aria-hidden="true"></i>n8n</div>
      <div class="stack-tag"><i class="ti ti-brand-html5" aria-hidden="true"></i>HTML / CSS</div>
      <div class="stack-tag"><i class="ti ti-brand-bootstrap" aria-hidden="true"></i>Bootstrap</div>
    </div>
  </div>

  <div class="section">
    <div class="section-label">// open to</div>
    <div class="open-grid">
      <div class="open-item"><i class="ti ti-link" aria-hidden="true"></i>Web3 & blockchain projects</div>
      <div class="open-item"><i class="ti ti-rocket" aria-hidden="true"></i>Startup product development</div>
      <div class="open-item"><i class="ti ti-circuit-board" aria-hidden="true"></i>System design & automation</div>
      <div class="open-item"><i class="ti ti-users" aria-hidden="true"></i>Tech leadership & collaboration</div>
    </div>
  </div>

  <div class="counter">profile_views = <span id="pv">∞</span></div>
</div>
