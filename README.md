<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>DigiQash Agencies</title>

  <!-- Use link for Google font (optional) -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#f6f9fc;
      --primary:#701214;
      --accent:#129815;
      --muted:#6b7280;
      --card:#ffffff;
      --cta:#0456d6;
      --success:#25D366;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      font-family:'Inter', Arial, system-ui, -apple-system, "Segoe UI", sans-serif;
      margin:0;
      background: linear-gradient(180deg,#f7fbff 0%, #f4f7f9 100%);
      color:#111827;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }

    .container{
      max-width:1100px;
      margin:28px auto;
      padding:20px;
    }

    header{
      background: linear-gradient(90deg,var(--primary), #8b1f1f);
      color:#fff;
      padding:18px 20px;
      border-radius:12px;
      box-shadow: 0 8px 30px rgba(16,24,40,0.08);
    }
    header .header-inner{display:flex;align-items:center;gap:12px}
    #branding h1{margin:0;font-size:1.25rem;letter-spacing:0.4px;font-weight:700}
    nav{margin-left:auto}
    nav ul{display:flex;gap:12px;margin:0;padding:0;list-style:none}
    nav a{
      color:rgba(255,255,255,0.95);
      text-decoration:none;
      padding:8px 12px;
      border-radius:8px;
      transition:background .18s, transform .12s;
      font-weight:600;
      font-size:0.95rem;
    }
    nav a:hover{background:rgba(255,255,255,0.06);transform:translateY(-2px)}

    #digiqash-agencies{
      margin-top:18px;
      padding:18px;
      border-radius:12px;
      background:linear-gradient(180deg,#ffffff,#fbfffc);
      box-shadow:0 8px 20px rgba(8,15,24,0.04);
      border:1px solid #eef6f0;
    }
    #digiqash-agencies h2{
      text-transform:capitalize;margin:0 0 8px 0;color:var(--primary);font-size:1.15rem;
    }
    #digiqash-agencies p{margin:0;color:var(--muted);line-height:1.5}

    .controls{display:flex;flex-wrap:wrap;gap:12px;margin-top:18px;align-items:center}
    .selector{display:flex;align-items:center;gap:8px}
    .selector label{font-weight:600;color:var(--muted)}
    select{
      padding:10px 12px;border-radius:10px;border:1px solid #e6e9ee;background:white;min-width:220px;
      box-shadow:0 6px 18px rgba(16,24,40,0.03);
      transition:box-shadow .12s, transform .08s;
    }
    select:focus{outline:none;box-shadow:0 10px 24px rgba(16,24,40,0.06);transform:translateY(-1px)}

    .button{
      background:linear-gradient(90deg,var(--cta), #3b82f6);
      color:white;padding:10px 16px;border:none;border-radius:999px;cursor:pointer;font-weight:700;
      box-shadow:0 10px 30px rgba(3,102,214,0.12);
      transition:transform .12s, box-shadow .12s, opacity .12s;
    }
    .button:hover{transform:translateY(-3px);box-shadow:0 18px 36px rgba(3,102,214,0.16)}

    .register-ghost{
      background:transparent;border:1px dashed rgba(0,0,0,0.06);padding:8px 12px;border-radius:10px;color:var(--muted);
    }

    /* Summary injection area */
    #summaryWrapper{
      margin-top:16px;
    }
    .summary-card{
      background:linear-gradient(180deg,#f8fffb,#ffffff);
      border-radius:12px;padding:16px;border:1px solid #e9f6ed;
      box-shadow:0 8px 30px rgba(14,34,8,0.04);
      color:#0f172a;
    }
    .summary-card h2{margin:0 0 8px 0;color:var(--primary)}
    .whatsapp-button{
      display:inline-block;margin-top:10px;background:var(--success);color:#fff;padding:8px 12px;border-radius:8px;text-decoration:none;font-weight:700;
      box-shadow:0 8px 20px rgba(37,211,102,0.12);
    }

    /* Chat area */
    .chat-area{display:flex;gap:12px;align-items:flex-end;flex-wrap:wrap;margin-top:18px}
    #chatbox{
      background:linear-gradient(180deg,#fffdf2,#fff7d6);
      width:340px;height:240px;border-radius:12px;padding:12px;border:1px solid #f3e6b8;overflow-y:auto;
      box-shadow:0 12px 30px rgba(20,30,60,0.06);
    }
    #chatbox .msg{margin-bottom:8px;padding:8px 10px;border-radius:10px;max-width:80%}
    #chatbox .user{background:rgba(15,23,42,0.06);align-self:flex-start}
    #chatbox .bot{background:rgba(37,211,102,0.12);align-self:flex-end}
    .chat-input{display:flex;gap:8px;align-items:center}
    #inputbox{flex:1;min-width:140px;padding:10px;border-radius:10px;border:1px solid #e6e9ee}

    /* Responsive */
    @media(max-width:900px){
      .container{padding:16px}
      #chatbox{width:100%}
      nav ul{display:none}
    }
  </style>
</head>
<body>
  <header>
    <div class="container header-inner">
      <div id="branding">
        <h1>DigiQash Agencies</h1>
      </div>
      <nav>
        <ul>
          <li><a href="#" aria-label="Home">Home</a></li>
          <li><a href="#" aria-label="About">About</a></li>
          <li><a href="#" aria-label="Services">Services</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <section id="digiqash-agencies">
      <h2>unlock your financial freedom with digiqash agencies</h2>
      <p>Digiqash agencies is an online platform that connects students, freelancers, stay-at-home parents, jobless and youths to smart earning so that you can start making money using your smartphone.</p>
    </section>

    <div class="controls" aria-hidden="false">
      <div class="selector">
        <label for="country">Select Country:</label>
        <select id="country" aria-label="Select Country">
          <option value="">Select a Country</option>
          <option value="kenya">Kenya</option>
          <option value="cameroon">Cameroon</option>
          <option value="ghana">Ghana</option>
          <option value="uganda">Uganda</option>
          <option value="malawi">Malawi</option>
        </select>
      </div>

      <button class="button" id="registrationButton" aria-label="Register">Register Here</button>
      <button class="register-ghost" id="moreInfoBtn">More Info</button>
    </div>

    <!-- Summary block: we'll inject the rich HTML here -->
    <div id="summaryWrapper" style="display:none;"></div>

    <!-- Chat area -->
    <div class="chat-area">
      <div id="chatbox" role="log" aria-live="polite"></div>

      <div style="min-width:220px;flex:1;max-width:420px">
        <div class="chat-input">
          <input id="inputbox" type="text" placeholder="Type a message..." aria-label="Message input" />
          <button class="button" id="sendBtn" aria-label="Send message">Send</button>
        </div>
        <p style="margin:8px 0 0 0;color:var(--muted);font-size:0.9rem">Chatbot: try "hello" or "how are you"</p>
      </div>
    </div>
  </main>

  <script>
    // Chat functionality
    const chatbox = document.getElementById('chatbox');
    const inputbox = document.getElementById('inputbox');
    const sendBtn = document.getElementById('sendBtn');

    function appendMessage(text, cls){
      const el = document.createElement('div');
      el.className = 'msg ' + cls;
      el.textContent = text;
      chatbox.appendChild(el);
      chatbox.scrollTop = chatbox.scrollHeight;
    }

    function getBotResponse(userMessage){
      const m = userMessage.trim().toLowerCase();
      if(!m) return "Please type something.";
      if(m.includes("hello") || m.includes("hi")) return "Hello there 🤗 — how can I help you today?";
      if(m.includes("how are you")) return "I'm doing well, thanks for asking!";
      if(m.includes("register") || m.includes("join")) return "Click the 'Register Here' button to start registration (WhatsApp link).";
      return "I'm not sure how to reply. Please reach out on the WhatsApp button or try a different question.";
    }

    function sendMessage(){
      const text = inputbox.value.trim();
      if(!text) return;
      appendMessage("You: " + text, 'user');
      inputbox.value = '';
      setTimeout(()=>{
        appendMessage("Bot: " + getBotResponse(text), 'bot');
      }, 300);
    }

    sendBtn.addEventListener('click', sendMessage);
    inputbox.addEventListener('keydown', function(e){
      if(e.key === 'Enter') sendMessage();
    });

    // Country summaries and registration
    const countrySelector = document.getElementById('country');
    const summaryWrapper = document.getElementById('summaryWrapper');
    const registrationButton = document.getElementById('registrationButton');
    const moreInfoBtn = document.getElementById('moreInfoBtn');

    // Default registration link (can be customized or made country-specific)
    const registrationLink = 'https://wa.me/254117410138?text=Hello%20am%20interested%20in%20Digiqashagencies';

    registrationButton.addEventListener('click', function(){
      window.open(registrationLink, '_blank');
    });

    moreInfoBtn.addEventListener('click', function(){
      if(summaryWrapper.style.display === 'none'){
        summaryWrapper.style.display = 'block';
        if(!summaryWrapper.innerHTML.trim()) summaryWrapper.innerHTML = '<div class="summary-card"><h2>How it works</h2><p>Select a country to view specific earning details. Click register to connect on WhatsApp and proceed with activation.</p></div>';
      } else {
        summaryWrapper.style.display = 'none';
      }
    });

    const countrySummaries = {
      kenya: `<div class="summary-card">
                <h2>DigiQash Agencies Summary - Kenya</h2>
                <p>To be officially launched on <strong>1st November</strong> at 11:00 am.</p>
                <p>Once you register your account, you can earn over Ksh 2,000 daily by completing simple tasks from your account.</p>
                <h3>Ways to Earn:</h3>
                <ul>
                  <li>Welcome bonus of KSH100 instantly credited upon activation.</li>
                  <li>Answering easy survey questions.</li>
                  <li>Watch TikTok and YouTube videos, create and share memes, write blogs, watch Reels.</li>
                  <li>Invite friends and earn up to KSH 1500 daily across 3 levels.</li>
                </ul>
                <p>To join, register and activate your account with <strong>KSH 500 (one-time)</strong>.</p>
                <a class="whatsapp-button" href="https://wa.me/254117410138?text=Hello%20am%20interested%20in%20Digiqashagencies" target="_blank" rel="noopener">WhatsApp us</a>
             </div>`,

      cameroon: `<div class="summary-card">
                  <h2>DigiQash Agencies Summary - Cameroon</h2>
                  <p>To be officially launched on <strong>1st November</strong> at 9:00 am.</p>
                  <p>Once you register your account, you can earn over XAF 11,000 daily by completing simple tasks.</p>
                  <p>To join, register and activate your account with <strong>XAF 2900 (one-time)</strong>.</p>
                  <a class="whatsapp-button" href="https://wa.me/254117410138" target="_blank" rel="noopener">WhatsApp us</a>
                </div>`,

      ghana: `<div class="summary-card">
                <h2>DigiQash Agencies Summary - Ghana</h2>
                <p>To be officially launched on <strong>1st November</strong> at 8:00 am.</p>
                <p>Earn over GHS 250 daily doing simple tasks. One-time activation fee: <strong>GHS 70</strong>.</p>
                <a class="whatsapp-button" href="https://wa.me/233000000000" target="_blank" rel="noopener">WhatsApp us</a>
              </div>`,

      uganda: `<div class="summary-card">
                 <h2>DigiQash Agencies Summary - Uganda</h2>
                 <p>To be officially launched on <strong>1st November</strong> at 11:00 am.</p>
                 <p>Earn over UGX 40,000 daily. One-time activation fee: <strong>UGX 18,500</strong>.</p>
                 <a class="whatsapp-button" href="https://wa.me/256000000000" target="_blank" rel="noopener">WhatsApp us</a>
               </div>`,

      malawi: `<div class="summary-card">
                 <h2>DigiQash Agencies Summary - Malawi</h2>
                 <p>To be officially launched on <strong>1st November</strong> at 10:00 am.</p>
                 <p>Earn over MWK 40,000 daily. One-time activation fee: <strong>MWK 15,000</strong>.</p>
                 <a class="whatsapp-button" href="https://wa.me/265000000000" target="_blank" rel="noopener">WhatsApp us</a>
               </div>`
    };

    countrySelector.addEventListener('change', function(){
      const selected = countrySelector.value;
      if(selected && countrySummaries[selected]){
        summaryWrapper.innerHTML = countrySummaries[selected];
        summaryWrapper.style.display = 'block';
      } else {
        summaryWrapper.style.display = 'none';
        summaryWrapper.innerHTML = '';
      }
    });
  </script>
</body>
</html>
