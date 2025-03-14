<script>
  import Nav from "./components/nav.svelte";
  import Footer from "./components/footer.svelte";
  import MainContent from "./components/content.svelte";

  let visible;
</script>

<div class="bg-gradient"></div>
<Nav />
<MainContent />
<Footer />

<style>
  .bg-gradient {
    position: absolute;
    width: 860px;
    height: 100%;
    top: -54px;
    left: -211px;
    opacity: 10%;
    background: linear-gradient(
      to right,
      var(--primary),
      var(--secondary),
      var(--white)
    );
    backdrop-filter: blur(120px);
    border-radius: 100%;
  }
</style>
