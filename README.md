# Akuisisi Data Cuaca Denpasar, Bali Menggunakan Open-Meteo API

## 1. Deskripsi Proyek

Proyek ini bertujuan untuk melakukan akuisisi data cuaca historis di wilayah Denpasar, Bali, menggunakan Open-Meteo Historical Weather API.

Data yang diperoleh kemudian diolah menggunakan Python dan Pandas, lalu disimpan dalam format CSV untuk kebutuhan analisis dan dokumentasi.

## 2. Sumber Data

- Nama sumber: Open-Meteo
- API: Historical Weather API
- URL: https://open-meteo.com/en/docs/historical-weather-api
- Lokasi: Denpasar, Bali, Indonesia
- Latitude: -8.65
- Longitude: 115.22
- Timezone: Asia/Singapore

## 3. Periode Pengambilan Data

- Tanggal mulai: 1 November 2026
- Tanggal selesai: 7 November 2026
- Interval data: Per jam (hourly)

## 4. Variabel Data

Dataset memiliki delapan kolom:

1. waktu
2. lokasi
3. suhu_celsius
4. kelembapan_persen
5. curah_hujan_mm
6. kecepatan_angin_kmh
7. tutupan_awan_persen
8. kode_cuaca

## 5. Metode Akuisisi

Proses akuisisi dilakukan menggunakan Python dengan tahapan:

1. Mengimpor library Requests dan Pandas.
2. Menentukan koordinat dan periode pengambilan data.
3. Mengirim permintaan ke Open-Meteo API.
4. Menerima respons dalam format JSON.
5. Mengubah data JSON menjadi DataFrame.
6. Memeriksa dan menyimpan data ke format CSV.
7. Membuat dokumentasi provenance dan checklist etika.

## 6. Struktur Folder

```text
akuisisi-cuaca-bali/
├── data/
│   └── raw/
│       └── data_cuaca_bali.csv
├── notebooks/
│   └── akuisisi_cuaca_bali.ipynb
├── docs/
│   ├── provenance.json
│   └── data_ethics_checklist.csv
└── README.md
```

## 7. Dokumentasi dan Etika Data

Data diperoleh dari sumber publik Open-Meteo. Proyek ini hanya mengambil informasi cuaca dan tidak mengumpulkan data pribadi.

Waktu akses, sumber data, parameter pengambilan, dan hash dataset dicatat dalam file provenance.json.

## 8. Lisensi dan Atribusi

Sumber data: Open-Meteo.

Atribusi dan ketentuan penggunaan data mengikuti dokumentasi resmi Open-Meteo. Periksa ketentuan lisensi data yang digunakan sebelum mendistribusikan ulang dataset.

## 9. Catatan

Data cuaca historis Open-Meteo berbasis reanalisis dan pemodelan cuaca, bukan pengukuran langsung dari satu stasiun cuaca.# Meteo_Cuaca
