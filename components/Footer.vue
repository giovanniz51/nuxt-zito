<template>
  <div>
    <footer class="text-light py-5 text-center">
      <b-container>
        <b-row>
          <b-col cols="12" md="6" lg="3" class="my-2">
            <h4>Adresse</h4>
            <p>Giovanni Zito</p>
            <p>Schenkenbergstraße 49</p>
            <p>73733 Esslingen</p>
          </b-col>
          <b-col cols="12" md="6" lg="3" class="my-2">
            <h4>KONTAKT</h4>
            <p><b-icon icon="phone" style="color: #307ECC" font-scale="1.5"></b-icon> 0176-81227725</p>
            <p><b-icon icon="envelope" style="color: #307ECC" font-scale="1.5"></b-icon> kontakt@zito-webdesign.de</p>
          </b-col>
          <b-col cols="12" md="6" lg="3" class="my-2">
            <h4>Info</h4>
            <p><router-link to="/leistungen">Webhosting</router-link></p>
            <p><router-link to="/leistungen">SEO</router-link></p>
            <p><router-link to="/leistungen">Wartung & Service</router-link></p>
          </b-col>
          <b-col cols="12" md="6" lg="3" class="my-2">
            <h4>Links</h4>
            <p><router-link to="datenschutz">Datenschutz</router-link></p>
            <p><router-link to="agb">AGB</router-link></p>
            <p><router-link to="impressum">Impressum</router-link></p>
          </b-col>
        </b-row>
      </b-container>
    </footer>
    <div class="footer-copy py-2 text-light">
      <b-container>
        <b-row>
          <b-col>
            <p style="margin: 0">&copy; Zito-WebDesign</p>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <cookie-law theme="dark-lime">
      <div slot-scope="props" class="text-center" style="width:100%;">
        <p>
          Diese Website benutzt Cookies. Wenn du die Website weiter nutzt, gehen wir von deinem Einverständnis aus.
        </p>
         <button class="btn btn-primary" @click="props.accept"><span>OK</span></button>
      </div>
    </cookie-law>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
  footer {
      background: $secondary;

      h4 {
        font-size: 1.2rem;
        text-transform: uppercase;
      }

      p {
        font-size: .9rem;
        margin-bottom: .5rem;
      }
  }

  .footer-copy {
      background: $primary;
  }
</style>
