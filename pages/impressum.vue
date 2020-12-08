<template>
  <div class="impressum">
    <b-container class="py-3 impressum__intro">
      <b-row style="margin-bottom: 1rem">
        <b-col cols="12">
        <h1>Impressum</h1> <h2>Angaben gemäß § 5 TMG:</h2> <p>Giovanni Zito<br /> Zito-Webdesign.de<br
            /> Schenkenbergstraße 49<br /> 73733 Esslingen </p> <h2>Kontakt:</h2> <table><tr>
            <td>Telefon: </td> <td>  017681227725</td></tr> <tr><td>E-Mail:</td> <td>kontakt@zito-webdesign.de</td>
            </tr></table> <p> </p>
            <br>
            <br>
            <h1>Haftungsausschluss (Disclaimer)</h1> <h2>Haftung für Inhalte</h2> <p>Als Diensteanbieter sind wir
            gemäß § 7 Abs.1 TMG für eigene Inhalte auf diesen Seiten nach den allgemeinen
            Gesetzen verantwortlich. Nach §§ 8 bis 10 TMG sind wir als Diensteanbieter jedoch nicht verpflichtet,
            übermittelte oder gespeicherte fremde Informationen zu überwachen oder nach Umständen zu
            forschen, die auf eine rechtswidrige Tätigkeit hinweisen.</p> <p>Verpflichtungen zur Entfernung oder
            Sperrung der Nutzung von Informationen nach den allgemeinen Gesetzen bleiben hiervon unberührt. Eine
            diesbezügliche Haftung ist jedoch erst ab dem Zeitpunkt der Kenntnis einer konkreten Rechtsverletzung
            möglich. Bei Bekanntwerden von entsprechenden Rechtsverletzungen werden wir diese Inhalte umgehend
            entfernen.</p> <h2>Haftung für Links</h2> <p>Unser Angebot enthält Links zu externen Webseiten
            Dritter, auf deren Inhalte wir keinen Einfluss haben. Deshalb können wir für diese fremden Inhalte
            auch keine Gewähr übernehmen. Für die Inhalte der verlinkten Seiten ist stets der jeweilige
            Anbieter oder Betreiber der Seiten verantwortlich. Die verlinkten Seiten wurden zum Zeitpunkt der Verlinkung auf
            mögliche Rechtsverstöße überprüft. Rechtswidrige Inhalte waren zum Zeitpunkt der
            Verlinkung nicht erkennbar.</p> <p>Eine permanente inhaltliche Kontrolle der verlinkten Seiten ist jedoch ohne
            konkrete Anhaltspunkte einer Rechtsverletzung nicht zumutbar. Bei Bekanntwerden von Rechtsverletzungen
            werden wir derartige Links umgehend entfernen.</p> <h2>Urheberrecht</h2> <p>Die durch die Seitenbetreiber
            erstellten Inhalte und Werke auf diesen Seiten unterliegen dem deutschen Urheberrecht. Die
            Vervielfältigung, Bearbeitung, Verbreitung und jede Art der Verwertung außerhalb der Grenzen des
            Urheberrechtes bedürfen der schriftlichen Zustimmung des jeweiligen Autors bzw. Erstellers. Downloads
            und Kopien dieser Seite sind nur für den privaten, nicht kommerziellen Gebrauch gestattet.</p> <p>Soweit
            die Inhalte auf dieser Seite nicht vom Betreiber erstellt wurden, werden die Urheberrechte Dritter beachtet.
            Insbesondere werden Inhalte Dritter als solche gekennzeichnet. Sollten Sie trotzdem auf eine
            Urheberrechtsverletzung aufmerksam werden, bitten wir um einen entsprechenden Hinweis. Bei Bekanntwerden
            von Rechtsverletzungen werden wir derartige Inhalte umgehend entfernen.</p><p> </p>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import Gallery  from "../components/Gallery";
  export default {
  head: {
    title: 'Impressum – Zito-Webdesign',
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
  .impressum h2 {
    color: $primary;
    font-size: 1.5rem;
  }
</style>
