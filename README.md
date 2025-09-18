<p align="right">Bahasa: Indonesia</p>

<img src="https://raw.githubusercontent.com/aflacake/wikiriset/main/gmbr/Logo%20WikiRiset.png" alt="Logo WikiRiset"/>

# WikiRiset – Dalam Pengembangan
Tempatnya penelitian unggahan catatan karya Anda secara gratis! dalam bentuk format HTML dalam stuktur folder rapih dan dalam pengawasan.

## Apa itu WikiRiset?
WikiRiset adalah repositori sumber daya terbuka (_open source_) dikembangkan mandiri oleh Nazwa Shabrina Zain sebagai alat terbukanya karya penelitian seseorang.

**Tujuan**\
WikiRiset tempat alat mencatat dan mengekplorasi beragam topik namun mengutamakan matematika dan fisika. Ketika matematika dan fisika muncul dibidang lain misalnya ilmu komputer, WikiRiset juga akan mengeksplorasinya.

**Bantu sumbangkan!**\
Jika Anda meluangkan waktu untuk menemukan sesuatu dalam literatur, mempelajari bukti, dan contoh. Tambahkan ke dalam catatan di WikiRiset! Orang lain dapat manfaatnya dan begitu pula manfaat juga dirasakan oleh Anda sendiri.

Dalam melakukannya, ikuti praktik akademis umum untuk mendukung suntingan Anda:
- Berikan justifikasi dengan mengutip literatur relevan.
- Berikan bukti relevan (untuk klaim).
- Atau pemeriksaan kewarasan lainnya.

## Kontribusi Riset
Senang menyambut karya Anda di WikiRiset. Memastikan karya penelitian Anda bermanfaat dan berpendidikan.

> Kesulitan berkontribusi di WikiRiset? isi formulir berikut [dalam konstruksi].

Ada aturan jelas sebelum Anda berkontribusi di WikiRiset:

### Peraturan
Tulisan Anda harus mengikat dan mematuhi udang-undang berlaku Indonesia:
- Undang-Undang Nomor 28 Tahun 2014 tentang Hak Cipta.
- Kekerasan:
  - Undang-Undang No. 23 Tahun 2002 tentang Perlindungan Anak.
  - Undang-Undang No. 12 Tahun 2022, tentang Tindak Pidana Kekerasan Seksual (TPKS).
- Undang-Undang Nomor 44 Tahun 2008, tentang Pornografi. 
- Pasal 28 ayat (2) UU ITE 2024, tentang Menjerat Penyebar Kebencian SARA.

Dengan menyatakan:
1. Tidak boleh menggunggah karya hak cipta tanpa izin.
2. Tidak diperbolehkan konten kekerasan, vulgar, dan pornografi.
3. Tidak diperbolehkan SARA (Suku, Agama, Ras, dan Antargolongan) untuk suatu yang negatif seperti kebencian.
4. Tidak diperbolehkan mengirim file mengandung malware atau virus.

Sewaktu-waktu aturan ini bisa diperubah.

#### Konten
WikiRiset hanya menerima konten relevan dengan pendidikan dan penelitian. Setiap kontribusi harus menyertakan dasar akademis berupa referensi, data, atau argumen logis yang bisa ditemukan dan verifikasi. Konten bersifat iklan, opini tanpa bukti, atau tidak relevan dengan penelitian akan ditolak.

1. Konten Yang Dimuat di WikiRiset:
   - **Artikel penelitian asli:** Hasil riset, studi kasus, prototipe, dan laporan teknis.
   - _**Review:**_ Ringkasan literatur yang sudah ada.
   - **Data dan dokumentasi:** Dataset, eksperimen, dan metodologi.
   - **Verifikasi riset:** Laporan mencoba ulang eksperimen orang lain.
   - **Tutorial:** Panduan menerapkan metode tertentu dalam penelitian.
  
   Diperbolehkan:
   - _**Negative result:**_ Hasil gagal namun tetap berharga.
   - _**Open problem statement:**_ Masalah terbuka ditawarkan.
  
2. Konten Yang Tidak Dicantumkan
   - Iklan, promosi, dan konten non-akademis.
   - Artikel opini tanpa bukti literatur.
   - Plagiat karya orang lain tanpa atribusi.
   - Konten berbahaya.
   - Informasi palsu dan menyesatkan.
  
**Struktur jelas**
1. Judul
2. Abstrak
3. Latar belakang
4. Metode
5. Hasil
6. Diskusi
7. Referensi

#### Menggunggah
1. _Fork_ repositori ini.
2. Gunakan templat dibawah ini:
   ```html
   <!DOCTYPE html>
   <html>
       <head>
           <title>Halaman Judul Penelitian Anda</title>
           <style>
               body {
                   margin: 0 auto;
                   padding: 32px 16px;
                   max-width: 850px;
                   font-family: "Georgia", "Times New Roman", serif;
                   font-size: 16px;
                   line-height: 1.6;
                   color: #222;
                   background: #ffffff;
               }
            
               h1 {
                   margin-bottom: 16px;
                   font-size: 36px;
                   font-weight: bold;
               }
            
               h2 {
                   margin-top: 32px;
                   margin-bottom: 12px;
                   font-size: 24px;
                   font-weight: bold;
               }
            
               h3 {
                   margin-top: 24px;
                   margin-bottom: 8px;
                   font-size: 20px;
                   font-weight: bold;
               }
            
               p {
                   margin-bottom: 16px;
                   font-size: 16px;
               }
            
               .referensi {
                   font-size: 14px;
                   line-height: 1.4;
               }
               
               .lisensi {
                   margin-top: 32px;
                   padding-top: 16px;
                   font-size: 14px;
                   border-top: 1px solid #ccc;
                   color: #444;
               }
                   .lisensi a {
                       color: #0066cc;
                       text-decoration: none;
                   }
                   .lisensi a:hover {
                       text-decoration: underline;
                   }
                   
              .bilahNavigasi {
                padding: 16px 0;
                display: flex;
                gap: 20px;
                font-family: "Georgia", serif;
                font-size: 18px;
                border-bottom: 2px solid #222;
              }
                  .bilahNavigasi a {
                    text-decoration: none;
                    color: #222;
                  }
                
                  .bilahNavigasi a:hover {
                    text-decoration: underline;
                  }
           </style>
       </head>
       <body>
           <img src="https://raw.githubusercontent.com/aflacake/wikiriset/main/gmbr/Logo%20WikiRiset.png" width="100px" height="20px" />
            <!-- bilah -->
            <nav class="bilahNavigasi">
                <a href="https://wikiriset.pages.dev">Beranda</a>
                <a href="https://github.com/aflacake/wikiriset/blob/main/konten/panduan.md">Konten</a>
                <a href="https://wikiriset.pages.dev/#kontribusi">Kontribusi</a>
                <a href="https://wikiriset.pages.dev/#kontak">Kontak</a>
            </nav>
        
           <h1><!-- Judul --></h1>
           <!-- Konten dimulai -->
     
           <h2><!-- Abstrak --></h2>
           <!-- Konten dimulai -->
     
           <h2><!-- Latar Belakang --></h2>
           <!-- Konten dimulai -->
     
           <h2><!-- Metode --></h2>
           <!-- Konten dimulai -->
     
           <h2><!-- Hasil --></h2>
           <!-- Konten dimulai -->
     
           <h2><!-- Diskusi --></h2>
           <!-- Konten dimulai -->
     
            <section class="referensi">
               <h2><!-- Referensi --></h2>
               <!-- Konten dimulai -->
           </section>
           
           <section class="lisensi">
               <!-- Konten dimulai -->
           </section>
       </body>
   </html>
   ```
3. Letakkan di dalam folder **sesuai kategori**:
   ```
   konten/matematika/2025-0001-nazwa-sigma-spiral.html
   ```
   Kalau fisika:
   ```
   konten/fisika/2025-0001-nazwa-benda-jatuh.html
   ```
4. Memperbarui `indeks.json` agar muncul dipencarian:
   Isi bidang yang wajib diisi `judul`, `abstrak`, dan `jalur`.

   Contoh:
   ```json
   [
     {
       "judul": "Analisis Sigma Spiral: Penyelesaian Persamaan Transendental",
       "abstrak": "Penelitian ini membahas tentang Sigma Spiral sebuah persamaan spiral yang melibatkan fungsi logaritma alami dan eksponensial.",
       "jalur": "https://wikiriset.pages.dev/konten/matematika/2025-0001-nazwa-sigma-spiral"
     }
   ]
   ```
5. Kiriman Anda sedang dalam peninjauan. Ketika sudah disetujui maka tampilan halaman Anda akan berlokasi `wikiriset/konten/matematika/2025-0001-nazwa-sigma-spiral.html`.

#### Hak Cipta
Semua karya yang dipublikasikan di WikiRiset dilisensikan di bawah lisensi **Creative Commons Attribution 4.0 International (CC-BY-4.0)**, kecuali penulis menentukan lisensi lain.
