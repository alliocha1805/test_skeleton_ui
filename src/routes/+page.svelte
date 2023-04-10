<script>
import { Avatar } from '@skeletonlabs/skeleton';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Test Dashboard KOnsult.io avec Skeleton UI" />
</svelte:head>

<div class="p-10 space-4 grid-cols-1 gap-4 md:grid grid-cols-4 gap-4">
	<div class="card p-4 col-span-4 2xl:col-span-2">
		<div class="p-4 flex flex-row -mx-3">
			<div class="flex-none w-2/3 max-w-full px-3">
				<p class="mb-0 font-sans font-semibold leading-normal text-lg">Chiffre d'affaire du Mois</p>
				<h5 class="text-green mb-0 font-bold">38000 $</h5>
			</div>
			<div class="px-3 text-right basis-1/3">
				<div class="inline-block w-12 h-12 text-center 500">
					<svg class="h-16 w-16 text-green-500"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
						<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/>
					</svg>
				</div>
			</div>
		</div>
	</div>
	<div class="card p-4 col-span-2 2xl:col-span-1">
		<div class="p-4 flex flex-row -mx-3">
			<div class="flex-none w-2/3 max-w-full px-3">
				<p class="mb-0 font-sans font-semibold leading-normal text-lg">Consultants</p>
				<h5 class="text-green mb-0 font-bold">785</h5>
			</div>
			<div class="px-3 text-right basis-1/3">
				<div class="inline-block w-12 h-12 text-center 500">
					<svg class="h-16 w-16 text-green-500"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
						<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"/>
					</svg>
				</div>
			</div>
		</div>
	</div>
	<div class="card p-4 col-span-2 2xl:col-span-1">
		<div class="p-4 flex flex-row -mx-3">
			<div class="flex-none w-2/3 max-w-full px-3">
				<p class="mb-0 font-sans font-semibold leading-normal text-lg">Consultants en interccontrat</p>
				<h5 class="text-green mb-0 font-bold">84</h5>
			</div>
			<div class="px-3 text-right basis-1/3">
				<div class="inline-block w-12 h-12 text-center 500">
				<svg class="h-16 w-16 text-red-500"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
					<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"/>
				</svg>
				</div>
			</div>
		</div>
	</div>
	<div class="card p-4 col-span-2 2xl:col-span-1">
		<div class="p-4 flex flex-row -mx-3">
			<div class="flex-none w-2/3 max-w-full px-3">
				<p class="mb-0 font-sans font-semibold leading-normal text-lg">Clients Actifs</p>
				<h5 class="text-green mb-0 font-bold">85</h5>
			</div>
			<div class="px-3 text-right basis-1/3">
				<div class="inline-block w-12 h-12 text-center 500">
					<svg class="h-16 w-16 text-green-500"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
						<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"/>
					</svg>
				</div>
			</div>
		</div>
	</div>
	<div class="card p-4 col-span-2 2xl:col-span-1">
		<div class="p-4 flex flex-row -mx-3">
			<div class="flex-none w-2/3 max-w-full px-3">
				<p class="mb-0 font-sans font-semibold leading-normal text-lg">Clients Inactifs</p>
				<h5 class="text-green mb-0 font-bold">24</h5>
			</div>
			<div class="px-3 text-right basis-1/3">
				<div class="inline-block w-12 h-12 text-center 500">
					<svg class="h-16 w-16 text-red-500"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
						<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 17h8m0 0V9m0 8l-8-8-4 4-6-6"/>
					</svg>
				</div>
			</div>
		</div>
	</div>
</div>

<style>

</style>
