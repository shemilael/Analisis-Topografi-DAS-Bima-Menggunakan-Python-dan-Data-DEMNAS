
# Analisis Topografi DAS Bima: Menggunakan Python dan Data DEMNAS (.tif)

Repository ini berisi notebook Python yang digunakan untuk melakukan analisis topografi Daerah Aliran Sungai (DAS) di wilayah Bima, menggunakan data DEMNAS (Digital Elevation Model Nasional) dalam format .tif. Data DEMNAS memberikan informasi elevasi permukaan bumi yang digunakan untuk mengidentifikasi dan mendelineasi DAS secara otomatis.

## Tujuan Proyek

Tujuan dari proyek ini adalah untuk memberikan pemahaman yang lebih baik tentang bagaimana data DEM dapat digunakan untuk menganalisis topografi sebuah DAS, serta mengidentifikasi area rawan banjir atau erosi yang membutuhkan perhatian lebih dalam pengelolaan sumber daya alam dan perencanaan wilayah.

## Struktur Repository

- **`notebooks/`**: Folder ini berisi file notebook `.ipynb` yang berisi seluruh analisis langkah demi langkah.
- **`data/`**: Folder ini berisi data DEM (.tif) yang digunakan untuk analisis.
- **`results/`**: Folder yang berisi hasil analisis, seperti peta, visualisasi, dan laporan.
- **`requirements.txt`**: Daftar dependensi Python yang digunakan dalam proyek ini (misalnya, `rasterio`, `numpy`, `matplotlib`, `geopandas`, dll.).

## Langkah Penggunaan

### 1. Persiapkan Lingkungan

Pastikan untuk menginstal semua dependensi berikut sebelum menjalankan notebook:

```
rasterio
numpy
matplotlib
geopandas
plotly
pandas
scipy
```

Untuk menginstal dependensi, jalankan:

```
pip install -r requirements.txt
```

### 2. Unduh Data DEMNAS

Unduh dataset DEMNAS untuk wilayah Bima dari portal resmi: [DEMNAS Portal](https://tanahair.indonesia.go.id/portal-web/unduh/demnas)

### 3. Jalankan Notebook

1. Buka Jupyter Notebook atau Google Colab.
2. Akses file notebook `.ipynb` di folder **`notebooks/`**.
3. Ikuti langkah-langkah dalam notebook untuk melakukan analisis topografi dan delineasi DAS.

### 4. Hasil Analisis

Setelah menjalankan notebook, Anda akan memperoleh hasil analisis berupa:

- Peta topografi dan kontur DAS Bima.
- Visualisasi elevasi permukaan bumi.
- Analisis sifat topografi seperti kemiringan lereng dan arah aliran.

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, Anda dapat melakukan fork dan mengirimkan pull request. Setiap kontribusi yang membantu meningkatkan proyek ini sangat dihargai.

## Lisensi

Proyek ini dilisensikan di bawah MIT License - lihat [LICENSE](LICENSE) untuk detail lebih lanjut.

## Penafian

Proyek ini hanya untuk tujuan pendidikan dan penelitian. Semua data yang digunakan dalam proyek ini diperoleh dari sumber resmi dan bersifat publik.
