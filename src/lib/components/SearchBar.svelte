<script>
  export let search = "Search";
</script>

<div class="top-nav">
  <div class="search-wrap">
    <input type="text" id="search-box" placeholder="{search}"><button class="search-button">Search</button>
  </div>
  <div class="buttons-wrap">
    
  </div>
</div>


<style>
  .top-nav{
    background-color: #151515;
    height: 80px;
    opacity: 98%;
    width: 100%;
    margin-left: 20%;
    position: sticky;
    top: 0;
    z-index: 100;
    border-bottom: 1px solid grey;
  }

  .search-wrap{
    margin-left: 2rem;
  }
  #search-box {
    margin: 2rem;
    width: 10%;
    border-radius: 5px;

  }

  .search-button{
    box-sizing: border-box;
    background-color: blue;
    padding-inline: 1rem;
    border-radius: 10px;
    color: white;
  }
  .search-button:hover{
    background-color: #151515;
    color: white;
    transition: 200ms ease-in-out;
  }

  </style>
