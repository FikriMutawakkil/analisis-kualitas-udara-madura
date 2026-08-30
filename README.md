# Analisis Kualitas Udara — Kecamatan Pakong, Madura

Proyek ini menganalisis kualitas udara di **Kecamatan Pakong, Kabupaten Pamekasan, Madura, Jawa Timur** menggunakan data satelit **Sentinel-5P (TROPOMI)** yang diakses melalui **openEO API** di **Copernicus Data Space Ecosystem (CDSE)**.

## Identitas
- **Nama:** [A. Fikri Mutawakkil]
- **NIM:** [240411100105]
- **Mata Kuliah / Tugas:** Data Understanding & Eksplorasi Data Kualitas Udara

## Ringkasan Proyek

**Business Understanding:**
Mengamati kualitas udara melalui 4 polutan utama sebagai indikator baik-buruknya kualitas udara suatu wilayah:
- **NO2** (Nitrogen Dioksida) — indikator aktivitas transportasi/industri
- **CO** (Karbon Monoksida) — hasil pembakaran tidak sempurna
- **CH4** (Metana) — gas rumah kaca, terkait pertanian & lahan gambut
- **SO2** (Sulfur Dioksida) — terkait pembakaran bahan bakar fosil/industri

**Data Understanding:**
- Sumber data: Copernicus Data Space Ecosystem — koleksi `SENTINEL_5P_L2`
- Wilayah studi: Kecamatan Pakong, Pamekasan (lihat `data/peta madura.geojson`)
- Periode: 24 Agustus 2025 – 24 Agustus 2026

**Eksplorasi Data (EDA):**
- Visualisasi peta wilayah studi
- Identifikasi missing value (data satelit berlubang akibat tutupan awan)
- Penanganan missing value dengan interpolasi linear (gap-filling)
- Identifikasi outlier (metode IQR / boxplot)
- Identifikasi noise data (rolling mean vs data harian)

## Struktur Folder
