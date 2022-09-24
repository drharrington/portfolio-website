<script>
  import devLogo from './assets/dev-logo.svg'
  import Counter from './lib/Counter.svelte'
  import Navbar from './lib/Navbar.svelte';
</script>

<main>
  <div>
    <a href="https://acmcsuf.com" target="_blank"> 
      <img src={devLogo} class="logo dev" alt="Svelte Logo" />
    </a>
  </div>
  <h1>Dominic Harrington</h1>

  <div class="card">
    <Counter />
    <Navbar />
  </div>
</main>

<style>
  .logo {
    height: em;
    padding: 1.5em;
    will-change: filter;
  }
  
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }

  .logo.dev:hover {
    filter: drop-shadow(0 0 2em #1E6CFF);
  }
</style>
