<script>
    import CardTracker from "../../lib/components/CardTracker.svelte";
    import SearchBar from "../../lib/components/SearchBar.svelte";
    import Candidate from "../../lib/components/Candidate.svelte";
</script>

<SearchBar currentPage="Dashboard" />
<section>
    <h1 class="text-3xl title">Overview</h1>
    <div class="flex justify-evenly">
        <CardTracker position="Sr. Web Developer" recentPost="10" applicantCount="65" />
        <CardTracker position="UI/UX Designer" recentPost="30+" applicantCount="33"/>
        <CardTracker position="Data Analyst" recentPost="30+" applicantCount="75"/>
    </div>
</section>

<section>
    <h1 class="text-3xl title">Candidates</h1>
    <div class="flex flex-wrap gap-2 justify-evenly">
        <Candidate {candidate1}/>
    </div>
</section>


<style>

    .title{
        margin: 2rem;
        cursor: default;
    }

</style>