<template>
  <div>
    <basic-card v-bind:lnk="'https://github.com/alexarlord-boop/alexarlord-web'" class="golographic">
      <template v-slot:image>
        <svg xmlns="http://www.w3.org/2000/svg" width="7rem" height="7rem" fill="currentColor" class="bi bi-arrows-fullscreen m-3" viewBox="0 0 16 16">
          <path fill-rule="evenodd" d="M5.828 10.172a.5.5 0 0 0-.707 0l-4.096 4.096V11.5a.5.5 0 0 0-1 0v3.975a.5.5 0 0 0 .5.5H4.5a.5.5 0 0 0 0-1H1.732l4.096-4.096a.5.5 0 0 0 0-.707zm4.344 0a.5.5 0 0 1 .707 0l4.096 4.096V11.5a.5.5 0 1 1 1 0v3.975a.5.5 0 0 1-.5.5H11.5a.5.5 0 0 1 0-1h2.768l-4.096-4.096a.5.5 0 0 1 0-.707zm0-4.344a.5.5 0 0 0 .707 0l4.096-4.096V4.5a.5.5 0 1 0 1 0V.525a.5.5 0 0 0-.5-.5H11.5a.5.5 0 0 0 0 1h2.768l-4.096 4.096a.5.5 0 0 0 0 .707zm-4.344 0a.5.5 0 0 1-.707 0L1.025 1.732V4.5a.5.5 0 0 1-1 0V.525a.5.5 0 0 1 .5-.5H4.5a.5.5 0 0 1 0 1H1.732l4.096 4.096a.5.5 0 0 1 0 .707z"/>
        </svg>
      </template>
      <template v-slot:small-icon>
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="#fff" class="bi bi-github"
             viewBox="0 0 16 16">
          <path
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
        </svg>
      </template>
      <template v-slot:title>This Website</template>
      <template v-slot:text>
        I specialize in creating advanced applications that solves real-world problems and offer exceptional user experience.
        The website is a hub for my projects, that I really enjoyed working on.

      </template>
      <template v-slot:tooltips>
        <tool-tip>Vue.js</tool-tip>
        <tool-tip>Bootstrap</tool-tip>
        <tool-tip>Github Pages</tool-tip>
        <tool-tip>CI</tool-tip>
        <tool-tip>CD</tool-tip>
      </template>
    </basic-card>
  </div>
</template>

<script>

import BasicCard from "@/components/cards/BasicCard.vue";
import Tooltip from "@/components/Tooltip.vue";
export default {
  name: "WebSiteCard",
  components: {
    'basic-card': BasicCard,
    'tool-tip': Tooltip
  }
}
</script>

<style lang="sass">

</style>