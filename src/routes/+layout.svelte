<script>
  import "../app.css";
  import Header from "../components/Header.svelte";
</script>

<div class="bg-black px-32">
  <Header/>
    <slot />
</div>
