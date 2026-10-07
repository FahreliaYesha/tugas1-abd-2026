# Data Tugas 1

## Dataset yang Dipilih

Isi informasi berikut sebelum Milestone 1.

| Item | Isi |
|---|---|
| Nama dataset | `Indonesia palm oil - Supply chain data` |
| Sumber | `Trase - Indonesia Palm Oil Supply Chain https://trase-website-revamp-b82958.netlify.app/open-data/datasets/supply-chains-indonesia-palm-oil` |
| Lisensi/ketentuan pakai | `Creative Commons CC BY 4.0 untuk charts, graphics, maps, dan representasi data pada platform Trase. Penggunaan untuk tujuan komersial perlu menghubungi Trase.` |
| Ukuran | `> 1.000.000 baris` |
| Periode data | `2013-2022` |
| Unit analisis | `Aliran rantai pasok minyak kelapa sawit Indonesia berdasarkan tahun, negara produksi, jenis produk, dan indikator keberlanjutan` |

## Tempat Mencari Dataset

Pilih dataset Indonesia yang legal digunakan, dapat didokumentasikan sumbernya, dan memenuhi batas ukuran tugas.

| Situs | Kegunaan |
|---|---|
| [Satu Data Indonesia](https://data.go.id/) | Portal data terbuka lintas instansi pemerintah Indonesia. |
| [Badan Pusat Statistik](https://www.bps.go.id/) | Statistik sosial, ekonomi, kependudukan, dan data wilayah. |
| [BMKG Data Online](https://dataonline.bmkg.go.id/) | Data cuaca, iklim, gempa bumi, dan observasi meteorologi. |
| [Hugging Face Datasets](https://huggingface.co/datasets) | Dataset publik yang dapat dicari berdasarkan topik, bahasa, atau ukuran. |
| [Kaggle Datasets](https://www.kaggle.com/datasets) | Katalog dataset publik; periksa lisensi dan dokumentasi pembuatnya. |
| [Google Dataset Search](https://datasetsearch.research.google.com/) | Mesin pencari untuk menemukan dataset dari berbagai portal. |
| [Trase Open Data](https://trase.earth/open-data) | Menyediakan dataset rantai pasok berbagai komoditas dan indikator keberlanjutan, termasuk minyak kelapa sawit Indonesia. |

## Cara Memperoleh Data

1. Buka URL sumber di atas.
2. Unduh file ke folder `data/raw/` tanpa mengubah data mentah.
3. Catat nama file dan checksum bila tersedia.
4. Ubah variabel `DATA_PATH` pada `notebooks/01_data_profiling.ipynb` agar menunjuk ke file tersebut.

## Aturan Penyimpanan

- Jangan commit dataset mentah atau hasil olahan berukuran besar ke Git.
- File pada `data/raw/` adalah data asli dan tidak boleh diubah.
- Simpan hasil transformasi yang dapat direproduksi pada `data/processed/`.
