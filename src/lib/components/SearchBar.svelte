
<script>
  export let currentPage = "Current Page";
  export let search = "Search";
  
</script>

<div class="top-nav">
  <div class="current-wrap">
    <h1 class="m-6 text-2xl text-white cursor-default">{currentPage}</h1>
  </div>
  <div class="search-wrap">
    <input type="text" id="search-box" placeholder="{search}"><button class="search-button">Search</button>
  </div>
</div>


<style>
  .top-nav{
    background-color: #151515;
    height: 80px;
    opacity: 98%;
    width: 100%;
    position: sticky;
    top: 0;
    z-index: 100;
    border-bottom: 1px solid grey;
    display: flex;
    justify-content: space-evenly;
  }

  .current-wrap{
    display: inline;
  }

  #search-box {
    margin: 2rem;
    width: 15rem;
    border-radius: 5px;
  }
  #search-box {
    background-image: url('/images/search-icon.svg');
    background-repeat: no-repeat;
    background-position: left 10px center;
    background-size: 20px 20px;
    padding-inline: 30px; 
  }

  .search-button{
    box-sizing: border-box;
    background-color: blue;
    padding-inline: 1rem;
    border-radius: 10px;
    color: white;
  }
  .search-button:hover{
    scale: 105%;
    color: purple;
  }
  </style>
