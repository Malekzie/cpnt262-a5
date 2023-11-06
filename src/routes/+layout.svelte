<script>
    import "../app.css";
    import NavBar from "../lib/components/NavBar.svelte";
    import SearchBar from "../lib/components/SearchBar.svelte";
  </script>
 
 <NavBar />
<SearchBar />
 <div class="margin">
   <slot />
 </div>

 <style>
    .margin {
      margin-left: 20%;
    }
 </style>