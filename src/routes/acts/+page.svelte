<script>
  import Header from "$lib/Header.svelte";
  import Nav from "$lib/Nav.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Header subtitle="Acts" />
<Nav />
<main class="content section">
  <img class="column is-half" src="/" alt="" />
  <div class="text column is-half"></div>
  <img class="column is-half" src="/" alt="" />
  <div class="text column is-half"></div>
</main>
<Footer />

<style>
  .content {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
  }
  img {
    width: 50%;
    height: auto;
  }
  .text {
    margin-top: 5%;
    margin-bottom: 5%;
    padding: 1%;
    background-color: #e5c2dd;
    align-items: center;
    opacity: 99%;
  }
  p {
    font-family: "Permanent Marker", cursive;
    opacity: 100%;
  }
  main.content {
    background-color: #1d2f3e;
    margin-bottom: 0%;
  }
</style>
