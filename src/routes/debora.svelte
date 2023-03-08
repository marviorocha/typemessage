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

  <p class="post  type-font py-5" >
Querida professora Déborah,

		 </p>

		  <p class="post  type-font py-5" >
Hoje, no Dia Internacional da Mulher, eu gostaria de expressar minha sincera gratidão e admiração por você. Como uma mulher forte e dedicada, você tem sido uma inspiração para mim e para muitas outras pessoas.

		 </p>

  <p class="post  type-font py-5" >


Sua paixão pelo ensino e pelo aprendizado é verdadeiramente inspiradora. Você é um modelo de resiliência e perseverança, sempre encorajando seus alunos a se esforçarem ao máximo e nunca desistirem de seus sonhos.
</p>

  <p class="post  type-font py-5" >
Você nos ensina muito mais do que simplesmente o currículo escolar. Você nos ensina a sermos bons cidadãos, a respeitar uns aos outros e a valorizar as diferenças.
</p>

  <p class="post  type-font py-5" >
Nós apreciamos muito a maneira como você se preocupa conosco, sempre disposta a ajudar e orientar. Seu trabalho como educadora tem um impacto duradouro em nossas vidas, ajudando-nos a alcançar nossos objetivos e a sermos bem-sucedidos em nossas carreiras.
</p>
  <p class="post  type-font py-5" >

Hoje, e todos os dias, reconhecemos e celebramos a força e a resiliência das mulheres como você. Obrigado por ser uma inspiração para todos nós e por tudo o que você faz por seus alunos. Feliz Dia Internacional da Mulher!
</p>
		 </p>

        </Typewriter>











	  </div>

    </div>
  </div>

</div>


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
