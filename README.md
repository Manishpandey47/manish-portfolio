<!DOCTYPE html>
<html lang='en'>
<head>
  <meta charset='utf-8' />
  <meta name='viewport' content='width=device-width, initial-scale=1' />
  <title>Manish Pandey — Portfolio (Editable Photo)</title>
  <style>
    :root{ --bg:#0b1220; --panel:#0f172a; --card:#111827; --muted:#94a3b8; --text:#e5e7eb; --brand:#22c55e; --brand-2:#38bdf8; --border:#1f2937; }
    body{margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Arial;background:linear-gradient(180deg,var(--panel),var(--bg));color:var(--text)}
    a{color:#38bdf8;text-decoration:none} a:hover{text-decoration:underline}
    header{position:sticky;top:0;z-index:20;background:rgba(15,23,42,.85);backdrop-filter:blur(8px);border-bottom:1px solid var(--border)}
    .nav{max-width:1200px;margin:0 auto;padding:12px 16px;display:flex;justify-content:space-between;align-items:center}
    .logo{width:34px;height:34px;border-radius:8px;background:linear-gradient(135deg,#22c55e,#38bdf8);display:grid;place-items:center;color:#0b1220;font-weight:900}
    .links a{color:#cbd5e1;margin-left:12px;padding:6px 8px;border-radius:8px} .links a:hover{background:#0b1220}
    main{max-width:1200px;margin:0 auto;padding:24px 16px 64px}
    section{margin:24px 0;border:1px solid var(--border);border-radius:16px;overflow:hidden;background:radial-gradient(1000px 600px at 110% -10%, rgba(167,139,250,.08), transparent 40%), linear-gradient(180deg, rgba(255,255,255,.02), rgba(255,255,255,.01));}
    .content{padding:16px 18px 20px}
    .section-header{display:flex;justify-content:space-between;align-items:baseline;padding:12px 16px;border-bottom:1px solid var(--border)}
    .section-header h2{margin:0;color:#f8fafc}
    .hero{display:grid;grid-template-columns:1.2fr .8fr;gap:18px;align-items:center}
    .card{padding:20px;border:1px solid var(--border);border-radius:16px;background:linear-gradient(135deg, rgba(56,189,248,.08), rgba(34,197,94,.08))}
    .btn{padding:10px 14px;border:1px solid var(--border);border-radius:10px;background:#0b1220;color:#fff;cursor:pointer}
    .btn.primary{background:linear-gradient(135deg,#22c55e,#38bdf8);color:#0b1220;border:none;font-weight:700}
    .stats{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:12px}
    .stat{background:#0b1220;border:1px solid var(--border);border-radius:12px;padding:12px;text-align:center}
    .stat b{font-size:22px}
    .tag{display:inline-flex;gap:6px;padding:6px 10px;border-radius:999px;background:#0b1220;border:1px solid var(--border);font-size:12px}
    /* Photo */
    .photo-wrap{position:relative}
    .profile-photo{width:100%;max-height:520px;object-fit:cover;border-radius:16px;border:1px solid var(--border)}
    .photo-actions{position:absolute;right:12px;bottom:12px;display:flex;gap:8px;z-index:5}
    .photo-actions .btn{background:rgba(11,18,32,.92);border-color:#334155}
    .photo-toolbar{display:flex;gap:8px;margin-top:10px;justify-content:flex-end}
    input[type=file]{display:none}
    @media (max-width:900px){ .hero{grid-template-columns:1fr} .stats{grid-template-columns:repeat(2,1fr)} }
  </style>
</head>
<body>
  <header>
    <div class='nav'>
      <div style='display:flex;align-items:center;gap:10px'><div class='logo'>MP</div><strong>Manish Pandey</strong></div>
      <div class='links'>
        <a href='#about'>About</a>
        <a href='#skills'>Skills</a>
        <a href='#experience'>Experience</a>
        <a href='#certs'>Certifications</a>
        <a href='#testimonials'>Testimonials</a>
        <a href='#contact'>Contact</a>
      </div>
    </div>
  </header>

  <main>
    <section id='hero'>
      <div class='content hero'>
        <div class='card'>
          <h1 style='margin:0;font-size:34px'>Manish Pandey</h1>
          <div style='color:#cbd5e1;margin-top:4px;font-size:18px'>Senior Consultant — Technical Support, Incident Management & IT Operations</div>
          <div style='margin-top:10px;color:#a1a1aa'>Lucknow, India • <a href='mailto:manishpandey47@yahoo.com'>manishpandey47@yahoo.com</a> • <a href='tel:+918802914640'>+91 8802914640</a></div>
          <div style='margin-top:16px;display:flex;gap:10px;flex-wrap:wrap'>
            <a class='btn primary' href='#contact'>Let’s Connect</a>
            <a class='btn' href='manish_Pandey_resume.pdf' download>Download Résumé (PDF)</a>
            <button class='btn' onclick='window.print()'>Print / Save as PDF</button>
          </div>
          <div class='stats'>
            <div class='stat'><b>10+ yrs</b><div>Experience</div></div>
            <div class='stat'><b>8+ domains</b><div>Ops & Support</div></div>
            <div class='stat'><b>High Sev</b><div>Incident Leadership</div></div>
          </div>
          <div style='margin-top:12px'>
            <span class='tag'>IT Service Delivery</span>
            <span class='tag'>Problem & Change</span>
            <span class='tag'>Project Management</span>
            <span class='tag'>Stakeholder Management</span>
          </div>
        </div>
        <div>
          <div class='photo-wrap'>
            <img id='profilePhoto' class='profile-photo' alt='Profile photo'
                 src='data:https://github.com/Manishpandey47/manish-portfolio/blob/main/assets/Profile.jpg;utf8,<?xml version="1.0" encoding="UTF-8"?><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 200"><rect width="200" height="200" fill="#0b1220"/><circle cx="100" cy="72" r="40" fill="#1f2937"/><rect x="35" y="120" width="130" height="60" rx="30" fill="#1f2937"/></svg>'
                 data-default-src='data:https://github.com/Manishpandey47/manish-portfolio/blob/main/assets/Profile.jpg;utf8,<?xml version="1.0" encoding="UTF-8"?><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 200"><rect width="200" height="200" fill="#0b1220"/><circle cx="100" cy="72" r="40" fill="#1f2937"/><rect x="35" y="120" width="130" height="60" rx="30" fill="#1f2937"/></svg>'>
            <div class='photo-actions'>
              <input id='photoInput' type='file' accept='image/*'>
              <button class='btn' id='btnChangePhoto' title='Change profile picture'>Change Photo</button>
              <button class='btn' id='btnResetPhoto' title='Reset to default'>Reset</button>
            </div>
          </div>
          <div class='photo-toolbar'>
            <button class='btn' id='btnChangePhoto2'>Change Photo</button>
            <button class='btn' id='btnResetPhoto2'>Reset</button>
          </div>
        </div>
      </div>
    </section>

    <section id='about'>
      <div class='section-header'><h2>About</h2><div style='color:#94a3b8;font-size:13px'>Profile & Value Proposition</div></div>
      <div class='content'>
        <p>IT professional with 10+ years managing Technical Support, Incident/Problem/Change and Business Operations, improving processes and service availability. Currently a Senior Consultant at HCL Technologies, leading project delivery, high‑severity incident response, and mentoring teams.</p>
      </div>
    </section>

    <section id='skills'>
      <div class='section-header'><h2>Skills & Tools</h2><div style='color:#94a3b8;font-size:13px'>Core Competencies & Technology</div></div>
      <div class='content' style='display:grid;grid-template-columns:1fr 1fr;gap:16px'>
        <div>
          <h3>Core Competencies</h3>
          <div style='display:flex;flex-wrap:wrap;gap:8px;margin-top:8px'>
            <span class='tag'>Strategic & Operational IT Planning</span><span class='tag'>NOC Monitoring</span><span class='tag'>Database Management</span>
            <span class='tag'>Incident/Problem/Change (IPC)</span><span class='tag'>SLA Management</span><span class='tag'>Site & URL Configuration</span>
            <span class='tag'>Escalation Management</span><span class='tag'>SOP Implementation & Review</span><span class='tag'>Application Support & Analysis</span><span class='tag'>Stakeholder Management</span>
          </div>
        </div>
        <div>
          <h3>Technology</h3>
          <div style='display:flex;flex-wrap:wrap;gap:8px;margin-top:8px'>
            <span class='tag'>AWS</span><span class='tag'>SAP</span><span class='tag'>Redwood Cronacle</span><span class='tag'>HPOVO</span><span class='tag'>Cargonet</span><span class='tag'>ServiceNow</span><span class='tag'>MS Office</span><span class='tag'>Kentico</span>
          </div>
        </div>
      </div>
    </section>

    <section id='experience'>
      <div class='section-header'><h2>Experience</h2><div style='color:#94a3b8;font-size:13px'>Timeline & Contributions</div></div>
      <div class='content'>
        <ul>
          <li><b>Senior Consultant — HCL Technologies Ltd., Lucknow</b> (Jul 2021 – Present)</li>
          <li><b>Team Lead — HCL Technologies Ltd.</b> (Mar 2018 – Jun 2021)</li>
          <li><b>Application Support Analyst — AON Hewitt (Payroll: ITC InfoTech), Gurgaon</b> (May 2017 – Mar 2018)</li>
          <li><b>NOC Engineer — TCS (Payroll: Future Focus Infotech), Gurgaon</b> (Jul 2015 – May 2017)</li>
          <li><b>NOC Engineer — Huawei (Payroll: Evolve Tech) at Idea Cellular</b> (Feb 2014 – Jun 2015)</li>
          <li><b>NOC Engineer — Aptara Corporations Pvt. Ltd., Noida</b> (Oct 2012 – Jan 2014)</li>
          <li><b>Microsoft Trainer — Educomp Solutions Ltd., Varanasi</b> (Aug 2011 – Dec 2011)</li>
        </ul>
      </div>
    </section>

    <section id='certs'>
      <div class='section-header'><h2>Certifications & Education</h2><div style='color:#94a3b8;font-size:13px'>Validated Expertise</div></div>
      <div class='content' style='display:grid;grid-template-columns:1fr 1fr;gap:16px'>
        <div><h3>Certifications</h3><ul><li>AWS Certified Cloud Practitioner (CLF‑C01) — 2022</li><li>ITIL Foundation 2017 V3</li></ul></div>
        <div><h3>Education</h3><p><b>B.Tech — Computer Science & Engineering</b><br/>Gautam Buddha Technical University, Lucknow</p></div>
      </div>
    </section>

    <section id='testimonials'>
      <div class='section-header'><h2>Testimonials</h2><div style='color:#94a3b8;font-size:13px'>What colleagues & stakeholders say</div></div>
      <div class='content'>
        <div style='background:#0b1220;border:1px solid var(--border);border-radius:12px;padding:16px;margin-bottom:10px'>“Manish is the person you want in the room during high‑severity incidents — calm, structured, and relentlessly focused on restoring service.”<div style='margin-top:8px;color:#cbd5e1;font-weight:600'>— Senior Delivery Manager, HCL</div></div>
        <div style='background:#0b1220;border:1px solid var(--border);border-radius:12px;padding:16px;margin-bottom:10px'>“He established robust SOPs and improved cross‑team coordination, which directly reduced escalations and improved SLA compliance.”<div style='margin-top:8px;color:#cbd5e1;font-weight:600'>— Client Project Lead, Tech Data</div></div>
        <div style='background:#0b1220;border:1px solid var(--border);border-radius:12px;padding:16px'>“A natural mentor with an eye for detail — our onboarding time dropped significantly under his guidance.”<div style='margin-top:8px;color:#cbd5e1;font-weight:600'>— Team Member</div></div>
      </div>
    </section>

    <section id='contact'>
      <div class='section-header'><h2>Contact</h2><div style='color:#94a3b8;font-size:13px'>Let’s build something impactful</div></div>
      <div class='content' style='display:grid;grid-template-columns:1fr 1fr;gap:16px'>
        <div style='background:#0b1220;border:1px solid var(--border);border-radius:12px;padding:16px'>
          <h3>Direct</h3>
          <p>Email: <a href='mailto:manishpandey47@yahoo.com'>manishpandey47@yahoo.com</a><br/>Phone: <a href='tel:+918802914640'>+91 8802914640</a><br/>Location: Lucknow, 226010</p>
          <div style='display:flex;gap:10px'><button class='btn' id='copyEmail'>Copy Email</button><a class='btn' href='mailto:manishpandey47@yahoo.com?subject=Hello%20Manish&body=Hi%20Manish,%20'>Quick Mail</a></div>
        </div>
        <div style='background:#0b1220;border:1px solid var(--border);border-radius:12px;padding:16px'>
          <h3>Message</h3>
          <form onsubmit='return sendMail(this)'>
            <input name='name' placeholder='Your name' required style='margin-top:8px;width:100%;padding:10px;border-radius:10px;border:1px solid var(--border);background:#0b1220;color:#fff'>
            <input name='email' type='email' placeholder='Your email' required style='margin-top:8px;width:100%;padding:10px;border-radius:10px;border:1px solid var(--border);background:#0b1220;color:#fff'>
            <textarea name='message' rows='5' placeholder='Project details' required style='margin-top:8px;width:100%;padding:10px;border-radius:10px;border:1px solid var(--border);background:#0b1220;color:#fff'></textarea>
            <div style='margin-top:12px'><button class='btn primary' type='submit'>Send</button></div>
          </form>
        </div>
      </div>
    </section>
  </main>

  <footer style='text-align:center;color:#94a3b8;padding:24px;border-top:1px solid var(--border)'>© <span id='year'></span> Manish Pandey. All rights reserved.</footer>

  <script>
    // Footer year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Copy email
    document.getElementById('copyEmail').addEventListener('click', async ()=>{ try{ await navigator.clipboard.writeText('manishpandey47@yahoo.com'); alert('Email copied!'); }catch(e){ alert('Copy failed'); } });

    // Photo editor: change/reset & persistence
    const imgEl = document.getElementById('profilePhoto');
    const fileEl = document.getElementById('photoInput');
    const changeBtns = [document.getElementById('btnChangePhoto'), document.getElementById('btnChangePhoto2')];
    const resetBtns  = [document.getElementById('btnResetPhoto'), document.getElementById('btnResetPhoto2')];
    const DEFAULT_SRC = imgEl.getAttribute('data-default-src') || imgEl.src;

    // Load saved image if present
    try {
      const saved = localStorage.getItem('mp_profile_photo');
      if (saved) imgEl.src = saved;
    } catch (e) { /* localStorage may be blocked */ }

    changeBtns.forEach(btn => btn && btn.addEventListener('click', () => fileEl.click()));

    fileEl.addEventListener('change', async (e) => {
      const file = e.target.files && e.target.files[0];
      if (!file) return;
      if (!file.type.startsWith('image/')) { alert('Please choose an image file.'); return; }
      try {
        const dataUrl = await resizeToDataURL(file, 900, 900, 0.92);
        imgEl.src = dataUrl;
        try { localStorage.setItem('mp_profile_photo', dataUrl); } catch (err) {}
      } catch (err) {
        console.error(err); alert('Unable to load image.');
      } finally { e.target.value=''; }
    });

    resetBtns.forEach(btn => btn && btn.addEventListener('click', () => {
      try { localStorage.removeItem('mp_profile_photo'); } catch(e) {}
      imgEl.src = DEFAULT_SRC;
    }));

    function resizeToDataURL(file, maxW=900, maxH=900, quality=0.92) {
      return new Promise((resolve, reject) => {
        const reader = new FileReader();
        reader.onload = () => {
          const img = new Image();
          img.onload = () => {
            let w = img.width, h = img.height;
            const ratio = Math.min(maxW / w, maxH / h, 1);
            w = Math.round(w * ratio); h = Math.round(h * ratio);
            const c = document.createElement('canvas');
            c.width = w; c.height = h;
            const ctx = c.getContext('2d');
            ctx.fillStyle = '#0b1220';
            ctx.fillRect(0,0,w,h);
            ctx.drawImage(img, 0, 0, w, h);
            const mime = file.type.includes('png') ? 'image/png' : 'image/jpeg';
            try { resolve(c.toDataURL(mime, quality)); } catch (err) { reject(err); }
          };
          img.onerror = reject;
          img.src = reader.result;
        };
        reader.onerror = reject;
        reader.readAsDataURL(file);
      });
    }

    // Contact form (mailto)
    function sendMail(form){
      const name = encodeURIComponent(form.name.value.trim());
      const email = encodeURIComponent(form.email.value.trim());
      const message = encodeURIComponent(form.message.value.trim());
      const subject = `Portfolio Inquiry from ${name}`;
      const body = `Name: ${name}%0AEmail: ${email}%0A%0A${message}`;
      window.location.href = `mailto:manishpandey47@yahoo.com?subject=${subject}&body=${body}`;
      return false;
    }
    window.sendMail = sendMail;
  </script>
</body>
</html>
