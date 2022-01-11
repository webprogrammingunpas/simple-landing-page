<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Geodatabase</title>

    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css"
    integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A=="
    crossorigin=""/>
    <style>
        #mapid { height: 700px; }
    </style>
</head>
<body>
    <div id="mapid"></div>
    
</body>
    <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"
    integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA=="
    crossorigin=""></script>
    <script>
        var mymap = L.map('mapid').setView([-1.3583941525531325, 120.60760847805666], 5);
        L.tileLayer('https://api.mapbox.com/styles/v1/{id}/tiles/{z}/{x}/{y}?access_token={accessToken}', {
            attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors, Imagery © <a href="https://www.mapbox.com/">Mapbox</a>',
            maxZoom: 18,
            id: 'mapbox/streets-v11',
            tileSize: 512,
            zoomOffset: -1,
            accessToken: 'pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4NXVycTA2emYycXBndHRqcmZ3N3gifQ.rJcFIG214AriISLbB6B5aw'
        }).addTo(mymap);

        var marker = L.marker([-1.3583941525531325, 120.60760847805666]).addTo(mymap);
        var circle = L.circle([-1.3583941525531325, 120.60760847805666], {
            color: 'red',
            fillColor: '#f03',
            fillOpacity: 0.5,
            radius: 200000
        }).addTo(mymap);
        var polygon = L.polygon([
            [2.313515, 120.498778],
            [-1.134908, 125.825761],
            [-5.11383611292963, 124.47165987638473],
            [-4.77020625995542, 117.76502578285782],
            [-1.2498539573437557, 116.42369896415242]
        ]).addTo(mymap);

        marker.bindPopup("This is marker popup");
        circle.bindPopup("I am a circle.").openPopup();
        polygon.bindPopup("I am a polygon.");


        var popup = L.popup()
            .setLatLng([0.19243763676280343, 113.3581752884544])
            .setContent("I am a standalone popup.")
            .openOn(mymap);

            var popup = L.popup();

        function onMapClick(e) {
            popup
                .setLatLng(e.latlng)
                .setContent("Koordinat :" + e.latlng.toString())
                .openOn(mymap);
        }

        mymap.on('click', onMapClick);
    </script>
</html>
