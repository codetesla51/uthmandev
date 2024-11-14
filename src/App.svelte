<script>
  import Layout from "./lib/layout.svelte";
  import Home from "./pages/home.svelte"
  import Stack from "./pages/stack.svelte"
  import Projects from "./pages/projects.svelte"
    import Overlay from "./lib/overlay.svelte";
      import Typewriter from './lib/typer.svelte';

</script>

<Layout>
  <Home />
  <Stack />
  <Projects />
  <Overlay />
</Layout>