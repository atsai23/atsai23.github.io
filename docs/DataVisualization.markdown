---
layout: page
title: Data Visualizations
permalink: /DataViz/
---
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_e6658fd49515d4f1ae97f0f842a9029a {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>
        
    <script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/leaflet.markercluster.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/MarkerCluster.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/MarkerCluster.Default.css"/>
    <script src="https://cdn.jsdelivr.net/npm/leaflet-tag-filter-button/src/leaflet-tag-filter-button.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/leaflet-easybutton@2/src/easy-button.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet-tag-filter-button/src/leaflet-tag-filter-button.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet-easybutton@2/src/easy-button.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/css-ripple-effect@1.0.5/dist/ripple.min.css"/>
</head>
<body>
    
    
            <div class="folium-map" id="map_e6658fd49515d4f1ae97f0f842a9029a" ></div>
        
</body>
<script>
    
    
            var map_e6658fd49515d4f1ae97f0f842a9029a = L.map(
                "map_e6658fd49515d4f1ae97f0f842a9029a",
                {
                    center: [47.6, -122.3],
                    crs: L.CRS.EPSG3857,
                    zoom: 12,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );
            L.control.scale().addTo(map_e6658fd49515d4f1ae97f0f842a9029a);

            

        
    
            var tile_layer_9a0897b58245510f0fcd9f0b232d8c6d = L.tileLayer(
                "https://cartodb-basemaps-{s}.global.ssl.fastly.net/light_all/{z}/{x}/{y}.png",
                {"attribution": "\u0026copy; \u003ca target=\"_blank\" href=\"http://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors \u0026copy; \u003ca target=\"_blank\" href=\"http://cartodb.com/attributions\"\u003eCartoDB\u003c/a\u003e, CartoDB \u003ca target=\"_blank\" href =\"http://cartodb.com/attributions\"\u003eattributions\u003c/a\u003e", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_e6658fd49515d4f1ae97f0f842a9029a);
        
    
            var marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e = L.markerClusterGroup(
                {}
            );
            map_e6658fd49515d4f1ae97f0f842a9029a.addLayer(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            var marker_71d86863b472753ed73b7467f4750e93 = L.marker(
                [47.612905, -122.31477],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_71d86863b472753ed73b7467f4750e93.bindTooltip(
                `<div>
                     10 Degrees
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_06a06ef31dcada36b34fa27bb2f85082 = L.marker(
                [47.577271, -122.407364],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_06a06ef31dcada36b34fa27bb2f85082.bindTooltip(
                `<div>
                     Alki Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2c3b66e55caa0aee538065efcbf15f58 = L.marker(
                [47.618587, -122.317818],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2c3b66e55caa0aee538065efcbf15f58.bindTooltip(
                `<div>
                     Calypte Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_aae84cdada859ed04b57cbbdfb5cd7e7 = L.marker(
                [47.6139358, -122.3174302],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_aae84cdada859ed04b57cbbdfb5cd7e7.bindTooltip(
                `<div>
                     Cassandria Blackmore Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fcd2dacd5a80cf69ebe51d918b3a0c57 = L.marker(
                [47.58879805, -122.3070771],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fcd2dacd5a80cf69ebe51d918b3a0c57.bindTooltip(
                `<div>
                     Eritrean Association in Greater Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8329d1852613646478799ea50aa0b484 = L.marker(
                [47.649069, -122.36089],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8329d1852613646478799ea50aa0b484.bindTooltip(
                `<div>
                     Image Journal
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bde055dfb2cc5fdb458bda013c0fcf9e = L.marker(
                [47.5756053, -122.3206151],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bde055dfb2cc5fdb458bda013c0fcf9e.bindTooltip(
                `<div>
                     Rainier Glass Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_17784951ed812807d992336364010d13 = L.marker(
                [47.601715, -122.320429],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_17784951ed812807d992336364010d13.bindTooltip(
                `<div>
                     Ravenna-Eckstein Community Center & Yesler
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0c752ccbd2f9866447ec048404d0af91 = L.marker(
                [47.595513, -122.327132],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0c752ccbd2f9866447ec048404d0af91.bindTooltip(
                `<div>
                     REDred Photo School & Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d21b0316b64c818407027b44de79fba6 = L.marker(
                [47.601443, -122.28545],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d21b0316b64c818407027b44de79fba6.bindTooltip(
                `<div>
                     Radio Variedades KXPA 1540 AM
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cb68801e95eaa325638ceffce62c9578 = L.marker(
                [47.6117662, -122.3338683],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cb68801e95eaa325638ceffce62c9578.bindTooltip(
                `<div>
                     Regal Meridian 16
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8f0972dc2c80370d14f744a45fbb9859 = L.marker(
                [47.5749176, -122.3376252],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8f0972dc2c80370d14f744a45fbb9859.bindTooltip(
                `<div>
                     Seattle Pottery Supply
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_92141dd08d5eafc148d3e1fcdb8e5b89 = L.marker(
                [47.529579, -122.320518],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_92141dd08d5eafc148d3e1fcdb8e5b89.bindTooltip(
                `<div>
                     South Park Neighborhood and Senior Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fd1ca053c3a6380fde78ad65516d1259 = L.marker(
                [47.610411, -122.302087],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fd1ca053c3a6380fde78ad65516d1259.bindTooltip(
                `<div>
                     Wa Na Wari
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1d20e1a9d8240cbb862140d16aed854d = L.marker(
                [47.62056855, -122.350491],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1d20e1a9d8240cbb862140d16aed854d.bindTooltip(
                `<div>
                     Seattle Center-SIFF Film Center and Cinema at the Uptown
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_59b08b7eb08bc5ef9db5d2c69ef1bc86 = L.marker(
                [47.6722229, -122.3118912],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_59b08b7eb08bc5ef9db5d2c69ef1bc86.bindTooltip(
                `<div>
                     University of Washington Suzzallo Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ede9cc019df9a5ffad31817cd7c7eafd = L.marker(
                [47.6867128, -122.3636508],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ede9cc019df9a5ffad31817cd7c7eafd.bindTooltip(
                `<div>
                     Avast Recording Co
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8d9d319b5914e006171777c946677df6 = L.marker(
                [47.6237608, -122.352406],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8d9d319b5914e006171777c946677df6.bindTooltip(
                `<div>
                     Seattle Center Cornish Playhouse
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f9f95d01a0cdbbc79491475f9ba2ab9a = L.marker(
                [47.649878, -122.342711],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f9f95d01a0cdbbc79491475f9ba2ab9a.bindTooltip(
                `<div>
                     Stone Way Cafe
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1c62e978d0be78163e121b22976d2ef9 = L.marker(
                [47.66909, -122.385796],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1c62e978d0be78163e121b22976d2ef9.bindTooltip(
                `<div>
                     Bill Matthews' Conga Joy
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6da88845dd0de830bc5f54a18f5114a2 = L.marker(
                [47.66629, -122.314484],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6da88845dd0de830bc5f54a18f5114a2.bindTooltip(
                `<div>
                     Mossy Bottom Records
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5ebf4b97af2df3e6ed0d705532a6f341 = L.marker(
                [47.6017992, -122.3366083],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5ebf4b97af2df3e6ed0d705532a6f341.bindTooltip(
                `<div>
                     Highway 99 Blues Club
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9c446e06275983edc1151997195d1c32 = L.marker(
                [47.6080964, -122.3388114],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9c446e06275983edc1151997195d1c32.bindTooltip(
                `<div>
                     Traver Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_94985d8497bc10a368a81ca27822c22c = L.marker(
                [47.607943, -122.326933],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_94985d8497bc10a368a81ca27822c22c.bindTooltip(
                `<div>
                     Vito's
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5dd7e07b48fe7897a08d53a2bb644a8f = L.marker(
                [47.721672, -122.338554],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5dd7e07b48fe7897a08d53a2bb644a8f.bindTooltip(
                `<div>
                     Haller Lake Community Club
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b48f2839448704fbb6ac722cc5294307 = L.marker(
                [47.6626739, -122.2991137],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b48f2839448704fbb6ac722cc5294307.bindTooltip(
                `<div>
                     The Art Study
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a9a5d3db648200dbcf26ca6692d9a510 = L.marker(
                [47.621106, -122.3537817],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a9a5d3db648200dbcf26ca6692d9a510.bindTooltip(
                `<div>
                     Seattle Center ArtsED WA in Seattle Center Pavillion
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c56542b3ff317e13d7612f109ed48efc = L.marker(
                [47.59511695, -122.3270859],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c56542b3ff317e13d7612f109ed48efc.bindTooltip(
                `<div>
                     Urban Artworks in Inscape
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9849fbbaa4f205daa07c79af477b5a34 = L.marker(
                [47.5480284, -122.3164558],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9849fbbaa4f205daa07c79af477b5a34.bindTooltip(
                `<div>
                     Miller School of Art
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_75ed37f863b4d2db8a3e7bf37718d41c = L.marker(
                [47.618798, -122.3293302],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_75ed37f863b4d2db8a3e7bf37718d41c.bindTooltip(
                `<div>
                     El Corazon
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b6ceb3d4c373c70cf92ec4eb45d5354d = L.marker(
                [47.6688694, -122.3126674],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b6ceb3d4c373c70cf92ec4eb45d5354d.bindTooltip(
                `<div>
                     Zanadu Comics
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a0eee0b2598dd6bd86832d81ea3e3f82 = L.marker(
                [47.6682756, -122.3860837],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a0eee0b2598dd6bd86832d81ea3e3f82.bindTooltip(
                `<div>
                     Sunset Tavern
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6abc20d12fae3337f6e5d696420571ac = L.marker(
                [47.69657535, -122.3933821],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6abc20d12fae3337f6e5d696420571ac.bindTooltip(
                `<div>
                     Planet Art
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6b2c3b12ff81357e31d6cdf731fe8f59 = L.marker(
                [47.622562, -122.321701],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6b2c3b12ff81357e31d6cdf731fe8f59.bindTooltip(
                `<div>
                     Bass Northwest
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0805cc8e89679d61b0901ee67c006d5d = L.marker(
                [47.51842745, -122.2976981],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0805cc8e89679d61b0901ee67c006d5d.bindTooltip(
                `<div>
                     Museum of Flight
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3ac99b435281dc928a7e62788521e0c4 = L.marker(
                [47.6129184, -122.316028],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3ac99b435281dc928a7e62788521e0c4.bindTooltip(
                `<div>
                     Hollow Earth Radio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b6a1d401f653793adaf590ca7755d038 = L.marker(
                [47.5488654, -122.3174654],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b6a1d401f653793adaf590ca7755d038.bindTooltip(
                `<div>
                     L x W x H
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_74b79c141dbbbbe65e65ea7028bf9cae = L.marker(
                [47.6506373, -122.3496713],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_74b79c141dbbbbe65e65ea7028bf9cae.bindTooltip(
                `<div>
                     Ophelia's Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3896ead3333fb83c250636235a54e59a = L.marker(
                [47.5989184, -122.3331591],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3896ead3333fb83c250636235a54e59a.bindTooltip(
                `<div>
                     Stonington Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0c92c5511d9532e6880847b24f4260d5 = L.marker(
                [47.6040236, -122.3309956],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0c92c5511d9532e6880847b24f4260d5.bindTooltip(
                `<div>
                     Seattle Public Library Main
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c838bd0d80bac3a483bab5014f2e2234 = L.marker(
                [47.6591931, -122.3498604],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c838bd0d80bac3a483bab5014f2e2234.bindTooltip(
                `<div>
                     Fremont Abbey Arts Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9c9e8eb0b1410a2e58c5d5a08050b26b = L.marker(
                [47.6186813, -122.3249251],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9c9e8eb0b1410a2e58c5d5a08050b26b.bindTooltip(
                `<div>
                     Ghost Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_dd23e31b90ea87dcfc2e6ba6456b1323 = L.marker(
                [47.621666, -122.321304],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_dd23e31b90ea87dcfc2e6ba6456b1323.bindTooltip(
                `<div>
                     Spin Cycle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_33c6dc95fbd500b78a5c92529419ecbf = L.marker(
                [47.602902, -122.333954],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_33c6dc95fbd500b78a5c92529419ecbf.bindTooltip(
                `<div>
                     57 Biscayne
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_46cdcdb59169481cd0d4c3972637ad65 = L.marker(
                [47.656206, -122.312972],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_46cdcdb59169481cd0d4c3972637ad65.bindTooltip(
                `<div>
                     University of Washington Gallagher Law Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_be3134e916da736dd8bce82a90fcb538 = L.marker(
                [47.6656768, -122.3136491],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_be3134e916da736dd8bce82a90fcb538.bindTooltip(
                `<div>
                     Broadway Bound Children's Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f4b45719fa8dd56b020d719aa3b448f9 = L.marker(
                [47.544634, -122.328371],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f4b45719fa8dd56b020d719aa3b448f9.bindTooltip(
                `<div>
                     Equinox Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5791aa45d19b4c5ba1a24d6f838d1756 = L.marker(
                [47.596665, -122.325649],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5791aa45d19b4c5ba1a24d6f838d1756.bindTooltip(
                `<div>
                     Chinese Information and Service Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_540edbd5951acd71e4d73523b5b8f811 = L.marker(
                [47.61989555, -122.3427626],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_540edbd5951acd71e4d73523b5b8f811.bindTooltip(
                `<div>
                     Winston Wachter Fine Art
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_161cb3aadfad5d518d0dd26dd43f3cc5 = L.marker(
                [47.5440673, -122.2824356],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_161cb3aadfad5d518d0dd26dd43f3cc5.bindTooltip(
                `<div>
                     Jazz Night School
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9da6863309f23e82ee9ab946e078bde9 = L.marker(
                [47.6581986, -122.3042543],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9da6863309f23e82ee9ab946e078bde9.bindTooltip(
                `<div>
                     University of Washington Intellectual House
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b610de5083e51d7dd6dd3a4abb806a0f = L.marker(
                [47.680642, -122.26227],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b610de5083e51d7dd6dd3a4abb806a0f.bindTooltip(
                `<div>
                     Magnuson Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7ee2d34eb25dabeb968246c751940338 = L.marker(
                [47.62294115, -122.2907778],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7ee2d34eb25dabeb968246c751940338.bindTooltip(
                `<div>
                     Seattle JazzED at MLK Fame Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1b3fc153f0ee60bd5f21796c2cc4861d = L.marker(
                [47.6144138, -122.317071],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1b3fc153f0ee60bd5f21796c2cc4861d.bindTooltip(
                `<div>
                     Nortthwest Film Forum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fa295dd7155233bfc3172389ca7f2728 = L.marker(
                [47.690653, -122.357728],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fa295dd7155233bfc3172389ca7f2728.bindTooltip(
                `<div>
                     School of Rock
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_319361c43add918fe76639a2985d200c = L.marker(
                [47.6002759, -122.3299406],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_319361c43add918fe76639a2985d200c.bindTooltip(
                `<div>
                     Foster/White Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ec1ae7cc9ec1fb4748c74df57ec74b8c = L.marker(
                [47.68714104, -122.3551792],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ec1ae7cc9ec1fb4748c74df57ec74b8c.bindTooltip(
                `<div>
                     Seattle Public Library Greenwood
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d6662be0cca4bdf4504402fc1b3392a9 = L.marker(
                [47.616283, -122.297218],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d6662be0cca4bdf4504402fc1b3392a9.bindTooltip(
                `<div>
                     DASSdance Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_27e439185158b56becbfb67c24cffad9 = L.marker(
                [47.6839218, -122.3064199],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_27e439185158b56becbfb67c24cffad9.bindTooltip(
                `<div>
                     Roaring Mouse Creative Arts Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_589f7902723e6c6681b61d150db5a625 = L.marker(
                [47.6593651, -122.3180274],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_589f7902723e6c6681b61d150db5a625.bindTooltip(
                `<div>
                     911 Media Arts Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_06130019a0403f164c218981f559e56d = L.marker(
                [47.739364, -122.345273],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_06130019a0403f164c218981f559e56d.bindTooltip(
                `<div>
                     Jo Ann Fabrics and Crafts Aurora
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3c81244a5ab9034a03f40ff22bad6b43 = L.marker(
                [47.65066, -122.34989],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3c81244a5ab9034a03f40ff22bad6b43.bindTooltip(
                `<div>
                     Jive Time
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e5b309626041889b6dd179fc0010ccb7 = L.marker(
                [47.6185686, -122.3172487],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e5b309626041889b6dd179fc0010ccb7.bindTooltip(
                `<div>
                     Artist Trust
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_278900783ad4ff05d9621b55d79f6312 = L.marker(
                [47.636174, -122.356958],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_278900783ad4ff05d9621b55d79f6312.bindTooltip(
                `<div>
                     Paper Source Queen Anne
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5f636976d3c9bde0d08a43af729769c7 = L.marker(
                [47.60051, -122.331586],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5f636976d3c9bde0d08a43af729769c7.bindTooltip(
                `<div>
                     Pilchuck Glass School Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_60b4b66de919b07a36b764459784e8b9 = L.marker(
                [47.66541915, -122.3824426],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_60b4b66de919b07a36b764459784e8b9.bindTooltip(
                `<div>
                     New York Fashion Academy
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cb24b9b7d5a700387b22a2bbdd6bd374 = L.marker(
                [47.6640977, -122.3310449],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cb24b9b7d5a700387b22a2bbdd6bd374.bindTooltip(
                `<div>
                     The Chapel Performance Space at Good Shepherd Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_da6fcedfa353808f548bdb4581feccd0 = L.marker(
                [47.623616, -122.356725],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_da6fcedfa353808f548bdb4581feccd0.bindTooltip(
                `<div>
                     SIFF Cinema Uptown (see SIFF for answers to survey)
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c550b669ce4586f61b14818514f6e6b7 = L.marker(
                [47.681091, -122.324814],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c550b669ce4586f61b14818514f6e6b7.bindTooltip(
                `<div>
                     Mockingbird Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_85e01908e02fb3eec401ffefdf34d20e = L.marker(
                [47.621704, -122.33886],
                {"tags": ["Live/Work"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_85e01908e02fb3eec401ffefdf34d20e.bindTooltip(
                `<div>
                     The Lofts at 325
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_20daf904945759c1e78a015567067a82 = L.marker(
                [47.65708, -122.342359],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_20daf904945759c1e78a015567067a82.bindTooltip(
                `<div>
                     Seattle Sound Repair
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_298129fa03780ec9410b1393c3354567 = L.marker(
                [47.612602, -122.289642],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_298129fa03780ec9410b1393c3354567.bindTooltip(
                `<div>
                     St. Clouds
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d743fef9af7c791a823fa757c5a2440e = L.marker(
                [47.6069251, -122.3372059],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d743fef9af7c791a823fa757c5a2440e.bindTooltip(
                `<div>
                     Patricia Rovzar Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_aa896d8b17a10f7e1013d4ee6b7539ba = L.marker(
                [47.7230197, -122.3562457],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_aa896d8b17a10f7e1013d4ee6b7539ba.bindTooltip(
                `<div>
                     Seattle Public Library Broadview
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_107d4585408c3c47db3c836bf696e973 = L.marker(
                [47.67173, -122.317154],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_107d4585408c3c47db3c836bf696e973.bindTooltip(
                `<div>
                     The Trading Musician
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6cfaf1d92f2b500cd695a522ef3c3a51 = L.marker(
                [47.684772, -122.315903],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6cfaf1d92f2b500cd695a522ef3c3a51.bindTooltip(
                `<div>
                     Comics Journal / Fantagraphics Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2352ca17ec1ca403f4d0a2e622d4899c = L.marker(
                [47.5515231, -122.3186879],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2352ca17ec1ca403f4d0a2e622d4899c.bindTooltip(
                `<div>
                     Krab Jab Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9500914ff4ebca42169917efbf62929f = L.marker(
                [47.539444, -122.294067],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9500914ff4ebca42169917efbf62929f.bindTooltip(
                `<div>
                     Van Asselt Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e47251f366d4881b6c2d1a69ee3768c0 = L.marker(
                [47.6166738, -122.335888],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e47251f366d4881b6c2d1a69ee3768c0.bindTooltip(
                `<div>
                     Cornish College of the Arts-Commons
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5531eff94a58b4e10d707a65c86e799a = L.marker(
                [47.6089681, -122.3221023],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5531eff94a58b4e10d707a65c86e799a.bindTooltip(
                `<div>
                     Swedish Hospital Art Collection
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3f7e987f978fc6e3546d0323df3ee4f2 = L.marker(
                [47.604249, -122.323564],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3f7e987f978fc6e3546d0323df3ee4f2.bindTooltip(
                `<div>
                     Service League Harborview Medical Center Art Collection
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b6e5ecd68155a474c6171aaf123d9f5c = L.marker(
                [47.6760806, -122.3629711],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b6e5ecd68155a474c6171aaf123d9f5c.bindTooltip(
                `<div>
                     Tin Hat
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f4f2b11ab53871164eed1d892b346e32 = L.marker(
                [47.6106553, -122.3171103],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f4f2b11ab53871164eed1d892b346e32.bindTooltip(
                `<div>
                     Lee Center for the Arts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0e57e9817925c7e85e5b56d2c6cfd723 = L.marker(
                [47.57968, -122.40967],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0e57e9817925c7e85e5b56d2c6cfd723.bindTooltip(
                `<div>
                     Alki Bathhouse Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f6ec940f915865d0e292e5b8ff85d40d = L.marker(
                [47.657714, -122.305882],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f6ec940f915865d0e292e5b8ff85d40d.bindTooltip(
                `<div>
                     University of Washington Music Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a8afbaf55ad3d03eb0b371eb034a3400 = L.marker(
                [47.5504345, -122.3182596],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a8afbaf55ad3d03eb0b371eb034a3400.bindTooltip(
                `<div>
                     Georgetown Arts and Cultural Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_dfc72d1d611b1c0e42a6bde8a3bc09a4 = L.marker(
                [47.66116, -122.326927],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_dfc72d1d611b1c0e42a6bde8a3bc09a4.bindTooltip(
                `<div>
                     Golden Oldies
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7e9d87e6b0b6327ff49ae6106002409b = L.marker(
                [47.60038, -122.335144],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7e9d87e6b0b6327ff49ae6106002409b.bindTooltip(
                `<div>
                     Mack 9 Music Group
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e8fd6bb0764e4a3d2466df2983a2dd67 = L.marker(
                [47.6777479, -122.3280274],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e8fd6bb0764e4a3d2466df2983a2dd67.bindTooltip(
                `<div>
                     Anthony Peters' Tap Dance Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_82f006103a7a9afa1f3db882377d9db4 = L.marker(
                [47.64891855, -122.3771253],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_82f006103a7a9afa1f3db882377d9db4.bindTooltip(
                `<div>
                     Seattle Film Institute
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9654e76a88ced7fedc291e97d4b9f796 = L.marker(
                [47.68861, -122.355293],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9654e76a88ced7fedc291e97d4b9f796.bindTooltip(
                `<div>
                     Fiber Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2e548c5f57e88d5ab9636bc619d8bc66 = L.marker(
                [47.621319, -122.320541],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2e548c5f57e88d5ab9636bc619d8bc66.bindTooltip(
                `<div>
                     Julia's on Broadway
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3cfd4cc08e1c985091b84fb983ec2bf7 = L.marker(
                [47.5998538, -122.3331316],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3cfd4cc08e1c985091b84fb983ec2bf7.bindTooltip(
                `<div>
                     Artforte Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a1185193121e415c78a83444d5b11f78 = L.marker(
                [47.610031, -122.338524],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a1185193121e415c78a83444d5b11f78.bindTooltip(
                `<div>
                     Aaron Brothers Art & Framing
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fc2dfbd49cf716dae7a9154e90693226 = L.marker(
                [47.6174134, -122.3349055],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fc2dfbd49cf716dae7a9154e90693226.bindTooltip(
                `<div>
                     Cornish College of the Arts-Centennial Lab
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_74a6137df122baee083045c64528ca48 = L.marker(
                [47.6183638, -122.3572268],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_74a6137df122baee083045c64528ca48.bindTooltip(
                `<div>
                     Sisko Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5a960f0871735228f6b3e79e9911c2ce = L.marker(
                [47.692089, -122.355721],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5a960f0871735228f6b3e79e9911c2ce.bindTooltip(
                `<div>
                     Tara Academy of Irish Dance Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8bdcaa317d5c2ee11909b93879a29457 = L.marker(
                [47.548885, -122.317596],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8bdcaa317d5c2ee11909b93879a29457.bindTooltip(
                `<div>
                     Interstitial
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bd4596faa09bde3869709d3f44d7d8bf = L.marker(
                [47.705193, -122.322426],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bd4596faa09bde3869709d3f44d7d8bf.bindTooltip(
                `<div>
                     Northgate Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_44b56833cff0a13cf944a41776608baa = L.marker(
                [47.6127129, -122.3163494],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_44b56833cff0a13cf944a41776608baa.bindTooltip(
                `<div>
                     Seattle Academy of Arts and Sciences
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_18147dbf4d2cf80ea0573112d0383c1d = L.marker(
                [47.675001, -122.303815],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_18147dbf4d2cf80ea0573112d0383c1d.bindTooltip(
                `<div>
                     Thrive Art School
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_59f20e6189e8d85ad701e6efdda62376 = L.marker(
                [47.5511485, -122.3874063],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_59f20e6189e8d85ad701e6efdda62376.bindTooltip(
                `<div>
                     Seattle Yarn
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d19d87ecd8478c353164e5a569053f24 = L.marker(
                [47.661064, -122.275932],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d19d87ecd8478c353164e5a569053f24.bindTooltip(
                `<div>
                     St. Stephens Episcopal Church
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c2a9e4ff9a2f6dd9dab864c9fd70bd83 = L.marker(
                [47.66909, -122.385796],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c2a9e4ff9a2f6dd9dab864c9fd70bd83.bindTooltip(
                `<div>
                     The Control Room
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bb9b4d41647c8e1154824744dce7ae08 = L.marker(
                [47.6609225, -122.3151058],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bb9b4d41647c8e1154824744dce7ae08.bindTooltip(
                `<div>
                     Burke Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7e9b6f81d20b07846a5f557e252add65 = L.marker(
                [47.540237, -122.37336],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7e9b6f81d20b07846a5f557e252add65.bindTooltip(
                `<div>
                     High Point Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d57b71c491374462010bc75627a87956 = L.marker(
                [47.6171641, -122.3374413],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d57b71c491374462010bc75627a87956.bindTooltip(
                `<div>
                     Woodside/Braseth Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6269268b159fbcc992720b9c935e837b = L.marker(
                [47.602619, -122.3323144],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6269268b159fbcc992720b9c935e837b.bindTooltip(
                `<div>
                     Howard House
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5bd273b9079771d6acd587cc10b70008 = L.marker(
                [47.66867, -122.382344],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5bd273b9079771d6acd587cc10b70008.bindTooltip(
                `<div>
                     Dakota Art Store
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_794b6b2760d8fc0df85100ea93688d29 = L.marker(
                [47.682785, -122.355621],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_794b6b2760d8fc0df85100ea93688d29.bindTooltip(
                `<div>
                     Phinney Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c39b829fe3441b05b6a01cfcc6d649cd = L.marker(
                [47.6141557, -122.3413991],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c39b829fe3441b05b6a01cfcc6d649cd.bindTooltip(
                `<div>
                     Cinerama
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3ef3e6046ab3aa96cafc78dbd13b8830 = L.marker(
                [47.7203793, -122.2979988],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3ef3e6046ab3aa96cafc78dbd13b8830.bindTooltip(
                `<div>
                     The Movement Lab
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b3e3ec6f1e0a0433b9747addd778b08b = L.marker(
                [47.577168, -122.297668],
                {"tags": ["Live/Work"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b3e3ec6f1e0a0433b9747addd778b08b.bindTooltip(
                `<div>
                     Veronica Mt Baker Lofts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a5c665193694ada2073e39b25220b1eb = L.marker(
                [47.614417, -122.314238],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a5c665193694ada2073e39b25220b1eb.bindTooltip(
                `<div>
                     Porchlight Coffee & Records
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c4881b5a5edaf80add378b729efae3f5 = L.marker(
                [47.6207729, -122.3551686],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c4881b5a5edaf80add378b729efae3f5.bindTooltip(
                `<div>
                     Seattle Center Pottery Northwest
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_495a524c40749e9afd15101869f6fb7d = L.marker(
                [47.612072, -122.344917],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_495a524c40749e9afd15101869f6fb7d.bindTooltip(
                `<div>
                     Tune HiFi
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a881d85a8103fb0122e40cd01d55789d = L.marker(
                [47.661797, -122.340996],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a881d85a8103fb0122e40cd01d55789d.bindTooltip(
                `<div>
                     Creative Music Adventures
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_270917a900c20d680892a74c72344eae = L.marker(
                [47.5420331, -122.272057],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_270917a900c20d680892a74c72344eae.bindTooltip(
                `<div>
                     Adefua Cultural Exchange Workshop
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_97a166e52e4c7638d719a47c4a059381 = L.marker(
                [47.664829, -122.369316],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_97a166e52e4c7638d719a47c4a059381.bindTooltip(
                `<div>
                     Light in the Attic Records
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a99a4714afd53d30ae12c4ef0dce776b = L.marker(
                [47.658408, -122.290305],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a99a4714afd53d30ae12c4ef0dce776b.bindTooltip(
                `<div>
                     University of Washington Elisabeth C. Miller Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3530dc87950e0a9fb82c56dd6a6999a9 = L.marker(
                [47.604534, -122.320335],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3530dc87950e0a9fb82c56dd6a6999a9.bindTooltip(
                `<div>
                     Art With A Heart
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_460689ca8002e88b3d7bede80b731ea3 = L.marker(
                [47.5487509, -122.3170704],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_460689ca8002e88b3d7bede80b731ea3.bindTooltip(
                `<div>
                     Belle and Wissell/Oxbow
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7ad3156a106ab7877a99ef7314d4650d = L.marker(
                [47.631859, -122.321548],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7ad3156a106ab7877a99ef7314d4650d.bindTooltip(
                `<div>
                     Saint Marks
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_00779f714bed93aa971a2be981eda2af = L.marker(
                [47.6325497, -122.3206894],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_00779f714bed93aa971a2be981eda2af.bindTooltip(
                `<div>
                     Gage Academy of Art
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_45ea181c21d8430ec95cf116f70c31a9 = L.marker(
                [47.65663, -122.309154],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_45ea181c21d8430ec95cf116f70c31a9.bindTooltip(
                `<div>
                     University of Washington Kane Walker-Ames Room
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_97437d93b168f6fee9e8ba57d1087816 = L.marker(
                [47.659863, -122.278038],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_97437d93b168f6fee9e8ba57d1087816.bindTooltip(
                `<div>
                     Laurelhurst Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4a7af0fc6a470e7d37cfdc554b2949cc = L.marker(
                [47.680391, -122.325888],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4a7af0fc6a470e7d37cfdc554b2949cc.bindTooltip(
                `<div>
                     Green Lake Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1528b0d31bbe4ce11b0de1e81e7c3781 = L.marker(
                [47.665052, -122.37122],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1528b0d31bbe4ce11b0de1e81e7c3781.bindTooltip(
                `<div>
                     Chihuly Workshop
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_96cd5d80aae64c9a91be07c2bf2a0267 = L.marker(
                [47.5514664, -122.3283134],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_96cd5d80aae64c9a91be07c2bf2a0267.bindTooltip(
                `<div>
                     Gallery Context
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fb88c04d37ad28cac56c780bfd888de3 = L.marker(
                [47.610901, -122.3254749],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fb88c04d37ad28cac56c780bfd888de3.bindTooltip(
                `<div>
                     Martin-Zambito Fine Art
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ad517e33a69c4933fcd5b2fad4d1a9e8 = L.marker(
                [47.622562, -122.321693],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ad517e33a69c4933fcd5b2fad4d1a9e8.bindTooltip(
                `<div>
                     Arts and Visually Impaired Audiences
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_dd29e79d8f7db7a97c448303baccd9d2 = L.marker(
                [47.6604, -122.280525],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_dd29e79d8f7db7a97c448303baccd9d2.bindTooltip(
                `<div>
                     Glassybaby University Village
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a0ee28acd1ec724de2ccdb0bc571f7f7 = L.marker(
                [47.672783, -122.391548],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a0ee28acd1ec724de2ccdb0bc571f7f7.bindTooltip(
                `<div>
                     Ballard Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_47c03681c417c8d58df778ff26d85248 = L.marker(
                [47.6973909, -122.3736435],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_47c03681c417c8d58df778ff26d85248.bindTooltip(
                `<div>
                     Flamenco Gitana
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f672cab5b512e01aaa34bb3ae9ab2010 = L.marker(
                [47.63382, -122.276352],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f672cab5b512e01aaa34bb3ae9ab2010.bindTooltip(
                `<div>
                     Allied Arts Foundation
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7f9fb7bcc768bcdf20d476ae85e0a004 = L.marker(
                [47.56093545, -122.352001],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7f9fb7bcc768bcdf20d476ae85e0a004.bindTooltip(
                `<div>
                     Duwamish Longhouse
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_beb581cf27968abe41a9bd4c7328aff8 = L.marker(
                [47.665687, -122.382206],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_beb581cf27968abe41a9bd4c7328aff8.bindTooltip(
                `<div>
                     Monster Art & Clothing
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f5bd29dfa491fdad3edc2895b455ee60 = L.marker(
                [47.56538, -122.386383],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f5bd29dfa491fdad3edc2895b455ee60.bindTooltip(
                `<div>
                     West Seattle Art Nest
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5a0a8c2a113766cc00d7591f2ed3c191 = L.marker(
                [47.614395, -122.321198],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5a0a8c2a113766cc00d7591f2ed3c191.bindTooltip(
                `<div>
                     Neighbours
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3ed6c8cc221565436b40290ccf5ccd09 = L.marker(
                [47.6609714, -122.3138972],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3ed6c8cc221565436b40290ccf5ccd09.bindTooltip(
                `<div>
                     STG Neptune Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8f7f6a551532701637df6fd385e2d41f = L.marker(
                [47.675826, -122.317088],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8f7f6a551532701637df6fd385e2d41f.bindTooltip(
                `<div>
                     Ted Brown Music
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5a1db5bc8828f8098c548aeb5620ed75 = L.marker(
                [47.61760085, -122.3345624],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5a1db5bc8828f8098c548aeb5620ed75.bindTooltip(
                `<div>
                     Cornish College of the Arts- Annex
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a9c75b910bc380b30a77752d72762fd4 = L.marker(
                [47.551844, -122.319481],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a9c75b910bc380b30a77752d72762fd4.bindTooltip(
                `<div>
                     Mainframe
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_23bb50db4cf6888ddd7d30f2ce387644 = L.marker(
                [47.664752, -122.3127097],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_23bb50db4cf6888ddd7d30f2ce387644.bindTooltip(
                `<div>
                     Grand Illusion
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2c2233a80189e87e29b94675d1b4aaa3 = L.marker(
                [47.6163466, -122.3538499],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2c2233a80189e87e29b94675d1b4aaa3.bindTooltip(
                `<div>
                     Seattle Art Museum Olympic Sculture Park
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7cdb105945ceac742047b7e7c47a68f1 = L.marker(
                [47.610493, -122.341634],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7cdb105945ceac742047b7e7c47a68f1.bindTooltip(
                `<div>
                     Design In Public
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1bf4e40fe17749bfe45f72ac1157ba83 = L.marker(
                [47.6157581, -122.321786],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1bf4e40fe17749bfe45f72ac1157ba83.bindTooltip(
                `<div>
                     Seattle Central Community College Broadway Performance Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b5aaeaf9f39a253f9e5d0b1075595726 = L.marker(
                [47.6808468, -122.3238474],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b5aaeaf9f39a253f9e5d0b1075595726.bindTooltip(
                `<div>
                     eXit Space School of Dance
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_32ea5e1dbf0e63757ed688f13fab0da2 = L.marker(
                [47.622452, -122.358414],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_32ea5e1dbf0e63757ed688f13fab0da2.bindTooltip(
                `<div>
                     Music4Life
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_60fba78a98f64e3afbd6313ea723c48f = L.marker(
                [47.665938, -122.318411],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_60fba78a98f64e3afbd6313ea723c48f.bindTooltip(
                `<div>
                     Blessed Sacrament Church
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fedee4d97d6fa0536fc7538ac5f99d03 = L.marker(
                [47.66083775, -122.3376838],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fedee4d97d6fa0536fc7538ac5f99d03.bindTooltip(
                `<div>
                     Electrokitty Recordings
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ef7f200f5ca432869d61ee10c5d00128 = L.marker(
                [47.6088638, -122.3413696],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ef7f200f5ca432869d61ee10c5d00128.bindTooltip(
                `<div>
                     Brooke Westlund Studio + Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_172dddf8822f40b57050d72e28820033 = L.marker(
                [47.618248, -122.35743],
                {"tags": ["Live/Work"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_172dddf8822f40b57050d72e28820033.bindTooltip(
                `<div>
                     NW Work Lofts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7071e33daff7a48f33a964417b24187e = L.marker(
                [47.610974, -122.34275],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7071e33daff7a48f33a964417b24187e.bindTooltip(
                `<div>
                     World Beads
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f2f98fb2737aa03368e1e366326bc0df = L.marker(
                [47.640102, -122.341103],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f2f98fb2737aa03368e1e366326bc0df.bindTooltip(
                `<div>
                     Hillman Guitar Instruction
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_84eec611db0d0753778d771c095f1e47 = L.marker(
                [47.612338, -122.319368],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_84eec611db0d0753778d771c095f1e47.bindTooltip(
                `<div>
                     The Factory
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fc7bf23c2c2e7c0101427f345b2b6cfa = L.marker(
                [47.608707, -122.341049],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fc7bf23c2c2e7c0101427f345b2b6cfa.bindTooltip(
                `<div>
                     Holy Cow Records
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4ff325acea47dee0079ac31d6e13b260 = L.marker(
                [47.598572, -122.333794],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4ff325acea47dee0079ac31d6e13b260.bindTooltip(
                `<div>
                     The Pioneer Collective
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_472a41253debd3959f90cc2a55d55f03 = L.marker(
                [47.6081315, -122.3390359],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_472a41253debd3959f90cc2a55d55f03.bindTooltip(
                `<div>
                     Vetri Glass Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7738d524e0b7b3b3abee50b6a6ba3d7d = L.marker(
                [47.60501625, -122.3295729],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7738d524e0b7b3b3abee50b6a6ba3d7d.bindTooltip(
                `<div>
                     Municipal Tower Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_359873d18f45a2a1ef2f0ae559ef40b6 = L.marker(
                [47.556855, -122.284429],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_359873d18f45a2a1ef2f0ae559ef40b6.bindTooltip(
                `<div>
                     Royal Esquire Club Inc.
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9344057ac8417ae7995225f728795dc6 = L.marker(
                [47.687136, -122.355306],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9344057ac8417ae7995225f728795dc6.bindTooltip(
                `<div>
                     Stretch and Staple Canvas Printing Company
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cefb8a44111ea17b18b50984d78c6711 = L.marker(
                [47.6019002, -122.3137703],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cefb8a44111ea17b18b50984d78c6711.bindTooltip(
                `<div>
                     Central District Forum for Arts & Ideas
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d34576a672be8d2c205a6f4a050f6121 = L.marker(
                [47.7059559, -122.3228384],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d34576a672be8d2c205a6f4a050f6121.bindTooltip(
                `<div>
                     Seattle Public Library Northgate
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ff5ca6b27413b25b9f8a38fab0560783 = L.marker(
                [47.7060528, -122.3397162],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ff5ca6b27413b25b9f8a38fab0560783.bindTooltip(
                `<div>
                     Fucko Alley Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9310313a81ff94c45cf240ab9b9c03d3 = L.marker(
                [47.5951899, -122.3099181],
                {"tags": ["Live/Work"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9310313a81ff94c45cf240ab9b9c03d3.bindTooltip(
                `<div>
                     Artspace Hiawatha Lofts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4da748358b25678cebcc894af78e2897 = L.marker(
                [47.62056855, -122.350491],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4da748358b25678cebcc894af78e2897.bindTooltip(
                `<div>
                     Seattle Center Mural Ampitheater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3b0ba3ab465784933e1d7fed6cbe8cc4 = L.marker(
                [47.6536581, -122.3168679],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3b0ba3ab465784933e1d7fed6cbe8cc4.bindTooltip(
                `<div>
                     University of Washington Hutchison Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_23045f5a0e05770c288b0077168761cf = L.marker(
                [47.665541, -122.3178615],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_23045f5a0e05770c288b0077168761cf.bindTooltip(
                `<div>
                     Seattle Public Library University
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_177ae5a23c48a9740cc0c4285443a0c8 = L.marker(
                [47.539423, -122.291018],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_177ae5a23c48a9740cc0c4285443a0c8.bindTooltip(
                `<div>
                     East African Community Services
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a32b34492978ac2c89dae90f5538a862 = L.marker(
                [47.5989643, -122.3331035],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a32b34492978ac2c89dae90f5538a862.bindTooltip(
                `<div>
                     Gallery IMA
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bbff6e99cade5edef919bfd39e219651 = L.marker(
                [47.656761, -122.312027],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bbff6e99cade5edef919bfd39e219651.bindTooltip(
                `<div>
                     University of Washington D Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5c8b54d400a9eb0170105a4989183e68 = L.marker(
                [47.693851, -122.317268],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5c8b54d400a9eb0170105a4989183e68.bindTooltip(
                `<div>
                     Math 'n' Stuff
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d2b759c537eaf60400d05df0b6ebbff9 = L.marker(
                [47.6132461, -122.3409939],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d2b759c537eaf60400d05df0b6ebbff9.bindTooltip(
                `<div>
                     Sub Pop Records
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ba0d159a9deb52685d03e536ae681f95 = L.marker(
                [47.551598, -122.375336],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ba0d159a9deb52685d03e536ae681f95.bindTooltip(
                `<div>
                     Khambatta Dance Company
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_49429b49398911d3cc40a43ee2198166 = L.marker(
                [47.619567, -122.359014],
                {"tags": ["Live/Work"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_49429b49398911d3cc40a43ee2198166.bindTooltip(
                `<div>
                     Bayview Work Lofts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_910a5a6d28f620efa2cfee46922cb414 = L.marker(
                [47.608811, -122.340249],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_910a5a6d28f620efa2cfee46922cb414.bindTooltip(
                `<div>
                     Can Can Kitchen and Cabaret
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_354b7b0c6ea39726dcb2a090f5ad67b6 = L.marker(
                [47.68239, -122.26369],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_354b7b0c6ea39726dcb2a090f5ad67b6.bindTooltip(
                `<div>
                     Seattle Musical Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8a5776a45bd0ac186978d4b91475ce15 = L.marker(
                [47.513939, -122.38636],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8a5776a45bd0ac186978d4b91475ce15.bindTooltip(
                `<div>
                     Brace Point Pottery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cdb41268886c1f466ea20e1116ffa022 = L.marker(
                [47.600886, -122.334547],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cdb41268886c1f466ea20e1116ffa022.bindTooltip(
                `<div>
                     Emerald City Guitars
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4f518a6ad708dbab3fb4b959613f24cb = L.marker(
                [47.6229209, -122.3293344],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4f518a6ad708dbab3fb4b959613f24cb.bindTooltip(
                `<div>
                     Lo-Fi Performance Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_94a0641ea1097080c7a1ece8dbd75052 = L.marker(
                [47.60502955, -122.3171573],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_94a0641ea1097080c7a1ece8dbd75052.bindTooltip(
                `<div>
                     Flying House Productions
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_25d6de0ab7d2ece0c37d8d3246c7bbe4 = L.marker(
                [47.6086439, -122.337685],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_25d6de0ab7d2ece0c37d8d3246c7bbe4.bindTooltip(
                `<div>
                     Triple Door Theater and Musicquarium Lounge
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_541157041d78058248e946da3fab9942 = L.marker(
                [47.539026, -122.388536],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_541157041d78058248e946da3fab9942.bindTooltip(
                `<div>
                     Northwest Encaustic
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1f92cc1b09b370eae17e20b076f0d2b1 = L.marker(
                [47.553764, -122.387314],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1f92cc1b09b370eae17e20b076f0d2b1.bindTooltip(
                `<div>
                     OutWest
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_361559b4fa58ce4da0aba4648c9988fd = L.marker(
                [47.595059, -122.326235],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_361559b4fa58ce4da0aba4648c9988fd.bindTooltip(
                `<div>
                     Glassbox
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7f7e8dacdfe5d79f583ba812cd727afa = L.marker(
                [47.6151383, -122.342923],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7f7e8dacdfe5d79f583ba812cd727afa.bindTooltip(
                `<div>
                     Bad Animals
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0145e9aabc63c8574144172cccca3d63 = L.marker(
                [47.55059151, -122.3183935],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0145e9aabc63c8574144172cccca3d63.bindTooltip(
                `<div>
                     Georgetown Trailer Park Mall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_09db0e0d61da1548403bfba23b1e7358 = L.marker(
                [47.5803398, -122.3112978],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_09db0e0d61da1548403bfba23b1e7358.bindTooltip(
                `<div>
                     El Centro de la Raza
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f9fa178a699177f595daa2cf41a69ffc = L.marker(
                [47.64052875, -122.3758254],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f9fa178a699177f595daa2cf41a69ffc.bindTooltip(
                `<div>
                     Master Works
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b78b6aaa70113b3569b273c8633d6dc3 = L.marker(
                [47.6091749, -122.3339671],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b78b6aaa70113b3569b273c8633d6dc3.bindTooltip(
                `<div>
                     5th Avenue Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ab8c7b758d7c7e0f732c1f258e1249eb = L.marker(
                [47.638016, -122.294137],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ab8c7b758d7c7e0f732c1f258e1249eb.bindTooltip(
                `<div>
                     Washington Park Arboretum and Madison Park Graham Visitors Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cabce947c71a5277ebe2778c2e3e89f4 = L.marker(
                [47.6148138, -122.3217378],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cabce947c71a5277ebe2778c2e3e89f4.bindTooltip(
                `<div>
                     Erickson Theater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0886d2f8554686e226a2ab1bd2b00074 = L.marker(
                [47.61819595, -122.3362331],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0886d2f8554686e226a2ab1bd2b00074.bindTooltip(
                `<div>
                     ArtsFund
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c81936eb63db7d36b822d379a7852791 = L.marker(
                [47.597744, -122.312012],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c81936eb63db7d36b822d379a7852791.bindTooltip(
                `<div>
                     JCCCW Japanese Cultural & Community Center of WA
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3d7aa077d8e2b8ee871ba5064a2e4384 = L.marker(
                [47.548977, -122.31663],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3d7aa077d8e2b8ee871ba5064a2e4384.bindTooltip(
                `<div>
                     Brass Tacks
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1a1503b867969fde123ac0b0b465fd45 = L.marker(
                [47.594673, -122.309662],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1a1503b867969fde123ac0b0b465fd45.bindTooltip(
                `<div>
                     Nu Black Arts West Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6da7bcb4b1225691966264981ba45436 = L.marker(
                [47.644508, -122.399582],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6da7bcb4b1225691966264981ba45436.bindTooltip(
                `<div>
                     Magnolia Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3574f0c7e1d9d038784ab679c142caf5 = L.marker(
                [47.54807515, -122.3758471],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3574f0c7e1d9d038784ab679c142caf5.bindTooltip(
                `<div>
                     Seattle Public Library High Point
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8563398fc2e3a086a5ee69f6e2f7e413 = L.marker(
                [47.6394417, -122.3660888],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8563398fc2e3a086a5ee69f6e2f7e413.bindTooltip(
                `<div>
                     Fountainhead Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c647518e0ffd609c33baf7a4e4e37f91 = L.marker(
                [47.65066, -122.34989],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c647518e0ffd609c33baf7a4e4e37f91.bindTooltip(
                `<div>
                     Atlas Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8bcd78d66ed714f3d4544004e7a581d3 = L.marker(
                [47.623844, -122.349586],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8bcd78d66ed714f3d4544004e7a581d3.bindTooltip(
                `<div>
                     Pacific Northwest Ballet
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_89a9b7f9d22d8462a9c1626865822b8c = L.marker(
                [47.601849, -122.308388],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_89a9b7f9d22d8462a9c1626865822b8c.bindTooltip(
                `<div>
                     Seattle Neighborhood Group
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0962b6034e1c9a4fc734579e5381a1ac = L.marker(
                [47.623726, -122.342773],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0962b6034e1c9a4fc734579e5381a1ac.bindTooltip(
                `<div>
                     Photo-tronics, Inc.
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_41dcd159cd04cabb1f851a2d8251f686 = L.marker(
                [47.669975, -122.313045],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_41dcd159cd04cabb1f851a2d8251f686.bindTooltip(
                `<div>
                     The Audio Connection
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_39da0c246b85b4414b5c650cda78501e = L.marker(
                [47.572735, -122.37043],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_39da0c246b85b4414b5c650cda78501e.bindTooltip(
                `<div>
                     West Seattle Fabric Company
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_64239b38a682610d3bdbcf0469909386 = L.marker(
                [47.521026, -122.363573],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_64239b38a682610d3bdbcf0469909386.bindTooltip(
                `<div>
                     Barnes & Noble - Westwood Village
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ba1d85687845ee965d2cd9ba2f745345 = L.marker(
                [47.5719192, -122.3342902],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ba1d85687845ee965d2cd9ba2f745345.bindTooltip(
                `<div>
                     Danse Perdue's Psychomachia Theater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9f16b7ad83c767e2e8bd5de0cf35b829 = L.marker(
                [47.606213, -122.333794],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9f16b7ad83c767e2e8bd5de0cf35b829.bindTooltip(
                `<div>
                     The Hyogo Business and Cultural Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f94b38f7c5e43b0b86ad57b3e0f1bb2c = L.marker(
                [47.569634, -122.307473],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f94b38f7c5e43b0b86ad57b3e0f1bb2c.bindTooltip(
                `<div>
                     Jefferson Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_eeb3746cd3641bc88910175f8f171cb8 = L.marker(
                [47.553658, -122.335594],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_eeb3746cd3641bc88910175f8f171cb8.bindTooltip(
                `<div>
                     Earwig Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5fe3b3f5f97d4e4db09e2486149c235c = L.marker(
                [47.6007271, -122.3313269],
                {"tags": ["Live/Work"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5fe3b3f5f97d4e4db09e2486149c235c.bindTooltip(
                `<div>
                     Impact Hub Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1e3969c578319f2b4c01dd90f3acbef8 = L.marker(
                [47.6378686, -122.3571792],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1e3969c578319f2b4c01dd90f3acbef8.bindTooltip(
                `<div>
                     Paragon
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9380d344bbab8edf11a7fd5da4129f6c = L.marker(
                [47.72447, -122.348],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9380d344bbab8edf11a7fd5da4129f6c.bindTooltip(
                `<div>
                     Bitter Lake Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1ddd4e763c797123468c21ef9aff44c4 = L.marker(
                [47.59507, -122.327179],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1ddd4e763c797123468c21ef9aff44c4.bindTooltip(
                `<div>
                     Shunpike
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3c4410adce53e8a6432aba6125a89236 = L.marker(
                [47.551707, -122.277981],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3c4410adce53e8a6432aba6125a89236.bindTooltip(
                `<div>
                     The Collaboratory
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ef13ebfb004ca6bb933a23d6702c20bf = L.marker(
                [47.72465145, -122.3293843],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ef13ebfb004ca6bb933a23d6702c20bf.bindTooltip(
                `<div>
                     Haller Lake United Methodist Church
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d91c0257b1b29899b36e1674abec131c = L.marker(
                [47.691631, -122.355713],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d91c0257b1b29899b36e1674abec131c.bindTooltip(
                `<div>
                     Urban Light Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8714c84c648816dd52f735dbb63329f9 = L.marker(
                [47.619053, -122.336395],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8714c84c648816dd52f735dbb63329f9.bindTooltip(
                `<div>
                     The Seattle Times
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_95d7b6c01cf1475cc5547f0270624616 = L.marker(
                [47.66209, -122.39917],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_95d7b6c01cf1475cc5547f0270624616.bindTooltip(
                `<div>
                     Sunshine from Polynesia
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_59b21af1edb5db9bedf781dc80346160 = L.marker(
                [47.551817, -122.319454],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_59b21af1edb5db9bedf781dc80346160.bindTooltip(
                `<div>
                     Georgetown Atelier
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1a02a6314b1144ebf3d83c7cd25d1653 = L.marker(
                [47.649357, -122.360626],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1a02a6314b1144ebf3d83c7cd25d1653.bindTooltip(
                `<div>
                     First Free Methodist
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e89a9dad9b48ad7656a5ee8bd3b74476 = L.marker(
                [47.610874, -122.32547],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e89a9dad9b48ad7656a5ee8bd3b74476.bindTooltip(
                `<div>
                     Historic Seattle Dearborn House
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f8288eddf9f2695a09a08d89ad2077af = L.marker(
                [47.691212, -122.354279],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f8288eddf9f2695a09a08d89ad2077af.bindTooltip(
                `<div>
                     All That Dance
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_872d13b8619f9acfcaddb06a9bcc70f0 = L.marker(
                [47.719806, -122.297703],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_872d13b8619f9acfcaddb06a9bcc70f0.bindTooltip(
                `<div>
                     Arab Center of Washington
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_98f76df1155ff5d432a79c31d044028f = L.marker(
                [47.6038849, -122.3300938],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_98f76df1155ff5d432a79c31d044028f.bindTooltip(
                `<div>
                     City Hall Lobby Gallery & Anne Focke Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7b08aff87f9b0cda7668d397be1904b2 = L.marker(
                [47.6133929, -122.3259406],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7b08aff87f9b0cda7668d397be1904b2.bindTooltip(
                `<div>
                     The Northwest School
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ab9b48af2da579e7bdb42ee49f7970ee = L.marker(
                [47.5900022, -122.3362466],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ab9b48af2da579e7bdb42ee49f7970ee.bindTooltip(
                `<div>
                     Bemis Building
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5caf996fff4dd134d05842d105b0efc6 = L.marker(
                [47.6127484, -122.3192097],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5caf996fff4dd134d05842d105b0efc6.bindTooltip(
                `<div>
                     Pound Arts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_eff480a62d6330b09d289afd6bf7de51 = L.marker(
                [47.623882, -122.348251],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_eff480a62d6330b09d289afd6bf7de51.bindTooltip(
                `<div>
                     KCTS 9
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_245ca98a9400f8cc9365d8dcf472f0ae = L.marker(
                [47.654293, -122.324905],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_245ca98a9400f8cc9365d8dcf472f0ae.bindTooltip(
                `<div>
                     Gasworks Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_746e94bbeb9d4032492a1b6d8411001f = L.marker(
                [47.615789, -122.3441663],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_746e94bbeb9d4032492a1b6d8411001f.bindTooltip(
                `<div>
                     AXIS Pioneer Square
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_03cfa1bad0191446213e3feb87352d6d = L.marker(
                [47.599457, -122.333794],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_03cfa1bad0191446213e3feb87352d6d.bindTooltip(
                `<div>
                     Linda Hodges Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3e2160251113fe97e316f4bc19884c5c = L.marker(
                [47.6129328, -122.3181106],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3e2160251113fe97e316f4bc19884c5c.bindTooltip(
                `<div>
                     Crybaby Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7ecbef64a6603dedfd4c0bd26f7cc259 = L.marker(
                [47.6106553, -122.3171103],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7ecbef64a6603dedfd4c0bd26f7cc259.bindTooltip(
                `<div>
                     KXSU Radio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4141a3cf59d6c178ebbb7a11af174105 = L.marker(
                [47.66116457, -122.3388849],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4141a3cf59d6c178ebbb7a11af174105.bindTooltip(
                `<div>
                     Seattle Public Library Wallingford
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_35ae3430e6d6bd8848055a5baac94ea8 = L.marker(
                [47.62149775, -122.3482387],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_35ae3430e6d6bd8848055a5baac94ea8.bindTooltip(
                `<div>
                     Seattle Center EMP and Sky Church
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a94e38930d0fb97bb60c24b2cbdeb9fc = L.marker(
                [47.5775947, -122.4109498],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a94e38930d0fb97bb60c24b2cbdeb9fc.bindTooltip(
                `<div>
                     Log House Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2ec241d84bee8ae4a5f1346fdd4787aa = L.marker(
                [47.5819689, -122.3869421],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2ec241d84bee8ae4a5f1346fdd4787aa.bindTooltip(
                `<div>
                     Admiral Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b787366596846d4e6416c68041f13fe3 = L.marker(
                [47.61407, -122.321734],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b787366596846d4e6416c68041f13fe3.bindTooltip(
                `<div>
                     Capitol Cider
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7018ea1d317961ce8b97d8ad15c65009 = L.marker(
                [47.5514664, -122.3283134],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7018ea1d317961ce8b97d8ad15c65009.bindTooltip(
                `<div>
                     CoCA
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c04bd8e33b84f664c13c69d71983228d = L.marker(
                [47.556461, -122.268508],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c04bd8e33b84f664c13c69d71983228d.bindTooltip(
                `<div>
                     The Makery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a67bb26049ee8718850b04cad4a78c1d = L.marker(
                [47.52876, -122.322873],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a67bb26049ee8718850b04cad4a78c1d.bindTooltip(
                `<div>
                     South Park Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ad9ac52a14eca3898fcf17b055b31b78 = L.marker(
                [47.6870482, -122.3554887],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ad9ac52a14eca3898fcf17b055b31b78.bindTooltip(
                `<div>
                     American Dance Institute
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_697dd10148d3304f88e4fd9d91d5c01e = L.marker(
                [47.593601, -122.3334874],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_697dd10148d3304f88e4fd9d91d5c01e.bindTooltip(
                `<div>
                     WaMu Theater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6b491ee3ffb2b01190c9a937e339a4b6 = L.marker(
                [47.621688, -122.307328],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6b491ee3ffb2b01190c9a937e339a4b6.bindTooltip(
                `<div>
                     Miller Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_223672938f08429c14e175a9d0bb193f = L.marker(
                [47.6685294, -122.3793357],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_223672938f08429c14e175a9d0bb193f.bindTooltip(
                `<div>
                     Egan's Ballard Jam House
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d0e8dcf9e7c50fb802a1e31a2a32f761 = L.marker(
                [47.698452, -122.346947],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d0e8dcf9e7c50fb802a1e31a2a32f761.bindTooltip(
                `<div>
                     Music Center of the Northwest
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ab4d3e9354c5a8dffabe263f19318aa5 = L.marker(
                [47.614746, -122.319069],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ab4d3e9354c5a8dffabe263f19318aa5.bindTooltip(
                `<div>
                     Everyday Music
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6234bc4c91328b04f1c0c429d69205d9 = L.marker(
                [47.6701069, -122.313258],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6234bc4c91328b04f1c0c429d69205d9.bindTooltip(
                `<div>
                     Danaca Design
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e32b1481e527f941b7083ad2daed7683 = L.marker(
                [47.5524608, -122.3317069],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e32b1481e527f941b7083ad2daed7683.bindTooltip(
                `<div>
                     Seattle Arts & Lectures
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_114109521e719c97d9444385e01c4f29 = L.marker(
                [47.6585722, -122.3065403],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_114109521e719c97d9444385e01c4f29.bindTooltip(
                `<div>
                     University of Washington Jacob Lawrence Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0f194c1e72f5800b567e1d08c1053058 = L.marker(
                [47.6136108, -122.3444191],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0f194c1e72f5800b567e1d08c1053058.bindTooltip(
                `<div>
                     Tula's
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_878d1286c504cfe0fb44c5772f6d876e = L.marker(
                [47.60812795, -122.3369748],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_878d1286c504cfe0fb44c5772f6d876e.bindTooltip(
                `<div>
                     Benaroya Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_241c6badfb538d9676934fd2c7175651 = L.marker(
                [47.5994156, -122.3305147],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_241c6badfb538d9676934fd2c7175651.bindTooltip(
                `<div>
                     Grover Thurston Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_acd26fe87622f2e490adc5c150b7543e = L.marker(
                [47.5980081, -122.3248662],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_acd26fe87622f2e490adc5c150b7543e.bindTooltip(
                `<div>
                     Seattle Pinball Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9d59e230104a05cd63dd12062d256a39 = L.marker(
                [47.55786, -122.285888],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9d59e230104a05cd63dd12062d256a39.bindTooltip(
                `<div>
                     Rainier Valley Historical Society
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fa28dd93ed3cdaa574aadf7ca307740f = L.marker(
                [47.6585538, -122.3133686],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fa28dd93ed3cdaa574aadf7ca307740f.bindTooltip(
                `<div>
                     Open Flight Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bd0e9a80c5cf35d3108170f90281e1c1 = L.marker(
                [47.639149, -122.326256],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bd0e9a80c5cf35d3108170f90281e1c1.bindTooltip(
                `<div>
                     The Tudor Choir
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_636bea1317d3d96c122559785fc20dcc = L.marker(
                [47.65492433, -122.3145764],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_636bea1317d3d96c122559785fc20dcc.bindTooltip(
                `<div>
                     University of Washington Samuel E. Kelly Ethnic Cultural Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a3c1796e9ff06d1097d7ae848c2ca1d3 = L.marker(
                [47.66093, -122.314283],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a3c1796e9ff06d1097d7ae848c2ca1d3.bindTooltip(
                `<div>
                     Neptune Music Co
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8df967a3d7117248f13df9858fa9ecee = L.marker(
                [47.6132437, -122.331356],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8df967a3d7117248f13df9858fa9ecee.bindTooltip(
                `<div>
                     STG Paramount Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_540983f093bb6621d54448dbd3c8caf8 = L.marker(
                [47.64532095, -122.4013599],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_540983f093bb6621d54448dbd3c8caf8.bindTooltip(
                `<div>
                     Seattle Public Library Magnolia
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6693425ed16b042778822bf381ea8def = L.marker(
                [47.6102805, -122.3424974],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6693425ed16b042778822bf381ea8def.bindTooltip(
                `<div>
                     Pink Door
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_227666bab9a49b932d898c76ca8b4c7e = L.marker(
                [47.5494855, -122.2518888],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_227666bab9a49b932d898c76ca8b4c7e.bindTooltip(
                `<div>
                     Seward Park Clay Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a6cb3d72f8b18f5b0d7c014445fd3cb6 = L.marker(
                [47.705251, -122.290856],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a6cb3d72f8b18f5b0d7c014445fd3cb6.bindTooltip(
                `<div>
                     Meadowbrook Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0c11c0f8b3d3a3bfbb12ba2b308f44cf = L.marker(
                [47.558342, -122.284828],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0c11c0f8b3d3a3bfbb12ba2b308f44cf.bindTooltip(
                `<div>
                     Green Eileen
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ede59d5d12a50f842e921fb995fcb2b3 = L.marker(
                [47.6916342, -122.3557113],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ede59d5d12a50f842e921fb995fcb2b3.bindTooltip(
                `<div>
                     Echo Echo Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ede14379baa4737c2749e8cf06efc71b = L.marker(
                [47.6259637, -122.3582053],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ede14379baa4737c2749e8cf06efc71b.bindTooltip(
                `<div>
                     On the Boards
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a4ffc96dd3c622e35e71a8153323d5e0 = L.marker(
                [47.554125, -122.281108],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a4ffc96dd3c622e35e71a8153323d5e0.bindTooltip(
                `<div>
                     Rainier Chamber of Commerce & Rainier Chamber Foundation
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_266b300749f3607f78e8d33865aee6bb = L.marker(
                [47.58682808, -122.3044908],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_266b300749f3607f78e8d33865aee6bb.bindTooltip(
                `<div>
                     Seattle Scenic Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2a8b4b3b14de0395c1bfaff44edba887 = L.marker(
                [47.658765, -122.3178929],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2a8b4b3b14de0395c1bfaff44edba887.bindTooltip(
                `<div>
                     University of Washington Glenn Hughes Penthouse Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_25bbdf85052b43abc38a57319bad9540 = L.marker(
                [47.622963, -122.341438],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_25bbdf85052b43abc38a57319bad9540.bindTooltip(
                `<div>
                     Glazer's Camera
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2cd34c14a80fea8623d16d9aff6d1404 = L.marker(
                [47.5803398, -122.3112978],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2cd34c14a80fea8623d16d9aff6d1404.bindTooltip(
                `<div>
                     Seattle Fandango Project in El Centro De La Raza
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c8dc9611873d8a90bc7a5c369deed59a = L.marker(
                [47.5995076, -122.3326934],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c8dc9611873d8a90bc7a5c369deed59a.bindTooltip(
                `<div>
                     Christian Grevstad Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a09b701a94692845130f5fb8aeabfb05 = L.marker(
                [47.560926, -122.384098],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a09b701a94692845130f5fb8aeabfb05.bindTooltip(
                `<div>
                     School of Rock West Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c38ff726d736bbbfa36dcaf2b119e58f = L.marker(
                [47.523941, -122.2762979],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c38ff726d736bbbfa36dcaf2b119e58f.bindTooltip(
                `<div>
                     Somali Community Services of Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f0860f7c8939271dbf7e85cd5a058bf7 = L.marker(
                [47.599202, -122.326082],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f0860f7c8939271dbf7e85cd5a058bf7.bindTooltip(
                `<div>
                     Kobo at Hibo
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fc94542746e4e39a51675318dc5db7c1 = L.marker(
                [47.599537, -122.331978],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fc94542746e4e39a51675318dc5db7c1.bindTooltip(
                `<div>
                     88 Keys Dueling Piano Bar
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4d39d8ff1090720aff25d6602ee5be80 = L.marker(
                [47.6081862, -122.3025461],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4d39d8ff1090720aff25d6602ee5be80.bindTooltip(
                `<div>
                     Coyote Central
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e79a1ce0621e3bba06739e5f3b2e45e8 = L.marker(
                [47.6513614, -122.3534984],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e79a1ce0621e3bba06739e5f3b2e45e8.bindTooltip(
                `<div>
                     ArtFX Studio Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_58ea5ff81ff6f1ee96f7f566435e1d18 = L.marker(
                [47.62178, -122.359718],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_58ea5ff81ff6f1ee96f7f566435e1d18.bindTooltip(
                `<div>
                     House Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_51cd5de105a34634ed639c138b6fabc8 = L.marker(
                [47.558197, -122.2850094],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_51cd5de105a34634ed639c138b6fabc8.bindTooltip(
                `<div>
                     Columbia City Gallery SEEDArts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3eadc4b6fb0ae194ef6e60ab82a32601 = L.marker(
                [47.6563251, -122.3076233],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3eadc4b6fb0ae194ef6e60ab82a32601.bindTooltip(
                `<div>
                     University of Washington East Asia Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_36e2df9d67db94bcfb6a8664ef4781ca = L.marker(
                [47.68213235, -122.2632982],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_36e2df9d67db94bcfb6a8664ef4781ca.bindTooltip(
                `<div>
                     Sand Point Arts & Cultural Exchange
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7c99564b737f4e35db3948ac8b10d480 = L.marker(
                [47.7086, -122.32479],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7c99564b737f4e35db3948ac8b10d480.bindTooltip(
                `<div>
                     Tall's Camera
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ad8d959bc3c6d190f7f355e90e1e85ba = L.marker(
                [47.562161, -122.38679],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ad8d959bc3c6d190f7f355e90e1e85ba.bindTooltip(
                `<div>
                     Leisure Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3f79c21fd6b9c115ac6f2d1f668c7eab = L.marker(
                [47.6672369, -122.2770498],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3f79c21fd6b9c115ac6f2d1f668c7eab.bindTooltip(
                `<div>
                     New West Edition
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d3a1746019e68890fe98898aac7cdaf4 = L.marker(
                [47.56452925, -122.3858692],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d3a1746019e68890fe98898aac7cdaf4.bindTooltip(
                `<div>
                     Unified Outreach Youth Arts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_06c4c637ad64050febf4fb1043dbe44e = L.marker(
                [47.671066, -122.373662],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_06c4c637ad64050febf4fb1043dbe44e.bindTooltip(
                `<div>
                     Blowing Sands Glass Studio/Laura Frost Fine Arts Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8b25a8ae24e9b07ae2581f1be3de8946 = L.marker(
                [47.627329, -122.36935],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8b25a8ae24e9b07ae2581f1be3de8946.bindTooltip(
                `<div>
                     Greg Thompson Productions
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_135027327eb7d90b201a0b051f2f3d33 = L.marker(
                [47.6230082, -122.2907548],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_135027327eb7d90b201a0b051f2f3d33.bindTooltip(
                `<div>
                     MLK Community Center-Ewajo Dance Center and F.A.M.E.
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fd372987ec33a4eb78972077a225e766 = L.marker(
                [47.655709, -122.310569],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fd372987ec33a4eb78972077a225e766.bindTooltip(
                `<div>
                     University of Washington Meany Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9dd5ad32a9d73c2805f8312c09b76121 = L.marker(
                [47.5977324, -122.326797],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9dd5ad32a9d73c2805f8312c09b76121.bindTooltip(
                `<div>
                     Nagomi Tea House
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6254d402246e5aa86df072c8c4088f16 = L.marker(
                [47.6071955, -122.3382555],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6254d402246e5aa86df072c8c4088f16.bindTooltip(
                `<div>
                     Seattle Art Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_62da97c730fa32b1103aaa8f1111076c = L.marker(
                [47.658562, -122.313115],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_62da97c730fa32b1103aaa8f1111076c.bindTooltip(
                `<div>
                     Bulldog News
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_35bca91ca4bdd7bd2ca6182c8fb08da3 = L.marker(
                [47.5963028, -122.3338311],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_35bca91ca4bdd7bd2ca6182c8fb08da3.bindTooltip(
                `<div>
                     HeART, the Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5dfe1199f80d8fa677f284b884c2144d = L.marker(
                [47.6684204, -122.350826],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5dfe1199f80d8fa677f284b884c2144d.bindTooltip(
                `<div>
                     Woodland Park Zoo and Stage
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_048dcb181c6c7d10db2943ab9424e8c3 = L.marker(
                [47.6689407, -122.3793225],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_048dcb181c6c7d10db2943ab9424e8c3.bindTooltip(
                `<div>
                     Ballard Alki Lodge IOOF-Ballard-Alki Lodge #170
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_724ca8371a80135de306d01a5a7f8e2a = L.marker(
                [47.5420331, -122.272057],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_724ca8371a80135de306d01a5a7f8e2a.bindTooltip(
                `<div>
                     Planet Afua
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5b8e05db4c08bee73c5005a8349b9843 = L.marker(
                [47.61456, -122.315534],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5b8e05db4c08bee73c5005a8349b9843.bindTooltip(
                `<div>
                     Cuff Complex
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_723e5d361b577bed1789f11a866db0bc = L.marker(
                [47.5779867, -122.3114095],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_723e5d361b577bed1789f11a866db0bc.bindTooltip(
                `<div>
                     Seattle Public Library Beacon Hill
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_95d35ae6571295711f363dc2643194ac = L.marker(
                [47.6144145, -122.3179029],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_95d35ae6571295711f363dc2643194ac.bindTooltip(
                `<div>
                     Vermillion Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b4791a89011442a4a1a7eedafeddec90 = L.marker(
                [47.6778643, -122.2907142],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b4791a89011442a4a1a7eedafeddec90.bindTooltip(
                `<div>
                     Seattle Public Library Northeast
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_701d3440e4532a50d8898c19593db057 = L.marker(
                [47.574394, -122.333908],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_701d3440e4532a50d8898c19593db057.bindTooltip(
                `<div>
                     Monster Concerts INC DBA STUDIO SEVEN
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_96f88ef9bc13f004a77f80ce15fefd25 = L.marker(
                [47.6190574, -122.3473634],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_96f88ef9bc13f004a77f80ce15fefd25.bindTooltip(
                `<div>
                     Seattle Center SIS Productions/ReAct & Pork Filled Players at Prima Vera Arts Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_057e211632056538935e865f289c282a = L.marker(
                [47.6803384, -122.3577114],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_057e211632056538935e865f289c282a.bindTooltip(
                `<div>
                     Ostara Group
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6f876db6f9a291ef9074e4b81ae7ea43 = L.marker(
                [47.623844, -122.349586],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6f876db6f9a291ef9074e4b81ae7ea43.bindTooltip(
                `<div>
                     Seattle Center Phelps Center PNB Studios & Offices
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1fe275b758d5b501b7f78b41818117e9 = L.marker(
                [47.63905, -122.357315],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1fe275b758d5b501b7f78b41818117e9.bindTooltip(
                `<div>
                     Nancy's Sewing Basket
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_18757cf31c39c3ec4325775cbac9af14 = L.marker(
                [47.6576318, -122.4063301],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_18757cf31c39c3ec4325775cbac9af14.bindTooltip(
                `<div>
                     Red Eagle Soaring Native Youth Theatre and Daybreak Star Cultural Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8a89fa2abe69d88f185e6e4fc3a8f8c8 = L.marker(
                [47.6040236, -122.3309956],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8a89fa2abe69d88f185e6e4fc3a8f8c8.bindTooltip(
                `<div>
                     Seattle Public Library International Districtrict/Chinatown
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_979097b15b8fbf9b86b4f54f18cef751 = L.marker(
                [47.714474, -122.304138],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_979097b15b8fbf9b86b4f54f18cef751.bindTooltip(
                `<div>
                     Piano Studio Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3cdf47040e259249fa4b497909b936dc = L.marker(
                [47.605053, -122.340225],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3cdf47040e259249fa4b497909b936dc.bindTooltip(
                `<div>
                     Threshold Gallery at Mithun
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_868d003e0f547572c7b37214fd3e26e2 = L.marker(
                [47.707703, -122.323263],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_868d003e0f547572c7b37214fd3e26e2.bindTooltip(
                `<div>
                     Kennelly Keys Music
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ecf3677b4e678b51e1e1982890f4302b = L.marker(
                [47.656517, -122.342033],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ecf3677b4e678b51e1e1982890f4302b.bindTooltip(
                `<div>
                     Seattle Conservatory of Music
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1d81a6fd38869556ffb25d95d8fffb38 = L.marker(
                [47.721649, -122.345955],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1d81a6fd38869556ffb25d95d8fffb38.bindTooltip(
                `<div>
                     Oberloh Woodwind and Brass Works
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c073b56bd70395f3d075af6651e41754 = L.marker(
                [47.597092, -122.317932],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c073b56bd70395f3d075af6651e41754.bindTooltip(
                `<div>
                     Seattle Indian Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_689cc056c0fe41103ee61e70d35a4a5d = L.marker(
                [47.624592, -122.356451],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_689cc056c0fe41103ee61e70d35a4a5d.bindTooltip(
                `<div>
                     Mercer Street Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0023cf93b62e7668f613fc708d54cfac = L.marker(
                [47.654404, -122.370996],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0023cf93b62e7668f613fc708d54cfac.bindTooltip(
                `<div>
                     Voda Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_dff99c32624ab92301e0e966c4f9d46e = L.marker(
                [47.5524847, -122.3339033],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_dff99c32624ab92301e0e966c4f9d46e.bindTooltip(
                `<div>
                     Slim's Last Chance
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ccbe371317cfe95e69cd0a5393f2609b = L.marker(
                [47.60004, -122.333781],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ccbe371317cfe95e69cd0a5393f2609b.bindTooltip(
                `<div>
                     Cafe Nordo
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f89b33fc37c39d31b271a46c7f1da63f = L.marker(
                [47.59922, -122.333919],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f89b33fc37c39d31b271a46c7f1da63f.bindTooltip(
                `<div>
                     Purlieu Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_33e7a03577b97b68241fe7f7fe388c44 = L.marker(
                [47.559012, -122.285612],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_33e7a03577b97b68241fe7f7fe388c44.bindTooltip(
                `<div>
                     Ark Lodge Cinemas
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d60aca7aa0bab8fcc6e96e09137834ce = L.marker(
                [47.6612543, -122.3656412],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d60aca7aa0bab8fcc6e96e09137834ce.bindTooltip(
                `<div>
                     Superior Audio Service
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8637f9adf79dbad691c00be067091e84 = L.marker(
                [47.536369, -122.293419],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8637f9adf79dbad691c00be067091e84.bindTooltip(
                `<div>
                     International Drop-In Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e3d5e37a3fa42bab220232e7658741a0 = L.marker(
                [47.7203793, -122.2979988],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e3d5e37a3fa42bab220232e7658741a0.bindTooltip(
                `<div>
                     North Seattle Chamber of Commerce/Lake City Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_79a50d009da9aea277094ab657a4d728 = L.marker(
                [47.6182617, -122.3577413],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_79a50d009da9aea277094ab657a4d728.bindTooltip(
                `<div>
                     Canlis Glass
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2b5922b8bf5fe2e6b364b00cb28da3cb = L.marker(
                [47.622675, -122.297416],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2b5922b8bf5fe2e6b364b00cb28da3cb.bindTooltip(
                `<div>
                     Baas Framing Studio & The Madison Art Collective
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_129c4c47ebd5936ce2d10afa71d10391 = L.marker(
                [47.594554, -122.3095312],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_129c4c47ebd5936ce2d10afa71d10391.bindTooltip(
                `<div>
                     C Art Gallery in Artspace Hiawatha Lofts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8a3a35044c232080dc7198b31c1819dc = L.marker(
                [47.6513564, -122.3515985],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8a3a35044c232080dc7198b31c1819dc.bindTooltip(
                `<div>
                     High Dive
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f573d1b7ef02a8698539920dbb0d1b91 = L.marker(
                [47.579594, -122.3255672],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f573d1b7ef02a8698539920dbb0d1b91.bindTooltip(
                `<div>
                     Emerald City Trapeze
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7e9af87263c4b1c3bac0c4d2fba3df56 = L.marker(
                [47.62033, -122.320908],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7e9af87263c4b1c3bac0c4d2fba3df56.bindTooltip(
                `<div>
                     World Beads Capitol Hill
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_653e0acb419be27fc66aa7b3f4805494 = L.marker(
                [47.6239543, -122.3507651],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_653e0acb419be27fc66aa7b3f4805494.bindTooltip(
                `<div>
                     Seattle Center McCaw Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_486bcea8ecd22cbeda7d780258d5d109 = L.marker(
                [47.6134869, -122.3144433],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_486bcea8ecd22cbeda7d780258d5d109.bindTooltip(
                `<div>
                     Humanities Washington
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_33d6a913b8cc822840bdaccf87a5f8d0 = L.marker(
                [47.661797, -122.340996],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_33d6a913b8cc822840bdaccf87a5f8d0.bindTooltip(
                `<div>
                     The Drum Exchange
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7a2da92871db16d25e544c70223988aa = L.marker(
                [47.65168, -122.402069],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7a2da92871db16d25e544c70223988aa.bindTooltip(
                `<div>
                     Daybreak Star Cultural Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b07c64967b35c3c9a2ae119161fc48cc = L.marker(
                [47.69556835, -122.3124687],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b07c64967b35c3c9a2ae119161fc48cc.bindTooltip(
                `<div>
                     Northwest Puppet Center/ Carter Family Marionettes Maple Leaf
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9f29d9b59eed773a17bd62f3cb386fd7 = L.marker(
                [47.656467, -122.364128],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9f29d9b59eed773a17bd62f3cb386fd7.bindTooltip(
                `<div>
                     Glass Eye Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e30d6a3886d528a157b9298fd4576e7b = L.marker(
                [47.6115947, -122.3252001],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e30d6a3886d528a157b9298fd4576e7b.bindTooltip(
                `<div>
                     Washington State Arts Alliance
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_37071d787f764b6bb347f12a72c7d1e1 = L.marker(
                [47.614293, -122.346108],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_37071d787f764b6bb347f12a72c7d1e1.bindTooltip(
                `<div>
                     Peter Miller Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a1c7512c9a97792cbac6e0953f0f03bc = L.marker(
                [47.605728, -122.339195],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a1c7512c9a97792cbac6e0953f0f03bc.bindTooltip(
                `<div>
                     Seattle Metropolitan
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9f2f12df906fd13436429a6fbf12e1e7 = L.marker(
                [47.68667, -122.299241],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9f2f12df906fd13436429a6fbf12e1e7.bindTooltip(
                `<div>
                     Storum Jewish Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fd9a6c32b01e5aac07ddae3d2ff206b1 = L.marker(
                [47.5681098, -122.2973139],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fd9a6c32b01e5aac07ddae3d2ff206b1.bindTooltip(
                `<div>
                     Kings Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_62498b04008417c88eb2b19962e79494 = L.marker(
                [47.613079, -122.315788],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_62498b04008417c88eb2b19962e79494.bindTooltip(
                `<div>
                     Pony
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_157513d8f28f579536c91935a89120e4 = L.marker(
                [47.601907, -122.3017753],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_157513d8f28f579536c91935a89120e4.bindTooltip(
                `<div>
                     Seattle Public Library Douglas-Truth
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5ce3723a55290a7c392a7b6f645622b0 = L.marker(
                [47.6604, -122.280525],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5ce3723a55290a7c392a7b6f645622b0.bindTooltip(
                `<div>
                     Paint the Town
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ec985d54f0e45de6be507cbffb3dc84c = L.marker(
                [47.668137, -122.362778],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ec985d54f0e45de6be507cbffb3dc84c.bindTooltip(
                `<div>
                     Studio Litho
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_252c22b6a853091660e0e8b051e8e9e8 = L.marker(
                [47.675988, -122.306571],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_252c22b6a853091660e0e8b051e8e9e8.bindTooltip(
                `<div>
                     Ravenna Third Place Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b66b58067d3a396dd038c01fb47eee60 = L.marker(
                [47.60501625, -122.3295729],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b66b58067d3a396dd038c01fb47eee60.bindTooltip(
                `<div>
                     Seattle Office of Arts & Culture
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_32543f8c2ef558e8c0434d81e251cec7 = L.marker(
                [47.613453, -122.345268],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_32543f8c2ef558e8c0434d81e251cec7.bindTooltip(
                `<div>
                     Singles Going Steady
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_73160a291788a1eda026e876347eb863 = L.marker(
                [47.650349, -122.307216],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_73160a291788a1eda026e876347eb863.bindTooltip(
                `<div>
                     University of Washington Q Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2a4e28fc27bcd4ed3e05cbbe52450b14 = L.marker(
                [47.6683879, -122.3339953],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2a4e28fc27bcd4ed3e05cbbe52450b14.bindTooltip(
                `<div>
                     Wikstrom Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9c7acd37256b42ea9198876baeb2460c = L.marker(
                [47.6402468, -122.3766398],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9c7acd37256b42ea9198876baeb2460c.bindTooltip(
                `<div>
                     Victory Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ce65728622e5aa441766a5d2c4c21d0d = L.marker(
                [47.613796, -122.324783],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ce65728622e5aa441766a5d2c4c21d0d.bindTooltip(
                `<div>
                     Gay City Health Project
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d7e945a5da7b5816580bdefa02db2ecd = L.marker(
                [47.6252101, -122.3559613],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d7e945a5da7b5816580bdefa02db2ecd.bindTooltip(
                `<div>
                     St. Paul's Episcopal Church
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4cf99e00cb907ccfc85f065590262f64 = L.marker(
                [47.6614929, -122.3322973],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4cf99e00cb907ccfc85f065590262f64.bindTooltip(
                `<div>
                     Sea Monster Lounge
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_00891d367769020547046423a4fbfc2c = L.marker(
                [47.6083293, -122.3408128],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_00891d367769020547046423a4fbfc2c.bindTooltip(
                `<div>
                     Lisa Harris Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a2b85c7908e4342f9cc86e4afcb69a82 = L.marker(
                [47.552562, -122.320193],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a2b85c7908e4342f9cc86e4afcb69a82.bindTooltip(
                `<div>
                     Nupasa Art Studio & Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_20d5b2fe96aaa0fee361222fe193636b = L.marker(
                [47.614429, -122.317253],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_20d5b2fe96aaa0fee361222fe193636b.bindTooltip(
                `<div>
                     Longhouse Media
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9ab1d5d7f6b26a50919f4779c734bfad = L.marker(
                [47.698257, -122.355942],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9ab1d5d7f6b26a50919f4779c734bfad.bindTooltip(
                `<div>
                     The Salvation Army
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_67de79f57588bfb3978c68cfcef5d5a0 = L.marker(
                [47.61287415, -122.3352762],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_67de79f57588bfb3978c68cfcef5d5a0.bindTooltip(
                `<div>
                     AMC Pacific Place 11
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f991cc3b38d4af62b4f2aeea1c12477e = L.marker(
                [47.66098, -122.349632],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f991cc3b38d4af62b4f2aeea1c12477e.bindTooltip(
                `<div>
                     American Music
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_626714b25459d03eafb9d8cf07dcc1f2 = L.marker(
                [47.600586, -122.334579],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_626714b25459d03eafb9d8cf07dcc1f2.bindTooltip(
                `<div>
                     Central Saloon
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_01f5fbf55e1375419df2729d93d6feb9 = L.marker(
                [47.678528, -122.316147],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_01f5fbf55e1375419df2729d93d6feb9.bindTooltip(
                `<div>
                     Fluteworks Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_10d0e5ad15194eb05a1d432a08871ffa = L.marker(
                [47.6094497, -122.3418366],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_10d0e5ad15194eb05a1d432a08871ffa.bindTooltip(
                `<div>
                     Art Stall Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_241d7d32fb54a80d7d7b01126c96c03d = L.marker(
                [47.614125, -122.317716],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_241d7d32fb54a80d7d7b01126c96c03d.bindTooltip(
                `<div>
                     Unicorn
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cc7352d3d3370bdaccc6c5248b89adf5 = L.marker(
                [47.6846957, -122.3828419],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cc7352d3d3370bdaccc6c5248b89adf5.bindTooltip(
                `<div>
                     City of Seattle Loyal Hts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5969e5690366e8f693553a2f87920a85 = L.marker(
                [47.6080964, -122.3388114],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5969e5690366e8f693553a2f87920a85.bindTooltip(
                `<div>
                     SRG Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_daf5dfc8c7ac6283d6397058b19c7520 = L.marker(
                [47.60718365, -122.3240443],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_daf5dfc8c7ac6283d6397058b19c7520.bindTooltip(
                `<div>
                     Frye Art Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6084b79e9218471d087611bc30c3e648 = L.marker(
                [47.597923, -122.318398],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6084b79e9218471d087611bc30c3e648.bindTooltip(
                `<div>
                     Asian Resource Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5d0d97b500e5e7223cbfad7eb7781ad7 = L.marker(
                [47.635509, -122.359505],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5d0d97b500e5e7223cbfad7eb7781ad7.bindTooltip(
                `<div>
                     Queen Anne Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b9992f67d04b5e502f141407e7dda512 = L.marker(
                [47.617963, -122.336148],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b9992f67d04b5e502f141407e7dda512.bindTooltip(
                `<div>
                     Cornish College of the Arts- Main
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_764049d9345d70e14dce5aaf69039784 = L.marker(
                [47.52135525, -122.2705023],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_764049d9345d70e14dce5aaf69039784.bindTooltip(
                `<div>
                     Seattle Public Library Rainier Beach
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4a0ec7d79b506b2d12e127b1686f7547 = L.marker(
                [47.60801, -122.302349],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4a0ec7d79b506b2d12e127b1686f7547.bindTooltip(
                `<div>
                     Garfield Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7ccf46add1daeda95c509df7231e94a6 = L.marker(
                [47.7018484, -122.3023713],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7ccf46add1daeda95c509df7231e94a6.bindTooltip(
                `<div>
                     ActivSpace North Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d60bdb83823029b5125e8752af5dbc48 = L.marker(
                [47.6688574, -122.3841041],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d60bdb83823029b5125e8752af5dbc48.bindTooltip(
                `<div>
                     Majestic Bay
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_88863780869535c9988c96a3d46762fb = L.marker(
                [47.6593157, -122.3179173],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_88863780869535c9988c96a3d46762fb.bindTooltip(
                `<div>
                     Jack Straw
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5447cdbf4d4316d0a1bbc48bafe696f6 = L.marker(
                [47.547234, -122.351929],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5447cdbf4d4316d0a1bbc48bafe696f6.bindTooltip(
                `<div>
                     South Seattle Community College Olympic Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_975652fd71e8c4980ce1508c4acca72d = L.marker(
                [47.68998, -122.354958],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_975652fd71e8c4980ce1508c4acca72d.bindTooltip(
                `<div>
                     Rosewood Guitar
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_43e8d725b97b5126c0f4b5ec4456c6d3 = L.marker(
                [47.673092, -122.26796],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_43e8d725b97b5126c0f4b5ec4456c6d3.bindTooltip(
                `<div>
                     The National Archives at Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0c9db7e0cbc8f96f6e866f9be97efeb1 = L.marker(
                [47.6003, -122.30735],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0c9db7e0cbc8f96f6e866f9be97efeb1.bindTooltip(
                `<div>
                     Pratt Fine Arts Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7e59b6068858d70003b23bac55f40c63 = L.marker(
                [47.557722, -122.284917],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7e59b6068858d70003b23bac55f40c63.bindTooltip(
                `<div>
                     Vespertine Noise
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6ef0fef1aa0fa3e3c16bc8ea97d25917 = L.marker(
                [47.611258, -122.315128],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6ef0fef1aa0fa3e3c16bc8ea97d25917.bindTooltip(
                `<div>
                     Contactcreate
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_eb2f8c496621d691742dc4b927183b3b = L.marker(
                [47.5826992, -122.3847046],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_eb2f8c496621d691742dc4b927183b3b.bindTooltip(
                `<div>
                     Seattle Public Library West Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8f7b3e54d34a7148e79dbcfa7695af82 = L.marker(
                [47.599373, -122.331978],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8f7b3e54d34a7148e79dbcfa7695af82.bindTooltip(
                `<div>
                     Klondike Gold Rush National Historic Park
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b9a791a75d4519c41921a566161762c6 = L.marker(
                [47.5510384, -122.3518643],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b9a791a75d4519c41921a566161762c6.bindTooltip(
                `<div>
                     South Seattle Community College Little Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bf245d04ec3338233dab7f9244793090 = L.marker(
                [47.674446, -122.317734],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bf245d04ec3338233dab7f9244793090.bindTooltip(
                `<div>
                     Alexander's Bead Bazaar
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7e7d2d3314e81cf6a6b2e28fef4f38f0 = L.marker(
                [47.6871653, -122.3554887],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7e7d2d3314e81cf6a6b2e28fef4f38f0.bindTooltip(
                `<div>
                     Art On The Ridge
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9dfd6689ff7f61bf0792bde53edc6976 = L.marker(
                [47.651569, -122.341705],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9dfd6689ff7f61bf0792bde53edc6976.bindTooltip(
                `<div>
                     Studio Instrument Rentals, Inc.
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a06cda23fa2b8af5c807d0def1c5cdc7 = L.marker(
                [47.6012598, -122.330003],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a06cda23fa2b8af5c807d0def1c5cdc7.bindTooltip(
                `<div>
                     Gallery 110 in Tashiro Kaplan
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3beb6ed1a2bd36efe87da787c71de86b = L.marker(
                [47.649921, -122.306355],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3beb6ed1a2bd36efe87da787c71de86b.bindTooltip(
                `<div>
                     University of Washington Health Sciences Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0de0774eb72b43d9abe030aa89c54b7f = L.marker(
                [47.614554, -122.318207],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0de0774eb72b43d9abe030aa89c54b7f.bindTooltip(
                `<div>
                     The Stranger
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ae22e95f641d4cdc5181891572572f07 = L.marker(
                [47.524445, -122.2705],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ae22e95f641d4cdc5181891572572f07.bindTooltip(
                `<div>
                     Rainier Beach Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_412036f60bff7c97b7ab4d4143935b0c = L.marker(
                [47.62532335, -122.3220406],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_412036f60bff7c97b7ab4d4143935b0c.bindTooltip(
                `<div>
                     Rainier Chapter House DAR
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_81551a54da5a8f589fa2ff26102d4da6 = L.marker(
                [47.602364, -122.334595],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_81551a54da5a8f589fa2ff26102d4da6.bindTooltip(
                `<div>
                     Gallery Frames
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0b5e7f7e432997ed33cdc19e8fbbb250 = L.marker(
                [47.5607163, -122.3871398],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0b5e7f7e432997ed33cdc19e8fbbb250.bindTooltip(
                `<div>
                     Arts West
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_83b1d47b4535138576a62bd616cc38d6 = L.marker(
                [47.598796, -122.313501],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_83b1d47b4535138576a62bd616cc38d6.bindTooltip(
                `<div>
                     Bremelo Press
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ecc38953e936632a2c4f9241fb6e403f = L.marker(
                [47.6679185, -122.3838941],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ecc38953e936632a2c4f9241fb6e403f.bindTooltip(
                `<div>
                     Full Tilt Ballard
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cee1972bc220abd2ec57ad1e4ae4c5c0 = L.marker(
                [47.5995312, -122.3331168],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cee1972bc220abd2ec57ad1e4ae4c5c0.bindTooltip(
                `<div>
                     Davidson Galleries
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7a146f14eb3ecd9579b88126f8c5fc4d = L.marker(
                [47.61056225, -122.3163719],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7a146f14eb3ecd9579b88126f8c5fc4d.bindTooltip(
                `<div>
                     Photographic Center Northwest
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0752ee9ee2b74c4e9aab625bfca35c96 = L.marker(
                [47.550125, -122.287086],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0752ee9ee2b74c4e9aab625bfca35c96.bindTooltip(
                `<div>
                     Filipino Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_55fcc98e5b4070e1c31481c3c881d247 = L.marker(
                [47.62336, -122.320374],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_55fcc98e5b4070e1c31481c3c881d247.bindTooltip(
                `<div>
                     All Pilgrims Christian Church
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_87d508b68412de98829f76102c3e8a55 = L.marker(
                [47.6607139, -122.3135097],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_87d508b68412de98829f76102c3e8a55.bindTooltip(
                `<div>
                     Landmark Varsity Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5a90d0aa8134d9803cbd46a1f1c8c256 = L.marker(
                [47.62384645, -122.3535963],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5a90d0aa8134d9803cbd46a1f1c8c256.bindTooltip(
                `<div>
                     Seattle Center Seattle Repertory Theatre at Leo K
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5e3c0228d4333905b983eff0935f3a7b = L.marker(
                [47.5975149, -122.3339613],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5e3c0228d4333905b983eff0935f3a7b.bindTooltip(
                `<div>
                     Azuma Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_868d35eabf00dd3a5ece955095d47e22 = L.marker(
                [47.5514664, -122.3283134],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_868d35eabf00dd3a5ece955095d47e22.bindTooltip(
                `<div>
                     Kate Alkarni Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_faf1c88d5a0504014b50c9ea6a5ee30e = L.marker(
                [47.6108495, -122.3323316],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_faf1c88d5a0504014b50c9ea6a5ee30e.bindTooltip(
                `<div>
                     A Contemporary Theatre (ACT)
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_243906f34daeb88f564f85b1388c1361 = L.marker(
                [47.6534516, -122.3585927],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_243906f34daeb88f564f85b1388c1361.bindTooltip(
                `<div>
                     Makerhaus
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3b83371037a541fd0f59a946d331170b = L.marker(
                [47.6903817, -122.3573889],
                {"tags": ["Live/Work"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3b83371037a541fd0f59a946d331170b.bindTooltip(
                `<div>
                     Works Progress
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b6ec2f9e388c6ad958ab469b47c96080 = L.marker(
                [47.6091917, -122.3345412],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b6ec2f9e388c6ad958ab469b47c96080.bindTooltip(
                `<div>
                     Jeffrey Moose Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_04f74b8f349c048dde719a1c0b8bb552 = L.marker(
                [47.6194127, -122.3583566],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_04f74b8f349c048dde719a1c0b8bb552.bindTooltip(
                `<div>
                     Arthur Murray Dance Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6f5e7b83c7a223aebac5fc1de11639c4 = L.marker(
                [47.635185, -122.357361],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6f5e7b83c7a223aebac5fc1de11639c4.bindTooltip(
                `<div>
                     Queen Anne Book Company
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d8c9afa61ba0bde3e33e154e7766c33e = L.marker(
                [47.59511695, -122.3270859],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d8c9afa61ba0bde3e33e154e7766c33e.bindTooltip(
                `<div>
                     Satori Lab in Inscape
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_34da8a20ff18eb35e7239cc57084abe3 = L.marker(
                [47.683737, -122.3555197],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_34da8a20ff18eb35e7239cc57084abe3.bindTooltip(
                `<div>
                     Tasty Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7961b82da558301e4809e2350d175e66 = L.marker(
                [47.64632043, -122.3381967],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7961b82da558301e4809e2350d175e66.bindTooltip(
                `<div>
                     Center for Wooden Boats Wallingford
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_54cd2d4d05b7bef2cfa3b52c1c76d6ba = L.marker(
                [47.5878916, -122.3339403],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_54cd2d4d05b7bef2cfa3b52c1c76d6ba.bindTooltip(
                `<div>
                     Showbox SODO
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_84fcae46add1db0521b10ab3aff3af61 = L.marker(
                [47.62198, -122.35166],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_84fcae46add1db0521b10ab3aff3af61.bindTooltip(
                `<div>
                     Art/Not Terminal Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d87f077c4eec9ed9bc8e2001857e396d = L.marker(
                [47.609297, -122.341213],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d87f077c4eec9ed9bc8e2001857e396d.bindTooltip(
                `<div>
                     Milagros Mexican Folk Art Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1401506d101338d5a5b7374d37ba306c = L.marker(
                [47.6011373, -122.3295897],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1401506d101338d5a5b7374d37ba306c.bindTooltip(
                `<div>
                     Hanson Scott Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1103b1646131b4777d42e0ca24a62f0c = L.marker(
                [47.66858144, -122.3907201],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1103b1646131b4777d42e0ca24a62f0c.bindTooltip(
                `<div>
                     Electric Coffin Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6aebd6842f95036e356c1bf35fa1e6f5 = L.marker(
                [47.604548, -122.329935],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6aebd6842f95036e356c1bf35fa1e6f5.bindTooltip(
                `<div>
                     Washington Lawyers for the Arts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2d757921294210fc2dacd64bc545ef7f = L.marker(
                [47.667054, -122.313051],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2d757921294210fc2dacd64bc545ef7f.bindTooltip(
                `<div>
                     The Dreaming Comics and Games
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6bdee13a769e665f0cfe98db80cc21b8 = L.marker(
                [47.6178924, -122.3357243],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6bdee13a769e665f0cfe98db80cc21b8.bindTooltip(
                `<div>
                     Cornish College of the Arts- Notion
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2191c4104bab5c051d176ba87607a461 = L.marker(
                [47.6669041, -122.3127673],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2191c4104bab5c051d176ba87607a461.bindTooltip(
                `<div>
                     Seattle's Performers LLC
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_295321928dacad0f720a99d4ee4f7597 = L.marker(
                [47.649347, -122.348076],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_295321928dacad0f720a99d4ee4f7597.bindTooltip(
                `<div>
                     History House of Greater Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4c23da0aa97a048a25e20972152b77d9 = L.marker(
                [47.561455, -122.387177],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4c23da0aa97a048a25e20972152b77d9.bindTooltip(
                `<div>
                     Pegasus Book Exchange
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0587c8d9108466c33d9802d66e56f3a0 = L.marker(
                [47.7083148, -122.3281769],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0587c8d9108466c33d9802d66e56f3a0.bindTooltip(
                `<div>
                     Barnes & Noble -Northgate
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8bf2dafc8a551614c4f06ac7177bdce0 = L.marker(
                [47.690365, -122.352966],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8bf2dafc8a551614c4f06ac7177bdce0.bindTooltip(
                `<div>
                     City Arts Magazine/Encore Media Group
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8331efe0a7485bbe3eb6623f8d129959 = L.marker(
                [47.55990535, -122.2869601],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8331efe0a7485bbe3eb6623f8d129959.bindTooltip(
                `<div>
                     Seattle Public Library Columbia
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3015a735225302bafa7d3e1c4a2136b9 = L.marker(
                [47.600216, -122.334579],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3015a735225302bafa7d3e1c4a2136b9.bindTooltip(
                `<div>
                     Stormy Muffin Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3aa38d65a9bd70182c3133dd641a5414 = L.marker(
                [47.625474, -122.30732],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3aa38d65a9bd70182c3133dd641a5414.bindTooltip(
                `<div>
                     Russian Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e3f2224f703dda413a3c2882174c6cc8 = L.marker(
                [47.689507, -122.35495],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e3f2224f703dda413a3c2882174c6cc8.bindTooltip(
                `<div>
                     Couth Buzzard Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e02c0a42b99d0c4bc37d9c60db43fd09 = L.marker(
                [47.667813, -122.384795],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e02c0a42b99d0c4bc37d9c60db43fd09.bindTooltip(
                `<div>
                     Venue Ballard
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_46fd25a87c7b214391b5c1a6c2929c71 = L.marker(
                [47.661858, -122.31279],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_46fd25a87c7b214391b5c1a6c2929c71.bindTooltip(
                `<div>
                     KUOW Puget Sound Public Radio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a1c6d9f2307c115dd046ae10310dc1c3 = L.marker(
                [47.6142655, -122.3197336],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a1c6d9f2307c115dd046ae10310dc1c3.bindTooltip(
                `<div>
                     Comet Tavern
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_42eba52ac41cb143564d468c0648955f = L.marker(
                [47.676398, -122.31739],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_42eba52ac41cb143564d468c0648955f.bindTooltip(
                `<div>
                     The Weaving Works
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a70c1581b90071d263f65d2b15f6d8a9 = L.marker(
                [47.550287, -122.277273],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a70c1581b90071d263f65d2b15f6d8a9.bindTooltip(
                `<div>
                     Bookworm Exchange
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e293d542d9c4a3ce52c4ba6f550dbe14 = L.marker(
                [47.61269145, -122.2900131],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e293d542d9c4a3ce52c4ba6f550dbe14.bindTooltip(
                `<div>
                     Seattle Public Library Madrona
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_13b8c34050c3936ef401176ad8368152 = L.marker(
                [47.641225, -122.325897],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_13b8c34050c3936ef401176ad8368152.bindTooltip(
                `<div>
                     Early Music Guild
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_51548cac2c868e71e1a456a3076adb63 = L.marker(
                [47.6908412, -122.3562513],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_51548cac2c868e71e1a456a3076adb63.bindTooltip(
                `<div>
                     Taproot Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1bedb4651dc2f8b0f742432a2c006d7d = L.marker(
                [47.669819, -122.386803],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1bedb4651dc2f8b0f742432a2c006d7d.bindTooltip(
                `<div>
                     Leif Erikson Lodge Sons of Norway
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_968db596993efcae49caebdfaf75c8ce = L.marker(
                [47.6688915, -122.3954081],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_968db596993efcae49caebdfaf75c8ce.bindTooltip(
                `<div>
                     BallardWorks LLC
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a43d3dff161ff9af8102948c28dae38b = L.marker(
                [47.558868, -122.287971],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a43d3dff161ff9af8102948c28dae38b.bindTooltip(
                `<div>
                     Southside Commons
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4a62a44185840c09040da07e27fbb7d0 = L.marker(
                [47.596419, -122.322446],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4a62a44185840c09040da07e27fbb7d0.bindTooltip(
                `<div>
                     ID/Chinatown Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_08805f0900869944c00367ecf5b0442a = L.marker(
                [47.6869229, -122.3878221],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_08805f0900869944c00367ecf5b0442a.bindTooltip(
                `<div>
                     Ballard Academy of Music & Dance
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cca6f2c9cdb22364b8aae419c5736a65 = L.marker(
                [47.59985, -122.32669],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cca6f2c9cdb22364b8aae419c5736a65.bindTooltip(
                `<div>
                     Prole Drift
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4c6065a547d6c7273cd7774280c7beea = L.marker(
                [47.596252, -122.315567],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4c6065a547d6c7273cd7774280c7beea.bindTooltip(
                `<div>
                     7 Point Studio and The Boro School
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9d0b36680ce7975b3c2ef441813e453c = L.marker(
                [47.627403, -122.347137],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9d0b36680ce7975b3c2ef441813e453c.bindTooltip(
                `<div>
                     Emeralda Works
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7e86f8d595a1007dc790976ac1a59604 = L.marker(
                [47.577553, -122.41095],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7e86f8d595a1007dc790976ac1a59604.bindTooltip(
                `<div>
                     Southwest Seattle Historical Society
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e4380878c4c5f8c14f48885671a7ca5d = L.marker(
                [47.5243382, -122.2695039],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e4380878c4c5f8c14f48885671a7ca5d.bindTooltip(
                `<div>
                     Northwest Tap Connection
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e5d0280af2e7252dcfa4a3aafba6b2c2 = L.marker(
                [47.6566657, -122.3135544],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e5d0280af2e7252dcfa4a3aafba6b2c2.bindTooltip(
                `<div>
                     University of Washington Jones Playhouse
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e047d664474d1f696ee6e63b2fbb3fd4 = L.marker(
                [47.6973909, -122.3736435],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e047d664474d1f696ee6e63b2fbb3fd4.bindTooltip(
                `<div>
                     ARC Dance
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d1fd02ed647cf04cac8b1f1de73cecbb = L.marker(
                [47.614323, -122.327164],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d1fd02ed647cf04cac8b1f1de73cecbb.bindTooltip(
                `<div>
                     Seattle Eagle Tavern
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d6f19d804db93b537fb69b443fe46f0d = L.marker(
                [47.544225, -122.267717],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d6f19d804db93b537fb69b443fe46f0d.bindTooltip(
                `<div>
                     Macabee Martial Arts Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1e49d0ef5d59a056ec77961117ced7a1 = L.marker(
                [47.69239, -122.31763],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1e49d0ef5d59a056ec77961117ced7a1.bindTooltip(
                `<div>
                     Between Cultures Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a5fda19c20275b0385f0c591924bb8d7 = L.marker(
                [47.562884, -122.385849],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a5fda19c20275b0385f0c591924bb8d7.bindTooltip(
                `<div>
                     Senior Center of West Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_617b35a25ec76a20bdeffb5e4f325bf3 = L.marker(
                [47.6233866, -122.3432681],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_617b35a25ec76a20bdeffb5e4f325bf3.bindTooltip(
                `<div>
                     School of Visual Concepts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_86b6996cb5a512a7734eab7669bcfcdb = L.marker(
                [47.613902, -122.3203375],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_86b6996cb5a512a7734eab7669bcfcdb.bindTooltip(
                `<div>
                     Frame Central/North West Framing Cloud Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_703897bfc05590666e64d46d78bec7dc = L.marker(
                [47.579173, -122.386637],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_703897bfc05590666e64d46d78bec7dc.bindTooltip(
                `<div>
                     Delridge Community Center & Hiawatha
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_197ba05f2a6d240fc21b8e4d4bdc1458 = L.marker(
                [47.5974306, -122.3339422],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_197ba05f2a6d240fc21b8e4d4bdc1458.bindTooltip(
                `<div>
                     Roq La Rue Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0ecee715d215228cd7176b4c1ceb3b42 = L.marker(
                [47.65818, -122.306292],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0ecee715d215228cd7176b4c1ceb3b42.bindTooltip(
                `<div>
                     University of Washington Art Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_64757e991a3e448e6fa0b2de9bbefb2d = L.marker(
                [47.655335, -122.30352],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_64757e991a3e448e6fa0b2de9bbefb2d.bindTooltip(
                `<div>
                     University of Washington School of Music & Brechemin Auditorium
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3e046e7f1d56338c0bfd317d3b689abb = L.marker(
                [47.643753, -122.309258],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3e046e7f1d56338c0bfd317d3b689abb.bindTooltip(
                `<div>
                     Montlake Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c06d1aeae50646412fc6235a15e3ef13 = L.marker(
                [47.6004712, -122.333963],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c06d1aeae50646412fc6235a15e3ef13.bindTooltip(
                `<div>
                     Juan Alonso Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fd90beede9a5840aa737e34e057bc389 = L.marker(
                [47.613959, -122.319574],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fd90beede9a5840aa737e34e057bc389.bindTooltip(
                `<div>
                     Neumos/Barboza
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4af93a1335432f6cc1153f5228ae6f76 = L.marker(
                [47.62084, -122.352825],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4af93a1335432f6cc1153f5228ae6f76.bindTooltip(
                `<div>
                     Seattle Center Fisher Pavilion
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_79909bb591680f1fffc0dad4ca11bb67 = L.marker(
                [47.61407, -122.323097],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_79909bb591680f1fffc0dad4ca11bb67.bindTooltip(
                `<div>
                     Stitches
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2f45b7a2cfd24a9373f95515c2a83b7b = L.marker(
                [47.614338, -122.320107],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2f45b7a2cfd24a9373f95515c2a83b7b.bindTooltip(
                `<div>
                     High Voltage Music Store
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3bd377632db0e06d3145c4b710d32a56 = L.marker(
                [47.5982213, -122.322122],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3bd377632db0e06d3145c4b710d32a56.bindTooltip(
                `<div>
                     Union Cultural Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ebed972138d4cc7615ad50fc6e4e7187 = L.marker(
                [47.6604, -122.280525],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ebed972138d4cc7615ad50fc6e4e7187.bindTooltip(
                `<div>
                     Impress Cards and Crafts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_833b074da89432361eb2bb8fa2d9a03a = L.marker(
                [47.6034343, -122.3115241],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_833b074da89432361eb2bb8fa2d9a03a.bindTooltip(
                `<div>
                     Pipsqueak
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f850a3f3c697da83b27df6a7c216d79b = L.marker(
                [47.6098589, -122.3417416],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f850a3f3c697da83b27df6a7c216d79b.bindTooltip(
                `<div>
                     The Market Theater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f6b11ed2323ee7d7082878f89bf1de63 = L.marker(
                [47.6652885, -122.3104377],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f6b11ed2323ee7d7082878f89bf1de63.bindTooltip(
                `<div>
                     Sanctuary Art Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_abe0fec7e6cde955ed4c27e97134abe3 = L.marker(
                [47.614714, -122.3462234],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_abe0fec7e6cde955ed4c27e97134abe3.bindTooltip(
                `<div>
                     Rendezvous & Jewel Box Theater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a8c61ff29e676eea1643d483131cbad3 = L.marker(
                [47.664948, -122.317176],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a8c61ff29e676eea1643d483131cbad3.bindTooltip(
                `<div>
                     Capitol Music Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5ac2dc4f59d70533df57e3b42d3db49d = L.marker(
                [47.586853, -122.329559],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5ac2dc4f59d70533df57e3b42d3db49d.bindTooltip(
                `<div>
                     The Color Group
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1afed889896014a9b99cf40e5d91175b = L.marker(
                [47.69038, -122.357391],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1afed889896014a9b99cf40e5d91175b.bindTooltip(
                `<div>
                     Dreamstrands Comics & Such, Inc.
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1f64cd15857808987bc0f58206e2735f = L.marker(
                [47.6685224, -122.3851065],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1f64cd15857808987bc0f58206e2735f.bindTooltip(
                `<div>
                     Sonic Boom
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9708c41b9ae34acc70bdb34a9f6f17d4 = L.marker(
                [47.6091917, -122.3345412],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9708c41b9ae34acc70bdb34a9f6f17d4.bindTooltip(
                `<div>
                     Seattle Architecture Foundation
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6a5e8e867017fc30e1e6ea8ccf078602 = L.marker(
                [47.698005, -122.317615],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6a5e8e867017fc30e1e6ea8ccf078602.bindTooltip(
                `<div>
                     Beadworld
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c0cac40ccf1b7ed152530ccff24d7c22 = L.marker(
                [47.6983998, -122.3470479],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c0cac40ccf1b7ed152530ccff24d7c22.bindTooltip(
                `<div>
                     Music Center of Northwest
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_36fc6076a28377a46d9ea6be337cfce8 = L.marker(
                [47.6052251, -122.3262281],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_36fc6076a28377a46d9ea6be337cfce8.bindTooltip(
                `<div>
                     Trinity Parish Church
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_20aba8bb8eb168cc6222dc906a0437a7 = L.marker(
                [47.6100244, -122.3172211],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_20aba8bb8eb168cc6222dc906a0437a7.bindTooltip(
                `<div>
                     Seattle University Bookstore
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_825a6e67577b8f868aca811eb3c19e3a = L.marker(
                [47.619994, -122.345018],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_825a6e67577b8f868aca811eb3c19e3a.bindTooltip(
                `<div>
                     One Reel
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b9bb2fb1cc1eed3f41586da745ef7dec = L.marker(
                [47.7170286, -122.2955694],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b9bb2fb1cc1eed3f41586da745ef7dec.bindTooltip(
                `<div>
                     AudioLogic
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e78aba51e5a9c937743ea7192630f003 = L.marker(
                [47.6113827, -122.3164132],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e78aba51e5a9c937743ea7192630f003.bindTooltip(
                `<div>
                     Elliott Bay Recording Inc
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b316c86e2ff0f82c21d17f6455f0237b = L.marker(
                [47.60501625, -122.3295729],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b316c86e2ff0f82c21d17f6455f0237b.bindTooltip(
                `<div>
                     Ethnic Heritage Art Gallery at Seattle Municipal Tower
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d0d714c682ca9f575ee713767d05b2b0 = L.marker(
                [47.63028375, -122.3141998],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d0d714c682ca9f575ee713767d05b2b0.bindTooltip(
                `<div>
                     Seattle Asian Art Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5579e18660b0cffdf00c422d7433e4a2 = L.marker(
                [47.613922, -122.316429],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5579e18660b0cffdf00c422d7433e4a2.bindTooltip(
                `<div>
                     Wall of Sound
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_46ea3db19f5784627ddffd2bae6eab02 = L.marker(
                [47.61426, -122.317856],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_46ea3db19f5784627ddffd2bae6eab02.bindTooltip(
                `<div>
                     Studio Current
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7efa24bca25c52ce57e9eb0a27893d1d = L.marker(
                [47.61426, -122.317856],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7efa24bca25c52ce57e9eb0a27893d1d.bindTooltip(
                `<div>
                     Zions Gate Records
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_beb9b066e384d7edfb26d171d8c1025c = L.marker(
                [47.6698215, -122.3843172],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_beb9b066e384d7edfb26d171d8c1025c.bindTooltip(
                `<div>
                     Seattle Public Library Ballard
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e3d3f999a48f7b22d1c31efdcb9ee9ad = L.marker(
                [47.6134869, -122.3144433],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e3d3f999a48f7b22d1c31efdcb9ee9ad.bindTooltip(
                `<div>
                     Chop Suey, LLC.
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5eb7c77a93507ce50b656ee36780be5c = L.marker(
                [47.621666, -122.312294],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5eb7c77a93507ce50b656ee36780be5c.bindTooltip(
                `<div>
                     Dance Underground
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_98ff1340c1ea80f6a533b05ec5b7aea4 = L.marker(
                [47.623835, -122.33846],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_98ff1340c1ea80f6a533b05ec5b7aea4.bindTooltip(
                `<div>
                     Guitar Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2eebd8d78b24acdc5593d28c52e4dcc9 = L.marker(
                [47.624979, -122.3211541],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2eebd8d78b24acdc5593d28c52e4dcc9.bindTooltip(
                `<div>
                     Metrix Create Space
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6bcc6bb2fac23b446dc41f4c3ad366eb = L.marker(
                [47.685528, -122.355046],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6bcc6bb2fac23b446dc41f4c3ad366eb.bindTooltip(
                `<div>
                     Woodland Park United Methodist
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a59103391801bf25b4a715233ccc3502 = L.marker(
                [47.6320524, -122.3127683],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a59103391801bf25b4a715233ccc3502.bindTooltip(
                `<div>
                     Volunteer Park Ampitheater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e0eb1f975ffc94547ad2e081d18227e7 = L.marker(
                [47.53683545, -122.2840438],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e0eb1f975ffc94547ad2e081d18227e7.bindTooltip(
                `<div>
                     Seattle Public Library New Holly
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_31826f4f8bcd65d6615e51be12f162c3 = L.marker(
                [47.6615557, -122.3294857],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_31826f4f8bcd65d6615e51be12f162c3.bindTooltip(
                `<div>
                     Open Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2b09a182ceceeb9d4f57c459642cfa16 = L.marker(
                [47.67146895, -122.3171254],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2b09a182ceceeb9d4f57c459642cfa16.bindTooltip(
                `<div>
                     Cafe Racer Espresso
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6411e9c8a3e3033d1a6a4f7ac83b9b4d = L.marker(
                [47.5975101, -122.3116039],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6411e9c8a3e3033d1a6a4f7ac83b9b4d.bindTooltip(
                `<div>
                     Kinokuniya Book Store
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3f8f07a1fd50645b55ec61a16589082b = L.marker(
                [47.62056855, -122.350491],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3f8f07a1fd50645b55ec61a16589082b.bindTooltip(
                `<div>
                     Seattle Center Pavilion
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a006189614a9ef637b8efc550156dd8b = L.marker(
                [47.682538, -122.34083],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a006189614a9ef637b8efc550156dd8b.bindTooltip(
                `<div>
                     Seattle Public Theater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ff4963c2307e120846694bc7377fca2d = L.marker(
                [47.61908755, -122.3428109],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ff4963c2307e120846694bc7377fca2d.bindTooltip(
                `<div>
                     Friends of KEXP
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_88c9b1f4cc4ccdffc3a335deb94cd94e = L.marker(
                [47.654194, -122.300385],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_88c9b1f4cc4ccdffc3a335deb94cd94e.bindTooltip(
                `<div>
                     University of Washington Drama Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e7d85af80d850be11623bb528e0f8244 = L.marker(
                [47.605034, -122.334244],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e7d85af80d850be11623bb528e0f8244.bindTooltip(
                `<div>
                     SURF Incubator
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1fad4386bc20e3b5baae17c47a4b0ee0 = L.marker(
                [47.656969, -122.304421],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1fad4386bc20e3b5baae17c47a4b0ee0.bindTooltip(
                `<div>
                     University of Washington Mathematics Research Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f03f67d50277d157c132779e10512181 = L.marker(
                [47.5614664, -122.3870841],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f03f67d50277d157c132779e10512181.bindTooltip(
                `<div>
                     Easy Street Records
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1f89476995939cd5fcb85992c8c5c4d0 = L.marker(
                [47.5316617, -122.3761768],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1f89476995939cd5fcb85992c8c5c4d0.bindTooltip(
                `<div>
                     Kenyon Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6ecc2196e405bdca09ae9b1dc2661f25 = L.marker(
                [47.613571, -122.319832],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6ecc2196e405bdca09ae9b1dc2661f25.bindTooltip(
                `<div>
                     Canoe Social Club
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d2b168861a5b556b6ba7c519c64eb016 = L.marker(
                [47.6934167, -122.3569439],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d2b168861a5b556b6ba7c519c64eb016.bindTooltip(
                `<div>
                     Geisa Dutra Piano Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bedfaa2cdda50131d91a897f504ce138 = L.marker(
                [47.5995772, -122.3345636],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bedfaa2cdda50131d91a897f504ce138.bindTooltip(
                `<div>
                     Edd Cox Fine Art
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5bccb76b5500d8a7dd6ef05bf5d74895 = L.marker(
                [47.6014352, -122.3300625],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5bccb76b5500d8a7dd6ef05bf5d74895.bindTooltip(
                `<div>
                     4Culture in Tashiro Kaplan
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9ee1c0e5414bc9beedc9289cbbb6be0a = L.marker(
                [47.6142042, -122.348419],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9ee1c0e5414bc9beedc9289cbbb6be0a.bindTooltip(
                `<div>
                     Form/Space Atelier
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_56baf5b3a9a9977a35ba2047ada45465 = L.marker(
                [47.6661353, -122.3818674],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_56baf5b3a9a9977a35ba2047ada45465.bindTooltip(
                `<div>
                     Tryptos Studio Collective
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_97a746cb5e06242c5354f741dc98512f = L.marker(
                [47.5891416, -122.3018907],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_97a746cb5e06242c5354f741dc98512f.bindTooltip(
                `<div>
                     Northwest African American Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d983483fbaa38d78780e36b86b474ecb = L.marker(
                [47.69038, -122.357727],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d983483fbaa38d78780e36b86b474ecb.bindTooltip(
                `<div>
                     Made Sewing Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_dd3f23f1177bdf7d218df4648ae0f2b0 = L.marker(
                [47.6624817, -122.3655177],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_dd3f23f1177bdf7d218df4648ae0f2b0.bindTooltip(
                `<div>
                     Ballard Rock Rooms/Birds Nest
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6ef6a7d313d881bda3acf395f6c56e29 = L.marker(
                [47.6547393, -122.3709909],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6ef6a7d313d881bda3acf395f6c56e29.bindTooltip(
                `<div>
                     Seattle Grip & Lighting
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_31f2f0d3dbcd8df353c7e216fd7ed11c = L.marker(
                [47.611415, -122.331472],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_31f2f0d3dbcd8df353c7e216fd7ed11c.bindTooltip(
                `<div>
                     Washington State Convention & Trade Center Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_72281ee7602264b1eae86e99b510f4cd = L.marker(
                [47.599017, -122.331575],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_72281ee7602264b1eae86e99b510f4cd.bindTooltip(
                `<div>
                     Color 1 Photo
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4454b4e9146b7e78327b0c414a785d20 = L.marker(
                [47.661133, -122.364212],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4454b4e9146b7e78327b0c414a785d20.bindTooltip(
                `<div>
                     Martin Blank Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2960f93475f79200bd0eb96bc8b7ecff = L.marker(
                [47.599653, -122.33026],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2960f93475f79200bd0eb96bc8b7ecff.bindTooltip(
                `<div>
                     Seattle Metropolitan Police Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c6ae175f8be6a42e1cceea2ab0b1ce2f = L.marker(
                [47.569904, -122.362556],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c6ae175f8be6a42e1cceea2ab0b1ce2f.bindTooltip(
                `<div>
                     Mode Music Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_690d2018398a0cb7762619059bbc8647 = L.marker(
                [47.69725335, -122.3736211],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_690d2018398a0cb7762619059bbc8647.bindTooltip(
                `<div>
                     Small Faces/Crown Hill Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_823180b8195fb6bc35e23e831b58dacb = L.marker(
                [47.63115945, -122.3426842],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_823180b8195fb6bc35e23e831b58dacb.bindTooltip(
                `<div>
                     National Film Festival for Talented Youth (NFFTY)
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b8396046f6c4fe837c9df5d2a45d89a3 = L.marker(
                [47.6500311, -122.3484385],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b8396046f6c4fe837c9df5d2a45d89a3.bindTooltip(
                `<div>
                     Seattle Public Library Fremont
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b603781b5a4c980a2a0109e359b6a72e = L.marker(
                [47.6802289, -122.3248831],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b603781b5a4c980a2a0109e359b6a72e.bindTooltip(
                `<div>
                     Little Red Hen
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4820c6075f8a40471687b5e62c047b8e = L.marker(
                [47.703865, -122.356766],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4820c6075f8a40471687b5e62c047b8e.bindTooltip(
                `<div>
                     Civetta Dance Space
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4be3f701b578a4397ab271db271de9ef = L.marker(
                [47.623769, -122.354085],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4be3f701b578a4397ab271db271de9ef.bindTooltip(
                `<div>
                     Panda Photographic Laboratories Inc
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bb9038078fb0f80eeb3134b7dc504fde = L.marker(
                [47.7197965, -122.2980932],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bb9038078fb0f80eeb3134b7dc504fde.bindTooltip(
                `<div>
                     Seattle Public Library Lake City
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c9eb9dd8dbad24db03919c8588d53011 = L.marker(
                [47.6489942, -122.3617027],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c9eb9dd8dbad24db03919c8588d53011.bindTooltip(
                `<div>
                     Seattle Pacific University McKinley Hall-Kreider Art Gallery, E.E. Bach Theater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_71e8e2f9934b6f637846c0f2073a63bb = L.marker(
                [47.5728531, -122.3231882],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_71e8e2f9934b6f637846c0f2073a63bb.bindTooltip(
                `<div>
                     Wilder Sound Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e2088afc43fdd30f04922ccf9a509afd = L.marker(
                [47.545139, -122.3874303],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e2088afc43fdd30f04922ccf9a509afd.bindTooltip(
                `<div>
                     Feedback Lounge
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_03227c1705738693b6cfa08a556ffbe0 = L.marker(
                [47.668377, -122.390541],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_03227c1705738693b6cfa08a556ffbe0.bindTooltip(
                `<div>
                     Seattle Creative Arts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7a7e539647f901ba31ebe0ba3b9c20b7 = L.marker(
                [47.5994214, -122.3133875],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7a7e539647f901ba31ebe0ba3b9c20b7.bindTooltip(
                `<div>
                     Densho: The Japanese American Legacy Project
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_30262baaeb9a1ce02aa041c7b0554e7a = L.marker(
                [47.595163, -122.309673],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_30262baaeb9a1ce02aa041c7b0554e7a.bindTooltip(
                `<div>
                     My World Dance and Fitness Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0101bd1ddcec53d89f1782b939e6cbbe = L.marker(
                [47.60003, -122.326102],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0101bd1ddcec53d89f1782b939e6cbbe.bindTooltip(
                `<div>
                     Bonfire at Panama Hotel
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4ad1ddc4717c09a056134a40318068aa = L.marker(
                [47.589146, -122.293938],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4ad1ddc4717c09a056134a40318068aa.bindTooltip(
                `<div>
                     The Knitting School
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_19f628b414884dfc87fa18945b1ae3d2 = L.marker(
                [47.67041, -122.384102],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_19f628b414884dfc87fa18945b1ae3d2.bindTooltip(
                `<div>
                     St. Luke's Episcopal Church Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a368bf7dfbf9de2e390f2751026201de = L.marker(
                [47.617073, -122.31649],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a368bf7dfbf9de2e390f2751026201de.bindTooltip(
                `<div>
                     Scratch Deli
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f29369273119c337b7dac0154fdbf8f3 = L.marker(
                [47.6850306, -122.344258],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f29369273119c337b7dac0154fdbf8f3.bindTooltip(
                `<div>
                     Of the Earth
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7048ce8725fb306d1bce6f84c0915258 = L.marker(
                [47.6539065, -122.3121096],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7048ce8725fb306d1bce6f84c0915258.bindTooltip(
                `<div>
                     Henry Art Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_921a61070754478c47ab70508caa7254 = L.marker(
                [47.5999167, -122.3267574],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_921a61070754478c47ab70508caa7254.bindTooltip(
                `<div>
                     Bryan Ohno Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f787c2495aff2c1723e80e77cd8c9afe = L.marker(
                [47.615477, -122.34221],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f787c2495aff2c1723e80e77cd8c9afe.bindTooltip(
                `<div>
                     Hot Glass Color
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e45269c71448bc9311b03de4125d4f67 = L.marker(
                [47.6112287, -122.3444605],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e45269c71448bc9311b03de4125d4f67.bindTooltip(
                `<div>
                     Steinbrueck Native Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_90f04a1ed8e9b40ca14619400b0d349d = L.marker(
                [47.613136, -122.304382],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_90f04a1ed8e9b40ca14619400b0d349d.bindTooltip(
                `<div>
                     Meter Music School
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9fb41c521e276a84a74d7967beaec9f0 = L.marker(
                [47.614273, -122.317245],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9fb41c521e276a84a74d7967beaec9f0.bindTooltip(
                `<div>
                     Three Dollar Bill Cinema
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_77e6ab8c4546036611f645d120e5065f = L.marker(
                [47.597873, -122.293854],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_77e6ab8c4546036611f645d120e5065f.bindTooltip(
                `<div>
                     Central Area Senior Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_15a931f4c09d1e1ecb41d983c50661b7 = L.marker(
                [47.5616585, -122.3237001],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_15a931f4c09d1e1ecb41d983c50661b7.bindTooltip(
                `<div>
                     Sunny Arms Artist Cooperative
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ca781e6cfa65c4fc455d90aea0252758 = L.marker(
                [47.599216, -122.296595],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ca781e6cfa65c4fc455d90aea0252758.bindTooltip(
                `<div>
                     Oromo Community Organization
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e8a3b3cd659063a3432e3f78ed6c551a = L.marker(
                [47.608495, -122.339743],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e8a3b3cd659063a3432e3f78ed6c551a.bindTooltip(
                `<div>
                     Showbox at the Market
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_87a6b5daa4b2fdfa6f7128479be26447 = L.marker(
                [47.689323, -122.3553],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_87a6b5daa4b2fdfa6f7128479be26447.bindTooltip(
                `<div>
                     Pocket Theater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bfdaf6ec5ad4fa4e2c2d3a2cd76148df = L.marker(
                [47.561654, -122.284859],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bfdaf6ec5ad4fa4e2c2d3a2cd76148df.bindTooltip(
                `<div>
                     Rainier Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5dfa6ce3a57fada917be46abfe297408 = L.marker(
                [47.659514, -122.35003],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5dfa6ce3a57fada917be46abfe297408.bindTooltip(
                `<div>
                     Underwood Stables
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c91b1e50657d177eb930c5af11f140d2 = L.marker(
                [47.5262606, -122.3225793],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c91b1e50657d177eb930c5af11f140d2.bindTooltip(
                `<div>
                     Seattle Public Library South Park
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_dd758a8124f76082a71ca93f6705a81d = L.marker(
                [47.6012805, -122.3297091],
                {"tags": ["Live/Work"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_dd758a8124f76082a71ca93f6705a81d.bindTooltip(
                `<div>
                     Artspace Tashiro Kaplan Lofts and the Angle & Corridor Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3401408b074c0fcaef4ea78d9ed8f02e = L.marker(
                [47.6204434, -122.3525072],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3401408b074c0fcaef4ea78d9ed8f02e.bindTooltip(
                `<div>
                     Seattle Center Seattle Children's Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a9ab1d22a0081f0c951afd50350b925f = L.marker(
                [47.72280815, -122.3134892],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a9ab1d22a0081f0c951afd50350b925f.bindTooltip(
                `<div>
                     Gansango Music & Dance
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_428c132da3bb184dcef357ba5e528e2e = L.marker(
                [47.622415, -122.31263],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_428c132da3bb184dcef357ba5e528e2e.bindTooltip(
                `<div>
                     Ada's Technical Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_785b05bdf6b79da6ce7768911acf88b0 = L.marker(
                [47.659126, -122.308582],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_785b05bdf6b79da6ce7768911acf88b0.bindTooltip(
                `<div>
                     University of Washington Foster Business Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_73c3b4fcec1e230dfa44ca7034d88172 = L.marker(
                [47.66867, -122.385491],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_73c3b4fcec1e230dfa44ca7034d88172.bindTooltip(
                `<div>
                     Secret Garden Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_db72d40e21c331f821b7b4b571397f14 = L.marker(
                [47.5559849, -122.2840929],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_db72d40e21c331f821b7b4b571397f14.bindTooltip(
                `<div>
                     Full Tilt Columbia City
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_244febc04c11db989ad3d24c6b9b922c = L.marker(
                [47.6151265, -122.3198707],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_244febc04c11db989ad3d24c6b9b922c.bindTooltip(
                `<div>
                     Century Ballroom
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_be6b70fb0926b9c887659f22816aeb01 = L.marker(
                [47.60129695, -122.3098251],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_be6b70fb0926b9c887659f22816aeb01.bindTooltip(
                `<div>
                     Langston Hughes Performing Arts Institute
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6020783a0492094f4f0e36e8dc6096c2 = L.marker(
                [47.6015999, -122.3332441],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6020783a0492094f4f0e36e8dc6096c2.bindTooltip(
                `<div>
                     Belltown Ballet BBC Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_dedfcc6ed84436e9548a8aac3f9173d9 = L.marker(
                [47.531185, -122.279564],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_dedfcc6ed84436e9548a8aac3f9173d9.bindTooltip(
                `<div>
                     SPCCCPPC
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1a4fdfb2be4285ce539fefa0139f1439 = L.marker(
                [47.7196359, -122.3125577],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1a4fdfb2be4285ce539fefa0139f1439.bindTooltip(
                `<div>
                     L.A.B at Seattle Drum School of Music
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c41279d3d8ba129432b3c300198128e9 = L.marker(
                [47.5993435, -122.3339158],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c41279d3d8ba129432b3c300198128e9.bindTooltip(
                `<div>
                     Flury and Company
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_18163e0009e5dfe6e035864e84276c56 = L.marker(
                [47.676288, -122.385388],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_18163e0009e5dfe6e035864e84276c56.bindTooltip(
                `<div>
                     Glass Art Society
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_12c9459462e628812b275910daacde3c = L.marker(
                [47.5707566, -122.3710219],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_12c9459462e628812b275910daacde3c.bindTooltip(
                `<div>
                     Avalon Glassworks
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_64d17342dc5a760a4f8280fc882a12b7 = L.marker(
                [47.52195755, -122.3878746],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_64d17342dc5a760a4f8280fc882a12b7.bindTooltip(
                `<div>
                     Dance! West Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c4007d7fb3f08f73e839d044ddae4174 = L.marker(
                [47.5530455, -122.3632976],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c4007d7fb3f08f73e839d044ddae4174.bindTooltip(
                `<div>
                     Seattle Public Library Delridge
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a20b0cb1e66b4c2f6e518e6025894eb4 = L.marker(
                [47.548885, -122.317596],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a20b0cb1e66b4c2f6e518e6025894eb4.bindTooltip(
                `<div>
                     The Alice Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e1dd99230c31e202ceb8e7c37986054e = L.marker(
                [47.6178573, -122.3348113],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e1dd99230c31e202ceb8e7c37986054e.bindTooltip(
                `<div>
                     Cornish College of the Arts- Raisbeck Performance Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e0e8411a42d0f60a57153d846fed07bf = L.marker(
                [47.663578, -122.317726],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e0e8411a42d0f60a57153d846fed07bf.bindTooltip(
                `<div>
                     Half Price Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8be913ca89da0b2bae0c3cda3babbd46 = L.marker(
                [47.6023356, -122.3358275],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8be913ca89da0b2bae0c3cda3babbd46.bindTooltip(
                `<div>
                     Ace Studios Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7d0e79b497d924f66e619d06de0c9cea = L.marker(
                [47.6151142, -122.3145155],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7d0e79b497d924f66e619d06de0c9cea.bindTooltip(
                `<div>
                     Rare Medium
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2555f71dc16803b1d26b0061972ffc0c = L.marker(
                [47.6182617, -122.3577413],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2555f71dc16803b1d26b0061972ffc0c.bindTooltip(
                `<div>
                     Interbay Worklofts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e0022044985bd5d8ae32acfbb5d400da = L.marker(
                [47.59029, -122.3341971],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e0022044985bd5d8ae32acfbb5d400da.bindTooltip(
                `<div>
                     Silver Platters SoDo
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_dd6edf9ede8a1cfd5a5b57c4e5eb6405 = L.marker(
                [47.6776991, -122.3963587],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_dd6edf9ede8a1cfd5a5b57c4e5eb6405.bindTooltip(
                `<div>
                     Nordic Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fab20877aeba46eadde0930efe0838eb = L.marker(
                [47.705199, -122.3509853],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fab20877aeba46eadde0930efe0838eb.bindTooltip(
                `<div>
                     Tim's Tavern
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3a1eb8654f5f14b76833c9148f2baa4a = L.marker(
                [47.689869, -122.322983],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3a1eb8654f5f14b76833c9148f2baa4a.bindTooltip(
                `<div>
                     Metropolitan Music
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_88f4348cecea9c87c2a788ae64791763 = L.marker(
                [47.55166065, -122.3866496],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_88f4348cecea9c87c2a788ae64791763.bindTooltip(
                `<div>
                     C & P Coffee Company
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d77b351648cc1c6b24177f782a4917c2 = L.marker(
                [47.674288, -122.317353],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d77b351648cc1c6b24177f782a4917c2.bindTooltip(
                `<div>
                     Hawthorne Stereo
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9c87e21ed1a1345e7a67bfa74d2978de = L.marker(
                [47.64922085, -122.3770904],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9c87e21ed1a1345e7a67bfa74d2978de.bindTooltip(
                `<div>
                     Q
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f0187da1b665f2e5bab63ff4ea17c99f = L.marker(
                [47.519753, -122.261269],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f0187da1b665f2e5bab63ff4ea17c99f.bindTooltip(
                `<div>
                     Rainier Dance Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_58a2b25b26b2ee10c23ea118cf7d6a53 = L.marker(
                [47.614429, -122.317253],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_58a2b25b26b2ee10c23ea118cf7d6a53.bindTooltip(
                `<div>
                     New Century Theatre Company Offices
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8037bd2919df24c0b841fccf5518cc11 = L.marker(
                [47.664074, -122.314514],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8037bd2919df24c0b841fccf5518cc11.bindTooltip(
                `<div>
                     Brooklyn Frame Shop
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_575bc3d9cd1b871e794f54959fda4516 = L.marker(
                [47.6669041, -122.3127673],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_575bc3d9cd1b871e794f54959fda4516.bindTooltip(
                `<div>
                     The Guitar Store
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3dc5876ab3d838c9d65bf5589ed9c25f = L.marker(
                [47.60755, -122.32401],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3dc5876ab3d838c9d65bf5589ed9c25f.bindTooltip(
                `<div>
                     Hugo House
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ffdfd2ff92a86d2ceba6272223d9907d = L.marker(
                [47.62056855, -122.350491],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ffdfd2ff92a86d2ceba6272223d9907d.bindTooltip(
                `<div>
                     Seattle Center Vera Project
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3a389e7d7839478a81abf659db99eb1c = L.marker(
                [47.618977, -122.320876],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3a389e7d7839478a81abf659db99eb1c.bindTooltip(
                `<div>
                     Phoenix Comics & Games
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bcde4c58559259431df74881a24160e6 = L.marker(
                [47.558494, -122.284164],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bcde4c58559259431df74881a24160e6.bindTooltip(
                `<div>
                     Vietnamese Friendship Association
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7fe8feed355a924cd3c1898555edc7cd = L.marker(
                [47.7018421, -122.3424979],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7fe8feed355a924cd3c1898555edc7cd.bindTooltip(
                `<div>
                     AMC Loews Oak Tree 6
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7ed67f770ccf8b1335bbe17ee6f98477 = L.marker(
                [47.6117204, -122.3130658],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7ed67f770ccf8b1335bbe17ee6f98477.bindTooltip(
                `<div>
                     Spring Street Center (Subud Pacific Northwest)
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0a6b1ec3e4ca071ae15bdc7710d8f670 = L.marker(
                [47.6093109, -122.3394956],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0a6b1ec3e4ca071ae15bdc7710d8f670.bindTooltip(
                `<div>
                     Hard Rock Cafe
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1ea8aa36a149efc7f40683a5fd970d37 = L.marker(
                [47.71056035, -122.3236524],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1ea8aa36a149efc7f40683a5fd970d37.bindTooltip(
                `<div>
                     Seattle Youth Symphony
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ac7a589fa16fc120f1e1a0bdfb5c0d7d = L.marker(
                [47.609505, -122.336502],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ac7a589fa16fc120f1e1a0bdfb5c0d7d.bindTooltip(
                `<div>
                     Seattle Magazine/Tiger Oak Media Inc
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_065c9b5ce14d5be45f43a4b2b442144a = L.marker(
                [47.5518058, -122.3246163],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_065c9b5ce14d5be45f43a4b2b442144a.bindTooltip(
                `<div>
                     School of Acrobatics & New Circus Arts (SANCA)
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_87d24b34b873217103af103604bf89aa = L.marker(
                [47.5989593, -122.3271163],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_87d24b34b873217103af103604bf89aa.bindTooltip(
                `<div>
                     Choeizan Enkyoji Nichiren Buddhist Temple
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5d557788dbb58dad6c64771a011df4c2 = L.marker(
                [47.641296, -122.39782],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5d557788dbb58dad6c64771a011df4c2.bindTooltip(
                `<div>
                     Roseanne's School of Dance
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3095e7c7b700f9a617fdc1d6a24b6770 = L.marker(
                [47.66853, -122.31189],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3095e7c7b700f9a617fdc1d6a24b6770.bindTooltip(
                `<div>
                     University of Washington Built Environment Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_17c8c8514c24ce998b6d6ebb9367b661 = L.marker(
                [47.622152, -122.356531],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_17c8c8514c24ce998b6d6ebb9367b661.bindTooltip(
                `<div>
                     98.1 Classical KING FM
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_94023b3726bd81f0ae4ef7abe3d83f7a = L.marker(
                [47.61033, -122.343685],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_94023b3726bd81f0ae4ef7abe3d83f7a.bindTooltip(
                `<div>
                     Soul Cat Guitars
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cee2b551767b54acd226cf65041da634 = L.marker(
                [47.608707, -122.341049],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cee2b551767b54acd226cf65041da634.bindTooltip(
                `<div>
                     B L M F Literary Saloon
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4495a1913771098a6e66ae727c00ad68 = L.marker(
                [47.613737, -122.2895678],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4495a1913771098a6e66ae727c00ad68.bindTooltip(
                `<div>
                     Conrow Porcelain Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cb0deb0da6c16bf57cb84bcf55cca039 = L.marker(
                [47.669819, -122.385689],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cb0deb0da6c16bf57cb84bcf55cca039.bindTooltip(
                `<div>
                     Jo Ann Fabrics and Crafts Ballard
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9569d9860bfbdbe922f25c38796d30ac = L.marker(
                [47.5997045, -122.3331303],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9569d9860bfbdbe922f25c38796d30ac.bindTooltip(
                `<div>
                     Glasshouse Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_73a0dea9bd380456382063926b133842 = L.marker(
                [47.66592, -122.317085],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_73a0dea9bd380456382063926b133842.bindTooltip(
                `<div>
                     Scarecrow Video
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f6ed383c2e14afa545f1eff3bac1b91a = L.marker(
                [47.62648, -122.3357295],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f6ed383c2e14afa545f1eff3bac1b91a.bindTooltip(
                `<div>
                     Center for Wooden Boats South Lake Union
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_dd368e490099bd81c48b89172054f993 = L.marker(
                [47.6122895, -122.3491939],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_dd368e490099bd81c48b89172054f993.bindTooltip(
                `<div>
                     Art Institute of Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cfa34bfa186e936295718ee665c77b36 = L.marker(
                [47.652168, -122.306648],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cfa34bfa186e936295718ee665c77b36.bindTooltip(
                `<div>
                     University of Washington Husky Union Building
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d78032be150fd63077f5fb5c0b8ab3d8 = L.marker(
                [47.572744, -122.322579],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d78032be150fd63077f5fb5c0b8ab3d8.bindTooltip(
                `<div>
                     Unique Art Framing & Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c33d7dc372a5ef91df1c4e7a86196201 = L.marker(
                [47.6657095, -122.3828003],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c33d7dc372a5ef91df1c4e7a86196201.bindTooltip(
                `<div>
                     Tractor Tavern
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f27baf20b6bb1e4323c24a67705275ab = L.marker(
                [47.528648, -122.270409],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f27baf20b6bb1e4323c24a67705275ab.bindTooltip(
                `<div>
                     Ethiopian Community Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_710713d146e886c2df8a3d3521799b71 = L.marker(
                [47.68682, -122.388387],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_710713d146e886c2df8a3d3521799b71.bindTooltip(
                `<div>
                     Mike and Mike's Guitar Bar
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_87666c0c4b71842063229a8b7afd077e = L.marker(
                [47.6149531, -122.3217473],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_87666c0c4b71842063229a8b7afd077e.bindTooltip(
                `<div>
                     Egyptian Theater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_50b2837410804f42219f87d781b3f597 = L.marker(
                [47.5994698, -122.3127638],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_50b2837410804f42219f87d781b3f597.bindTooltip(
                `<div>
                     Seattle Atelier
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c58242e5ca26154a75eba7743f7f50c8 = L.marker(
                [47.60089, -122.333385],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c58242e5ca26154a75eba7743f7f50c8.bindTooltip(
                `<div>
                     Martyr Sauce
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e712754aba40140e71749001b69ce7af = L.marker(
                [47.69077345, -122.3549791],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e712754aba40140e71749001b69ce7af.bindTooltip(
                `<div>
                     Bherd Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5ba0bedbab7f554f385e99df3c4ff685 = L.marker(
                [47.559563, -122.286736],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5ba0bedbab7f554f385e99df3c4ff685.bindTooltip(
                `<div>
                     Igimo Art Station, LLC
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_db92bda803a6e75a49001e229b12168f = L.marker(
                [47.601161, -122.3300592],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_db92bda803a6e75a49001e229b12168f.bindTooltip(
                `<div>
                     Platform Gallery in Tashiro Kaplan
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_abcba0f130a5997cd62cd63a13d0e010 = L.marker(
                [47.548363, -122.321178],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_abcba0f130a5997cd62cd63a13d0e010.bindTooltip(
                `<div>
                     Woodcraft of Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_58598107926c1439e07babc5bd60d833 = L.marker(
                [47.6321308, -122.3599365],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_58598107926c1439e07babc5bd60d833.bindTooltip(
                `<div>
                     Barsuk Records
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5a2318299d9fb7a2ae3e9faa31d77996 = L.marker(
                [47.6275898, -122.3369252],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5a2318299d9fb7a2ae3e9faa31d77996.bindTooltip(
                `<div>
                     Museum of History and Industry (MOHAI)
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4719a5480fd75de86f26a868cc84c53b = L.marker(
                [47.6229428, -122.3223317],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4719a5480fd75de86f26a868cc84c53b.bindTooltip(
                `<div>
                     Seattle Public Library Capitol Hill
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1daf5a1b49e6eb58eeb59d31ffb67d5c = L.marker(
                [47.6338273, -122.3627291],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1daf5a1b49e6eb58eeb59d31ffb67d5c.bindTooltip(
                `<div>
                     Seattle Public Library Queen Anne
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0a29a219dc8935af0703a7f346efab5d = L.marker(
                [47.6841406, -122.3555094],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0a29a219dc8935af0703a7f346efab5d.bindTooltip(
                `<div>
                     Versatile Arts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1824983f24d47cb8834470ae97992b8f = L.marker(
                [47.6002492, -122.3346249],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1824983f24d47cb8834470ae97992b8f.bindTooltip(
                `<div>
                     Orbit Audio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b8e01dce0c7f68975ea5cea4230a7f15 = L.marker(
                [47.6561433, -122.3426065],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b8e01dce0c7f68975ea5cea4230a7f15.bindTooltip(
                `<div>
                     Stone Soup Theatre/DownStage Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0e947bdfb076e737e1351be9bb3b283a = L.marker(
                [47.656967, -122.312055],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0e947bdfb076e737e1351be9bb3b283a.bindTooltip(
                `<div>
                     University of Washington Social Work Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_34ac460fba00b441e4a8336ca90398aa = L.marker(
                [47.552368, -122.320488],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_34ac460fba00b441e4a8336ca90398aa.bindTooltip(
                `<div>
                     Earl Harper Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_99ec5e02061ec7e9ab3338d116852db4 = L.marker(
                [47.5324205, -122.3249576],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_99ec5e02061ec7e9ab3338d116852db4.bindTooltip(
                `<div>
                     Black Box Operations 12th Avenue Arts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f1e697f24a6fa6a1c7f10a8c55eef75f = L.marker(
                [47.6090096, -122.3299408],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f1e697f24a6fa6a1c7f10a8c55eef75f.bindTooltip(
                `<div>
                     Town Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ce67dcb216561763665b2b2c5926a222 = L.marker(
                [47.6065659, -122.3374584],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ce67dcb216561763665b2b2c5926a222.bindTooltip(
                `<div>
                     RE Welch Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6f81fc72873bb7dc35b36d459baa07c4 = L.marker(
                [47.6048267, -122.336745],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6f81fc72873bb7dc35b36d459baa07c4.bindTooltip(
                `<div>
                     The Legacy Ltd
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_059e475a2e9a54632ca8b8feff512677 = L.marker(
                [47.661632, -122.34377],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_059e475a2e9a54632ca8b8feff512677.bindTooltip(
                `<div>
                     Off the Wall School of Music
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_796ff9ca43e2967fe8a4e739ea6b68ea = L.marker(
                [47.608707, -122.341049],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_796ff9ca43e2967fe8a4e739ea6b68ea.bindTooltip(
                `<div>
                     Golden Age Collectibles
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_52ad6e64aac533f9ea2cd61c9bf39fd2 = L.marker(
                [47.57419, -122.321154],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_52ad6e64aac533f9ea2cd61c9bf39fd2.bindTooltip(
                `<div>
                     Urban Work Lofts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d82d7c07d7417c2c167cd41e5043a485 = L.marker(
                [47.607586, -122.325935],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d82d7c07d7417c2c167cd41e5043a485.bindTooltip(
                `<div>
                     St. James Cathedral
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3ccf807af42c3a9d2809505c913e8c9e = L.marker(
                [47.73945, -122.34394],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3ccf807af42c3a9d2809505c913e8c9e.bindTooltip(
                `<div>
                     Arcane Comics & More
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_256fb791596beec52aed6546dc439219 = L.marker(
                [47.548225, -122.316483],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_256fb791596beec52aed6546dc439219.bindTooltip(
                `<div>
                     Georgetown Music Store
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4693bfcdad15526b5e8e95f80f5342cc = L.marker(
                [47.53246, -122.32496],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4693bfcdad15526b5e8e95f80f5342cc.bindTooltip(
                `<div>
                     All Metal Arts Hazardfactory
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6e2fe19afe4d1aa7aef47f4ec8ef0bf7 = L.marker(
                [47.60949, -122.308904],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6e2fe19afe4d1aa7aef47f4ec8ef0bf7.bindTooltip(
                `<div>
                     Filipino American National Historical Society
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_132207b5747c7d9b28f30e65c0715fea = L.marker(
                [47.645466, -122.383057],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_132207b5747c7d9b28f30e65c0715fea.bindTooltip(
                `<div>
                     Circle of Art Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_083776d32ffd9ed66d9a3a16ac4c21a6 = L.marker(
                [47.6155804, -122.3428879],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_083776d32ffd9ed66d9a3a16ac4c21a6.bindTooltip(
                `<div>
                     Seattle Glassblowing Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_070aaaa3e709094fee64b0a00d1e54fa = L.marker(
                [47.754509, -122.34565],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_070aaaa3e709094fee64b0a00d1e54fa.bindTooltip(
                `<div>
                     Hobby Lobby
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_311e82794d5c9b1f608d2e159a25620a = L.marker(
                [47.6558318, -122.3360715],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_311e82794d5c9b1f608d2e159a25620a.bindTooltip(
                `<div>
                     Jupiter Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_424bea3ec854556478d2a0e5e8ba27f9 = L.marker(
                [47.6253347, -122.3230672],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_424bea3ec854556478d2a0e5e8ba27f9.bindTooltip(
                `<div>
                     Cornish College of the Arts-Kerry Hall/Poncho Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_51e4cb986d448d47b61512fb77ba09b9 = L.marker(
                [47.6599873, -122.319659],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_51e4cb986d448d47b61512fb77ba09b9.bindTooltip(
                `<div>
                     Artist & Craftsman Supply
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_230434803643b417af582adfdc846038 = L.marker(
                [47.62215, -122.355423],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_230434803643b417af582adfdc846038.bindTooltip(
                `<div>
                     Seattle Center Key Arena
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a558b28ec1801ad6f9a2549cc9741a7a = L.marker(
                [47.6677253, -122.3170573],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a558b28ec1801ad6f9a2549cc9741a7a.bindTooltip(
                `<div>
                     Kirsten Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_826f79f89bd0afd86ed75056fa04800a = L.marker(
                [47.5573208, -122.2844836],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_826f79f89bd0afd86ed75056fa04800a.bindTooltip(
                `<div>
                     Columbia City Theater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_329c75446ac0b1f7f99ac3898872d1e7 = L.marker(
                [47.614273, -122.317245],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_329c75446ac0b1f7f99ac3898872d1e7.bindTooltip(
                `<div>
                     Capitol Hill Block Party
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_923fa0704b5902cb69371cb4143dbb0d = L.marker(
                [47.624282, -122.325052],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_923fa0704b5902cb69371cb4143dbb0d.bindTooltip(
                `<div>
                     Temple of Cairo
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a81b5e9453ae06871f1630d28192b5c4 = L.marker(
                [47.5510384, -122.3518643],
                {"tags": ["Heritage"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a81b5e9453ae06871f1630d28192b5c4.bindTooltip(
                `<div>
                     South Seattle Community College Chinese Gardens
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cd86f8c72c3ee98e9e107843c732804e = L.marker(
                [47.6088801, -122.3403995],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cd86f8c72c3ee98e9e107843c732804e.bindTooltip(
                `<div>
                     Left Bank Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7305000f9a8463902a4b9eb70c2dbd65 = L.marker(
                [47.605034, -122.334244],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7305000f9a8463902a4b9eb70c2dbd65.bindTooltip(
                `<div>
                     SURFincubator II
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5d6ac67c79473354f057313550010ba6 = L.marker(
                [47.6060923, -122.3395432],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5d6ac67c79473354f057313550010ba6.bindTooltip(
                `<div>
                     Alki Arts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_39cd0d557813ffc4221bb72560ceffa1 = L.marker(
                [47.6902621, -122.3549016],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_39cd0d557813ffc4221bb72560ceffa1.bindTooltip(
                `<div>
                     826 Seattle/ The Greater Seattle Bureau of Fearless Ideas
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0a2b43d09132440a9e0dc1aa41e39170 = L.marker(
                [47.65147, -122.3536],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0a2b43d09132440a9e0dc1aa41e39170.bindTooltip(
                `<div>
                     Bahia In Motion
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b93b9862c532592965be3e84646209d1 = L.marker(
                [47.538437, -122.38826],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b93b9862c532592965be3e84646209d1.bindTooltip(
                `<div>
                     ProletariYacht Club
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e538e26cdfa5f96a249175d7e0db1d18 = L.marker(
                [47.559883, -122.290634],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e538e26cdfa5f96a249175d7e0db1d18.bindTooltip(
                `<div>
                     Arts in Motion
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_05986571fc0583ace3b619c81bbe225d = L.marker(
                [47.6128253, -122.3422256],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_05986571fc0583ace3b619c81bbe225d.bindTooltip(
                `<div>
                     WA State Holocaust Ed Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7c77ced2553c1b3e5c24a292c2bd0538 = L.marker(
                [47.722147, -122.2941323],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7c77ced2553c1b3e5c24a292c2bd0538.bindTooltip(
                `<div>
                     Jamtown
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4a473bb119543b9fbea3df3763cd10a4 = L.marker(
                [47.610928, -122.329353],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4a473bb119543b9fbea3df3763cd10a4.bindTooltip(
                `<div>
                     Elderwise
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bad8db9227d130b4606e87c6bc8ec4ca = L.marker(
                [47.5803398, -122.3112978],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bad8db9227d130b4606e87c6bc8ec4ca.bindTooltip(
                `<div>
                     Empty Sea Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d7745fc1ae7b9ca765ccd6643495661f = L.marker(
                [47.6169084, -122.321152],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d7745fc1ae7b9ca765ccd6643495661f.bindTooltip(
                `<div>
                     M. Rosetta Hunter Art Gallery - Seattle Central Community College
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_496e909ef174cc0909cba1aa445c4fa0 = L.marker(
                [47.6119449, -122.344463],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_496e909ef174cc0909cba1aa445c4fa0.bindTooltip(
                `<div>
                     Northwest Woodworkers Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_eba165dfd0356b5e2235191638f7d24c = L.marker(
                [47.6550814, -122.3596788],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_eba165dfd0356b5e2235191638f7d24c.bindTooltip(
                `<div>
                     Degenerate Art Ensemble
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5cfd8cae94f4a0969fd9c1453b6d8653 = L.marker(
                [47.5994156, -122.3305147],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5cfd8cae94f4a0969fd9c1453b6d8653.bindTooltip(
                `<div>
                     Seattle Presents: A Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8fc49584b38848969f2134b92873a957 = L.marker(
                [47.59823, -122.32286],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8fc49584b38848969f2134b92873a957.bindTooltip(
                `<div>
                     Wing Luke Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c917d671f7a2ca2146c1b949d4c24bf1 = L.marker(
                [47.684927, -122.355308],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c917d671f7a2ca2146c1b949d4c24bf1.bindTooltip(
                `<div>
                     Moonphoto
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4fda47a53c167538d4ec463075b752f5 = L.marker(
                [47.6688694, -122.3126674],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4fda47a53c167538d4ec463075b752f5.bindTooltip(
                `<div>
                     Jet City Improv
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_0adf4f576d0430547439472e6dc3e6fb = L.marker(
                [47.6156632, -122.3171739],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_0adf4f576d0430547439472e6dc3e6fb.bindTooltip(
                `<div>
                     Velocity Dance Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_19f7187ad6c2e2bfa74d8ec2fd6bc596 = L.marker(
                [47.6404243, -122.3023631],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_19f7187ad6c2e2bfa74d8ec2fd6bc596.bindTooltip(
                `<div>
                     Seattle Public Library Montlake
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_44b2817619591da22c96282476fec621 = L.marker(
                [47.5342216, -122.3500717],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_44b2817619591da22c96282476fec621.bindTooltip(
                `<div>
                     Highland Park Improvement Club
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e3f6cd3cb27226b02df69b6751cfa423 = L.marker(
                [47.6149287, -122.3282665],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e3f6cd3cb27226b02df69b6751cfa423.bindTooltip(
                `<div>
                     Baltic Room
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_18ac33693a12451ebd80b513266239ec = L.marker(
                [47.698273, -122.328456],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_18ac33693a12451ebd80b513266239ec.bindTooltip(
                `<div>
                     Silver Platters Northgate
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_00bf974bbe5e92d06773d5151d5bf11c = L.marker(
                [47.599903, -122.332888],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_00bf974bbe5e92d06773d5151d5bf11c.bindTooltip(
                `<div>
                     Drygoods Design
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2b36e8c68bc7bc2df7e314496c6f86c9 = L.marker(
                [47.60089, -122.333879],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2b36e8c68bc7bc2df7e314496c6f86c9.bindTooltip(
                `<div>
                     The Comedy Underground
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2f0638874498d773b53cc6702f64b452 = L.marker(
                [47.6133227, -122.3086811],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2f0638874498d773b53cc6702f64b452.bindTooltip(
                `<div>
                     Gallery 1412
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b678e8e68cc2372551858f2084c87d12 = L.marker(
                [47.62056855, -122.350491],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b678e8e68cc2372551858f2084c87d12.bindTooltip(
                `<div>
                     Chihuly Garden and Glass
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fcfc524a9d6309f6f568919c5c40eeef = L.marker(
                [47.7199293, -122.3050328],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_fcfc524a9d6309f6f568919c5c40eeef.bindTooltip(
                `<div>
                     George Center for Community
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_64cb426fc12f58533bb481fc85df9516 = L.marker(
                [47.6017992, -122.3366083],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_64cb426fc12f58533bb481fc85df9516.bindTooltip(
                `<div>
                     Seattle Aquarium
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9d1abaa49c790124ae5c2dfd4df72ae1 = L.marker(
                [47.7030576, -122.3337619],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9d1abaa49c790124ae5c2dfd4df72ae1.bindTooltip(
                `<div>
                     Stage One Theatre- North Seattle Community College
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_2dbe90d55ac8d2d1aad1ba99eb3f5cd6 = L.marker(
                [47.61311, -122.288887],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_2dbe90d55ac8d2d1aad1ba99eb3f5cd6.bindTooltip(
                `<div>
                     Glassybaby Madrona
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_321b70b9b51196de78e18922891a02d9 = L.marker(
                [47.6676256, -122.3132962],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_321b70b9b51196de78e18922891a02d9.bindTooltip(
                `<div>
                     LUCID Lounge
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_53611c0b57a6f2c7c6b1e892edba9d42 = L.marker(
                [47.614211, -122.325396],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_53611c0b57a6f2c7c6b1e892edba9d42.bindTooltip(
                `<div>
                     Theater Schmeater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cb8a9c2e23baff823fd1b55c658a7a30 = L.marker(
                [47.601051, -122.333443],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cb8a9c2e23baff823fd1b55c658a7a30.bindTooltip(
                `<div>
                     Laguna
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9257d8906707529509790dff43a49ae9 = L.marker(
                [47.61426, -122.317856],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9257d8906707529509790dff43a49ae9.bindTooltip(
                `<div>
                     Annex Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_279a1fa47677f6fac0ac2cbfea8b7992 = L.marker(
                [47.542519, -122.269028],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_279a1fa47677f6fac0ac2cbfea8b7992.bindTooltip(
                `<div>
                     Columbia City Farmers Market
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d5175ec8da90c6ddd0e1421c994bd340 = L.marker(
                [47.5988665, -122.3239595],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d5175ec8da90c6ddd0e1421c994bd340.bindTooltip(
                `<div>
                     Theatre Off Jackson
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ce8beb9a58166cefba666a4dc16c0336 = L.marker(
                [47.5999356, -122.3353103],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ce8beb9a58166cefba666a4dc16c0336.bindTooltip(
                `<div>
                     Flatcolor Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e0ba4022b6085543f01c194e98bc1848 = L.marker(
                [47.6132215, -122.3051662],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e0ba4022b6085543f01c194e98bc1848.bindTooltip(
                `<div>
                     Central Cinema
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4e0723a7faa8d2d9e757baafca94985c = L.marker(
                [47.6081565, -122.3018854],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4e0723a7faa8d2d9e757baafca94985c.bindTooltip(
                `<div>
                     ALTspace
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_baf42aa547ff677f2fa21137bf930c33 = L.marker(
                [47.615215, -122.350227],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_baf42aa547ff677f2fa21137bf930c33.bindTooltip(
                `<div>
                     Artech
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8fec72642dcf338368a50c352d1030e4 = L.marker(
                [47.623119, -122.295752],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8fec72642dcf338368a50c352d1030e4.bindTooltip(
                `<div>
                     The Music Factory
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bdad290b729188b02ae61f82f0dafaf0 = L.marker(
                [47.616871, -122.331184],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bdad290b729188b02ae61f82f0dafaf0.bindTooltip(
                `<div>
                     Kremwerk
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_49060b3af713c640bb355ec47392bf58 = L.marker(
                [47.5610855, -122.3854525],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_49060b3af713c640bb355ec47392bf58.bindTooltip(
                `<div>
                     Twilight Artist Collective
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d58368bce0e1262c7f1f50bc2208c812 = L.marker(
                [47.6135576, -122.3442489],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d58368bce0e1262c7f1f50bc2208c812.bindTooltip(
                `<div>
                     Crocodile
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a087533361f9016372ee3cc6de8715cc = L.marker(
                [47.6167931, -122.3361846],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a087533361f9016372ee3cc6de8715cc.bindTooltip(
                `<div>
                     Cornish College of the Arts-Beebe Building
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d6d670aa5fa468028e93e5ce17d48e3a = L.marker(
                [47.599777, -122.328575],
                {"tags": ["Live/Work"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d6d670aa5fa468028e93e5ce17d48e3a.bindTooltip(
                `<div>
                     Addison on Fourth
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7108b960649d57f57eb65a7bbce0dc17 = L.marker(
                [47.649367, -122.332294],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7108b960649d57f57eb65a7bbce0dc17.bindTooltip(
                `<div>
                     Lightbank Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_03c406669ca6dd910355abbb7f17cf5b = L.marker(
                [47.6562474, -122.3092754],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_03c406669ca6dd910355abbb7f17cf5b.bindTooltip(
                `<div>
                     University of Washington Department of Architecture
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_29e65e779d40d5c6e64d06c7f777451e = L.marker(
                [47.6219768, -122.3230383],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_29e65e779d40d5c6e64d06c7f777451e.bindTooltip(
                `<div>
                     FRED Wildlife Refuge
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b97d092c64fac46b0187a830085584fe = L.marker(
                [47.657048, -122.305271],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b97d092c64fac46b0187a830085584fe.bindTooltip(
                `<div>
                     University of Washington Communications Building
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4a9c2c50e9f5b89cd6d427ca311e7059 = L.marker(
                [47.560593, -122.338676],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4a9c2c50e9f5b89cd6d427ca311e7059.bindTooltip(
                `<div>
                     IsGood Woodworks
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_15858027b288e23aa1980f0ee9794fff = L.marker(
                [47.556924, -122.2843057],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_15858027b288e23aa1980f0ee9794fff.bindTooltip(
                `<div>
                     Royal Room
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b771a42add788c3fe01236b9ba8dd2e4 = L.marker(
                [47.542263, -122.273064],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b771a42add788c3fe01236b9ba8dd2e4.bindTooltip(
                `<div>
                     Southeast Seattle Senior Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_071aa8fe2b2f8454d55fd8fc38f81bec = L.marker(
                [47.6182086, -122.2880059],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_071aa8fe2b2f8454d55fd8fc38f81bec.bindTooltip(
                `<div>
                     Prographica Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6e3a27748e938c0409f123256d57ddf1 = L.marker(
                [47.5490859, -122.3169537],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6e3a27748e938c0409f123256d57ddf1.bindTooltip(
                `<div>
                     Georgetown Records and Fantagraphics Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4f237cfa2f4009cd2acbd132b9c986bf = L.marker(
                [47.6010176, -122.3297496],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4f237cfa2f4009cd2acbd132b9c986bf.bindTooltip(
                `<div>
                     Design Commission Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3e13380c3bfe764493dff8929b04a57d = L.marker(
                [47.723804, -122.347351],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3e13380c3bfe764493dff8929b04a57d.bindTooltip(
                `<div>
                     Greenwood Violin Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c35251782eb7943a4e4ee1ca82833198 = L.marker(
                [47.6121708, -122.319849],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c35251782eb7943a4e4ee1ca82833198.bindTooltip(
                `<div>
                     Blick Art Materials
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_763c1d0d8429ffc1f7d72e3dfb7ea70e = L.marker(
                [47.6146657, -122.3196776],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_763c1d0d8429ffc1f7d72e3dfb7ea70e.bindTooltip(
                `<div>
                     Elliott Bay Book Company
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9eb4521af2952809b92c90de7eb5c580 = L.marker(
                [47.572998, -122.294708],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9eb4521af2952809b92c90de7eb5c580.bindTooltip(
                `<div>
                     Emerald City Fired Arts Studio and Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_9222f43d9eb68de555aa4445a7a8f179 = L.marker(
                [47.6236732, -122.3590953],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_9222f43d9eb68de555aa4445a7a8f179.bindTooltip(
                `<div>
                     501 Commons
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1405a68415202ba1aeedb0fd283f3241 = L.marker(
                [47.611458, -122.344795],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1405a68415202ba1aeedb0fd283f3241.bindTooltip(
                `<div>
                     Gallery Mack's Art Connection
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5c7498341769f59c21ee2abcdfa96071 = L.marker(
                [47.60284, -122.3145874],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5c7498341769f59c21ee2abcdfa96071.bindTooltip(
                `<div>
                     Washington Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d03986c82283c2f9abdaba0b35ea76c8 = L.marker(
                [47.66127, -122.314006],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d03986c82283c2f9abdaba0b35ea76c8.bindTooltip(
                `<div>
                     The Comic Stop U District
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c340eea5fa7427c6597c3ed5a79bb0cb = L.marker(
                [47.650017, -122.349812],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c340eea5fa7427c6597c3ed5a79bb0cb.bindTooltip(
                `<div>
                     Canvas Paint & Sip
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_8d44f61002a01b2e90268bc14ddeb4e8 = L.marker(
                [47.5972693, -122.321963],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_8d44f61002a01b2e90268bc14ddeb4e8.bindTooltip(
                `<div>
                     Hengda Dance Academy
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_356164939ed7041958d57a8926c94d21 = L.marker(
                [47.5601782, -122.387154],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_356164939ed7041958d57a8926c94d21.bindTooltip(
                `<div>
                     Northwest Art & Frame
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6a3fe60ff289c6210f31734ebefafd72 = L.marker(
                [47.668369, -122.398666],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6a3fe60ff289c6210f31734ebefafd72.bindTooltip(
                `<div>
                     Ballard NW Senior Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e3b327bb3a0430bfcb038eda02efcef2 = L.marker(
                [47.601212, -122.33522],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e3b327bb3a0430bfcb038eda02efcef2.bindTooltip(
                `<div>
                     Da Projectz Music Recording Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d701802026e56e414a60d0e70c7a0c89 = L.marker(
                [47.6217088, -122.3389018],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d701802026e56e414a60d0e70c7a0c89.bindTooltip(
                `<div>
                     MadArt
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a7524f1df2c886a9689cd15f0c563a53 = L.marker(
                [47.61205715, -122.3191481],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a7524f1df2c886a9689cd15f0c563a53.bindTooltip(
                `<div>
                     Vachon Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_803c030f86942412c21218bdf4a44169 = L.marker(
                [47.662073, -122.31303],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_803c030f86942412c21218bdf4a44169.bindTooltip(
                `<div>
                     Moksha
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_478e90fc6dc3c59cc2577a68c18f95a0 = L.marker(
                [47.618217, -122.35183],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_478e90fc6dc3c59cc2577a68c18f95a0.bindTooltip(
                `<div>
                     Seattle PI/Hearst Media Services
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cb8b507004bed2167b00b5a69b63f489 = L.marker(
                [47.6100596, -122.3163837],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cb8b507004bed2167b00b5a69b63f489.bindTooltip(
                `<div>
                     Kinsey Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_eb26b8e6b82de9f33e9aa8d7b03c458b = L.marker(
                [47.6127204, -122.3378104],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_eb26b8e6b82de9f33e9aa8d7b03c458b.bindTooltip(
                `<div>
                     The Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b2d5ac314cb78a1c6e8235b14aca9a39 = L.marker(
                [47.61941385, -122.3508085],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b2d5ac314cb78a1c6e8235b14aca9a39.bindTooltip(
                `<div>
                     Seattle Center Pacific Science Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3fd19187d333e45346ebc64fe5ee8fc5 = L.marker(
                [47.661911, -122.284111],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3fd19187d333e45346ebc64fe5ee8fc5.bindTooltip(
                `<div>
                     Paper Source
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_49a307c34cde111df130fdb5e9e555f9 = L.marker(
                [47.690174, -122.354958],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_49a307c34cde111df130fdb5e9e555f9.bindTooltip(
                `<div>
                     Seattle ReCreative
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7b88dd049074befd2719ef5161b74cfa = L.marker(
                [47.5700038, -122.3625235],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7b88dd049074befd2719ef5161b74cfa.bindTooltip(
                `<div>
                     Skylark Cafe & Club
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3bab1298576f2b959900d08da12b6053 = L.marker(
                [47.622829, -122.28698],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3bab1298576f2b959900d08da12b6053.bindTooltip(
                `<div>
                     The Bush School Speaker Series
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3bb24ef08196d52236d361ccc86c6fc0 = L.marker(
                [47.560037, -122.385507],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3bb24ef08196d52236d361ccc86c6fc0.bindTooltip(
                `<div>
                     Fuzzy Lounge Recording
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f0d20eae2afd8b7cdc72aefe333d6b62 = L.marker(
                [47.656479, -122.311352],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f0d20eae2afd8b7cdc72aefe333d6b62.bindTooltip(
                `<div>
                     University of Washington Odegard Undergraduate Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_49f003947b53f78de5d7b5a1297bc382 = L.marker(
                [47.6575835, -122.344895],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_49f003947b53f78de5d7b5a1297bc382.bindTooltip(
                `<div>
                     Windows Art Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f497d316f6562aaa7a893e4d279ef69f = L.marker(
                [47.6253458, -122.3561735],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f497d316f6562aaa7a893e4d279ef69f.bindTooltip(
                `<div>
                     Keys on Main
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d24be9884451b67073a353a46123a88d = L.marker(
                [47.568764, -122.386375],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d24be9884451b67073a353a46123a88d.bindTooltip(
                `<div>
                     Thunder Road Guitars
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f0ad159ac84e0cbab283d793b262bf62 = L.marker(
                [47.652184, -122.356773],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f0ad159ac84e0cbab283d793b262bf62.bindTooltip(
                `<div>
                     Sound Guitar Repair
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_42e29a52a3f15bdba2c310fa8ccad2f2 = L.marker(
                [47.610049, -122.282632],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_42e29a52a3f15bdba2c310fa8ccad2f2.bindTooltip(
                `<div>
                     Spectrum Dance Theater
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6623ca334e54f7ab9ca810ba8a16426c = L.marker(
                [47.6066246, -122.3369157],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6623ca334e54f7ab9ca810ba8a16426c.bindTooltip(
                `<div>
                     MIA Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1d5a7f064872f012093a48f09765ec8a = L.marker(
                [47.627403, -122.347137],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1d5a7f064872f012093a48f09765ec8a.bindTooltip(
                `<div>
                     Hall Spassov Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_01fd8eb345b873d8b65616c3336fe03f = L.marker(
                [47.6044443, -122.3074673],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_01fd8eb345b873d8b65616c3336fe03f.bindTooltip(
                `<div>
                     Rain City Rock Camp for Girls
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3bcc437caf5d1a920d4c8b6593a55725 = L.marker(
                [47.5825204, -122.334653],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3bcc437caf5d1a920d4c8b6593a55725.bindTooltip(
                `<div>
                     Living Computer Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f40faf2f26bbd4703bfa0acf5c63fdd8 = L.marker(
                [47.6604253, -122.3128269],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f40faf2f26bbd4703bfa0acf5c63fdd8.bindTooltip(
                `<div>
                     University Book Store
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_075eb6c6076b483dc1e68c214ede9ea0 = L.marker(
                [47.600887, -122.334482],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_075eb6c6076b483dc1e68c214ede9ea0.bindTooltip(
                `<div>
                     Revolution Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c02992d46af89e3781891974ee885996 = L.marker(
                [47.582653, -122.328331],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_c02992d46af89e3781891974ee885996.bindTooltip(
                `<div>
                     Pacific Fabrics and Crafts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3f5e6f2d6fbd65af4571f9aca0640d9e = L.marker(
                [47.62056855, -122.350491],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3f5e6f2d6fbd65af4571f9aca0640d9e.bindTooltip(
                `<div>
                     Seattle Center/Center House Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3cbc73bbc50c1b022620a6ad65aa9680 = L.marker(
                [47.668777, -122.295395],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3cbc73bbc50c1b022620a6ad65aa9680.bindTooltip(
                `<div>
                     The Curious Nest
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_1e72759b0ff41916205cad5f1b5be39f = L.marker(
                [47.615807, -122.328384],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_1e72759b0ff41916205cad5f1b5be39f.bindTooltip(
                `<div>
                     Vignettes Gallery at El Capitan Apartments
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4df03a3b2ddf81c6eae5e31e73e24353 = L.marker(
                [47.585333, -122.33327],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4df03a3b2ddf81c6eae5e31e73e24353.bindTooltip(
                `<div>
                     SoDo MakerSpace
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_66e7e6c98d93596acf1b781c00ebe8b3 = L.marker(
                [47.6151596, -122.3147172],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_66e7e6c98d93596acf1b781c00ebe8b3.bindTooltip(
                `<div>
                     The Project Room
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e4e2098f572fd43cf400727600dfc804 = L.marker(
                [47.5979017, -122.3339034],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e4e2098f572fd43cf400727600dfc804.bindTooltip(
                `<div>
                     Art Xchange Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b1a728dc89e79fa4b7a1632916a7cf76 = L.marker(
                [47.6070478, -122.3364073],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b1a728dc89e79fa4b7a1632916a7cf76.bindTooltip(
                `<div>
                     Abmeyer + Wood Fine Art
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e60dd18ed7bc98fe320acfa5feb24d6b = L.marker(
                [47.5655555, -122.3336229],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e60dd18ed7bc98fe320acfa5feb24d6b.bindTooltip(
                `<div>
                     Daniel Smith Art Supplies
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ff67d7e822cb4156bfdfea3538d72ce8 = L.marker(
                [47.6149584, -122.3257242],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ff67d7e822cb4156bfdfea3538d72ce8.bindTooltip(
                `<div>
                     True Love Art Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_28e2308dbf84efef61a82dbba29027dd = L.marker(
                [47.6841406, -122.3555094],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_28e2308dbf84efef61a82dbba29027dd.bindTooltip(
                `<div>
                     Avanti Art and Design/Avanti Co-Op Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cac7e7e412d8d3aae21dfe035ec9bacf = L.marker(
                [47.577168, -122.297668],
                {"tags": ["Live/Work"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_cac7e7e412d8d3aae21dfe035ec9bacf.bindTooltip(
                `<div>
                     Artspace Mt Baker Lofts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_e9e5486e066ef793eaca6dcbc4ad201f = L.marker(
                [47.6088638, -122.3413696],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_e9e5486e066ef793eaca6dcbc4ad201f.bindTooltip(
                `<div>
                     Cornish College of the Arts
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5d2cf1a4eca7ca3c87eb8a3bd838e46e = L.marker(
                [47.6514144, -122.3555957],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5d2cf1a4eca7ca3c87eb8a3bd838e46e.bindTooltip(
                `<div>
                     Fremont Studios
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ac5690f02d62206e628c8f85fdd7b7b1 = L.marker(
                [47.522442, -122.3762926],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ac5690f02d62206e628c8f85fdd7b7b1.bindTooltip(
                `<div>
                     Seattle Public Library Southwest
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b3817bb83c14d295bd2ab8e49ed168ec = L.marker(
                [47.6584363, -122.312882],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b3817bb83c14d295bd2ab8e49ed168ec.bindTooltip(
                `<div>
                     Magus Books
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_00219da38735e51ea65f72159a3e6b16 = L.marker(
                [47.654649, -122.304544],
                {"tags": ["Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_00219da38735e51ea65f72159a3e6b16.bindTooltip(
                `<div>
                     University of Washington Engineering Library
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b61cacbb30e223cb126379b89aef5d07 = L.marker(
                [47.59511695, -122.3270859],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b61cacbb30e223cb126379b89aef5d07.bindTooltip(
                `<div>
                     Inscape Building
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_bc01375e5db94025dca2befb3ec0d669 = L.marker(
                [47.6494509, -122.3481059],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_bc01375e5db94025dca2befb3ec0d669.bindTooltip(
                `<div>
                     Salsa Con Todo
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ab6963cf2fe0e44de6f21566b6a62d64 = L.marker(
                [47.58176075, -122.3130944],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ab6963cf2fe0e44de6f21566b6a62d64.bindTooltip(
                `<div>
                     Beacon Arts and Garden House
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4ee98a40e6ac5f2b4cc50bf99eaaf2c3 = L.marker(
                [47.6614953, -122.3199004],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4ee98a40e6ac5f2b4cc50bf99eaaf2c3.bindTooltip(
                `<div>
                     Blue Moon Tavern
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_83eba8444f8e066cd8e0dac94e94b7c1 = L.marker(
                [47.521908, -122.388489],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_83eba8444f8e066cd8e0dac94e94b7c1.bindTooltip(
                `<div>
                     Fauntleroy Schoolhouse/Fauntleroy Community Service Agency
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3a25e9d9d2d1103193e6913457bd34ac = L.marker(
                [47.6513564, -122.3515985],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_3a25e9d9d2d1103193e6913457bd34ac.bindTooltip(
                `<div>
                     Edge of Glass Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_07c3c66bc7c293590b2eacc717eae8c0 = L.marker(
                [47.56357765, -122.3630304],
                {"tags": ["Multi-use"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_07c3c66bc7c293590b2eacc717eae8c0.bindTooltip(
                `<div>
                     Youngstown Cultural Arts Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_dcb8b8a8a54bbd9889699c49340d8932 = L.marker(
                [47.560077, -122.286461],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_dcb8b8a8a54bbd9889699c49340d8932.bindTooltip(
                `<div>
                     Horn of Africa Services
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_531b724910586a57e8e08aacbe191177 = L.marker(
                [47.6524012, -122.3563132],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_531b724910586a57e8e08aacbe191177.bindTooltip(
                `<div>
                     West of Lenin
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7ebe1b85df0eccd4019611f53bd003f3 = L.marker(
                [47.6691001, -122.3857909],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7ebe1b85df0eccd4019611f53bd003f3.bindTooltip(
                `<div>
                     Ghost Light Theatricals/The Ballard Underground
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a04161bce6606d51280dc9291424307f = L.marker(
                [47.662434, -122.3304744],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a04161bce6606d51280dc9291424307f.bindTooltip(
                `<div>
                     Seattle Music Partners
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a925661bf203a22ddb4b549c4da8a267 = L.marker(
                [47.677133, -122.3539896],
                {"tags": ["Community Center"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_a925661bf203a22ddb4b549c4da8a267.bindTooltip(
                `<div>
                     Phinney Neighborhood Association
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_b5bfd209ec3ea79a531d7b9c1f3fa264 = L.marker(
                [47.649744, -122.349798],
                {"tags": ["Service/Supply"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_b5bfd209ec3ea79a531d7b9c1f3fa264.bindTooltip(
                `<div>
                     Dusty Strings
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5abc4c4ee81633c1b8f62d7bdb290f5d = L.marker(
                [47.6617428, -122.3180727],
                {"tags": ["Cinema"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5abc4c4ee81633c1b8f62d7bdb290f5d.bindTooltip(
                `<div>
                     Sundance Cinemas LLC-Sundance Seattle
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_be2b798bf073c1369677be9fa00135db = L.marker(
                [47.6212523, -122.3509484],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_be2b798bf073c1369677be9fa00135db.bindTooltip(
                `<div>
                     Seattle Center Seattle Children's Museum
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_270eb47e2061a53a0e9c5f1491908526 = L.marker(
                [47.6113032, -122.340846],
                {"tags": ["Performance"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_270eb47e2061a53a0e9c5f1491908526.bindTooltip(
                `<div>
                     STG Moore Theatre
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d90cd213c52de9b33a821d32a25f03bd = L.marker(
                [47.6814905, -122.3267044],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_d90cd213c52de9b33a821d32a25f03bd.bindTooltip(
                `<div>
                     Seattle Public Library Green Lake
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_ee12325d8caff955fb527a1f76c94653 = L.marker(
                [47.652355, -122.3538429],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_ee12325d8caff955fb527a1f76c94653.bindTooltip(
                `<div>
                     Nectar
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_42097109f4587f776e0f1d3ed8c04f2d = L.marker(
                [47.6760768, -122.3170608],
                {"tags": ["Literary"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_42097109f4587f776e0f1d3ed8c04f2d.bindTooltip(
                `<div>
                     East West Bookshop
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5cc8c3c0b43ffe1baa4cf56ac41aa836 = L.marker(
                [47.6131504, -122.3051798],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5cc8c3c0b43ffe1baa4cf56ac41aa836.bindTooltip(
                `<div>
                     Reel Grrls
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_32c1ec1fd7d8144b56f6d93955c0d31a = L.marker(
                [47.582939, -122.333694],
                {"tags": ["Studios"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_32c1ec1fd7d8144b56f6d93955c0d31a.bindTooltip(
                `<div>
                     McComb Sound
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_f0460813aba74ed14252abeb02a9fcf0 = L.marker(
                [47.68528, -122.354912],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_f0460813aba74ed14252abeb02a9fcf0.bindTooltip(
                `<div>
                     Illumination Learning Studio
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_5f785d3ef65d6bfb88d6f9236ac278f2 = L.marker(
                [47.63803, -122.325924],
                {"tags": ["Music"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_5f785d3ef65d6bfb88d6f9236ac278f2.bindTooltip(
                `<div>
                     Serafina
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_7c6325abd929bdf904fdecd0572357ca = L.marker(
                [47.550962, -122.318612],
                {"tags": ["Visual"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_7c6325abd929bdf904fdecd0572357ca.bindTooltip(
                `<div>
                     Eight and Sand Gallery
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6ddf538be27ef31bfadeaa2bde235e3a = L.marker(
                [47.657048, -122.305271],
                {"tags": ["Arts/Cultural Training or Education"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_6ddf538be27ef31bfadeaa2bde235e3a.bindTooltip(
                `<div>
                     University of Washington Mary Gates Hall
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4a4fae382d9fa11b56dd747a85c57740 = L.marker(
                [47.622541, -122.34748],
                {"tags": ["Arts/Cultural Administration or Advocacy"]}
            ).addTo(marker_cluster_6a339f04bd98b68b397aacfb9f90cb9e);
        
    
            marker_4a4fae382d9fa11b56dd747a85c57740.bindTooltip(
                `<div>
                     Bill & Melinda Gates Foundation Visitor Center
                 </div>`,
                {"sticky": true}
            );
        
    
            var tag_filter_button_e543bff5b8cfe5a550b03d22aa5da690 = L.control.tagFilterButton(
                {"clearText": "clear", "data": ["Arts/Cultural Administration or Advocacy", "Arts/Cultural Training or Education", "Cinema", "Community Center", "Education", "Heritage", "Literary", "Live/Work", "Multi-use", "Music", "Performance", "Service/Supply", "Studios", "Visual"], "filterOnEveryClick": true, "icon": "fa-filter", "openPopupOnHover": false}
            ).addTo(map_e6658fd49515d4f1ae97f0f842a9029a);
        
</script>

  <br>
   For this visualization I used a dataset from the City of Seattle to plot cultural spaces in Seattle. I filtered out spaces that were not active, then plotted them on an interactive map. Because there were so many spaces I chose to have the map cluster the points as you zoom out. I also added a filter for type of space (dominant discipline). There were too many categories to add different symbology for each discipline, but adding the filter lets the user see only particular space types they are interested in. Finally, I added a tooltip so people can see the name of a space. 
  
</body>
</html>
