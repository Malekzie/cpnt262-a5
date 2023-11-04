<script>
</script>


<nav class="navbar">
  <h1><a href="/">Logo</a></h1>
  <ul> 
    <a href="/"><li>Dashboard</li></a>
    <a href="/messages"><li>Messages</li></a>
    <a href="/calendar"><li>Calendar</li></a>
  </ul>
    <p>Recruitment</p>
  <ul>
    <a href="/jobs"><li>Jobs</li></a>
    <a href="/candidate"><li>Candidates</li></a>
    <a href="/careers"><li>Career Site</li></a>
  </ul>
    <p>Organization</p>
  <ul>
    <a href="/employees"><li>Employees</li></a>
    <a href="/documents"><li>Documents</li></a>
    <a href="/reports
    "><li>Report</li></a>
  </ul>
</nav>

  <header>
    <h1 class="text-white">Hey there</h1>
  </header>

  <style>
    :root{
      --text-color: #898989;
      --gradient: linear-gradient(to right, #ff416c, #ff4b2b);
    }
    .navbar{
      box-sizing: border-box;
      width: 20%;
      background: #151515;
      display: flex;
      height: 100%;
      flex-direction: column;
      color: var(--text-color);
      position: sticky;
      position: fixed;
    }

    nav ul{
      display: flex;
      flex-direction: column;
      justify-content: space-evenly;
      height: 100%;
      list-style: none;
      padding: 20px;
    }
    nav h1{
      color: white;
      font-size: 1.5rem;
      padding: 1rem;
      margin: 0;
      border-bottom: var(--bb);
      text-align: center;
    }
    /* Logo Hover Effect */
    nav h1:hover{
      color: rgb(184, 178, 178);
      transition: 200ms ease-in-out;
    }

    nav ul li {
     padding: 1rem;
     border-radius: 10px;
    }
    /* Links Hover effect */
    nav ul li:hover{
      transition: 200ms ease-in-out;
      background: var(--gradient);
      color: white;
    }
    /* Description separators */
    nav p{
      color: var(--text-color);
      cursor: default;
      padding-left: 1rem;
    }


  </style>