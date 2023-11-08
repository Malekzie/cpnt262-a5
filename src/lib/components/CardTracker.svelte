<script>
  export let position = "Position";
  export let recentPost = "0";
  export let applicantCount = "0";
  export let recentApplicants = "0";

  $: recentPost = parseInt(recentPost);
  $: applicantCount = parseInt(applicantCount);
  $: recentApplicants = Math.floor(applicantCount / 7 + 5);
</script>
  
  <div class="p-2 rounded-md cursor-pointer gradient w-80">
    <div class="ml-4">
      <h1 class="text-2xl text-white">{position}</h1>
      <p class="text-sm white">Posted {recentPost} days ago</p>
    </div>
    <div class="mt-5 ml-5">
      <span class="text-3xl">{applicantCount}</span>
       <span class="text-white">Applicants</span> 
       <span class="ml-10 text-sm text-blue-400">{recentApplicants} applied last week</span>
    </div>
  </div>

  

<style>
  
  .gradient{
    background: linear-gradient(90deg, rgb(15, 194, 39), rgb(37, 19, 141));
  }
</style>