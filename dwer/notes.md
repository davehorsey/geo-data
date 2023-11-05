## DWER-001

``` zsh 
ogr2ogr -f FlatGeobuf dwer-001.fgb "https://public-services.slip.wa.gov.au/public/rest/services/SLIP_Public_Services/Boundaries/MapServer/9/query?where=1%3D1&outFields=*&featureEncoding=esriDefault&f=geojson" OGRGeoJSON
```