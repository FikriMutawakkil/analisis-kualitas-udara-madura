# Analisis Kualitas Udara NO₂

Analisis konsentrasi **Nitrogen Dioxide (NO₂)** menggunakan data Sentinel-5P/TROPOMI melalui **Copernicus Data Space Ecosystem (CDSE)** dan **openEO**.

## Tujuan
Menganalisis perubahan nilai NO₂ pada wilayah penelitian selama periode 24 Agustus 2025–3 Agustus 2026 dan menghasilkan data serta visualisasi time-series.

## Sumber Data
- Copernicus Data Space Ecosystem
- Sentinel-5P / TROPOMI
- Collection: `SENTINEL_5P_L2`
- Band: `NO2`

## Periode Penelitian
24 Agustus 2025 – 3 Agustus 2026

## Wilayah Penelitian
AOI menggunakan bounding box:
- West: 113.5196999
- South: -7.0594754
- East: 113.573856
- North: -7.0215453
- CRS: EPSG:4326

## Tools
- Google Colab
- Python
- openEO
- Copernicus Data Space
- GeoJSON

## Struktur Repository
```text
analisis-kualitas-udara-no2/
├── README.md
├── notebook/
│   └── analisis_NO2.ipynb
├── geojson/
│   └── aoi.geojson
├── data/
│   └── README.md
├── hasil/
│   └── README.md
└── requirements.txt
```

## Catatan Keamanan
Jangan menyimpan password, access token, refresh token, atau credential Copernicus di repository GitHub.
