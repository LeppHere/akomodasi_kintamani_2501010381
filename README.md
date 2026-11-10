# Akuisisi Data Akomodasi Kecamatan Kintamani

## Identitas
- Nama: Fadhil Firjatullah
- NIM: 2501010381
- Mata Kuliah: Akuisisi Data dan Manajemen Data (BIFP-243)
- Wilayah: Kecamatan Kintamani, Kabupaten Bangli, Bali

## Sumber Data
- OpenStreetMap (OSM) melalui Overpass API
- BIG Satu Peta untuk batas administrasi
- BPS Kabupaten Bangli sebagai data pembanding

## Hasil Akuisisi
Total data akomodasi yang diperoleh: 32 objek.

Kategori:
- Hotel: 16
- Guest House: 9
- Hostel: 4
- Chalet: 2
- Motel: 1

## Validasi
Sebanyak 10 sampel diperiksa berdasarkan atribut OSM dan posisi koordinat terhadap batas Kecamatan Kintamani.

## Struktur Folder
- data/raw: data mentah hasil akuisisi
- data/interim: data hasil pengolahan
- notebooks: notebook Google Colab
- docs: dokumentasi dan validasi
- reports: peta dan laporan

## Catatan
Data OpenStreetMap dapat memiliki atribut yang belum lengkap dan tidak selalu mencerminkan seluruh akomodasi yang beroperasi di lapangan.

## Lisensi
Data OpenStreetMap © kontributor OpenStreetMap, tersedia di bawah Open Database License (ODbL).