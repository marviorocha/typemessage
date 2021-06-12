<script context="module">
	export const prerender = true;
</script>

<script>
	import Counter from '$lib/Counter/index.svelte';
	import Typewriter from 'svelte-typewriter';
</script>

<svelte:head>
	<title>Type Mensager</title>
</svelte:head>


<div class="relative min-h-screen pb-20 font-mono text-cyan-900">

  <div class="flex justify-center py-5">
    <div class="container max-w-3xl p-4">
      <h1 class="py-5">De: Marvio Rocha</h1>
      
	  <div class="post py-5">
 		<Typewriter interval={200}>
		 
		 <p class="type-font">Lorem ipsum dolor sit amet consectetur adipisicing elit. 
		 		Tempore nulla velit laudantium suscipit fugit recusandae cum quo adipisci 
				 atque repudiandae alias quibusdam molestias possimus exercitationem, 
				 delectus autem sunt molestiae? Delectus!
				   
				  <iframe width="100%" height="355" src="https://www.youtube-nocookie.com/embed/jYq1pHJYQmw?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
				 </p>
		 
		 </Typewriter>


	  </div>
       
    </div>
  </div>
  
</div>

<section class="container mx-auto">
 
 	 


	
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
