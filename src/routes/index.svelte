<!-- <script>
	import Map from '../components/Map.svelte';
	export let ready

	src="https://maps.googleapis.com/maps/api/js?key=&callback=initMap";

</script>; -->

<style>

    /* :global(body) {
	padding: 0
	} */
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

<!-- { #if ready }
<Map></Map>
{ /if } -->
<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d1149.7357982553297!2d-68.3147282!3d-54.8068293!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xbc4c23218a5e80b9%3A0x943a7c699e6ea0c7!2sCECU!5e0!3m2!1ses!2sar!4v1581365683721!5m2!1ses!2sar" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen=""></iframe>

<p><strong> Derechos Reservados © 2020 creado por: <a  title = "ggcon"  href = "http://ggcon.com.ar">ggcon</a></strong></p>
