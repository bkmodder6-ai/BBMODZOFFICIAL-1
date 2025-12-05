<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BB MODZ OFFICIAL</title>
<style>
  body {
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #000000, #1a1a1a);
    font-family: 'Courier New', monospace;
    color: white;
    text-align: center;
  }

  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    padding: 30px 15px;
  }

  .logo img {
    width: 180px;
    height: 180px;
    border-radius: 50%;
    box-shadow: 0 0 40px #ff0000;
    border: 2px solid #111;
    animation: pulse 2s infinite alternate;
  }

  @keyframes pulse {
    0% { box-shadow: 0 0 25px #ff0000; transform: scale(1); }
    50% { box-shadow: 0 0 50px #ff3333; transform: scale(1.05); }
    100% { box-shadow: 0 0 25px #ff0000; transform: scale(1); }
  }

  h1 {
    color: #ff0000;
    font-size: 28px;
    margin-top: 20px;
  }

  h2 {
    color: #ff3333;
    font-size: 20px;
    margin-bottom: 25px;
  }

  .generate-box {
    border: 1px solid #ff000055;
    padding: 15px;
    margin: 10px auto;
    width: 80%;
    max-width: 340px;
    border-radius: 12px;
    font-size: 16px;
    color: #ffcccc;
    transition: 0.3s;
  }

  .generate-box:hover {
    box-shadow: 0 0 15px #ff0000;
  }

  .btn {
    background-color: transparent;
    border: 2px solid #ff0000;
    color: #ff0000;
    padding: 12px 28px;
    margin-top: 10px;
    margin-right: 10px;
    border-radius: 10px;
    font-size: 18px;
    cursor: pointer;
    transition: 0.3s;
  }

  .btn:hover {
    background-color: #ff0000;
    color: #000;
    box-shadow: 0 0 15px #ff0000;
  }

  .telegram-box {
    margin-top: 30px;
    border: 1px solid #ff000055;
    padding: 20px;
    border-radius: 12px;
    max-width: 340px;
    margin-left: auto;
    margin-right: auto;
    background-color: #111;
  }

  .telegram-box p {
    color: #ff3333;
    font-size: 15px;
    margin-bottom: 12px;
  }

  .telegram-btn {
    background: linear-gradient(90deg, #ff0000, #ff3333);
    color: #000;
    font-weight: bold;
    padding: 10px 25px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: 0.3s;
  }

  .telegram-btn:hover {
    transform: scale(1.05);
  }

  .key-box {
    margin-top: 20px;
    font-size: 16px;
    color: #ff3333;
    word-break: break-word;
  }

  @media (max-width: 480px) {
    h1 { font-size: 22px; }
    h2 { font-size: 18px; }
    .btn { font-size: 16px; padding: 10px 20px; }
  }
</style>
</head>
<body>

<div class="container">
  <div class="logo">
    <img src="https://i.supaimg.com/fb5e2529-2481-4cad-9d5b-82f618f4165f.png" alt="Logo">
  </div>

  <h1>BB MODZ OFFICIAL KEY GENERATOR</h1>
  <h2>BB MODZ ON TOP</h2>

  <div class="generate-box">– Press Generate –</div>

  <!-- MAIN BUTTONS -->
  <button class="btn" onclick="generateKey()">GENERATE KEY</button>
  <button class="btn" onclick="copyKey()">COPY KEY</button>

  <div class="key-box" id="keyBox"></div>

  <div class="telegram-box">
    <p>❤️ Any Problem? Join Telegram!</p>
    <button class="telegram-btn" onclick="window.open('https://t.me/+HUNtRRfb_UY4ODg1', '_blank')">Join Now</button>
  </div>
</div>

<script>
  const earnLink = "https://earnlinks.in/2aqB"; 

  function generateKey() {
    const chars = "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789";
    let key = "";
    for (let i = 0; i < 16; i++) {
      key += chars.charAt(Math.floor(Math.random() * chars.length));
      if ((i + 1) % 4 === 0 && i < 15) key += "-";
    }

    document.getElementById("keyBox").innerHTML =
      "🔑 Your Key: <b>" + key + "</b>";

    // Auto-open earn link
    window.open(earnLink, "_blank");
  }

  function copyKey() {
    const keyText = document.getElementById("keyBox").innerText.replace("🔑 Your Key: ", "");
    if (keyText.trim() !== "") {
      navigator.clipboard.writeText(keyText);
      alert("✅ Key copied to clipboard!");
    } else {
      alert("⚠️ Please generate a key first!");
    }
  }
</script>

</body>
</html>
