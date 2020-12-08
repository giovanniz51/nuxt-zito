<template>
  <div class="services">
    <b-container class="py-3 services__intro">
      <b-row style="margin-bottom: 1rem">
        <b-col cols="12">
          <h1>Leistungen</h1>
        </b-col>
      </b-row>
      <b-row>
        <b-col cols="12">
          <h2>Ich entwickle komplexe Websites und Software für meine Kunden</h2>
          <p>Die Entwicklung von Websites und Software ist meine Leidenschaft, optisch und technisch muss diese auf neustem Stand sein, damit Ihre Kunden die beste Usability von der Website / Internetseite geboten bekommen.</p>
          <p>
            Meine Kunden erhalten ein Produkt, welches deren individuellen Anforderungen entspricht.
          </p>
        </b-col>
      </b-row>
    </b-container>
    <div class="flickity py-3 text-light">
      <div>
        <b-row class="my-5" >
          <b-container fluid>
            <b-col cols="12">
              <client-only>
                <flickity ref="flickity" :options="flickityOptions">
                  <div class="carousel-cell">
                    <div style="min-height: 30rem">
                      <img class="my-3 rounded-circle" src="@/static/fullslide1-180x180.jpg" alt="">
                      <h2>KONZEPTION & BERATUNG</h2>
                      <p>
                        Als Freelancer unterstütze ich Sie mit meiner langjährigen Erfahrung. Mit mir haben Sie einen Partner gefunden, der langfristig und lösungsorientiert denkt, um Projekte zukunftsfähig umzusetzen. Professionelle Website Beratung, Konzeption und Erstellung aus einer Hand!
                      </p>
                    </div>
                  </div>
                  <div class="carousel-cell">
                    <div style="min-height: 30rem">
                      <img class="my-3 rounded-circle" src="@/static/laptopmockup_sliderdy-180x180.jpg" alt="">
                      <h2>PROGRAMMIERUNG/ENTWICKLUNG</h2>
                      <p>
                        Als erfahrener Webdesigner und Programmierer für Websites und Software, biete ich Ihnen auf Sie abgestimmte Programme und die Entwicklung von hochwertigen Projekten.
                      </p>
                      <p>Ich habe mich auf das CMS WordPress spezialisiert, welches Ihnen ermöglicht, selbst Änderungen an der Website und am Webdesign vor zu nehmen. Aber auch andere Lösungen sind möglich.</p>
                    </div>
                  </div>
                  <div class="carousel-cell">
                    <div style="min-height: 30rem">
                      <img class="my-3 rounded-circle" src="@/static/pexels-photo-326514-180x180.jpeg" alt="">
                      <h2>WEBHOSTING</h2>
                      <p>
                        Meine Kunden profitieren nicht nur von meiner Erfahrung im Bereich Entwicklung und Webdesign. Meine Hosting-Leistungen ermöglichen es einen umfassenden Service zu bieten. Mit mir als Webdesigner für Ihre Website und als Webhosting Partner, bekommen sie alles aus einer Hand und haben eine Anlaufstelle für Ihr Internetauftritt
                      </p>
                    </div>
                  </div>
                  <div class="carousel-cell">
                    <div style="min-height: 30rem">
                      <img class="my-3 rounded-circle" src="@/static/pexels-photo-326424-180x180.jpeg" alt="">
                      <h2>SEO/SUCHMASCHINENOPTIMIERUNG</h2>
                      <p>
                        Als erfahrener SEO Spezialist, kümmere ich um die notwendigen Optimierungsarbeiten. Mit meiner individuellen Suchmaschinenoptimierung verbessern sich Ihre Besucher- und Umsatzzahlen ihrer Website.
                      </p>
                      <p>
                        Damit Sie optimal mit den gewünschten Keywords, bei Google, Bing & Co gefunden werden muss Ihre Website optimal programmiert und optimiert sein.
                      </p>
                    </div>
                  </div>
                  <div class="carousel-cell">
                    <div style="min-height: 30rem">
                      <img class="my-3 rounded-circle" src="@/static/pexels-photo-251225-180x180.jpeg" alt="">
                      <h2>WARTUNG & SERVICE</h2>
                      <p>
                        Ich möchte, dass meine Kunden langfristig mit der Zusammenarbeit zufrieden sind. Deshalb biete ich Ihnen meinen langfristigen Service an. Dabei bin ich stets verfügbar und sorge für einen reibungslosen Betrieb Ihrer Website und Projekte. Beauftragen Sie mich mit der Instandhaltung Ihrer Website, und Sie müssen sich keine Sorgen mehr über die Aktualisierung und den reibungslosen Betrieb mehr machen.
                      </p>
                    </div>
                  </div>
                </flickity>
              </client-only>
            </b-col>
          </b-container>
        </b-row>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    head: {
    title: 'Leistungen – Zito-Webdesign',
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
  .services {
    .services__intro h2 {
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
    text-align: center;

    h2 {
      font-size: 1.5rem;
    }
  }

</style>
