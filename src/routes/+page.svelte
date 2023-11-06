<script>
  let User = "Admin";
  let welcome = "Welcome to your dashboard. Please select what you are about to do today from the menu on the left.";
  let downMessage = "Recruitment and Organization are still under development."
</script>

<section class="max-h-screen cursor-default bg-amber-200">
  <div class="flex flex-col items-center justify-center h-screen">
    <h1 class="text-6xl font-bold text-gray-900">Hello {User}</h1>
    <p class="mt-5 text-xl text-gray-600">{welcome}</p>
    <p class="mt-5 text-xl text-gray-600 line-through">{downMessage}</p>
  </div>
</section>

<div></div>

