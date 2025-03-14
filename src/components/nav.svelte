<!-- Nav Bar -->
<nav class="nav-bar">
  <h1 class="logo">Skillup</h1>
  <ul>
    <li>Home</li>
    <li>Courses</li>
    <li>About</li>
    <li>Contact</li>
  </ul>
  <button class="btn-nav">Sign Up</button>
</nav>

<style>
  .nav-bar {
    width: 1100px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    text-align: center;
    margin: 40px auto auto;
  }

  .logo {
    font-weight: 700;
    font-size: 20px;
    color: var(--black);
    cursor: progress;
  }

  ul {
    display: flex;
    gap: 40px;
    list-style-type: none;
    color: var(--lightBlack);
  }

  li {
    cursor: pointer;
    color: var(--black);
  }

  .btn-nav {
    padding: 12px 24px;
    border-radius: 32px;
    border: none;
    color: var(--white);
    background: var(--primary);
    font-weight: 600;
    font-size: 20px;
    cursor: pointer;
    text-decoration: none;
    box-shadow: 0px 1px 1px 0px #00000040;
  }
</style>
