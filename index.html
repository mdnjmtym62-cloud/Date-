<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dis Oui — Invitation interactive</title>
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;0,700;1,400&family=Plus+Jakarta+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
  
  <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>

  <style>
    :root {
      --bg-color: #f5ede4;
      --card-bg: #fcfaf7;
      --primary: #5c1428;
      --primary-hover: #450e1d;
      --text-dark: #2b2325;
      --text-muted: #8c7f7d;
      --border: #e6dacd;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-color: var(--bg-color);
      font-family: 'Plus Jakarta Sans', sans-serif;
      color: var(--text-dark);
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 20px;
    }

    .container {
      width: 100%;
      max-width: 440px;
      margin: 0 auto;
    }

    /* CARTE ET TYPOGRAPHIE */
    .card {
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 40px 28px;
      box-shadow: 0 10px 30px rgba(92, 20, 40, 0.04);
      text-align: center;
      position: relative;
    }

    .tagline {
      font-size: 10px;
      text-transform: uppercase;
      letter-spacing: 2px;
      color: var(--text-muted);
      margin-bottom: 14px;
      font-weight: 600;
    }

    h1.title {
      font-family: 'Cormorant Garamond', serif;
      font-size: 32px;
      line-height: 1.25;
      color: var(--primary);
      margin-bottom: 8px;
      font-weight: 600;
    }

    p.subtitle {
      font-family: 'Cormorant Garamond', serif;
      font-size: 15px;
      color: var(--text-muted);
      font-style: italic;
      margin-bottom: 24px;
    }

    /* ENVELOPPE */
    .envelope-wrapper {
      cursor: pointer;
      padding: 30px 0 10px 0;
    }
    .envelope {
      width: 180px;
      height: 120px;
      background: #ebdccb;
      margin: 0 auto 20px auto;
      border-radius: 6px;
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
      box-shadow: 0 8px 20px rgba(0,0,0,0.06);
      border: 1px solid #dccbb7;
      transition: transform 0.2s;
    }
    .envelope:hover {
      transform: translateY(-3px);
    }
    .seal {
      width: 34px;
      height: 34px;
      background: var(--primary);
      border-radius: 50%;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 14px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }

    /* BOUTONS ET INTERACTIONS */
    .btn-group {
      display: flex;
      justify-content: center;
      gap: 12px;
      position: relative;
      min-height: 60px;
      align-items: center;
      margin-top: 15px;
    }

    .btn-yes {
      background-color: var(--primary);
      color: #fff;
      border: none;
      padding: 12px 36px;
      font-size: 14px;
      border-radius: 6px;
      cursor: pointer;
      font-weight: 500;
      transition: background 0.2s;
    }
    .btn-yes:hover {
      background-color: var(--primary-hover);
    }

    .btn-no {
      background-color: transparent;
      color: var(--text-muted);
      border: 1px solid var(--border);
      padding: 12px 28px;
      font-size: 14px;
      border-radius: 6px;
      cursor: pointer;
      position: absolute;
      transition: all 0.15s ease-out;
    }

    .funny-text {
      font-family: 'Cormorant Garamond', serif;
      font-size: 14px;
      color: var(--text-muted);
      font-style: italic;
      margin-top: 15px;
      min-height: 20px;
    }

    /* FORMULAIRE & RECAPITULATIF */
    .form-control {
      width: 100%;
      padding: 12px 14px;
      border: 1px solid var(--border);
      border-radius: 6px;
      font-family: inherit;
      font-size: 13.5px;
      background: #fff;
      color: var(--text-dark);
      outline: none;
      margin-bottom: 12px;
    }
    .form-control:focus {
      border-color: var(--primary);
    }

    .plan-box {
      background: #f7f2eb;
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 20px;
      margin: 20px 0;
      text-align: center;
    }
    .plan-title {
      font-family: 'Cormorant Garamond', serif;
      font-size: 22px;
      color: var(--primary);
      font-weight: 700;
      margin-bottom: 4px;
    }
    .plan-sub {
      font-size: 13px;
      color: var(--text-muted);
      margin-bottom: 12px;
    }
    .plan-badge {
      display: inline-block;
      border: 1px solid var(--border);
      padding: 4px 12px;
      border-radius: 4px;
      font-size: 11px;
      letter-spacing: 1.5px;
      text-transform: uppercase;
      color: var(--text-dark);
      background: #fff;
    }

    .btn-full {
      width: 100%;
      background-color: var(--primary);
      color: white;
      border: none;
      padding: 14px;
      font-size: 12px;
      letter-spacing: 1.5px;
      text-transform: uppercase;
      font-weight: 600;
      border-radius: 6px;
      cursor: pointer;
      margin-top: 10px;
    }
    .btn-full:hover {
      background-color: var(--primary-hover);
    }

    /* GESTION DES VUES */
    .view-section {
      display: none;
    }
    .view-section.active {
      display: block;
      animation: fadeIn 0.3s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(6px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <div class="container">

    <div id="envelope-view" class="view-section card active">
      <div class="envelope-wrapper" onclick="openEnvelope()">
        <div class="envelope">
          <div class="seal">♥</div>
        </div>
        <div class="tagline">TOUCHE LA LETTRE</div>
      </div>
    </div>

    <div id="question-view" class="view-section card">
      <div class="tagline" id="recipientTag">POUR TOI, PRUNELLE ❤️</div>
      <h1 class="title">Ça te dit un date avec moi ?</h1>
      <p class="subtitle">(dire non ne sert à rien, mais tu peux essayer)</p>

      <div class="btn-group" id="btnContainer">
        <button class="btn-yes" onclick="clickYes()">Oui</button>
        <button class="btn-no" id="noBtn" onmouseover="dodgeNoButton()" onclick="dodgeNoButton()">Non</button>
      </div>

      <div class="funny-text" id="funnyText"></div>
    </div>

    <div id="plan-view" class="view-section card">
      <div class="tagline">PARFAIT</div>
      <h1 class="title">Voilà le plan</h1>

      <div class="plan-box">
        <div class="plan-title" id="displayActivity">Manger</div>
        <div class="plan-sub" id="displayPlace">Yopougon académie</div>
        <div class="plan-badge" id="displayDateTime">MARDI 1 SEPTEMBRE — 11:00</div>
      </div>

      <div style="text-align: left; margin-bottom: 15px;">
        <label style="font-size: 10px; letter-spacing: 1.5px; text-transform: uppercase; color: var(--text-muted); font-weight: 600; display: block; margin-bottom: 6px;">
          UN MOT POUR MOI (FACULTATIF)
        </label>
        <input type="text" id="replyNote" class="form-control" placeholder="...">
      </div>

      <button class="btn-full" onclick="confirmFinal()">CONFIRMER</button>
    </div>

    <div id="final-view" class="view-section card">
      <div style="font-size: 28px; color: var(--primary); margin-bottom: 8px;">♥</div>
      <div class="tagline">C'EST NOTÉ</div>
      <h1 class="title">C'est un rendez-vous !</h1>
      <p class="subtitle" style="margin-top: 8px;">Ton message a été transmis avec succès.</p>
    </div>

  </div>

  <script>
    // Phrasés identiques à la vidéo de démonstration
    const funnyMessages = [
      "Tu es sûr·e...",
      "Le bouton est fatigué, laisse-le tranquille.",
      "Il s'enfuit. Comme tes excuses.",
      "Sérieusement, clique sur Oui !",
      "Ça ne sert à rien de dire non..."
    ];
    let msgIndex = 0;

    let inviteData = {
      to: "PRUNELLE",
      activity: "Manger",
      place: "Yopougon académie",
      date: "MARDI 1 SEPTEMBRE",
      time: "11:00",
      email: ""
    };

    window.onload = function() {
      const params = new URLSearchParams(window.location.search);
      if (params.has('to')) {
        inviteData.to = params.get('to');
        inviteData.activity = params.get('act') || inviteData.activity;
        inviteData.place = params.get('place') || inviteData.place;
        inviteData.date = params.get('date') || inviteData.date;
        inviteData.time = params.get('time') || inviteData.time;
        inviteData.email = params.get('email') || '';
      }
      
      document.getElementById('recipientTag').innerText = `POUR TOI, ${inviteData.to.toUpperCase()} ❤️`;
      document.getElementById('displayActivity').innerText = inviteData.activity;
      document.getElementById('displayPlace').innerText = inviteData.place;
      document.getElementById('displayDateTime').innerText = `${inviteData.date.toUpperCase()} — ${inviteData.time}`;
    };

    function switchView(viewId) {
      document.querySelectorAll('.view-section').forEach(el => el.classList.remove('active'));
      document.getElementById(viewId).classList.add('active');
    }

    function openEnvelope() {
      switchView('question-view');
    }

    function dodgeNoButton() {
      const btn = document.getElementById('noBtn');
      const container = document.getElementById('btnContainer');

      const maxMoveX = container.clientWidth / 2 - 35;
      const randomX = (Math.random() * maxMoveX * 2) - maxMoveX;
      const randomY = (Math.random() * 50) - 25;

      btn.style.transform = `translate(${randomX}px, ${randomY}px)`;
      document.getElementById('funnyText').innerText = funnyMessages[msgIndex % funnyMessages.length];
      msgIndex++;
    }

    function clickYes() {
      confetti({
        particleCount: 70,
        spread: 60,
        origin: { y: 0.6 },
        colors: ['#5c1428', '#ebdccb', '#ffffff']
      });
      switchView('plan-view');
    }

    function confirmFinal() {
      confetti({
        particleCount: 100,
        spread: 80,
        origin: { y: 0.6 },
        colors: ['#5c1428', '#ebdccb', '#ffffff']
      });
      
      const userReply = document.getElementById('replyNote').value.trim();
      
      if (inviteData.email) {
        fetch(`https://formsubmit.co/ajax/${inviteData.email}`, {
          method: "POST",
          headers: { 'Content-Type': 'application/json' },
          body: JSON.stringify({
            Sujet: `🎉 ${inviteData.to} a accepté ton invitation !`,
            MotRecu: userReply || "Aucun mot rédigé."
          })
        }).catch(err => console.log(err));
      }

      switchView('final-view');
    }
  </script>
</body>
</html>
