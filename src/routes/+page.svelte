<script>
	import '../app.css';
</script>

<svelte:head>
	<title>Welcome to ChainPay</title>
</svelte:head>

<div
	class="flex min-h-screen flex-col bg-[#E5E5E5] bg-[url('/bg.webp')] bg-contain bg-[center_top_60px] bg-no-repeat"
>
	<main class="mx-auto flex w-full max-w-screen-xl grow flex-col items-center px-6">
		<h1 class="center mb-8 mt-16 md:mt-40">
			<img src="/logo.png" alt="ChainPay" class="w-[266px] md:w-[366px]" />
		</h1>
		<h3 class="center mb-6 max-w-lg text-center font-roboto text-xl text-[#5A5A5A]">
			Simplifying Invoice Creation and Payments in the Solana Ecosystem
		</h3>
		<a
			href="#"
			class="rounded-lg bg-[#17FB9B] px-12 py-5 font-roboto text-xl font-bold text-[#050505] hover:bg-[#00ee99]"
			>Download Pitch Deck</a
		>
		<img src="/pay.webp" alt="ChainPay" class="mx-auto mb-16 mt-16 block w-full max-w-[960px]" />
	</main>
	<footer
		class="mx-auto my-4 w-full max-w-screen-xl px-6 text-center font-roboto text-xs text-black md:text-lg"
	>
		Copyright © 2024 ChainPay. All rights reserved.
	</footer>
</div>
