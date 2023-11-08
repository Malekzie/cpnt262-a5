<script>
  import { candidateInfo } from "../javascript/data";
  export let candidate;
</script>

<div class="flex flex-col justify-center gap-2 p-2 text-white align-middle transition ease-linear rounded-lg delay-50 bg-slate-700 hover:scale-105">
<img class="mx-auto rounded-md w-80" src={candidate.image} alt={candidate.name} />
<h1 class="text-2xl text-center">{candidate.name}</h1>
<p class="text-center">{candidate.description}</p>
<div class="flex flex-wrap justify-center gap-2 cursor-pointer">
  {#each candidate.skills.split(', ') as skill}
    <div class="p-2 text-sm transition delay-75 rounded-md hover:bg-slate-600 bg-slate-900 hover:scale-110">{skill}</div>
  {/each}
</div>
</div>
