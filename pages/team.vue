<template>
  <b-container class="m-0 p-0 bwhite" fluid>
    <b-container class="m-0 p-0 h80" fluid> </b-container>
    <b-row class="m-0 p-0">
      <b-col md="2" cols="0"></b-col>
      <b-col md="8" cols="12" class="m-0 p-0">
        <p class="amarenared t32 text-center" v-html="$t('team.title')"></p>

        <b-card-group deck>
          <b-card class="border-0 text-center">
            <b-card-body class="text-center p-0 m-0">
              <b-img
                src="~/assets/amdp.png"
                class="rounded-circle imgteam"
              ></b-img>
              <b-card-title>Alessandro Merletti De Palo</b-card-title>
              <b-card-sub-title> Film Director - CFO - QCO </b-card-sub-title>
              <b-card-text>
                <b-link class="amarenared" v-b-modal.amdpmodal> BIO </b-link>
              </b-card-text>
            </b-card-body>
          </b-card>

          <b-card class="border-0">
            <b-card-body class="text-center p-0 m-0">
              <b-img
                src="~/assets/gio.jpg"
                class="rounded-circle imgteam"
              ></b-img>
              <b-card-title>Giovanni Caloro</b-card-title>
              <b-card-sub-title> Film Director - CEO </b-card-sub-title>
              <b-card-text>
                <b-link class="amarenared" v-b-modal.giomodal> BIO </b-link>
              </b-card-text>
            </b-card-body>
          </b-card>
        </b-card-group>

        <b-container class="my-2"></b-container>

        <b-card-group deck>
          <b-card class="border-0">
            <b-card-body class="text-center p-0 m-0">
              <b-img
                src="~/assets/nina.jpg"
                class="rounded-circle imgteam"
              ></b-img>
              <b-card-title>Nina Gurgoglione</b-card-title>
              <b-card-sub-title> Production Main Supervisor </b-card-sub-title>
              <b-card-text>
                <b-link class="amarenared" v-b-modal.ninamodal> BIO </b-link>
              </b-card-text>
            </b-card-body>
          </b-card>

          <b-card class="border-0">
            <b-card-body class="text-center p-0 m-0">
              <b-img
                src="~/assets/ari.jpg"
                class="rounded-circle imgteam"
              ></b-img>
              <b-card-title>Arianna Giri</b-card-title>
              <b-card-sub-title>
                Junior Producer and New Business
              </b-card-sub-title>
              <b-card-text>
                <b-link class="amarenared" v-b-modal.arimodal> BIO </b-link>
              </b-card-text>
            </b-card-body>
          </b-card>

          <b-card class="border-0 m-0 p-0">
            <b-card-body class="text-center p-0 m-0">
              <b-img
                src="~/assets/ste.jpg"
                class="rounded-circle imgteam"
              ></b-img>
              <b-card-title>Stefano Brandoni</b-card-title>
              <b-card-sub-title>
                Business and Marketing Strategist
              </b-card-sub-title>
              <b-card-text>
                <b-link class="amarenared" v-b-modal.stemodal> BIO </b-link>
              </b-card-text>
            </b-card-body>
          </b-card>
        </b-card-group>
        <b-container class="h80"></b-container>
        <b-container class="h80"></b-container>
      </b-col>
      <b-col md="2" cols="0"></b-col>
    </b-row>
    <b-modal
      ok-only
      hide-header-close
      id="amdpmodal"
      title="Alessandro Merletti De Palo"
    >
      <b-container class="text-center">
        <b-img
          src="~/assets/amdp.png"
          class="rounded-circle imgteam mb-3"
        ></b-img>
        <p class="t18" v-html="$t('team.amdp2')"></p>
        <p class="t18" v-html="$t('team.amdp3')"></p>
        <p class="t18" v-html="$t('team.amdp4')"></p>
        <p class="t18" v-html="$t('team.amdp5')"></p>
      </b-container>
    </b-modal>
    <b-modal ok-only hide-header-close id="giomodal" title="Giovanni Caloro">
      <b-container class="text-center">
        <b-img
          src="~/assets/gio.jpg"
          class="rounded-circle imgteam mb-3"
        ></b-img>
        <p class="t18" v-html="$t('team.gio2')"></p>
        <p class="t18" v-html="$t('team.gio3')"></p>
        <p class="t18" v-html="$t('team.gio4')"></p>
        <p class="t18" v-html="$t('team.gio5')"></p>
      </b-container>
    </b-modal>
    <b-modal ok-only hide-header-close id="ninamodal" title="Nina Gurgoglione">
      <b-container class="text-center">
        <b-img
          src="~/assets/nina.jpg"
          class="rounded-circle imgteam mb-3"
        ></b-img>
        <p class="t18" v-html="$t('team.nina2')"></p>
        <p class="t18" v-html="$t('team.nina3')"></p>
        <p class="t18" v-html="$t('team.nina4')"></p>
        <p class="t18" v-html="$t('team.nina5')"></p>
      </b-container>
    </b-modal>
    <b-modal ok-only hide-header-close id="arimodal" title="Arianna Giri">
      <b-container class="text-center">
        <b-img
          src="~/assets/ari.jpg"
          class="rounded-circle imgteam mb-3"
        ></b-img>
        <p class="t18" v-html="$t('team.ari2')"></p>
        <p class="t18" v-html="$t('team.ari3')"></p>
        <p class="t18" v-html="$t('team.ari4')"></p>
        <p class="t18" v-html="$t('team.ari5')"></p>
      </b-container>
    </b-modal>
    <b-modal ok-only hide-header-close id="stemodal" title="Stefano Brandoni">
      <b-container class="text-center">
        <b-img
          src="~/assets/ste.jpg"
          class="rounded-circle imgteam mb-3"
        ></b-img>
        <p class="t18" v-html="$t('team.ste2')"></p>
        <p class="t18" v-html="$t('team.ste3')"></p>
        <p class="t18" v-html="$t('team.ste4')"></p>
        <p class="t18" v-html="$t('team.ste5')"></p>
      </b-container>
    </b-modal>
  </b-container>
</template>

<script>
export default {
  async fetch({ store }) {
    await store.dispatch('getVideoAction')
    await store.dispatch('getBrandAction')
  },
}
</script>