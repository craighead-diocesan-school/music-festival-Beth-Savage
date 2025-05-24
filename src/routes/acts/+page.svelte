<script>
  import Header from "$lib/Header.svelte";
  import Nav from "$lib/Nav.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Header subtitle="Acts" />
<Nav />
<main class="content section">
  <div class="top text">
    <p>
      The music festival boasts an exciting lineup of talented musicians from a
      variety of genres, promising a diverse and entertaining experience for all
      attendees.
    </p>
  </div>
  <img class="column is-half" src="/tony-pham.jpg" alt="" />
  <div class="text column is-half">
    <p>
      On the main stage, the headliners are a mix of established and
      up-and-coming acts, guaranteed to draw in large crowds. The first
      headliner is a popular rock band, known for their high-energy performances
      and catchy hooks. They will be followed by a chart-topping pop artist,
      whose upbeat and infectious hits are sure to get the crowd dancing and
      singing along. The final headliner is a legendary hip-hop artist, whose
      iconic rhymes and charismatic stage presence will bring the festival to a
      thrilling close.
    </p>
  </div>
  <div class="text column is-half">
    <p>
      On the second stage, indie bands and singer-songwriters showcase their
      unique styles and sounds. The performers on this stage are often the most
      buzzed-about acts of the festival, with a loyal and passionate following.
      From dreamy shoegaze bands to alternative rock acts, the second stage
      offers a more intimate and personal experience for music lovers looking to
      discover new artists.
    </p>
    <p>
      The third stage is dedicated to up-and-coming artists from different
      genres, providing a platform for emerging talent to showcase their skills
      and gain exposure. This stage is a great opportunity for attendees to
      discover new artists and support the next generation of musicians.
    </p>
  </div>
  <img class="column is-half" src="/maxwell-collins.jpg" alt="" />
  <img class="column is-half" src="/tijs-van-leur.jpg" alt="" />
  <div class="text column is-half">
    <p>
      Throughout the festival, DJs and electronic acts keep the energy up
      between sets, playing a mix of classic and contemporary dance tracks that
      will keep the crowd moving and grooving.
    </p>
    <p>
      Overall, the music festival offers a diverse and exciting lineup that
      caters to different tastes and styles. From established headliners to
      emerging talent, the festival promises a memorable and thrilling musical
      experience for all attendees.
    </p>
  </div>
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
  .top{
    align-self: center;
    margin-left: 25%;
    margin-right: 25%;
    font-size: 1.25em;
  }
</style>
