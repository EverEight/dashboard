<script>
  // Global CSS
  import "../app.css";

  // Theme Mode
  import { ModeWatcher } from "mode-watcher";
</script>
<svelte:head> 
  <link rel="preload" as="font" href="/fonts/Geist/GeistVF.woff2" type="font/woff2" crossorigin="anonymous"> 
  <link rel="preload" as="font" href="/fonts/Geist/GeistMonoVF.woff2" type="font/woff2" crossorigin="anonymous"> 
</svelte:head>

<ModeWatcher />
<slot />

<style></style>
