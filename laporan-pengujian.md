# Laporan Pengujian

## Status
**Belum diuji secara langsung pada pelayar sebenar atau peranti fizikal dalam sesi ini.** Dokumen ini membezakan pemeriksaan statik daripada ujian runtime; jangan tafsirkan senarai pemeriksaan kod sebagai pengesahan fungsi pada semua peranti.

## Pemeriksaan statik yang dilakukan semasa penjanaan
- [x] Fail `index.html` dijana dengan HTML/CSS/JavaScript sebaris.
- [x] Bank data mempunyai tepat 25 item soalan; setiap item mempunyai empat pilihan, indeks jawapan dan penerangan.
- [x] Pautan video ialah pautan carian YouTube HTTPS; kandungan video individu tidak disahkan.
- [x] Terdapat dua permainan interaktif yang ditulis dalam JavaScript.
- [x] Kod mengandungi navigasi nota, penunjuk kemajuan, simpanan `localStorage`, audio boleh hidup/mati dan fungsi `window.print()`.
- [x] Butang menetapkan semula percubaan meminta pengesahan melalui `confirm()`.
- [x] Formula peratus menggunakan `score / 25 * 100`.
- [x] Laporan keputusan mengandungi skor, peratus, lencana dan semakan jawapan.

## Belum disahkan secara runtime
- [ ] Memuatkan halaman tanpa ralat JavaScript pada Chrome/Firefox/Safari.
- [ ] Menguji semua butang dan setiap laluan navigasi dengan input sebenar.
- [ ] Menguji simpanan/pemulihan `localStorage` pada mod privasi dan pelayar yang berbeza.
- [ ] Menguji suara Bahasa Melayu pada peranti yang menyediakan suara `ms-MY`.
- [ ] Menguji cetakan/PDF dan pemisahan halaman.
- [ ] Menguji reka letak pada telefon, tablet dan komputer sebenar.
- [ ] Menguji aksesibiliti dengan pembaca skrin dan papan kekunci.
- [ ] Menjalankan semakan keselamatan kandungan video luaran.

## Cadangan ujian penerimaan guru
1. Buka `index.html`, masukkan nama, mulakan sesi dan navigasi nota ke hadapan/belakang.
2. Pilih jawapan betul dan salah dalam permainan pertama; uji padanan permainan kedua.
3. Jawab 25 soalan dan sahkan setiap soalan mempunyai empat pilihan serta maklum balas.
4. Hantar dengan semua jawapan dijawab, kira skor manual dan bandingkan dengan laporan.
5. Cuba hantar dengan soalan belum dijawab; sahkan permintaan pengesahan.
6. Muat semula halaman dan cuba sambung sesi.
7. Matikan audio dan pastikan aplikasi masih boleh digunakan tanpa suara.
8. Cetak laporan atau pilih “Save as PDF”.
9. Ulang pada telefon dan komputer; periksa teks, butang, kontras dan navigasi papan kekunci.
