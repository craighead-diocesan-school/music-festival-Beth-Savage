<script>
  export let title = "Sunburst Festival";
  export let subtitle = "Subtitle";
</script>
<header class="hero is-primary">
  <div class="hero-body">
    <h1 class="title">{title}</h1>
    <h2 class="subtitle"> {subtitle}</h2>
  </div>
</header>

<style>
  header {
    background-image:url(/samuel-regan-asante.jpg);
    background-repeat: repeat-x;
    background-size: contain;
    padding: 5%;
  }
  .hero-body {
    background-color: #8F0A9E;
    margin-left:25%;
    margin-right:25%;
    align-items: center;
  }
  .title{
    color: #FFFFFF;
    font-size: 4em;
    text-align: center;
    font-family: "Trade Winds", system-ui;
  }
  .subtitle{
    color: #F0EAFA;
    font-size: 2em;
    text-align: left;
    margin-left: 15%;
    font-family: "Trade Winds", system-ui;
  }
</style>
