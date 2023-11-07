<script>
  import Card from "$lib/Card.svelte";

  const cardObj = [{
      title: 'Image title',
      description: 'This is a painting',
      button: 'This is button text',
      img: 'https://picsum.photos/seed/picsum/200/300'
  },
  {
      title: 'Image title',
      description: 'This is a painting',
      button: 'This is button text',
      img: 'https://picsum.photos/seed/picsum/200/300'
  },
 {
      title: 'Image title',
      description: 'This is a painting',
      button: 'This is button text',
      img: 'https://picsum.photos/seed/picsum/200/300'
  }]
</script>

<header>
  <h1>Hello World! - SvelteKit Edition</h1>
</header>
<p>This is my honest attempt at SvelteKit</p>

{#each cardObj as card}
  <Card {...card}/>
{/each}



