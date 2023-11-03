<script>
  const navItems = [
    {name: 'Home', href: '/', styling: "text-red-500 hover:text-purple-500"},
    {name: 'Price', href: '/', styling: "text-red-500 hover:text-purple-500"},
    {name: 'About', href: '/about', styling: "text-red-500 hover:text-purple-500"},
    {name: 'Contact', href: '/', styling: "text-red-500 hover:text-purple-500"}
  ];
</script>

<header class="flex justify-between m-5">
  <div>Logo</div>
  <ul class="flex gap-5">
    {#each navItems as {name, href, styling}}
    <li><a {href} {styling}> {name} </a></li>
    {/each}
  </ul>
</header>