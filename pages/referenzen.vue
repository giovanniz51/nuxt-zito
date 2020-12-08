<template>
  <div class="portfolio">
    <b-container class="py-3 portfolio__intro">
      <b-row style="margin-bottom: 1rem">
        <b-col cols="12" lg="8">
          <h1>Referenzen</h1>
          <h2>Konzeption, Webdesign, CMS, WordPress, E-commerce, Suchmaschienenoptimierung und Pflege – Fullservice für vollen Erfolg.</h2>
          <p>
            Im Laufe der Jahre konnte ich bereits einige Websites erstellen. Hier finden Sie einige Referenzen.
          </p>

          <Gallery></Gallery>
        </b-col>
        <b-col cols="12" lg="4" class="my-5 text-center">
          <img src="/myhammer.png" alt="">
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import Gallery  from "../components/Gallery";
  export default {
  components:{
    Gallery
  } ,
  head: {
    title: 'Referenzen – Zito-Webdesign',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Website, SEO, Webdesign zum pauschal Preis ohne versteckte Kosten. Konzeption, Gestaltung und Programmierung von Websites.'
      }
    ],
  },
  data() {
    return {
      flickityOptions: {
        freeScroll: true,
        wrapAround: true,
        prevNextButtons: true,
        pageDots: true,
        fade: true
      }
    }
  },
  }
</script>

<style lang="scss">
  .portfolio {
    .portfolio__intro h2 {
      color: $primary;
      font-size: 1.5rem;
    }
  }
  .flickity {
    background: $primary;
  }

  .carousel-cell {
    width: 100%;
    height: auto;
    margin-right: 10px;
    border-radius: 5px;
    text-align: center;
  }

</style>
