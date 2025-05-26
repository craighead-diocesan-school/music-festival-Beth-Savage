<script>
  import Header from "$lib/Header.svelte";
  import Nav from "$lib/Nav.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Header subtitle="Accommodations" />
<Nav />
<main class="content section">
  <div class="top text">
    <p>
      Experience the ultimate music festival adventure with our tent
      accommodation packages! With our comfortable and convenient tents, you can
      immerse yourself in the festival atmosphere and stay close to all the
      action.
    </p>
  </div>
  <figure class="column is-half">
    <img
      src="/krists-luhaers.jpg"
      alt="A girl at the camp ground"
      caption="krists-luhaers"
    />
    <figcaption>Image Krists Luhaers</figcaption>
  </figure>
  <div class="text column is-half">
    <p>
      Our tents are spacious and come equipped with everything you need for a
      comfortable stay. With comfortable beds, pillows, and blankets, you can
      get a good night's sleep and wake up feeling refreshed and ready for
      another day of music and fun. Located within the festival grounds, our
      tents are just a short walk away from all the stages and attractions. You
      won't have to worry about transportation or navigating crowds to get to
      the festival - you'll be right in the heart of it all.
    </p>
  </div>
  <div class="text column is-half">
    <p>
      Our tents also come with a range of amenities to make your stay even more
      comfortable. You'll have access to clean restroom facilities, hot showers,
      and charging stations for your devices. We also have a dedicated staff
      available to assist with any needs or questions you may have during your
      stay. But the best part of our tent accommodation packages is the
      community. You'll be surrounded by other festival-goers who are just as
      excited as you are to be a part of the experience. You'll make new
      friends, share stories, and create memories that will last a lifetime.
    </p>
  </div>
  <figure class="column is-half">
    <img
      src="/vonecia-carswell.jpg"
      alt="A group of people at the festival campground"
      caption="vonecia-carswell"
    />
    <figcaption>Image Vonecia Carswell</figcaption>
  </figure>
  <div class=" top text column is-half">
    <p>
      Don't miss out on this opportunity to enhance your music festival
      experience. Book your tent accommodation package today and get ready for
      an unforgettable adventure. We can't wait to see you there!
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
  .top {
    align-self: center;
    margin-left: 25%;
    margin-right: 25%;
    font-size: 1.25em;
  }
    figcaption {
        color: #f0eafa;
        font-size: 0.5em;
    }
</style>
