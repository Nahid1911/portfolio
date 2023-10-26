<script>
  let tabs = [
    { name: 'Home', path: '/' },
    { name: 'About', path: '/about' },
    { name: 'Contact', path: '/contact' },
  ]
</script>

<header class='sticky z-[10] top-0 duration-200 px-6 flex items-center justify-between border border-violet-950'>
  <h1 class="font-medium">
    <b class="font-bold poppins">Nahid</b> Raihan
  </h1>
    <div class="sm:flex items-center gap-4 hidden">
      {#each tabs as tab}
        <a class="duration-200 hover:text-violet-400" href={tab.path}>
          <p>{tab.name}</p>
        </a>
      {/each}

    <a href=" " target="_blank" class="blueShadow relative overflow-hidden px-2 py-2 group rounded-full bg-white text-slate-950">
      <div class="absolute top-0 right-full width-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200" />
    <h4 class="relative z-9">
      Get in touch
    </h4>   
    </a>
  </div>
</header>