<template>
  <div>
    
    <section style="position: relative;">
      

      <div class="center">
        <center>

          <h1 style="font-size: 3em; margin-bottom: 0;">Project Links</h1>
          
          <div style="color: #999">
            <p style="margin-bottom: 1em;">Links to the project and it's developers</p>
          </div>

          <v-btn class="mainAltButton" :href="githubLink" target="_blank">
            <v-icon style="margin-right: 0.5em;">mdi-github</v-icon>
            Github
          </v-btn>

          <v-btn class="mainAltButton" :href="discordLink" target="_blank">
            <v-icon style="margin-right: 0.5em;">mdi-discord</v-icon>
            Discord
          </v-btn>

          <h1 style="margin-top: 1em;">Contact Me</h1>

          <v-btn class="mainAltButton" :href="emailLink" target="_blank">
            <v-icon style="margin-right: 0.5em;">mdi-email</v-icon>
            Email
          </v-btn>

        </center>
      </div>


    </section>

    <p id="credits">Site by <v-icon color="#555">mdi-discord</v-icon> Front#2990.</p>

  </div>
</template>

<style scoped>
#credits {
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translate(-50%,0);
  color: #555;
}
</style>

<script>
export default {
  data() {
    return {
      githubLink: "https://github.com/Anarios/return-youtube-dislike",
      discordLink: "https://discord.gg/mYnESY4Md5",

      emailLink: "mailto:selivano.d@gmail.com "
    }
  }
}
</script>