<script>
  import { candidateInfo } from "../javascript/data"
</script>

<div class="w-3/12 text-white transition duration-300 rounded-md bg-slate-600 hover:scale-95">
  {#each candidateInfo as {name, description, skills, image}}
  <div>
    <img src={image} alt={name} />
    <h1 class="text-center">{name}</h1>
    <p class="text-center">{description}</p>
    <div class="flex flex-wrap justify-center gap-2">
      <div class="p-2 text-sm rounded-md bg-slate-700">{skills}</div>
    </div>
  </div>
  {/each}
</div>