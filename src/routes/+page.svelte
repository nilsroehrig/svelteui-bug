<script>
  import {SimpleGrid} from '@svelteuidev/core'
  const fruits = ["apple", "banana", "orange", "lemon"];
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<SimpleGrid cols={2}>
  {#each fruits as fruit}
    <div>{fruit}</div>
  {/each}
</SimpleGrid>
