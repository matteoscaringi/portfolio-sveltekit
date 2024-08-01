<script lang="ts">
  import Greeting from "./lib/Greeting.svelte";
  import About from "./lib/About.svelte";
  import Navbar from "./lib/Navbar.svelte";
</script>

<Navbar />
<Greeting />
<About />

<style lang="scss">
  :global(body) {
    background-color: #cfaf92;
    font-family: Montserrat, sans-serif;
    font-weight: 500;
  }
</style>