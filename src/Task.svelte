<script>
  export let color;
</script>

<div
  class="bg-white h-24 border-r-4 border-{color}-400 p-2 rounded-sm grid grid-cols-2 my-3 shadow">
  <h4 class="font-bold text-l">Feature X</h4>
  <div class="flex flex-row-reverse justify-end">
    <div
      class="bg-cover bg-center w-10 h-10 rounded-full border-4 border-white -mr-3"
      style="background-image: url(https://images.unsplash.com/photo-1530424426433-967ce567454d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=60)" />
    <div
      class="bg-cover bg-center w-10 h-10 rounded-full border-4 border-white -mr-3"
      style="background-image: url(https://images.unsplash.com/photo-1525879000488-bff3b1c387cf?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=300&q=60)" />
    <div
      class="bg-cover bg-center w-10 h-10 rounded-full border-4 border-white -mr-3"
      style="background-image: url(https://images.unsplash.com/photo-1521132293557-5b908a59d1e1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=300&q=60)" />
  </div>
  <span class="col-span-2 text-gray-700">Description...</span>
</div>
