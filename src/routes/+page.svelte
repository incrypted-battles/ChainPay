<script>
	import '../app.css';
</script>

<svelte:head>
	<title>Welcome to ChainPay</title>
</svelte:head>

<div
	class="flex flex-col min-h-screen bg-[#E5E5E5] bg-[url('/bg.webp')] bg-contain bg-no-repeat bg-[center_top_60px]"
>
	<main class="grow max-w-screen-xl mx-auto px-6 w-full flex flex-col items-center">
		<h1 class="text-[60px] center font-bold font-jakarta text-black mt-16 md:mt-40 mb-8">
			ChainPay
		</h1>
		<h3 class="text-xl center mb-6 max-w-lg text-center text-[#5A5A5A] font-roboto">
			Simplifying Invoice Creation and Payments in the Solana Ecosystem
		</h3>
		<a
			href="#"
			class="bg-[#17FB9B] hover:bg-[#00ee99] text-[#050505] font-roboto font-bold text-xl py-5 px-12 rounded-lg"
			>Download Pitch Deck</a
		>
		<img src="/pay.webp" alt="ChainPay" class="max-w-[960px] w-full mt-16 mb-16 mx-auto block" />
	</main>
	<footer
		class="text-center max-w-screen-xl mx-auto px-6 w-full my-4 font-roboto text-black text-base md:text-lg"
	>
		Copyright © 2024 ChainPay. All rights reserved.
	</footer>
</div>
