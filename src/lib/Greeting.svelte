<script lang="ts">
  import Icon from "@iconify/svelte";
  import Navbar from "./Navbar.svelte";
</script>

<main>
  <div class="greeting">
    <div class="greeting-text">
      <h1>Hello there!</h1>
      <h3>I'm Matteo, your passionate developer and video editor.</h3>

      <div class="social-icons">
        <a href="" target="_blank"><Icon icon="ri:discord-fill" /></a>
        <a href="https://x.com/matte0_s" target="_blank"
          ><Icon icon="ri:twitter-x-fill" /></a
        >
        <a href="https://github.com/matteoscaringi/" target="_blank"
          ><Icon icon="ri:github-fill" /></a
        >
      </div>
    </div>

    <img class="pfp" src="../../pfp.png" alt="Matteo Scaringi, with filter." />
  </div>
</main>

<style lang="scss">
  @import "../app.css";

  main {
    background-color: #f6debf;
    height: 35vh;

    display: flex;
    flex-direction: row;
    align-items: center;

    transition-duration: 250ms;

    @media screen and (max-width: 768px) {
      height: 60vh;

      transition-duration: 250ms;
    }
  }

  .greeting {
    display: flex;
    flex-direction: row;
    width: 100%;

    padding-left: 65px;
    padding-right: 65px;

    justify-content: space-between;
    align-items: center;

    transition-duration: 250ms;

    @media screen and (max-width: 768px) {
      flex-direction: column-reverse;
      justify-content: center;


      padding-top: 15px;

      padding-left: 0px;
      padding-right: 0px;

      width: 100%;
      height: 55vh;

      transition-duration: 250ms;
    }
  }

  .pfp {
    width: 251px;
    height: 251px;
    border-radius: 100%;

    transition-duration: 250ms;

    @media screen and (max-width: 768px) {
      width: 200px;
      height: 200px;

      padding-bottom: 30px;

      transition-duration: 250ms;
    }
  }

  .greeting-text {
    font-family: Montserrat, sans-serif;
    color: black;

    transition-duration: 250ms;

    @media screen and (max-width: 768px) {
      text-align: center;
      max-width: 65%;

      font-size: 14px;

      transition-duration: 250ms;
    }
  }

  .social-icons{
    margin-top: 10px;


    transition-duration: 250ms;

    @media screen and (max-width: 768px) {
      padding-bottom: 15px;
      margin-top: 20px;

      transition-duration: 250ms;
    }
  }

  h1 {
    padding-bottom: 8px;
  }
    
  h3, h1 {
    margin-top: 0px;
    margin-bottom: 0px;
  }

  a,
  a:visited {
    color: black;
    text-emphasis: none;
    transition-duration: 250ms;

    font-size: 30px;
  }

  a:hover {
    color: #6d6d6d;
    transition-duration: 250ms;
  }
</style>
