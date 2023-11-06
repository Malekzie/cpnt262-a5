<script>
    import CardTracker from "../../lib/components/CardTracker.svelte";
</script>

<section class="dash-grid">
    <div>
        <CardTracker numberTracker="0" trackerDescription="Total de casos confirmados" />
    </div>
</section>


<style>
    .dash-grid{
        display: grid;
        grid-template-columns: repeat(6, 1fr);
        grid-template-rows: repeat(6, 1fr);
    }
</style>