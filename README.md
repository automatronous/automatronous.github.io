<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>automatronous - Portfolio</title>
    <style>
        :root{--bg:#0a0a0f;--fg:#e0e0e0;--accent1:#00d4ff;--accent2:#ff6b9d;--glass:rgba(255,255,255,0.05)}
        *{margin:0;padding:0;box-sizing:border-box}
        body{font-family:system-ui,-apple-system,sans-serif;line-height:1.6;color:var(--fg);background:var(--bg);min-height:100vh}
        .c{max-w:1000px;m:auto;p:20px}
        h1{font-size:clamp(2.5rem,8vw,4rem);background:linear-gradient(45deg,var(--accent1),var(--accent2));-webkit-background-clip:text;-webkit-text-fill-color:transparent;ta:center;mb:1rem}
        .sub{font-size:1.1rem;opacity:.9;ta:center;mb:3rem}
        .sec{background:var(--glass);backdrop-filter:blur(12px);border:1px solid rgba(255,255,255,.1);br:20px;p:2rem;ma:2rem 0}
        h2{color:var(--accent1);font-size:1.8rem;mb:1.5rem}
        .skills{d:g;gc:repeat(auto-fit,minmax(150px,1fr));g:1rem;mb:3rem}
        .sk{background:var(--glass);p:1.5rem;br:12px;ta:center;border:1px solid rgba(255,255,255,.1);cursor:pointer;transition:all .3s}
        .sk:hover{transform:tr(-2px);box-shadow:0 10px 25px rgba(0,212,255,.2)}
        .pro{margin:3rem 0}
        h3{color:var(--accent2);mb:1rem;font-size:1.4rem}
        .pg{d:g;gc:repeat(auto-fit,minmax(280px,1fr));g:2rem}
        .pr{background:var(--glass);br:16px;p:2rem;border:1px solid rgba(255,255,255,.1);transition:all .3s}
        .pr:hover{scale:1.02;box-shadow:0 15px 30px rgba(255,107,157,.2)}
        a{color:var(--accent2);td:none;fw:600}
        a:hover{text-decoration:underline}
        .links{ta:center;mt:4rem}
        .links a{display:i-b;ma:.5rem 1rem;p:.8rem 1.6rem;background:linear-gradient(45deg,var(--accent1),var(--accent2));color:#fff;td:none;br:30px;fw:600;transition:all .3s;text-decoration:none}
        .links a:hover{ty:-2px;box-shadow:0 8px 20px rgba(0,212,255,.3)}
        @media(p:768px){.c{p:15px}.sec{p:1.5rem;ma:1.5rem 0}}
    </style>
</head>
<body>
    <div class="c">
        <header>
            <h1>automatronous</h1>
            <p class="sub">CS Student | AI/ML | Cyber | Hackathons</p>
        </header>
        <section class="sec">
            <h2>About</h2>
            <p>Curious CS freshman from Pune. Enthusiastic problem-solver! Aspiring AI/ML engineer: React apps, Python ML (agri hacks), ESP32 bots, Arduino. Cyber fan—secure code & hacking. History/gaming too. Tech: React/Flask, Python/ML, ESP32, UI/UX/CCNA. Collabs? 🚀</p>
        </section>
        <section class="sec">
            <h2>Skills</h2>
            <div class="skills">
                <div class="sk">React/JS</div>
                <div class="sk">Python/ML</div>
                <div class="sk">ESP32/Arduino</div>
                <div class="sk">Cybersecurity</div>
                <div class="sk">Flask/Supabase</div>
                <div class="sk">UI/UX</div>
            </div>
        </section>
        <section class="sec pro">
            <h2>Projects</h2>
            <div class="pg">
                <div class="pr">
                    <h3>Stock App</h3>
                    <p>React/Flask inventory tracker w/ animations.</p>
                    <a href="https://github.com/automatronous?tab=repositories" target="_blank">GitHub →</a>
                </div>
                <div class="pr">
                    <h3>Agri ML</h3>
                    <p>Hackathon model: satellite data predictions.</p>
                    <a href="https://github.com/automatronous?tab=repositories" target="_blank">GitHub →</a>
                </div>
                <div class="pr">
                    <h3>Sumo Bot</h3>
                    <p>ESP32 autonomous robot w/ motors.</p>
                    <a href="https://github.com/automatronous?tab=repositories" target="_blank">GitHub →</a>
                </div>
            </div>
        </section>
        <div class="links">
            <a href="https://github.com/automatronous" target="_blank">GitHub</a>
            <a href="mailto: ishanughade533@gmail.com">Email</a>
            <a href="https://www.linkedin.com/in/ishan-ughade-004485334?utm_source=share_via&utm_content=profile&utm_medium=member_android" target="_blank">LinkedIn</a>
        </div>
    </div>
</body>
</html>
