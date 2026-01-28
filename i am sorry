<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>I'm Sorry — My Heartfelt Apology</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&family=Great+Vibes&display=swap" rel="stylesheet">
  <style>
    *{box-sizing:border-box;margin:0;padding:0}
    body{
      font-family:Poppins,system-ui,Arial;
      background:linear-gradient(120deg,#ffe0e9,#fff4e6);
      color:#333;
      min-height:100vh;
      display:flex;
      flex-direction:column;
      align-items:center;
      justify-content:center;
      padding:20px;
      position:relative;
      overflow-x:hidden;
    }
    header{
      width:100%;
      text-align:center;
      padding:10px;
      margin-bottom:20px;
    }
    header h1{
      font-family:'Great Vibes',cursive;
      font-size:48px;
      color:#ff5470;
      margin-bottom:10px;
      text-shadow:0 0 10px rgba(255,84,112,0.5);
      animation:glow 2s ease-in-out infinite alternate;
    }
    @keyframes glow{
      from{text-shadow:0 0 10px rgba(255,84,112,0.5);}
      to{text-shadow:0 0 20px rgba(255,84,112,1);}
    }
    header p{font-size:16px;color:#555;padding:0 10px;}
    nav{
      display:flex;
      flex-wrap:wrap;
      gap:10px;
      justify-content:center;
      margin-bottom:20px;
    }
    nav button{
      padding:10px 18px;
      border:none;
      border-radius:8px;
      background:#ff5470;
      color:#fff;
      font-weight:600;
      cursor:pointer;
      transition:transform .2s,background .3s;
    }
    nav button:hover{
      background:#ff7f9d;
      transform:scale(1.05);
    }
    section{
      background:white;
      padding:20px;
      border-radius:16px;
      box-shadow:0 8px 20px rgba(0,0,0,0.1);
      max-width:800px;
      width:100%;
      display:none;
      animation:fade .5s ease-in-out;
    }
    section.active{display:block}
    .card{display:flex;flex-direction:column;align-items:center;text-align:center}
    .heart{font-size:72px;color:#ff5470;margin-bottom:10px}
    .message-box{width:100%;margin-top:10px}
    .message-box label{display:block;margin-bottom:4px;font-weight:600;color:#444}
    .message-box input,.message-box textarea{
      width:100%;
      padding:10px;
      border:1px solid #ddd;
      border-radius:8px;
      font-size:15px;
      margin-bottom:10px;
    }
    .message-box textarea{min-height:100px}
    .btn-row{
      display:flex;
      flex-wrap:wrap;
      gap:10px;
      justify-content:center;
      margin-top:10px;
    }
    .btn{
      padding:10px 16px;
      border:none;
      border-radius:10px;
      font-weight:600;
      cursor:pointer;
    }
    .primary{background:#ff5470;color:white}
    .secondary{background:#fff;border:1px solid #ff5470;color:#ff5470}
    .preview-card{
      background:linear-gradient(135deg,#fff7f8,#fff);
      padding:20px;
      border-radius:14px;
      box-shadow:inset 0 0 8px rgba(255,84,112,0.1);
      margin-top:20px;
      text-align:left;
    }
    .preview-card h2{
      font-family:'Great Vibes',cursive;
      font-size:32px;
      color:#ff5470;
      margin-bottom:10px;
      text-align:center;
    }
    .preview-card p{color:#333;margin-bottom:10px;white-space:pre-line;}
    footer{margin-top:20px;font-size:13px;color:#888;text-align:center}
    @keyframes fade{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)}}

    /* Floating Heart Background */
    .heart-bg{
      position:fixed;
      top:0;
      left:0;
      width:100%;
      height:100%;
      pointer-events:none;
      overflow:hidden;
      z-index:-1;
    }
    .heart-bg span{
      position:absolute;
      display:block;
      width:20px;
      height:20px;
      background:rgba(255,84,112,0.3);
      animation:float 8s infinite ease-in-out;
      clip-path:polygon(50% 0%,61% 12%,75% 20%,80% 35%,74% 52%,50% 100%,26% 52%,20% 35%,25% 20%,39% 12%);
    }
    @keyframes float{
      0%{transform:translateY(100vh) scale(0.6);opacity:0.2;}
      50%{opacity:1;}
      100%{transform:translateY(-10vh) scale(1);opacity:0;}
    }

    /* Mobile responsiveness */
    @media(max-width:600px){
      body{padding:15px;}
      header h1{font-size:34px;}
      nav button{flex:1 1 45%;font-size:14px;padding:8px 10px;}
      .heart{font-size:60px;}
      section{padding:15px;}
      .preview-card{font-size:14px;}
      textarea{font-size:14px;}
      .btn{font-size:14px;padding:8px 12px;}
    }
  </style>
</head>
<body>
  <div class="heart-bg"></div>

  <header>
    <h1>I'm Sorry ❤️</h1>
    <p>I made a mistake, and this little website is my way to say sorry and show how much you mean to me.</p>
  </header>

  <nav>
    <button data-page="home">Home</button>
    <button data-page="card">Sorry Card</button>
    <button data-page="questions">Q&A</button>
    <button data-page="promise">My Promises</button>
  </nav>

  <section id="home" class="active">
    <div class="card">
      <div class="heart">💖</div>
      <p>Welcome, my love. This space is just for you — a place where I express how sorry I am and how much I care. Please go through each page when you’re ready.</p>
    </div>
  </section>

  <section id="card">
    <div class="card">
      <div class="heart">💌</div>
      <div class="message-box">
        <label for="toName">To Jyoti</label>
        <input id="toName" value="My Sugarboo" />
        <label for="message">Message</label>
        <textarea id="message">I’m truly sorry for what I said. When I told you I’d leave you for someone else, I thought I was just joking — but I realize now how hurtful those words were. I never meant to make you feel insecure, unwanted, or unloved. You mean far too much to me for that.

You are the person who fills my days with laughter, warmth, and purpose. The idea of ever losing you, even in a joke, feels unbearable. I should have known better than to play with something so serious — your heart and our love are not things to take lightly.

Please know that I have no intention, now or ever, of leaving you. You are my choice, my peace, and my favorite part of life. I feel terrible for making you doubt that, even for a moment.

I promise to be more thoughtful with my words and actions. You deserve someone who always makes you feel safe, loved, and cherished — and I want to be that person for you.

I hope you can forgive me, not because I deserve it, but because I can’t stand the thought of you being hurt because of me. I love you, and I’ll spend every day proving that to you.</textarea>
        <label for="fromName">From Harish</label>
        <input id="fromName" value="Your Honey" />
      </div>
      <div class="btn-row">
        <button class="btn primary" id="showCard">Show Card</button>
        <button class="btn secondary" id="downloadCard">Download</button>
      </div>
      <div id="preview" class="preview-card" style="display:none">
        <h2 id="pTo">To: My Jyoti</h2>
        <p id="pMsg">I know I hurt you, and I regret it deeply. I miss your smile and laughter. Please forgive me.</p>
        <p id="pFrom">— Yours Harish</p>
      </div>
    </div>
  </section>

  <section id="questions">
    <div class="card">
      <div class="heart">💭</div>
      <p>Let me answer a few things you might be wondering...</p>
      <div class="btn-row">
        <button class="btn secondary" onclick="showAnswer('Why did I hurt you?','I never meant to, but I made a mistake. I was careless and I promise to learn from it.')">Why did you hurt me?</button>
        <button class="btn secondary" onclick="showAnswer('Do you really love me?','Yes, more than words can say. You mean everything to me.')">Do you really love me?</button>
        <button class="btn secondary" onclick="showAnswer('Will it happen again?','No, because I now understand how precious you are and how fragile feelings can be.')">Will it happen again?</button>
        <button class="btn secondary" onclick="showAnswer('What makes you miss me most?','Your warmth, your smile, and the way everything feels right when you are near.')">What do you miss most?</button>
      </div>
      <div id="answerBox" class="preview-card" style="display:none;margin-top:20px"></div>
    </div>
  </section>

  <section id="promise">
    <div class="card">
      <div class="heart">🤝</div>
      <h3>My Promises to You</h3>
      <ul style="text-align:left;margin-top:10px;line-height:1.6">
        I promise, love, I’ll never stray, <br>
        You’re my dawn, my brightest day.<br>
        The joke I made, a foolish part,<br>
        But truth still lives inside my heart.<br><br>

        I promise you through joy and pain,<br>
        My love will flow like endless rain.<br>
        I’ll stand by you when skies turn grey,<br>
        And chase your tears and fears away.<br><br>

        I promise I will hold you near,<br>
        Through every doubt, through every fear.<br>
        Your smile’s my sun, your voice—my song,<br>
        With you, my heart will always belong.<br><br>

        I’ll love you more with every year,<br>
        Through every laugh and every tear.<br>
        No word again will make you cry,<br>
        I’ll lift you up, I’ll never say goodbye.<br><br>

        For you’re my peace, my life, my art,<br>
        My forever home, my beating heart.<br>
        This is my vow, so pure and true,<br>
        My every promise begins with you. 💞<br><br>
      </ul>

      <div style="margin-top:20px;">
        <button onclick="forgiveMe()" style="padding:12px 20px;background:#ff5470;color:#fff;border:none;border-radius:12px;font-size:16px;cursor:pointer;">💞 Forgive Me?</button>
      </div>
    </div>
  </section>

  <footer>
    Made with love ❤️ just for you.
  </footer>

  <!-- Background Music -->
  <audio id="bg-music" loop>
    <source src="spanish-guitar-beauty-melody-289257.mp3" type="audio/mpeg">
  </audio>
  <button onclick="toggleMusic()" style="position:fixed;bottom:20px;right:20px;background:#ff5470;color:#fff;border:none;padding:10px 15px;border-radius:50%;cursor:pointer;">🎵</button>

  <script>
    const sections=document.querySelectorAll('section');
    const navBtns=document.querySelectorAll('nav button');
    navBtns.forEach(btn=>{
      btn.addEventListener('click',()=>{
        sections.forEach(s=>s.classList.remove('active'));
        document.getElementById(btn.dataset.page).classList.add('active');
        window.scrollTo({top:0,behavior:'smooth'});
      });
    });

    const toName=document.getElementById('toName');
    const fromName=document.getElementById('fromName');
    const message=document.getElementById('message');
    const showCard=document.getElementById('showCard');
    const pTo=document.getElementById('pTo');
    const pMsg=document.getElementById('pMsg');
    const pFrom=document.getElementById('pFrom');
    const preview=document.getElementById('preview');

    showCard.onclick=()=>{
      pTo.textContent='To: '+toName.value;
      pMsg.textContent=message.value;
      pFrom.textContent='— '+fromName.value;
      preview.style.display='block';
    };

    document.getElementById('downloadCard').onclick=()=>{
      const html='<!doctype html>'+document.documentElement.outerHTML;
      const blob=new Blob([html],{type:'text/html'});
      const url=URL.createObjectURL(blob);
      const a=document.createElement('a');
      a.href=url;
      a.download='sorry-card.html';
      document.body.appendChild(a);
      a.click();
      a.remove();
      URL.revokeObjectURL(url);
    };

    function showAnswer(question,answer){
      const box=document.getElementById('answerBox');
      box.style.display='block';
      box.innerHTML=`<h3>${question}</h3><p>${answer}</p>`;
    }

    // Floating hearts
    const bg=document.querySelector('.heart-bg');
    for(let i=0;i<25;i++){
      const h=document.createElement('span');
      h.style.left=Math.random()*100+'%';
      h.style.animationDelay=(Math.random()*8)+'s';
      bg.appendChild(h);
    }

    // Background music toggle
    const music=document.getElementById('bgMusic');
    function toggleMusic(){
      if(music.paused){music.play();}
      else{music.pause();}
    }

    // Forgive Me alert
    function forgiveMe(){
      alert('Thank you, my love ❤️ You’ve just made my world bright again.');
    }
  </script>
</body>
</html>
