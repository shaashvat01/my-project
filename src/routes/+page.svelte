<script>
  export let data;
</script>

<div class="container">
  <div class="content bg-black bg-opacity-50 p-10 rounded-lg">
    <h1 class="text-5xl font-bold mb-4 text-white">Welcome to Our Travel Blog</h1>
    <p class="text-xl mb-8 text-white">Explore recent travel stories and adventures from around the world.</p>
  </div>
</div>

<style>
  body, html {
    height: 100%;
    margin: 0;
  }
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-image: url('/travel-bg.jpg');
    background-size: cover;
    background-position: center;
  }
  .content {
    text-align: center;
  }
</style>
