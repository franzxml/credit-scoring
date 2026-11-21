# Credit Scoring

Proyek UAS Pembelajaran Mesin untuk memperkirakan risiko peminjam menunggak pembayaran kredit selama 90 hari atau lebih dalam dua tahun ke depan.

## Dataset

Gunakan dataset Give Me Some Credit dari Credit Fusion dan Will Cukierski. Kaggle mencantumkan bahwa penggunaan berkas mengikuti aturan kompetisi. [Halaman dataset](https://www.kaggle.com/competitions/GiveMeSomeCredit/data) · [Aturan kompetisi](https://www.kaggle.com/competitions/GiveMeSomeCredit/rules)

1. Masuk ke Kaggle dan buka tab Data pada halaman Give Me Some Credit.
2. Pilih **Download All**, lalu **Download as zip**. Jika Kaggle meminta persetujuan aturan, baca aturan yang ditampilkan.
3. Ekstrak berkas ke folder `data/` di repositori lokal.

| Berkas | Kegunaan |
| --- | --- |
| `cs-training.csv` | Data berlabel untuk eksplorasi, pelatihan, dan evaluasi internal. Kolom targetnya `SeriousDlqin2yrs`. |
| `cs-test.csv` | Data uji kompetisi untuk membuat prediksi. |
| `sampleEntry.csv` | Contoh format pengiriman hasil prediksi ke Kaggle. |
| `Data Dictionary.xls` | Kamus kolom dan definisi variabel. |

Folder `data/` disimpan secara lokal pada setiap salinan proyek.
