<script>
  import "../app.css";
  import Header from "../components/Header.svelte";
  import Footer from "../components/Footer.svelte";
</script>

<div>
  <Header />
  <main>
    <slot />
  </main>
  <Footer />  
</div>

