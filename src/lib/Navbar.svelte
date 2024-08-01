<nav class="navbar">
  <ul class="left">
    <li><a href="#/">Home</a></li>
    <li><a href="#about">About</a></li>
  </ul>
</nav>

<style lang="scss">
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
    padding: 25px;
    padding-left: 60px;
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
    transition: 250ms;
  }

  a:hover {
    color: #6d6d6d;
    transition: 250ms;
  }
</style>
