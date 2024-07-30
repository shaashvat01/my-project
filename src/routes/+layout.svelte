<script>
    import { page } from '$app/stores';
</script>

<nav class="bg-blue-600 p-4 shadow-md">
  <ul class="text-white flex justify-center space-x-8">
    <li><a href="/" class="text-white hover:underline">Home</a></li>
    <li><a href="/blog" class="text-white hover:underline">Blog </a></li>
    <li><a href="/resources" class="text-black hover:underline">Resources </a></li>
  </ul>
</nav>

<main>
  <slot />
</main>

<style>
  nav ul {
    display: flex;
    justify-content: center;
    list-style-type: none;
    padding: 0;
    margin: 0;
  }
  nav li {
    display: inline;
  }
  nav a {
    text-decoration: none;
  }
</style>
