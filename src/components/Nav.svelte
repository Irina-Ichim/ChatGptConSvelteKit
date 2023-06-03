<nav class="navbar">
    <h1 class="title">SvelteKit OpenAI</h1>
    <ul class="nav-links">
      <li><a href="/">Generador de Imágenes</a></li>
      <li><a href="/chat">ChatBot Gpt</a></li>
    </ul>
  </nav>
  
  <style>
    
    .navbar {
      background-color: #000;
      padding: 1rem;
      display: flex;
      justify-content: center;
      align-items: center;
      filter: drop-shadow(0 0 20px #fff) drop-shadow(0 0 20px #fff);
    }
  
    .title {
      font-size: 1.5rem;
      margin: 0;
      color: #fff;
      animation: animate 5s linear infinite;
    }
  
    .nav-links {
      list-style: none;
      display: flex;
      justify-content: flex-end;
      gap: 1rem;
      margin-top: 1rem;
    }
  
    .nav-links li {
      font-size: 1.2rem;
    }
  
    .nav-links a {
      text-decoration: none;
      color: #fff;
      padding: 0.5rem 1rem;
      border-radius: 4px;
      transition: background-color 0.3s ease;
    }
  
    .nav-links a:hover {
      background-color: #ddd;
    }
  
    @keyframes animate {
      0% {
        width: 0;
      }
      100% {
        width: 50%;
      }
    }
  </style>
  