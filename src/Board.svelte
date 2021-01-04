<script>
  import Column from "./Column.svelte";
</script>

<div class="px-6">
  <h1 class="text-5xl font-light text-purple-700 text-right">BORG</h1>
  <div class="grid grid-cols-4 gap-6 my-4">
    <Column title="ToDo" color="blue" />
    <Column title="In Progress" color="purple" />
    <Column title="QA" />
    <Column title="Done" color="green" />
  </div>
</div>
