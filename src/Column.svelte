<script>
  import Task from "./Task.svelte";

  export let title;
  export let color = "orange";
</script>

<style>
  .min-height-400 {
    min-height: 400px;
  }
</style>

<div class="p-3 shadow-md bg-gray-200 bg-opacity-75 min-height-400 rounded-sm">
  <h4
    class="font-light text-white bg-{color}-400 py-3 text-center text-lg rounded-sm">
    {title}
  </h4>
  <button
    class="w-full my-3 py-1 text-blue-700 bg-blue-200 border-0 focus:outline-none focus:border-blue-600 rounded-sm">+
    New task</button>
  <Task {color} />
  <Task {color} />
</div>
