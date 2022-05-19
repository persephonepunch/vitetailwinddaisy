<script>
  import logo from './assets/svelte.png'

</script>

<main>
  <button class="btn">Button</button>
  <button class="btn btn-primary">Button</button>
  <button class="btn btn-secondary">Button</button>
  <button class="btn btn-accent">Button</button>
  <button class="btn btn-ghost">Button</button>
  <button class="btn btn-link">Button</button>


  <ul class="menu bg-base-100 w-56">
    <li><a>Item 1</a></li>
    <li><a class="active">Item 2</a></li>
    <li><a>Item 3</a></li>
  </ul>

</main>

<style global lang="postcss">
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
