+++
title = "Unser Raum"
description = "Unser Raum im Gebäude 64"
date = "2022-08-05"
author = "MetaMeute"
+++

<figure class="image-scalable">
	<picture>
		<img loading="lazy" decoding="async" alt="Raum" class="image_figure image_processed" src="/images/room.jpg"/>
		<figcaption class="img_alt">Raum</figcaption>
	</picture>
</figure>

Die MetaMeute ist ein Hackspace für Alle und wir tun vielerlei Dinge.<br>
Über neue Besucher, die nicht zwangsweise Studenten sein müssen, freuen wir uns immer sehr.<br>
Meistens ist tagsüber offen. Ob jetzt gerade auf ist, kannst du in der Box auf der rechten Seite sehen.

Wir sind im Gebäude 64, Raum 82 des Erdgeschosses.
<figure class="image-scalable">
	<picture>
		<img loading="lazy" decoding="async" alt="Tür" class="image_figure image_processed" src="/images/door.jpg" style="width:25%"/>
		<figcaption class="img_alt">Tür</figcaption>
	</picture>
</figure>


<h3 id="osm">OpenStreetMap</h3>
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.8.0/dist/leaflet.css"
   integrity="sha512-hoalWLoI8r4UszCkZ5kL8vayOGVae1oxXe/2A4AO6J9+580uKHDO3JdHb7NzwwzK5xr/Fs0W40kiNHxM9vyTtQ=="
   crossorigin="anonymous">

<div id="mapid" style="height: 40rem; max-height: 100vmin;" class="my-5"></div>

<script src="https://unpkg.com/leaflet@1.8.0/dist/leaflet.js"
   integrity="sha512-BB3hKbKWOc9Ez/TAwyWxNXeoV9c1v6FIeYiBieIWkpLjauysF18NzgR1MBNBXf8/KABdlkX68nAhlwcDFLGPCQ=="
   crossorigin="anonymous"></script>

<script>
  var loc = [53.83378, 10.70434];
  var mymap = L.map('mapid').setView(loc, 19);
  var marker = L.marker(loc).addTo(mymap);

  marker.on('click', function (e) {
    window.open('https://www.openstreetmap.org/#map=16/' + loc[0] + '/' + loc[1], '_blank');
  });

  L.tileLayer('http://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    maxZoom: 19,
    attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
  }).addTo(mymap);
</script>
<small><a href="https://www.openstreetmap.org/?mlat=53.83378&amp;mlon=10.70434#map=19/53.83378/10.70434">Geht das noch größer?</a></small>
