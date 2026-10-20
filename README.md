# Dokumentasi Eksekusi Recipe: R-GEO-001

## Deskripsi Tugas
Memetakan sebaran titik episentrum gempa bumi (GeoJSON USGS) di atas peta dasar topografi dan batimetri raster (DEM GEBCO) wilayah Maluku Utara & Laut Molucca.

## Metadata Data
- **Data Vector:** USGS Earthquake Hazards API (`all_month.geojson`)
  - Geometry Type: Point (3D)
  - Coordinate System: EPSG:4326 (WGS 84)
- **Data Raster:** GEBCO Gridded Bathymetry (`dem_maluku.tif`)
  - Bounds: [124.0, -2.0, 129.0, 3.0]
  - Resolution: 15 arc-seconds

## Analisis Ringkas Geofisika
1. **Pola Seismisitas:**
   Aktivitas gempa bumi di Laut Molucca menunjukkan konsentrasi episentrum yang sangat padat akibat zona konvergensi ganda (*double subduction*) antara Lempeng Laut Molucca, Lempeng Halmahera, dan Lempeng Sangihe.
2. **Distribusi Kedalaman:**
   Gempa dangkal (< 70 km) mendominasi area palung laut dan batas busur vulkanik Halmahera, sedangkan gempa menengah-dalam tersebar di sepanjang penunjaman lempeng.

## Artifact Output
- Path Simpan: `artifacts/recipes/visualization/r-geo-001_maluku.png`
- Format: PNG High-Resolution (300 DPI)