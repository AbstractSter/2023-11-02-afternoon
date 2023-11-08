<script>
  import {cardObj} from "../lib/data.js";
  
  import Card from "../lib/components/Card.svelte";
  
</script>

<header>
  <h1>Hello World! - SvelteKit Edition</h1>
</header>
<p>This is my honest attempt at SvelteKit</p>

{#each cardObj as card}
  <Card {...card}/>
{/each}




