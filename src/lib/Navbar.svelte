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

    transition-duration: 250ms;
    
    @media (max-width: 768px) {
      gap: 10px;

      transition-duration: 250ms;
    }
  }

  .navbar {
    padding: 25px;
    padding-left: 60px;
    background-color: #f6debf;

    transition-duration: 250ms;

    @media (max-width: 768px) {
      padding: 30px 25px;
      justify-content: initial;

      transition-duration: 250ms;
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
