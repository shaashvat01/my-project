<script>
  import { page } from '$app/stores';
</script>

<nav class="navbar w-full bg-white p-4 shadow-md flex justify-center">
<ul class="nav-links flex space-x-8">
  <li><a href="/" class="nav-link">Home</a></li>
  <li><a href="/blog" class="nav-link">Blogs</a></li>
  <li><a href="/resources" class="nav-link">Resources</a></li>
</ul>
</nav>

<main>
<slot />
</main>

<style>
nav {
  width: 100%;
}
.nav-links {
  list-style-type: none;
  padding: 0;
  margin: 0;
  display: flex;
  justify-content: center;
}
.nav-link {
  color: black;
  text-decoration: none;
  font-size: 1.25rem; 
  margin-right: 2rem;
}
.nav-link:hover {
  text-decoration: underline;
}
</style>
