<script>
  import Board from "./Board.svelte";
</script>

<style global>
  /* purgecss start ignore */
  @tailwind base;
  @tailwind components;
  /* purgecss end ignore */

  @tailwind utilities;

  main {
    height: 100%;
  }
</style>

<main>
  <Board />
</main>
