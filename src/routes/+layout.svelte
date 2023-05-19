<script>
    import "../app.css";
    let image = '';
  </script>
  
  <slot />

  <main class="md:container md:mx-auto">
    <div class="flex flex-col md:flex-row">
        <!-- Sidebar -->
        <div class="bg-gray-800 text-white md:w-1/5">
          <!-- Sidebar content goes here -->
        </div>
      
        <!-- Main content -->
        <div class="flex-1 bg-gray-100">
          <!-- Main content goes here -->
        </div>
      </div>
  </main>
  <!-- <div class="container mx-auto bg-gray-200 rounded-xl shadow border p-8 m-10">
    <p class="text-3xl text-gray-700 font-bold mb-5">
       Welcome!
    </p>
    <p class="text-gray-500 text-lg">
       SvelteKit and Tailwind CSS in action
    </p>
</div>
<div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
    <div class="md:flex">
      <div class="md:shrink-0">
        <img class="h-48 w-full object-cover md:h-full md:w-48" src="{image}" alt="Modern building architecture">
      </div>
      <div class="p-8">
        <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Company retreats</div>
        <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Incredible accommodation for your team</a>
        <p class="mt-2 text-slate-500">Looking to take your team away on a retreat to enjoy awesome food and take in some sunshine? We have a list of places to do just that.</p>
      </div>
    </div>
  </div> -->