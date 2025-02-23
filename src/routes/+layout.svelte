<!-- src/routes/+layout.svelte -->
<script>
  import "bootstrap/dist/css/bootstrap.min.css"; // Bootstrap CSS
</script>


  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" style="font-style: oblique;" href="/"
        >LEARN SVELTE</a
      >
    </div>
    <ul class="navbar-nav me-auto mb-2 mb-lg-0" style="flex: content;">
      <li class="nav-item">
        <a class="nav-link" href="/">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="/about">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="/services">Services</a>
      </li>
    </ul>
  </nav>


<slot />
