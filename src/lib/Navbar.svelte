<nav class="navbar">
  <ul class="left">
    <li><a href="#/">Home</a></li>
    <li><a href="#about">About</a></li>
  </ul>
</nav>

<style lang="scss">
  @import "../app.css";

  .navbar,
  ul {
    display: flex;
    align-items: center;
    gap: 20px;

    @media (max-width: 768px) {
      gap: 10px;
    }
  }

  .navbar {
    padding: 45px 50px;
    justify-content: space-between;

    background-color: #f6debf;

    @media (max-width: 768px) {
      padding: 30px 25px;
      justify-content: initial;
    }
  }

  ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  a {
    text-decoration: none;
    color: inherit;
    padding: 10px;
  }
</style>
