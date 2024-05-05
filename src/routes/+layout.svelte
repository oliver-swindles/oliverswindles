<script lang="ts">
  import "../app.css";
  import Header from "$lib/components/Header.svelte";
  let { children } = $props();
</script>

<svelte:head>
    <title>Oliver Swindles</title>
</svelte:head>

<Header />
<main class="ml-16">
{@render children()}
</main>

