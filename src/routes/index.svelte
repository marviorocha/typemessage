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
 		<Typewriter interval={170}>
		 
	    <p class="post  type-font py-5" >
		Olá Tudo bem? Hoje, gostaria apresentar
		a você o Type Mensager, uma ideia que faz o usuário ler o conteúdo com um toque de curiosidade e um bom “Call To Action”. 
		Com o Type Mensager Você poderia criar mensagens personalizadas e até realizar vendas como esse botão abaixo: 
		</p>

        </Typewriter>

		<Typewriter delay={50000}>
			
			<button class="post self-center bg-blue-500 rounded px-4 py-2 
			font-sans  text-white hover:bg-blue-600">
			Comprar
			</button>
					
		</Typewriter>


		<Typewriter interval={150} delay={51000}>
			
		<p  class="post  type-font py-5">
		Além disso, o Type Mensager, pode realizar muitas outras coisas como colocar esse video do Youtube :
		<iframe id="ytplayer" type="text/html" width="720" height="405"
		src="https://www.youtube.com/embed/mTBNXXBrFDg?autoplay=1&controls=0&modestbranding=1&playsinline=1&color=white"
		frameborder="0" allowfullscreen>
		</p>

					
		</Typewriter>
 

		<Typewriter interval={150} delay={68000}>
			
		<p  class="post  type-font py-3">
		E para impactar ainda mais sua audiência, vou mostrar o quanto sei dançar através dessa animação em Gif
		<img class="rounded-full py-3 mx-32" width="300" height="300" src="https://media0.giphy.com/media/3oKIPyn8SKfUVOzEsM/source.gif" alt="Dance">
		E isso poderia também ser a página do produto.
		</p>
					
		</Typewriter>
 




		<Typewriter interval={150} delay={90000}>
		<p  class="post  type-font py-5">
		
		Se gostou disso? Entre em contato comigo através do meu 
		<a class="text-blue-800" href="https://linkedin.com/in/marviorocha">Linkedin</a> e me deixa seu feedback 
		o que achou da ideia do Type Mensager.

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
