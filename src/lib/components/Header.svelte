<script>
</script>

<div class="header__container">
  <header>
    <a href="/">
      <div class="header__wrapper">
        <img class="header__logo" src="/logo.png" alt="" />
        <h1>VeriDAO</h1>
      </div>
    </a>
  </header>
</div>

<style lang="postcss">
  .header__logo {
    @apply md:h-full max-h-20;
  }
  .header__container {
    @apply container relative mx-auto px-2;
  }

  a {
    text-decoration: none;
  }
  a:hover {
    @apply transition-all ease-in-out duration-500;
    @apply text-primary;
  }

  .header__wrapper {
    @apply flex flex-row items-center justify-items-center md:space-x-4 space-x-2 md:h-20 md:mt-8 mt-4;
    z-index: 100;
    width: 100%;
  }
</style>
