#   
<!DOCTYPE html>  
<html lang="en">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Mridu</title>  
  
  <!-- Favicon -->  
  <link rel="icon" type="image/png" href="logo.png">  
  
  <!-- Open Graph Meta Tags -->  
  <meta property="og:title" content="Mridu">  
  <meta property="og:description" content="Just another work in progress.">  
  <meta property="og:url" content="https://mridu.xyz">  
  <meta property="og:type" content="website">  
  
  <link rel="preconnect" href="https://fonts.googleapis.com">  
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>  
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">  
  
  <style>  
    * {  
      margin: 0;  
      padding: 0;  
      box-sizing: border-box;  
    }  
  
    body {  
      background-color: #7ec8e3;  
      font-family: 'Press Start 2P', cursive;  
      color: #1a1a1a;  
      min-height: 100vh;  
      display: flex;  
      flex-direction: column;  
      align-items: center;  
      justify-content: center;  
      padding: 2rem 1rem;  
      text-align: center;  
    }  
  
    .logo {  
      width: 180px;  
      height: auto;  
      image-rendering: pixelated;  
      image-rendering: crisp-edges;  
      margin-bottom: 1.5rem;  
    }  
  
    h1 {  
      font-size: 2.8rem;  
      margin-bottom: 1rem;  
      line-height: 1.4;  
    }  
  
    .tagline {  
      font-size: 0.85rem;  
      margin-bottom: 0.6rem;  
    }  
  
    .subtitle {  
      font-size: 0.65rem;  
      opacity: 0.85;  
      margin-bottom: 3rem;  
    }  
  
    footer {  
      margin-top: auto;  
      width: 100%;  
      max-width: 600px;  
      display: flex;  
      justify-content: space-between;  
      align-items: center;  
      font-size: 0.55rem;  
      padding: 1.5rem 0 0.5rem;  
    }  
  
    .x-link {  
      display: flex;  
      align-items: center;  
      gap: 0.4rem;  
      text-decoration: none;  
      color: #1a1a1a;  
    }  
  
    .x-link:hover {  
      opacity: 0.7;  
    }  
  
    .x-icon {  
      width: 16px;  
      height: 16px;  
    }  
  
    @media (max-width: 480px) {  
      h1 {  
        font-size: 2rem;  
      }  
      .logo {  
        width: 140px;  
      }  
      footer {  
        flex-direction: column;  
        gap: 0.8rem;  
      }  
    }  
  </style>  
</head>  
<body>  
  <img src="logo.png" alt="Potatoz mascot" class="logo">  
  
  <h1>Mridu.</h1>  
  <p class="tagline">Just another work in progress.</p>  
  <p class="subtitle">A personal space on the internet.</p>  
  
  <footer>  
    <span>© 2026 · mridu.xyz</span>  
    <a href="https://x.com/mridu_xyz" target="_blank" rel="noopener noreferrer" class="x-link">  
      <svg class="x-icon" viewBox="0 0 24 24" fill="currentColor">  
        <path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/>  
      </svg>  
      @mridu_xyz  
    </a>  
  </footer>  
</body>  
</html>  
