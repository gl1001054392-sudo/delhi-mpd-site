# Delhi Atlas / 2047

[Open Delhi Atlas](https://gl1001054392-sudo.github.io/delhi-mpd-site/)

An independent map of published Delhi planning geography. Explore 18 native DDA zone features, soft zone colors, Street/Satellite/geometry basemaps, and clickable planning context. Sources, dates, exports and limitations are available under **Info**.

The map is indicative and does not establish parcel permissions or policy eligibility. Satellite and aerial imagery have varying capture dates and require internet.

## Published files

- `index.html`: self-contained application, including Leaflet, source geometry, planning context and archive images.
- `original.html`: supplied original dashboard, preserved unchanged and clearly separated from the working map.
- `.nojekyll`: publish the files as a static GitHub Pages site.

GitHub Pages publishes **main / (root)**. Future updates replace `index.html` with the regenerated hosted version; no server, database or credentials are required.

## Sources

- [DDA Master Plan for Delhi 2047](https://dda.gov.in/master_plan_2047)
- [OpenStreetMap](https://www.openstreetmap.org/copyright) for street tiles.
- [Esri World Imagery](https://www.arcgis.com/home/item.html?id=10df2279f9684e4a9f6a7f08febac2a9) for satellite/aerial imagery, with provider attribution shown on the map.
- Independent Open-Meteo weather and CAMS forecasts load only when the Environment tool is opened.

Leaflet 1.9.4 copyright and license notices are retained in the embedded application. All provider attributions and source metadata remain available in the interface.
