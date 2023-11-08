<script>
  import { candidateInfo } from "../javascript/data"
  export let name = "Candidate Name"
  export let description = "Candidate Description"
  export let skills = "Candidate Skills"
  export let image = "Candidate Image"
</script>

<div class="w-3/12 text-white transition duration-300 rounded-md bg-slate-600 hover:scale-105">
  {#each candidateInfo as {name, description, skills, image}}
  <div>
    <img src={image} alt={name} />
    <h1>{name}</h1>
    <p>{description}</p>
    <div class="flex flex-wrap gap-2">
      <div class="p-2 text-sm rounded-md bg-slate-700">{skills}</div>
    </div>
  </div>
  {/each}
</div>