<script>
	import Footer from "$lib/layout/Footer.svelte";
  import Header from "$lib/layout/Header.svelte";
  import "../app.css";
</script>



<div
  class="bg-neutral-300 flex flex-col min-h-screen"
>
  <Header />
  <slot />
  <Footer />
</div>
