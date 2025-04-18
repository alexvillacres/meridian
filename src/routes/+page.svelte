
<script>
    let data = $props();
  </script>
  
  <h1 class="text-2xl font-bold">Countries</h1>
  <ul>
    {#each data.countries as country}
      <li>{country.name}</li>
    {/each}
  </ul>
  