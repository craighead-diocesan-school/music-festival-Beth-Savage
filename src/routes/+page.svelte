<script>
  import Header from "$lib/Header.svelte";
  import Nav from "$lib/Nav.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Header subtitle="Home" />
<Nav />

<main class="content section">
  <img
    class="column is-half"
    src="/hanny-naibaho.jpg"
    alt="One of the stages from the audience's view"
  />
  <div class="text column is-half">
    <p>
      Welcome to the ultimate music festival experience! Get ready for a day
      filled with live music, great food, and unforgettable memories.
    </p>
    <p>
      Our festival features a diverse lineup of talented musicians from
      different genres, sure to satisfy every taste in music. With multiple
      stages set up throughout the venue, you can easily move from one act to
      the next, discovering new favorites and enjoying classic hits.
    </p>
    <p>
      From up-and-coming artists to established headliners, we have curated an
      exciting lineup that will keep you dancing and singing along all day long.
      Our festival is the perfect opportunity to discover new music, see your
      favorite artists live, and make lasting memories with friends and family.
    </p>
  </div>
  <img
    class="column is-half"
    src="/aditya-chinchure.jpg"
    alt="A light show at the Festival"
  />
  <div class="text column is-half">
    <p>
      But the music is just the beginning. Our festival also boasts an
      impressive selection of food vendors, offering everything from classic
      festival fare to more gourmet options. You won't go hungry with the
      delicious treats and refreshing beverages available throughout the venue.
    </p>
    <p>
      In addition to the music and food, our festival also features a variety of
      activities to keep you entertained throughout the day. From art
      installations to merchandise booths, there is something for everyone to
      enjoy. You can even capture the memories with our festival photo booths
      and snap a selfie with your favorite artists.
    </p>
    <p>
      So don't miss out on this one-of-a-kind music festival experience. Get
      your tickets now and join us for a day of music, fun, and community. We
      can't wait to see you there!
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
  p{
    font-family: "Permanent Marker", cursive;
    opacity: 100%;
  }
  main.content{
    background-color: #1d2f3e;
    margin-bottom: 0%;
  }
</style>
