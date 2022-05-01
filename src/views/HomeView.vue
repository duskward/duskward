<template>
  <div>
    <v-img
      class="hero"
      ratio="16/9"
      max-height="1080"
      max-width="1920"
      lazy-src="https://media.discordapp.net/attachments/966490232147030036/970240468401152031/Duskward_png_vin720.png"
      src="https://media.discordapp.net/attachments/966490232147030036/970238546424242187/Duskward_comingsoon_vin720.gif">
      <template v-slot:placeholder>
        <v-img
          class="hero"
          ratio="16/9"
          max-height="1080"
          max-width="1920"
          lazy-src="https://media.discordapp.net/attachments/966490232147030036/970240468401152031/Duskward_png_vin720.png"
          src="https://media.discordapp.net/attachments/966490232147030036/970240468401152031/Duskward_png_vin720.png" />
      </template>
    </v-img>
    <v-container class="text-center mb-16">
      <!-- eslint-disable max-len -->
      <h1 class="my-8 pt-8">FAQ</h1>
      <h2 class="my-2 font-weight-medium mx-16">What is Duskward?</h2>

      <p class="body-1 font-weight-light mb-8 mx-16">Duskward is a vtuber project driven by world building, interconnected characters, and a living story. Duskward is a passion project from the ground up created by vtubers that love the art and culture of vtubing. We are not a corporation or an agency, we are like minded individuals that share a common goal of expanding the medium of vtubing.</p>
      <h2 class="my-2 font-weight-medium mx-16">Who are the members of Duskward?</h2>
      <p class="body-1 font-weight-light mb-8 mx-16">The members of Duskward are currently Seiryu Komatsu, Shimada Tiger, Winter Sionnach, Evevivig, and Hoshino Charlotte along with various members of staff teams. All of these members provide unique experiences and talents; familiarize yourself with each as their stories unfold! They have been hand selected to keep the world of Duskward authentically connected. There is a possibility of future members, however Duskward will be focused on these five for the foreseeable future.</p>
      <h2 class="my-2 font-weight-medium mx-16">What type of content will Duskward create?</h2>
      <p class="body-1 font-weight-light mb-8 mx-16">Each member of Duskward provides a unique streaming experience from one another, but streaming is only where Duskward content begins. Duskward seeks to break the mold and create new ways for fans to enjoy and interact with their favorite vtubers. From comics, to writing, to music, merchandise, and even video games, Duskward content will go beyond the streaming medium. We plan to release character profiles and mixed media lore chapters for each member over time soon!</p>
      <h2 class="my-2 font-weight-medium mx-16">Where can I find Duskward content and information?</h2>
      <p class="body-1 font-weight-light mb-8 mx-16">The official Duskward twitter and Duskward website will act as hubs for all Duskward news and content. Each individual member also has their own Twitter and streaming channels.
      <span class="d-block"><a href="https://twitter.com/duskward">https://twitter.com/duskward</a></span>
      <span class="d-block"><a href="https://duskward.live">https://duskward.live</a></span>
      </p>
    <!-- eslint-enable max-len -->
    </v-container>
  </div>
</template>

<script>
// import HelloWorld from '../components/HelloWorld';

export default {
  name: 'HomeView',

  components: {
    // HelloWorld,
  },
};
</script>

<style lang="scss" scoped>
.hero {
  overflow: hidden;
}
</style>
