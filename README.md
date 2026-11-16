# Peta 6 Danau UI

Peta interaktif enam danau di kampus Universitas Indonesia, Depok, beserta perkiraan arah aliran airnya.

Dibuat oleh Pramono Pido, Departemen Geografi, Fakultas Matematika dan Ilmu Pengetahuan Alam, Universitas Indonesia.
Halaman statis (MapLibre GL JS), terbuka tanpa akun: https://prampido.github.io/peta-danau-ui/

## Data
- `data/danau_ui_6.geojson`: 6 danau bernama dari OpenStreetMap (via Overture Maps rilis 2026-10-21). `elev_dsm_m` = perkiraan tinggi muka air dari Copernicus DEM GLO-30 (dibulatkan).
- `data/hutan_osm.geojson`: poligon forest/wood OSM di sekitar kampus.
- `data/kampus_ui_dan_ui_park.geojson`: batas landuse "Universitas Indonesia" dan "UI Park" dari OSM.
- `data/aliran_d8.geojson`: garis aliran perkiraan (D8 steepest descent setelah pit-fill) dari Copernicus GLO-30 30 m. Ilustratif, bukan hasil survei.

Kredit: Copernicus DEM GLO-30 (ESA/Airbus); © kontributor OpenStreetMap (ODbL) via Overture Maps; peta dasar © kontributor OpenStreetMap; citra © Esri; ketinggian 3D Mapzen Terrain Tiles (AWS Open Data). MapLibre GL JS (BSD-3-Clause) ada di `lib/`.
