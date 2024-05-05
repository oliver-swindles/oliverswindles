<script lang="ts">
  import "../app.css";
  import Header from "$lib/components/Header.svelte";
  import { dev } from "$app/environment";
  import { inject } from "@vercel/analytics";
  let { children } = $props();

  inject({ mode: dev ? 'development' : 'production' });
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
</svelte:head>

<Header />
<main class="ml-16">
{@render children()}
</main>

