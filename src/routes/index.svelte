<script lang="ts">
</script>

<svelte:head>
  <title>VeriDAO</title>
</svelte:head>

<main>
  <section>
    <div class="hero">
      <p class="subtitle">Decentralising NFT collections verification</p>
      <img src="/centralised2decentralised.png" alt="" />
    </div>
  </section>
  <section class="actions">
    <h2>Join us</h2>
    <p>
      Reach out to <a
        href="https://twitter.com/serglotz"
        rel="external noopener"
        target="_blank">Sergej</a
      >,
      <a
        href="https://twitter.com/veri_dao"
        rel="external noopener"
        target="_blank">Robin</a
      >,
      <a
        href="https://twitter.com/EthereumExperi1"
        rel="external noopener"
        target="_blank">Conor</a
      >
      or
      <a
        href="https://twitter.com/agraignic"
        rel="external noopener"
        target="_blank">Anthony</a
      >
    </p>
  </section>

  <section>
    <h2>A truly decentralized process</h2>
    <h3><span class="number">1.</span> Submit</h3>
    <p>
      Submit your NFT collection based on your smartcontract address to get
      verified ! 0 personal info asked.
    </p>
    <p>
      Either if you are an artist or a collector, verifying your collection will
      protect it from scams, duplicate and legitimise it so that it is worth
      more.
    </p>
    <h3><span class="number">2.</span> Vote</h3>
    <p>
      Mobilize your community members to vote for your collection to speed up
      the verification and incentivize them !
    </p>
    <h3><span class="number">3.</span> Challenge</h3>
    <p>
      If you find a collection that doesn't match the guidelines, is a scam, a
      duplicate or has flaws in its contract, <b>challenge it</b> and get the staked
      bounty !
    </p>
    <p>
      A dispute will be open in <a
        href="https://kleros.io/"
        rel="external noopener"
        target="_blank">Kleros</a
      >, for a completely decentralized arbitration.
    </p>
    <h3><span class="number">4.</span> Get listed</h3>
    <p>
      Once a collection is verified, it's automatically added to our API,
      website and propagate to our partners marketplaces.
    </p>
  </section>

  <br />
</main>

<style lang="postcss">
  main {
    @apply container;
  }

  section {
    @apply mt-4;
  }

  .hero {
    @apply flex flex-col justify-center items-center space-y-8;
  }
  .hero img {
    @apply w-1/3;
  }

  .subtitle {
    @apply text-lg font-bold;
  }

  .number {
    @apply text-primary;
  }

  .actions {
    @apply flex flex-col justify-items-center justify-around md:mt-8 mt-4 space-y-8;
  }

  h2 a {
    text-decoration: none;
  }

  a:hover {
    /* text-decoration: underline; */
    @apply transition-all ease-in-out duration-500;
    /* @apply bg-clip-text text-transparent bg-gradient-to-r from-primary to-blue-200; */
    @apply text-primary;
  }
</style>
