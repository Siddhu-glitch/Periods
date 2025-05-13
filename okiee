<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Feel Better, Lovely</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom right, #ffdde1, #ffe6f7);
      color: #4e2a3a;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
      min-height: 100vh;
      overflow-x: hidden;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5em;
      animation: fadeIn 2s ease-in-out;
    }

    p {
      font-size: 1.1rem;
      text-align: center;
      margin-bottom: 1.5em;
      animation: fadeIn 3s ease-in-out;
    }

    .button-group {
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
      justify-content: center;
      margin-bottom: 2em;
    }

    button {
      padding: 12px 20px;
      font-size: 1rem;
      border: none;
      border-radius: 25px;
      background-color: #ff8fab;
      color: white;
      cursor: pointer;
      transition: background 0.3s;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    button:hover {
      background-color: #ff5d8f;
    }

    .popup {
      margin-top: 1em;
      font-weight: bold;
      font-size: 1.2rem;
      background: #fff0f6;
      border-radius: 20px;
      padding: 1rem 1.5rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      display: none;
    }

    .todo-box {
      background: #fff1f8;
      border-radius: 20px;
      padding: 1.5rem;
      margin-top: 1rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      max-width: 400px;
      width: 100%;
    }

    .todo-box h3 {
      margin-bottom: 0.8rem;
    }

    ul {
      list-style: none;
      padding-left: 0;
      margin: 0;
    }

    li {
      margin-bottom: 0.5rem;
    }

    .footer {
      margin-top: 2rem;
      font-size: 0.9rem;
      opacity: 0.7;
      text-align: center;
    }

    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <h1>Hey You 🌸</h1>
  <p>You’re allowed to slow down. This is your time to rest, breathe, and let the world wait a little.</p>

  <div class="button-group">
    <button onclick="sendHug()">💗 Send Hug</button>
    <button onclick="showQuote()">🕊️ Comfort Quote</button>
  </div>

  <div id="popup" class="popup"></div>

  <div class="todo-box">
    <h3>To-Do ✅</h3>
    <ul>
      <li>💤 Take a nap without guilt</li>
      <li>☕ Sip something warm</li>
      <li>🎧 Listen to calming music</li>
      <li>🛁 Hot shower or bath</li>
      <li>💌 Read something soft & slow</li>
    </ul>

    <h3 style="margin-top:1.5em;">Not-To-Do ❌</h3>
    <ul>
      <li>🚫 Overthink</li>
      <li>🚫 Force productivity</li>
      <li>🚫 Feel guilty for resting</li>
      <li>🚫 Say “I’m being lazy”</li>
      <li>🚫 Forget you're amazing</li>
    </ul>
  </div>

  <div class="footer">Just here, reminding you how special you are 🌷</div>

  <script>
    const quotes = [
      "You’re not alone in this — even your hormones are rooting for you.",
      "This too shall pass, but until then… cozy up.",
      "You’re strong. Like... 'bleeding and still functioning' strong.",
      "Breathe. You are more than enough.",
      "Being soft is powerful too."
    ];

    function sendHug() {
      const popup = document.getElementById('popup');
      popup.style.display = 'block';
      popup.textContent = "🤗 Sending you the warmest hug ever. Wrapped in love and softness.";
    }

    function showQuote() {
      const random = quotes[Math.floor(Math.random() * quotes.length)];
      const popup = document.getElementById('popup');
      popup.style.display = 'block';
      popup.textContent = "✨ " + random;
    }
  </script>

</body>
</html>
