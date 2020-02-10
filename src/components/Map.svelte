
<script>
	//import mapStyles from './map-styles'; // optional

	let container;
	let map;
	let zoom = 8;
    let center = {lat: -54.8065109, lng: -68.3141208};
    
    import { onMount } from 'svelte';
    
	onMount(async () => {
		map = new google.maps.Map(container, {
            zoom,
			center,
			//styles: mapStyles // optional
		});
    });
</script>
<style>
.full-screen {
    width: 50vw;
    height: 50vh;
}
</style>

<div class="full-screen" bind:this={container}></div>