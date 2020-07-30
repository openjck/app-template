<script lang="ts">
  import Routes from "./routes/Routes.svelte";
  export let title: string;
</script>

<style>
  nav {
    margin: 20px 0;
  }
</style>

<h1>{title}</h1>

<nav>
  <a href="/">Home</a>
  <a href="/about">About</a>
</nav>

<Routes />
