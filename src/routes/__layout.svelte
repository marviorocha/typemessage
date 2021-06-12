<script>
	import Header from '$lib/Header/index.svelte';
	import '../app.css';
</script>

<Header />

<main>
	<slot />
</main>

<footer class="w-full bg-gray-100 flex justify-center h-20 text-cyan-900 bottom-0">
    <div class="container max-w-3xl flex justify-between h-20 items-center">
      <div class="p-4">This is a <a target="_blank" href="https://kit.svelte.dev">SvelteKit</a> app. 
		Buiding with Dev Marvio Rocha - <a href="https://marviorocha.com">MarvioRocha.com</a>
</div>
      <nav>
        <ul class="flex justify-start">
          <li class="p-4 underline"><a href="https://github.com/marviorocha">GitHub</a></li>
    
          <li class="p-4 underline"><a href="mailto:marviorocha@marviorocha.com">Email Me</a></li>
        </ul>
      </nav>
    </div>
  </footer>
 

 
