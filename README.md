
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SalmmonVR</title>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Rubik:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* Base Setup */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: linear-gradient(to bottom right, #ff5ca2, #00c3ff);
      font-family: 'Rubik', sans-serif;
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
      min-height: 100vh;
    }

    /* Header */
    header {
      text-align: center;
      margin-bottom: 30px;
      animation: fadeIn 1.2s ease-in-out;
    }

    header h1 {
      font-family: 'Pacifico', cursive;
      font-size: 2.5rem;
      background: linear-gradient(90deg, #fff0f5, #ccf5ff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-shadow: 2px 2px #00000030;
    }

    .pfp {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      border: 4px solid #fff;
      margin-top: 15px;
      transition: transform 0.3s ease;
    }

    .pfp:hover {
      transform: scale(1.1) rotate(3deg);
    }

    /* Card Sections */
    .section {
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(8px);
      border: 1px solid rgba(255, 255, 255, 0.2);
      border-radius: 20px;
      padding: 20px 25px;
      width: 90%;
      max-width: 500px;
      margin: 15px 0;
      box-shadow: 0 0 20px #00000020;
      animation: slideUp 1.5s ease-in-out;
    }

    h2 {
      font-size: 1.4rem;
      margin-bottom: 10px;
      border-bottom: 2px solid rgba(255, 255, 255, 0.3);
      padding-bottom: 6px;
      font-weight: bold;
    }

    p, ul {
      font-size: 1rem;
      line-height: 1.6;
    }

    ul {
      list-style: square inside;
    }

    li {
      margin: 6px 0;
      transition: transform 0.2s ease;
    }

    li:hover {
      transform: translateX(5px);
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.95); }
      to { opacity: 1; transform: scale(1); }
    }

    @keyframes slideUp {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Footer */
    footer {
      margin-top: auto;
      font-size: 0.9rem;
      color: #ffffff90;
      padding: 15px;
    }
  </style>
</head>
<body>

  <header>
    <h1>SalmmonVR</h1>
    <img class="pfp" src="PFP1.png" alt="SalmmonVR PFP" />
  </header>

  <div class="section">
    <h2>About Me 😈</h2>
    <p>
      Yo! I'm 14, single (😔), and people say I’m bipolar…? 😮‍💨<br>
      I’m OBSESSED with cats 🐈 and summer 🌞<br>
      I make Discord bots, games, and vibe hard in VR.<br>
      I don’t add randoms — just DM me if you're cool 😎
    </p>
  </div>

  <div class="section">
    <h2>Cool People (In order)</h2>
    <ul>
      <li>Buzz</li>
      <li>Slamz</li>
      <li>🍁 maple 🍁</li>
      <li>Hayden</li>
      <li>None…</li>
      <li>Still none 😭</li>
    </ul>
  </div>

  <footer>
    Made by SalmmonVR
  </footer>

</body>
</html>
