<template>
  <v-container style="height: 5000px">
    <v-row class="text-center tw-my-10">
      <v-col cols="12">

        <div class="meet tw-font-bold text-uppercase animate__animated animate__rubberBand animate__delay-1s" style="color: ivory; font-size: large">
          Meet
        </div>

        <v-img
            :src="require('../assets/02.svg')"
            class="my-3 animate__animated animate__fadeInDownBig animate__delay-2s"
            height="200"
        />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-1 font-weight-medium mb-3 text--disabled animate__animated animate__backInUp animate__delay-3s">
          A driven enthusiastic software development techie. I am self driven to find myself loving how to do OOP and solve problems.
        </h1>

        <!--        <p class="subheading font-weight-regular">-->
        <!--          For help and collaboration with other Vuetify developers,-->
        <!--          <br>please join our online-->
        <!--          <a-->
        <!--            href="https://community.vuetifyjs.com"-->
        <!--            target="_blank"-->
        <!--          >Discord Community</a>-->
        <!--        </p>-->
      </v-col>

      <v-col
          class="mb-5"
          cols="12"
      >
        <!--        <h2 class="headline font-weight-bold mb-3">-->
        <!--          What's next?-->
        <!--        </h2>-->

        <v-row justify="center">
          <!--          <a-->
          <!--            v-for="(next, i) in whatsNext"-->
          <!--            :key="i"-->
          <!--            :href="next.href"-->
          <!--            class="subheading mx-3"-->
          <!--            target="_blank"-->
          <!--          >-->
          <!--            {{ next.text }}-->
          <!--          </a>-->
        </v-row>
      </v-col>

      <v-col
          class="mb-5"
          cols="12"
      >
        <!--        <h2 class="headline font-weight-bold mb-3">-->
        <!--          Important Links-->
        <!--        </h2>-->

        <v-row justify="center">
          <!--          <a-->
          <!--            v-for="(link, i) in importantLinks"-->
          <!--            :key="i"-->
          <!--            :href="link.href"-->
          <!--            class="subheading mx-3"-->
          <!--            target="_blank"-->
          <!--          >-->
          <!--            {{ link.text }}-->
          <!--          </a>-->
        </v-row>
      </v-col>

      <v-col
          class="mb-5"
          cols="12"
      >
        <!--        <h2 class="headline font-weight-bold mb-3">-->
        <!--          Ecosystem-->
        <!--        </h2>-->

        <v-row justify="center">
          <!--          <a-->
          <!--            v-for="(eco, i) in ecosystem"-->
          <!--            :key="i"-->
          <!--            :href="eco.href"-->
          <!--            class="subheading mx-3"-->
          <!--            target="_blank"-->
          <!--          >-->
          <!--            {{ eco.text }}-->
          <!--          </a>-->
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import 'animate.css';
export default {
  name: 'HelloWorld',

  data: () => ({
    ecosystem: [
      {
        text: 'vuetify-loader',
        href: 'https://github.com/vuetifyjs/vuetify-loader',
      },
      {
        text: 'github',
        href: 'https://github.com/vuetifyjs/vuetify',
      },
      {
        text: 'awesome-vuetify',
        href: 'https://github.com/vuetifyjs/awesome-vuetify',
      },
    ],
    importantLinks: [
      {
        text: 'Documentation',
        href: 'https://vuetifyjs.com',
      },
      {
        text: 'Chat',
        href: 'https://community.vuetifyjs.com',
      },
      {
        text: 'Made with Vuetify',
        href: 'https://madewithvuejs.com/vuetify',
      },
      {
        text: 'Twitter',
        href: 'https://twitter.com/vuetifyjs',
      },
      {
        text: 'Articles',
        href: 'https://medium.com/vuetify',
      },
    ],
    whatsNext: [
      {
        text: 'Explore components',
        href: 'https://vuetifyjs.com/components/api-explorer',
      },
      {
        text: 'Select a layout',
        href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
      },
      {
        text: 'Frequently Asked Questions',
        href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
      },
    ],
  }),
}
</script>

<style>
.meet {
  /*position: absolute;*/
  /*top: 10%;*/
  /*bottom: 90%;*/
  z-index: 2;

}
</style>