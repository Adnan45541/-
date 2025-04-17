<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>For Mira 💖</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      overflow: hidden;
      background: black;
      font-family: 'Segoe UI', sans-serif;
      color: white;
    }

    .overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: rgba(0, 0, 0, 0.4);
      padding: 20px;
      box-sizing: border-box;
      z-index: 2;
      animation: fadeIn 3s ease forwards;
    }

    .message {
      font-size: 1.8rem;
      line-height: 2.5rem;
      opacity: 0;
      animation: revealText 4s ease-in-out forwards;
      animation-delay: 2s;
      margin-bottom: 20px;
    }

    .photo {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      border: 3px solid white;
      object-fit: cover;
      box-shadow: 0 0 20px rgba(255, 255, 255, 0.5);
      opacity: 0;
      animation: revealText 4s ease-in-out forwards;
      animation-delay: 3s;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes revealText {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    audio {
      display: none;
    }
  </style>
</head>
<body>
  <div class="overlay">
    <div class="message">
      I had told you that I will say her name and share her picture, I mean the person I love from my heart. I will reveal it after my admission exam, but I have tried my best to hold it in and now I can't. I can't wait. I'm scared to lose her, that's why the person is...<br><br>
      it's you actually, Mira. 💖
    </div>
    <img src="❤.jpg" alt="Mira's Picture" class="photo">
  </div>

  <audio autoplay loop>
    <source src="https://dl.sndup.net/fcbk/%D0%9A%D0%B0%D0%BC%D0%B8%D0%BD%20-%20EMIN%20%26%20JONY.mp3" type="audio/mpeg">
  </audio>
</body>
</html>
