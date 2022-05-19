<script>
 
  import {fade} from 'svelte/transition';
  export let name="Peter";


</script>

<main>
  <div class="flex flex-col flex-1">
  <button class="btn">Button</button>
  <button class="btn btn-primary">Button</button>
  <button class="btn btn-secondary">Button</button>
  <button class="btn btn-accent">Button</button>
  <button class="btn btn-ghost">Button</button>
  <button class="btn btn-link">Button</button>


  <h1>Hello {name}</h1>

  <img src="https://hagenblack-11ty.netlify.app/assets/images/jane-beiles-9456-2-p-1080.jpeg" class="max-w-full h-auto" alt="..." />

  <ul class="menu bg-base-100 w-56">
    <li><a>Item 1</a></li>
    <li><a class="active">Item 2</a></li>
    <li><a>Item 3</a></li>
  </ul>
</div>

</main>


