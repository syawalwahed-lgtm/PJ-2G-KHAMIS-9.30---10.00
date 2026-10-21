# Pengembaraan PJ Tahun 2

Aplikasi web pembelajaran berbahasa Melayu untuk murid Tahun 2, berfokus pada Unit 1: **Cabaran Ruang**. Aplikasi menggunakan HTML, CSS dan JavaScript tanpa rangka kerja atau pelayan.

## Fail
- `index.html` — aplikasi lengkap.
- `bank-soalan.md` — 25 soalan, empat pilihan, skema dan penerangan.
- `pemetaan-kurikulum.md` — pemetaan kurikulum dan batasan pengesahan.
- `laporan-pengujian.md` — skop pemeriksaan dan perkara yang belum diuji pada pelayar sebenar.

## Cara menggunakan
1. Muat turun dan ekstrak ZIP.
2. Buka `index.html` menggunakan Chrome, Edge, Firefox atau Safari terkini.
3. Masukkan nama murid dan tekan **Mula Pembelajaran**.
4. Teroka nota, buka carian video YouTube, cuba dua permainan dan jawab kuiz.
5. Pada keputusan, pilih **Cetak / Simpan PDF** untuk mencetak atau memilih pencetak PDF jika tersedia.

Kebanyakan ciri berfungsi tanpa internet. Pautan video memerlukan internet. Suara menggunakan `SpeechSynthesis` jika disokong oleh pelayar/peranti. Audio boleh dimatikan dengan butang di bahagian atas.

## Penerbitan GitHub Pages
1. Log masuk ke GitHub dan cipta repositori baharu (contohnya `pengembaraan-pj-tahun2`).
2. Muat naik `index.html` ke akar repositori; sertakan fail Markdown sebagai dokumentasi jika mahu.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, kemudian tekan **Save**.
6. Tunggu status deployment selesai. URL lazimnya `https://NAMA-PENGGUNA.github.io/NAMA-REPOSITORI/`. Gunakan URL yang dipaparkan oleh GitHub Pages; jangan anggap ia aktif sebelum deployment berjaya.

## Privasi dan keselamatan
Nama dan kemajuan disimpan menggunakan `localStorage` pada pelayar yang sama jika tersedia. Tiada akaun atau pangkalan data diperlukan. Jangan masukkan maklumat sensitif. Guru perlu menyemak kandungan video luaran sebelum murid menontonnya.

## Nota kurikulum
Pemetaan kurikulum dalam fail `pemetaan-kurikulum.md` menerangkan sumber rujukan dan batasan pengesahan. Sahkan SK/SP dengan salinan DSKP rasmi yang digunakan sekolah sebelum dijadikan rekod pentaksiran rasmi.
