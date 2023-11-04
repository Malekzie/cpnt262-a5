<script>
    import "../app.css";
    import NavBar from "../lib/components/NavBar.svelte";
  </script>
 
 <NavBar />

 <div class="margin">
   <slot />
 </div>

 <style>
    .margin {
      margin-left: 20%;
    }
 </style>