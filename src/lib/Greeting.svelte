<script lang="ts">
  import Icon from "@iconify/svelte";
</script>

<main>
  <div class="greeting">
    <img
      class="pfp"
      src="../../pfp-filter.png"
      alt="Matteo Scaringi, with filter."
    />

    <div class="greeting-text">
      <h1>Hello there!</h1>
      <h3>I'm Matteo, your average developer and video editor.</h3>

      <div class="social-icons">
        <a href="" target="_blank"><Icon icon="ri:discord-fill" /></a>
        <a href="https://x.com/matte0_s" target="_blank"><Icon icon="ri:twitter-x-fill" /></a>
        <a href="https://github.com/matteoscaringi/" target="_blank"><Icon icon="ri:github-fill" /></a>
      </div>
    </div>
  </div>
</main>

<style lang="scss">
  @import "../app.css";

  main {
    background-color: #92afd7;
    height: 35vh;

    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;

    margin: 5px;
    border-radius: 5px;
  }

  .greeting {
    display: flex;
    flex-direction: row;

    justify-content: center;
    align-items: center;
  }

  .pfp {
    width: 281px;
    height: 281px;
    border-radius: 100%;
  }

  .greeting-text {
    margin-left: 30px;
    line-height: 10px;
    font-family: Montserrat, sans-serif;

    color: white;
  }

  a, a:visited {
    color: white;
    text-emphasis: none;
    transition-duration: 250ms;

    font-size: 30px;
  }

  a:hover {
    color: #6d6d6d;
    transition-duration: 250ms;
  }
</style>
