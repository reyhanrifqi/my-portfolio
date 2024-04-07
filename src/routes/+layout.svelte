<script>
  import '../global.css';
  import Navigation from '../components/navigation.svelte';
  import Logo from '../components/logo.svelte';
</script>

<div class="main-container">
  <Navigation />
  <Logo />

  <div class="content-wrapper">
    <slot />
  </div>
</div>

<style>
  :root {
    margin: 0;
    padding: 0px;
    font-family: 'Noi Grotesk';
    background-color: #ebebeb;
  }

  :global(body, html) {
    margin: 0;
    padding: 0;
    height: 100%;
  }

  div.main-container {
    height: 100%;
    display: grid;
    grid-template-rows: auto auto 1fr;
    margin: 0;
  }

  div.content-wrapper {
    display: grid;
    box-sizing: border-box;
    background-color: #1b1b1b;
    margin: 0px 60px 0px 60px;
    height: 100%;
    padding: 5px;
  }
</style>
