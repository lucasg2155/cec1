<script>
	import Map from '../components/Map.svelte';
	import MapMarker from '../components/MapMarker.svelte';
</script>

<Map lat={35} lon={-84} zoom={3.5}>
	<MapMarker lat={37.8225} lon={-122.0024} label="Svelte Body Shaping"/>
	<MapMarker lat={33.8981} lon={-118.4169} label="Svelte Barbershop & Essentials"/>
	<MapMarker lat={29.7230} lon={-95.4189} label="Svelte Waxing Studio"/>
	<MapMarker lat={28.3378} lon={-81.3966} label="Svelte 30 Nutritional Consultants"/>
	<MapMarker lat={40.6483} lon={-74.0237} label="Svelte Brands LLC"/>
	<MapMarker lat={40.6986} lon={-74.4100} label="Svelte Medical Systems"/>
</Map>


<style>
	h1, figure, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>cecu</title>
</svelte:head>

<h1>centro empleados de comercio ushuaia</h1>
<figure>
	<img alt='clinica' src='clinica.jpg'>
	<figcaption>Sanatorio CECU</figcaption>
</figure>

<figure>
	<img alt='cecu' src='cecu.jpg'>
	<figcaption>Sede Sindical</figcaption>
</figure>



<p><strong> Derechos Reservados © 2020 creado por: <a  title = "ggcon"  href = "http://ggcon.com.ar">ggcon</a></strong></p>
