<script>
</script>


<nav class="navbar">
  <h1><a href="/">Logo</a></h1>
  <ul>
    <li><a href="/">Dashboard</a></li>
    <li><a href="/messages">Messages</a></li>
    <li><a href="/calendar">Calendar</a></li>
    <p>Recruitment</p>
    <li><a href="/jobs">Jobs</a></li>
    <li><a href="/candidate">Candidates</a></li>
    <li><a href="/referrals">Referrals</a></li>
    <li><a href="/careers">Career Site</a></li>
    <p>Organization</p>
    <li><a href="/employees">Employees</a></li>
    <li><a href="/documents">Documents</a></li>
    <li><a href="/reports">Reports</a></li>
  </ul>
</nav>

  <style>
    :root{
      --bb: 2px solid rgb(184, 178, 178);
      --gradient: linear-gradient(to right, #ff416c, #ff4b2b);
    }
    .navbar{
      box-sizing: border-box;
      width: 20%;
      background: slategrey;
      display: flex;
      flex-direction: column;
      height: 100vh;
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

    nav h1:hover{
      color: rgb(184, 178, 178);
      transition: 300ms ease-in-out;
    }

    nav ul li {
     padding: 1rem;
    }
    nav ul li:hover{
      background: var(--gradient);
      border-radius: 5px;
    }
    nav ul p{
      opacity: 20%;
      cursor: default;
    }
  </style>