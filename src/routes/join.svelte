<main>
  <form action="">
    <label for="address">Contract's address</label>
    <input type="text" id="address" placeholder="0x123456789" />

    <label for="address">Contract's Name</label>
    <input type="text" id="name" placeholder="BAYC" />

    <button>Submit</button>
  </form>
</main>

<style lang="postcss">
  label {
    /* @apply text-bold; */
  }
  form {
    @apply flex flex-col space-y-4;
  }
</style>
