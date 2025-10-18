# digiqash-agencies.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Digiqash Agencies — Reliable local cash services</title>
  <meta name="description" content="Digiqash Agencies — fast, secure cash & payments across Kenya, Ghana, Malawi, and Cameroon." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --accent:#06b6d4;
      --muted:#9aa4b2;
      --glass: rgba(255,255,255,0.03);
      --rounded:14px;
      color-scheme: dark;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:Inter,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial;
      background: linear-gradient(180deg,#071226 0%, #071a2a 60%);
      color:#e6eef6;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
    }
/* layout */
    .container{max-width:1100px;margin:32px auto;padding:24px;}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px;}
    .brand{display:flex;align-items:center;gap:12px}
    .logo {
      width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#7c3aed);
      display:flex;align-items:center;justify-content:center;font-weight:800;color:#032;
      box-shadow:0 6px 18px rgba(7,22,37,0.6);
    }
    .brand h1{font-size:18px;margin:0}
    nav{display:flex;gap:12px;align-items:center}
    nav a{color:var(--muted);text-decoration:none;padding:8px 12px;border-radius:10px;font-weight:600}
    nav a:hover{background:var(--glass);color:#fff}
 /* hero */
    .hero{
      display:grid;grid-template-columns:1fr 380px;gap:24px;align-items:center;margin-top:22px;
      background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);
      padding:28px;border-radius:18px;box-shadow:0 6px 30px rgba(2,6,23,0.6);
    }
    .hero h2{font-size:32px;margin:0 0 8px}
    .hero p{color:var(--muted);margin:0 0 18px}
    .cta-row{display:flex;gap:12px;flex-wrap:wrap}
    .btn{
      background:linear-gradient(90deg,var(--accent),#7c3aed);
      color:#012; padding:12px 16px;border:none;border-radius:12px;font-weight:700;
      cursor:pointer;box-shadow:0 8px 30px rgba(6,182,212,0.12);
    }
    .outline{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--muted);padding:10px 14px;border-radius:12px;cursor:pointer}

    /* right card */
    .card{
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:14px;padding:18px;
    }
    .balance{font-size:18px;font-weight:700;margin-bottom:6px}
    .small{font-size:13px;color:var(--muted)}

    /* services */
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:20px}
    .service{
      background:var(--card);border-radius:12px;padding:18px;min-height:120px;box-shadow:0 6px 20px rgba(2,6,23,0.6);
    }
    .service h3{margin:0 0 6px}
    .service p{color:var(--muted);font-size:14px;margin:0}

    /* countries */
    .countries{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-top:20px}
    .country{
      background:linear-gradient(180deg,#071226, #061222);
      border-radius:12px;padding:14px;cursor:pointer;border:1px solid rgba(255,255,255,0.03);
    }
    .country h4{margin:0 0 6px}
    .country p{margin:0;color:var(--muted);font-size:13px}
    /* details panel */
    .details{margin-top:18px;background:linear-gradient(180deg, rgba(255,255,255,0.015), transparent);padding:18px;border-radius:12px}
    .details h3{margin-top:0}
    .features{display:flex;gap:10px;flex-wrap:wrap;margin-top:10px}
    .feature{background:var(--glass);padding:10px 12px;border-radius:10px;font-size:13px;color:var(--muted)}

    /* contact */
    .contact{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:22px}
    .form input, .form textarea{
      width:100%;padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.03);
      background:transparent;color:inherit;margin-bottom:10px;font-size:14px;
    }
    .form textarea{min-height:120px;resize:vertical}
    footer{margin-top:28px;padding:20px 10px;color:var(--muted);text-align:center;font-size:13px}
 /* responsive */
    @media (max-width:920px){
      .hero{grid-template-columns:1fr; padding:18px}
      .grid{grid-template-columns:repeat(2,1fr)}
      .countries{grid-template-columns:repeat(2,1fr)}
      .contact{grid-template-columns:1fr}
    }
    @media (max-width:520px){
      .grid{grid-template-columns:1fr}
      .brand h1{font-size:16px}
      .logo{width:48px;height:48px}
    }
/* tiny helpers */
    .muted{color:var(--muted)}
    .kbd{display:inline-block;background:rgba(255,255,255,0.03);padding:4px 8px;border-radius:6px;font-weight:600}
    .topbar{display:flex;gap:12px;align-items:center}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">Dq</div>
        <div>
          <h1>Digiqash Agencies</h1>
          <div class="muted" style="font-size:13px">Local payments & cash services — Kenya • Ghana • Malawi • Cameroon</div>
        </div>
      </div>

      <nav aria-label="Main navigation">
        <a href="#services">Services</a>
        <a href="#countries">Countries</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero" aria-labelledby="hero-title">
      <div>
        <h2 id="hero-title">Digiqash Agencies — Fast. Secure. Local.</h2>
        <p>We provide trusted cash-in/cash-out, bill payments and agent services across Kenya, Ghana, Malawi and Cameroon. Built for agents, businesses and customers who need quick, reliable access to cash and digital payment rails.</p>

        <div class="cta-row">
          <button class="btn" onclick="scrollToSection('contact')">Become an Agent</button>
          <button class="outline" onclick="scrollToSection('countries')">See Countries</button>
        </div>

        <div style="margin-top:18px" class="muted">
          <strong>Why Digiqash?</strong>
          <div style="margin-top:8px">Secure settlements • Local support • Low fees • Fast onboarding</div>
        </div>
      </div>

      <aside class="card">
        <div class="balance">Agent dashboard (demo)</div>
        <div class="small">Available balance</div>
        <div style="font-size:28px;font-weight:800;margin-top:8px">KES 24,580</div>

        <div style="margin-top:14px" class="small">Recent activity</div>
        <ul style="margin:8px 0 0;padding-left:18px;color:var(--muted);font-size:13px">
          <li>Paid vendor — KES 1,200</li>
          <li>Cash-in — GH₵ 420</li>
          <li>Settlement — XAF 36,400</li>
        </ul>
      </aside>
    </section>

    <section id="services" class="grid" aria-label="Services">
      <div class="service">
        <h3>Agent Cash Services</h3>
        <p>Sign up as an agent to provide cash-in, cash-out, and merchant settlements at your store or kiosk.</p>
      </div>
      <div class="service">
        <h3>Bill & Airtime Payments</h3>
        <p>Top-up airtime, pay utility bills, and offer easy merchant payments for local businesses.</p>
      </div>
      <div class="service">
        <h3>Business Onboarding</h3>
        <p>Quick KYC and setup for small businesses — start accepting payments the same day.</p>
      </div>
    </section>

    <section id="countries" style="margin-top:10px">
      <h3 style="margin:6px 0 12px">Active Countries</h3>
      <div class="countries" role="list">
        <div class="country" role="listitem" onclick="showCountry('kenya')" aria-label="Kenya">
          <h4>Kenya</h4>
          <p>Mobile money integration, fast agent payouts, support in Swahili & English.</p>
        </div>

        <div class="country" role="listitem" onclick="showCountry('ghana')" aria-label="Ghana">
          <h4>Ghana</h4>
          <p>MTN/MoMo & Airtel integrations, merchant settlements and agent liquidity support.</p>
        </div>

        <div class="country" role="listitem" onclick="showCountry('malawi')" aria-label="Malawi">
          <h4>Malawi</h4>
          <p>Local network payouts, vendor settlements and low-fee cash services.</p>
        </div>

        <div class="country" role="listitem" onclick="showCountry('cameroon')" aria-label="Cameroon">
          <h4>Cameroon</h4>
          <p>Multi-currency support (XAF), agent onboarding and trusted local operations.</p>
        </div>
      </div>

      <div id="country-details" class="details" aria-live="polite">
        <h3>Kenya — Overview</h3>
        <p class="muted" id="country-desc">Digiqash supports fast cash-in/cash-out and direct settlements into popular mobile money wallets in Kenya.</p>

        <div class="features" id="country-features">
          <div class="feature">Mobile money integration</div>
          <div class="feature">Agent onboarding in 24–48h</div>
          <div class="feature">POS & USSD options</div>
        </div>
      </div>
    </section>

    <section id="contact" class="contact" aria-labelledby="contact-title">
      <div>
        <h3 id="contact-title">Get in touch / Become an agent</h3>
        <p class="muted">Fill the form below — we'll get back to you with onboarding details and local requirements.</p>

        <form class="form" onsubmit="submitForm(event)">
          <input type="text" id="name" placeholder="Full name" required>
          <input type="email" id="email" placeholder="Email address" required>
          <input type="text" id="country" placeholder="Country (Kenya, Ghana, Malawi, Cameroon)" required>
          <textarea id="message" placeholder="Tell us about your location / shop / services" required></textarea>
          <div style="display:flex;gap:10px">
            <button class="btn" type="submit">Send Request</button>
            <button type="button" class="outline" onclick="mailtoSupport()">Email Support</button>
          </div>
          <div id="form-msg" class="muted" style="margin-top:10px"></div>
        </form>
      </div>

      <aside class="card" style="height:100%">
        <div style="display:flex;align-items:center;justify-content:space-between">
          <div>
            <div class="muted">Head office</div>
            <div style="font-weight:700;margin-top:6px">Nairobi, Kenya</div>
          </div>
          <div style="text-align:right">
            <div class="muted">Support</div>
            <div style="font-weight:700;margin-top:6px">support@digiqash.example</div>
          </div>
        </div>

        <div style="margin-top:14px" class="small">
          <strong>Working hours:</strong><br/>
          Mon — Fri: 08:00 — 18:00 (local)
        </div>

        <div style="margin-top:12px" class="small muted">
          Tip: For faster onboarding include a photo of your ID and business location when we request it.
        </div>
      </aside>
    </section>

    <footer role="contentinfo">
      © <span id="year"></span> Dig iqash Agencies — Serving Kenya • Ghana • Malawi • Cameroon · Built with care.
    </footer>
  </div>

  <script>
    // small helpers
    function scrollToSection(id){
      const el = document.getElementById(id);
      if(el) el.scrollIntoView({behavior:'smooth', block:'start'});
    }

    // Update year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Country data
    const countries = {
      kenya: {
        title:'Kenya — Overview',
        desc:'Digiqash supports fast cash-in/cash-out and direct settlements into popular mobile money wallets in Kenya (M-Pesa, Airtel Money). We provide agent liquidity and local support in Kiswahili and English.',
        features: ['M-Pesa integration','Agent onboarding in 24–48h','POS & USSD options']
      },
      ghana: {
        title:'Ghana — Overview',
        desc:'In Ghana we integrate with MTN MoMo and AirtelTigo for fast transfers and merchant settlements. Local agents receive training and credit lines as eligible.',
        features: ['MTN MoMo & Airtel','Merchant settlement','Local agent support']
      },
      malawi: {
        title:'Malawi — Overview',
        desc:'Digiqash provides agent cash services and vendor payments across Malawi with simplified onboarding and tailored liquidity support.',
        features: ['Local payouts','Low-fee transfers','Vendor payments']
      },
      cameroon: {
        title:'Cameroon — Overview',
        desc:'We support settlements in XAF and have local partners for regulatory and compliance needs. Agents can serve merchant and consumer cash requests.',
        features: ['XAF settlements','Local partners','Agent onboarding']
      }
    };

    function showCountry(key){
      const data = countries[key];
      if(!data) return;
      document.getElementById('country-details').querySelector('h3').textContent = data.title;
      document.getElementById('country-desc').textContent = data.desc;

      const container = document.getElementById('country-features');
      container.innerHTML = '';
      data.features.forEach(f => {
        const d = document.createElement('div');
        d.className = 'feature';
        d.textContent = f;
        container.appendChild(d);
      });
      // scroll into view for users on mobile
      document.getElementById('country-details').scrollIntoView({behavior:'smooth', block:'start'});
    }

    // Basic contact form "submission" (demo)
    function submitForm(e){
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const email = document.getElementById('email').value.trim();
      const country = document.getElementById('country').value.trim();
      const message = document.getElementById('message').value.trim();

      // minimal validation
      if(!name || !email || !country || !message){
        document.getElementById('form-msg').textContent = 'Please fill all fields.';
        return;
      }

      // simulate success (replace with real backend or form provider)
      document.getElementById('form-msg').textContent = 'Thanks — your request has been sent. We will contact you shortly.';
      e.target.reset();
    }

    function mailtoSupport(){
      window.location.href = 'mailto:support@digiqash.example?subject=Agent enquiry&body=Hello%20Digiqash%2C%0A%0AI%20would%20like%20to%20become%20an%20agent%20in%20';
    }

    // Accessibility: allow keyboard activation for country tiles
    document.querySelectorAll('.country').forEach(el=>{
      el.tabIndex = 0;
      el.addEventListener('keydown', (ev)=>{
        if(ev.key === 'Enter' || ev.key === ' ') el.click();
      });
    });
  </script>
</body>
</html>












    
