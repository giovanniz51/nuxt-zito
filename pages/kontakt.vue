<template>
  <div class="kontakt">
    <b-container class="py-3 kontakt__intro">
      <b-row style="margin-bottom: 1rem">
        <b-col cols="12">
          <h1>Kontakt</h1>
          <h2>
            Kontakt zu Ihrem Webdesigner, optimal für Ihr Internetauftritt.
          </h2>
          <p>
            Ich freue mich, dass Sie mit mir Kontakt aufnehmen möchten. Sie benötigen ein Angebt oder eine Beratung ? Dann kontaktieren Sie mich.
          </p>
          <h2>Adresse</h2>
          <p>Giovanni Zito</p>
<p>Zito-Webdesign.de</p>
<p>Schenkenbergstraße 49</p>
<p>73733 Esslingen</p>
<p><b-icon icon="phone" style="color: #307ECC" font-scale="1.5"></b-icon> 0176-81227725</p>
            <p><b-icon icon="envelope" style="color: #307ECC" font-scale="1.5"></b-icon> kontakt@zito-webdesign.de</p>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import Gallery  from "../components/Gallery";
  export default {
  head: {
    title: 'Kontakt – Zito-Webdesign',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Website, SEO, Webdesign zum pauschal Preis ohne versteckte Kosten. Konzeption, Gestaltung und Programmierung von Websites.'
      }
    ],
  },
  components:{

  } ,
  }
</script>

<style lang="scss">
  .kontakt h2 {
    color: $primary;
    font-size: 1.5rem;
  }
</style>
