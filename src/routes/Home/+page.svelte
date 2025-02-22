<script>
    import 'bootstrap/dist/css/bootstrap.min.css';
    import { Button, Alert } from 'sveltestrap';
    import Navber from './navber.svelte';
  </script>
  
  <main class="container mt-5">
    <Navber/>
    <Alert color="info">Welcome to SvelteKit with Bootstrap!</Alert>
    <Button color="primary">Click Me</Button>
    <button class="btn btn-primary">Click Me</button>
  </main>
  