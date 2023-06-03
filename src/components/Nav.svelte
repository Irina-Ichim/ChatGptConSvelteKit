<script>
</script>

<section>
    <h1>SvelteKit OpenAI</h1>
</section>
<nav>
  <ul class="nav-links">
      <li><a href="/">Generador de Imágenes</a></li>
      <li><a href="/chat">ChatBot Gpt</a></li>
    </ul>
</nav>

  
  <style>
    
    section {
      background-color: #000;
      padding: 1rem;
      display: flex;
      justify-content: center;
      align-items: center;
     filter: drop-shadow(0 0 20px #fff) drop-shadow(0 0 20px #fff);
    }
  
    h1 {
      font-size: 1.8rem;
      margin: 0;
      color: #fff;
      animation: animate 10s linear infinite;
        filter: drop-shadow(0 0 20px #fff) drop-shadow(0 0 20px #fff);
    }
    @keyframes animate {
        0% {
            width: 50%;
        }
        100% {
            width: 80%;
        }
    }
    .nav-links {
        list-style: none;
        display: flex;
        justify-content: flex-end;
        gap: 1rem;
        margin-top: 1rem;
    }
    .nav-links a {
        text-decoration: none;
        color: #fff;
        padding: 0.5rem 1rem;
        border-radius: 4px;
        transition: background-color 0.3s ease;
        font-size:19px;
    }
    .nav-links a:hover {
        filter: drop-shadow(0 0 20px #fff) drop-shadow(0 0 20px #fff);
        color:black;
    }
  

  </style>
  