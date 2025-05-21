<script>
  export let title = "Sunburst Festival";
  export let subtitle = "Subtitle";
</script>

<header class="hero is-primary">
  <div class="hero-body">
    <h1 class="title">{title}</h1>
    <h2 class="subtitle">{subtitle}</h2>
  </div>
  <p class="credits">&copy Samuel Regan Asante</p>
</header>

<style>
  header {
    background-image: url(/samuel-regan-asante.jpg);
    background-repeat: repeat-x;
    background-size: contain;
    padding-top: 5%;
  }
  .hero-body {
    background-color: #8f0a9e;
    margin-left: 25%;
    margin-right: 25%;
    margin-bottom: 5%;
    align-items: center;
  }
  .title {
    color: #ffffff;
    font-size: 4em;
    text-align: center;
    font-family: "Trade Winds", system-ui;
  }
  .subtitle {
    color: #f0eafa;
    font-size: 2em;
    text-align: left;
    margin-left: 15%;
    font-family: "Trade Winds", system-ui;
  }
  .credits {
    color: #f0eafa;
    align-self: left;
    align-self: baseline;
    font-size: 0.5em;
  }
</style>
