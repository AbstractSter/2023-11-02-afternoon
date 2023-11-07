<script>
  export let title;
  export let description;
  export let button;
  export let img;
</script>

<article class="m-5 bg-yellow-50">
  <div class="my-5 bg-pink-50"></div>
  <h2>{title}</h2>
  <img src={img} alt="Sterling's Paintings">
  <p>{description}</p>
  <button>{button}</button>
</article>