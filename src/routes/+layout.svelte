<script>
    import "../app.css";
  </script>
  
  <header class="bg-slate-500">
    <nav>
      <ul class="flex justify-center gap-5 py-5">
        <li class="transition-colors hover:text-purple-600"><a href="">Home</a></li>
        <li class="transition-colors hover:text-purple-600"><a href="">About</a></li>
        <li class="transition-colors hover:text-purple-600"><a href="">Prices</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <slot />
  </main>
  <footer>
    <p class="py-5 text-center text-white bg-slate-500">This is the footer</p>
  </footer>