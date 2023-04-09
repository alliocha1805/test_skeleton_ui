<script>
	import '../app.postcss';
	import './styles.css';
		// Your selected Skeleton theme:
	import '@skeletonlabs/skeleton/themes/theme-skeleton.css';

	// This contains the bulk of Skeletons required styles:
	import '@skeletonlabs/skeleton/styles/all.css';

	// Finally, your application's global stylesheet (sometimes labeled 'app.css')
	import '../app.postcss';
	import { AppShell } from '@skeletonlabs/skeleton';
	import Navigation from '$lib/Navigation/Navigation.svelte';
	import { AppBar } from '@skeletonlabs/skeleton';
	import { Drawer, drawerStore } from '@skeletonlabs/skeleton';
	import { Avatar } from '@skeletonlabs/skeleton';
	function drawerOpen() 
  {
		drawerStore.open({});
	}

</script>


<Drawer>
	<h2 class="p-4">Navigation</h2>
	<hr />
	<Navigation />
</Drawer>
<AppShell slotSidebarLeft="bg-surface-500/5 w-0 lg:w-64">
	<svelte:fragment slot="pageHeader">
		<AppBar gridColumns="grid-cols-3" slotDefault="place-self-center" slotTrail="place-content-end">
			<svelte:fragment slot="lead">
					<button class="lg:hidden btn btn-sm mr-4 " on:click={drawerOpen}>
							<span>
									<svg viewBox="0 0 100 80" class="fill-token w-4 h-4">
											<rect width="100" height="20" />
											<rect y="30" width="100" height="20" />
											<rect y="60" width="100" height="20" />
									</svg>
							</span>
					</button>
			</svelte:fragment>
			<strong class="text-xl uppercase">Konsult.io</strong>
			
			<svelte:fragment slot="trail">
			<Avatar
				border="border-4 border-surface-300-600-token hover:!border-primary-500"
				cursor="cursor-pointer"
			/></svelte:fragment>
		</AppBar>
	</svelte:fragment>
	<svelte:fragment slot="sidebarLeft">
		<Navigation />
	</svelte:fragment>



	<!-- Router Slot -->
	<slot />
	<!-- ---- / ---- -->

	<!--<svelte:fragment slot="footer">
		Footer
	</svelte:fragment>-->
</AppShell>


<style>

</style>
