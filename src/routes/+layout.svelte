<nav>
  <a href="/">home</a>
  <a href="/target#10">#10</a>
  <a href="/target#20">#20</a>
  <a href="/target#30">#30</a>
</nav>

<div>
  <slot />
</div>

<style>
  nav {
    position: fixed;
    top: 0;
    left: 0;

    display: flex;
    flex-direction: column;
    gap: 1em;

    padding: 1em;
    width: 5em;
    height: 100%;

    background-color: lightgrey;
  }

  div {
    margin-left: 5em;
  }
</style>
