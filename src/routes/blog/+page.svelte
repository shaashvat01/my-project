<script>
  export let data;
</script>

<div class="h-screen flex items-center justify-center px-4">
  <div class="max-w-4xl mx-auto py-10">
    <h1 class="text-4xl font-bold mb-6 text-center">My Blogs</h1>
    <ul class="flex flex-wrap justify-between gap-6">
      <li class="flex-1 min-w-[250px] mb-4 p-4 bg-white shadow-md rounded-lg">
        <h2 class="text-2xl font-bold">Exploring the Alps</h2>
        <p>A breathtaking journey through the Swiss Alps...</p>
        <div class="flex justify-center">
          <div class="w-[300px] h-[200px] overflow-hidden rounded-lg shadow-md">
            <img src="/alps.jpg" alt="Alps" class="w-full h-full object-cover"/>
          </div>
        </div>
        <a href="" class="text-blue-600 hover:underline" target="_blank">Read more</a>
      </li>

      <li class="flex-1 min-w-[250px] mb-4 p-4 bg-white shadow-md rounded-lg">
        <h2 class="text-2xl font-bold">Exploring beach adventures in Bali</h2>
        <p>Enjoy and relax at the beach</p>
        <div class="flex justify-center">
          <div class="w-[300px] h-[200px] overflow-hidden rounded-lg shadow-md">
            <img src="/bali.jpg" alt="Bali" class="w-full h-full object-cover"/>
          </div>
        </div>
        <a href="" class="text-blue-600 hover:underline" target="_blank">Read more</a>
      </li>

      <li class="flex-1 min-w-[250px] mb-4 p-4 bg-white shadow-md rounded-lg">
        <h2 class="text-2xl font-bold">Discovering Tokyo</h2>
        <p>Explore the famous city of Tokyo.</p>
        <div class="flex justify-center">
          <div class="w-[300px] h-[200px] overflow-hidden rounded-lg shadow-md">
            <img src="/tokyo.jpg" alt="Tokyo" class="w-full h-full object-cover"/>
          </div>
        </div>
        <a href="" class="text-blue-600 hover:underline" target="_blank">Read more</a>
      </li>
    </ul>
  </div>
</div>
