<script>

 src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBDaeWicvigtP9xPv919E-RNoxfvC-Hqik&callback=iniciarMap";

 function iniciarMap(){
    var coord = {lat:-54.8065109 ,lng: -68.3141208};
    var map = new google.maps.Map(document.getElementById('map'),{
      zoom: 10,
      center: coord
    });
    var marker = new google.maps.Marker({
      position: coord,
      map: map
    });
}

	// export let map;
</script>

<style>
    /* map{
	height: 500px;
	width: 100%;
    } */
</style>

