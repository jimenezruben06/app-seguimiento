<script>
  import Search from "./lib/Search.svelte";
  import Menu from "./lib/Menu.svelte";
</script>

<div class="flex-container">
  <header>
    <div class="logo">
      <h1 class="app-name">App de Seguimiento</h1>
    </div>
  </header>

  <nav>
    <div>
      <Search />
    </div>
  </nav>

  <main>
    <div>
    </div>
  </main>

  </div>

<style>

  .flex-container{
    display: flex;
  }

  header{
    display: flex;
    flex: 60%;
  }

  .logo{
    margin-top: 25px;
    margin-left: 100px;
  }

  nav{
    display: flex;
    justify-content: right;
    flex: 40%;
    margin-top: 25px;
    margin-right: 100px;
  }

  aside {
    display: flex;
  }

</style>
