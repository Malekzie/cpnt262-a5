<script>
  export let numberTracker = 0;
  export let trackerDescription = "Descrição do tracker";
</script>

<div class="trackerCard">
    <h1>{numberTracker}</h1>
    <p>{trackerDescription}</p>
</div>


<style>
  .trackerCard{
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.2);
    padding: 20px;
    text-align: center;
  }
</style>