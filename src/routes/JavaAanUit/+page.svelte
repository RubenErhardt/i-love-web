<script>
    import { onMount } from 'svelte';
    onMount(() => {
      const toggleButton = document.getElementById('theme-toggle');
  
      toggleButton.addEventListener('click', () => {
        document.body.classList.toggle('dark-theme');
      });
  
    });
  </script>
  
  <style>
    /* Global Styles */
    :global(body) {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      transition: background-color 0.3s, color 0.3s;
    }

  
    :global(.dark-theme) {
      background-color: #333;
      color: #f0f0f0;
    }
  
    /* Scoped Styles for Components */
    .container {
      text-align: center;
      padding: 50px;
    }
  
    .info {
      margin-bottom: 20px;
    }
  
    button {
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
    }
  </style>
  
  <div class="container">
    <div class="info">
      <h1>Thema-toggle met JavaScript</h1>
      <p>Klik op de knop hieronder om tussen licht en donker thema te schakelen.</p>
    </div>
    <div class="toggle-container">
      <button id="theme-toggle">Schakel Thema</button>
    </div>
  </div>
  