<script>
  import Content from "./content/Content.svelte";
  import Tagbar from "./tagbar/Tagbar.svelte";
  import Addsbar from "./addbar/Addsbar.svelte";
</script>

<main>
  <Tagbar />
  <Content />
  <Addsbar />
</main>

<style>
  main {
    display: grid;
    grid-template-columns: 1fr 5fr 1fr;
  }
</style>