<script>
	import Footer from "$lib/AirsoftTag/layout/Footer.svelte";
  import Header from "$lib/AirsoftTag/layout/Header.svelte";
  import  "../../../app.css";
</script>



<div
  class="bg-[#1d1e21] flex flex-col min-h-screen"
>
  <Header />
  <slot />
  <Footer />
</div>
