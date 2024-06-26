# Panduan Pengguna NVDA NVDA_VERSION

[TOC]

<!-- KC:title: Referensi Perintah Cepat NVDA NVDA_VERSION  -->



## Pendahuluan {#toc2}

Selamat datang di NVDA!

NonVisual Desktop Access (NVDA) adalah pembaca layar sumber terbuka yang tersedia secara gratis untuk sistem operasi Microsoft Windows.
Dengan memberikan feedback (umpan balik) melalui pengucapan tiruan dan Braille, NVDA membuat penyandang tunanetra atau orang yang mengalami gangguan penglihatan dapat mengakses komputer yang menjalankan Windows tanpa biaya tambahan dibandingkan orang awas. 
NVDA dikembangkan oleh [NV Access](https://www.nvaccess.org/), dengan kontribusi dari masyarakat.

### Fitur Umum {#toc3}

NVDA juga membuat penyandang tunanetra dan gangguan penglihatan dapat mengakses dan berinteraksi dengan sistem operasi Windows dan berbagai aplikasi pihak ketiga.

Sorotan utamanya meliputi: 

* Dukungan untuk aplikasi populer yang meliputi web browser, email client, program obrolan melalui internet, dan office suites
* Speech synthesizer bawaan yang mendukung lebih dari 80 bahasa 
* Pelaporan format teks saat tersedia, seperti nama dan ukuran font, style, dan kesalahan ejaan
* Penyebutan secara otomatis teks yang berada di bawah mouse dan indikasi bunyi secara opsional dari posisi mouse tersebut
* Dukungan bagi banyak braille display yang dapat di-refresh, termasuk input braille komputer untuk braille display yang memiliki keyboard braille
* Kemampuan untuk menjalankan seluruhnya dari media portabel stik USB atau media portabel lainnya tanpa perlu instalasi 
* Paket instalasi aplikasi talking yang mudah digunakan
* Diterjemahkan ke dalam 51 bahasa 
* Dukungan bagi Sistem Operasi Windows modern yang meliputi varian 32 dan 64 bit
* Kemampuan untuk menjalankan logon Windows dan secure screen (layar keamanan) lainnya 
* Support for common accessibility interfaces such as Microsoft Active Accessibility, Java Access Bridge, IAccessible2 and UI Automation (UI Automation only supported in Windows 7 and later)
* Support for Windows Command Prompt and console applications

### Internasionalisasi {#toc4}

Semua orang di belahan bumi mana pun perlu memiliki akses teknologi yang sama, tak peduli bahasa apa pun yang mereka gunakan.
Selain Bahasa Inggris, NVDA telah diterjemahkan ke dalam 47 bahasa yang meliputi: Afrikaans, Albania, Amharik, Arab, Aragon, Portugis Brasil, Bulgaria, Katala, Spanyol Kolombia, Kroasia, Ceko, Denmark, Belanda, Persia, Finlandia, Prancis, Galicia, Yunani, Georgia, Jerman, Ibrani, Hindi, Hongaria, Islandia, Irlandia, Italia, Jepang, Korea, Nepal, Norwegia, Polandia, Portugis, Punjab, Romania, Rusia, Serbia, Slowakia, Slovenia, Spanyol, Swedia, Tamil, Thai, Tionghoa Tradisional dan Sederhana, Turki, Ukraina dan Vietnam.

### Dukungan Speech Synthesizer {#toc5}

Selain menampilkan pesan dan antarmuka dalam beberapa bahasa, NVDA juga membuat penggunanya dapat membaca konten dalam bahasa apa pun, selama memiliki speech synthesizer yang dapat mengucapkan bahasa tersebut.

NVDA dibundel dengan [eSpeak NG](https://github.com/espeak-ng/espeak-ng), sebuah speech synthesizer gratis, sumber-terbuka, multibahasa. 

Informasi tentang speech synthesizer  lain yang didukung NVDA dapat ditemukan di bagian [Speech Synthesizer yang Didukung](#SupportedSpeechSynths).

### Dukungan Braille {#toc6}

Bagi pengguna yang memiliki braille display yang dapat di-refresh, NVDA dapat menampilkan informasi dalam huruf Braille.
Harap lihat bagian [Braille Display yang Didukung](#SupportedBrailleDisplays) untuk mendapatkan informasi tentang braille display yang didukung.

NVDA mendukung kode braille  untuk banyak bahasa, termasuk kode braille komputer yang disingkat, tidak disingkat, dan untuk banyak bahasa.

### Lisensi dan Hak Cipta {#toc7}

NVDA adalah kontributor 2006-2016 NVDA hak cipta.

NVDA dilindungi oleh GNU General Public License (Versi 2).
Anda bebas membagikan atau mengubah software ini dengan cara yang Anda sukai selama disertai dengan lisensi tersebut dan Anda menyediakan semua kode sumber kepada siapa pun yang menginginkannya.
Ini berlaku pada salinan asli dan modifikasi dari software ini, ditambah karya-karya turunannya.
Untuk keterangan lebih lanjut, Anda dapat [melihat lisensi penuh.](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)

## Persyaratan Sistem {#toc8}

* Sistem operasi: semua edisi 32-bit dan 64-bit dari Windows XP, Windows Vista, Windows 7, Windows 8, Windows 8.1, dan Windows 10 (termasuk Sistem Operasi Server)
* Untuk Windows XP 32-bit, NVDA memerlukan Service Pack 2 atau yang lebih tinggi.
* Untuk Windows Server 2008, NVDA memerlukan Service Pack 1 atau yang lebih tinggi.
* Memori: RAM 256 MB atau lebih 
* Kecepatan prosesor: 1.0 ghz atau lebih 
* Ruang penyimpanan sekitar 90 MB. 

## Memulai dan Mengatur NVDA {#toc9}

Jika Anda belum mendapatkan salinan NVDA, Anda dapat mengunduhnya dari [www.nvaccess.org](NVDA_URL).

Buka bagian download (unduh) dan Anda akan menemukan link (tautan) untuk mengunduh NVDA versi terbaru. 

Dengan menjalankan file yang baru Anda unduh, salinan sementara NVDA akan dijalankan.
Anda kemudian akan ditanya apakah ingin memasang NVDA, membuat salinan portabel, atau tetap menggunakan salinan sementara tersebut.

Jika Anda berencana untuk selalu menggunakan NVDA di komputer ini, Anda mungkin ingin memilih untuk memasang NVDA.
Memasang NVDA akan mengizinkan fungsionalitas tambahannya berjalan, seperti automatic starting (mulai otomatis) setelah logon, kemampuan untuk membaca layar Windows Logon dan layar Windows security (yang tidak dapat dilakukan dengan salinan portabel dan sementara), dan pembuatan pintasan Start Menu dan pintasan desktop.
Salinan yang telah terpasang juga dapat membuat salinan portabel sendiri sewaktu-waktu. 

Jika Anda ingin membawa serta NVDA saat bepergian menggunakan USB thumb drive atau media dapat ditulisi (writable media) lainnya, maka Anda hendaknya membuat salinan portabel.
Salinan portabel juga memiliki kemampuan untuk memasang dirinya sendiri pada komputer apa pun nanti.
Akan tetapi, jika Anda ingin menyalin NVDA ke read-only media (media baca-saja) seperti CD, Anda hendaknya hanya menyalin paket unduhan.
Menjalankan versi portabel secara langsung dari read-only media tidak didukung untuk saat ini. 

Penggunaan salinan sementara NVDA juga merupakan opsi (misalnya, untuk tujuan demonstrasi), walau menjalankan NVDA dengan cara ini setiap waktu bisa jadi sangat memakan waktu. 

### Keterbatasan Salinan Sementara dan Portabel {#toc10}

Selain ketidakmampuan untuk berjalan secara otomatis selama dan/atau setelah log-on, salinan NVDA portabel dan sementara juga memiliki keterbatasan lain sebagai berikut: 

* Tidak dapat berinteraksi dengan aplikasi yang berjalan dengan hak istimewa administratif, tentu saja kecuali jika NVDA itu sendiri telah dijalankan juga dengan hak-hak ini (tidak disarankan). 
* Tidak dapat membaca layar User Account Control (UAC) saat mencoba menjalankan aplikasi dengan hak istimewa administratif.  
* Windows 8 dan yang lebih baru: tidak dapat mendukung input dari layar sentuh. 
* Windows 8 dan yang lebih baru: ketidakmampuan untuk menyediakan fitur seperti mode jelajah dan pengucapan karakter yang diketik dalam aplikasi Windows Store. 
* Windows 8 dan yang lebih baru: audio ducking tidak didukung. 

### Memasang NVDA {#toc11}

Jika Anda memasang NVDA langsung dari paket unduhan NVDA, tekan tombol Install NVDA.
Jika Anda telah menutup dialog ini atau ingin memasang dari salinan portabel, pilih item menu Install NVDA yang terletak di bawah Tools (Alat) dalam menu NVDA. 

Dialog pemasangan (installation) yang muncul akan memastikan apakah Anda ingin memasang NVDA dan akan memberi tahu Anda apakah pemasangan ini akan memperbarui pemasangan sebelumnya.
Jika Anda menekan tombol Continue, maka NVDA akan mulai terpasang.
Ada juga beberapa opsi dalam dialog ini yang akan dijelaskan sebagai berikut.
 Ketika pemasangan selesai, sebuah pesan akan muncul dan menyatakan bahwa pemasangan telah berhasil. 
Menekan OK pada tahap ini akan memulai ulang (restart) salinan NVDA yang baru dipasang. 

#### Memulai di Windows Logon {#toc12}

Opsi ini akan membuat Anda dapat memilih apakah NVDA akan secara otomatis dimulai saat ada di layar Windows Logon, sebelum Anda memasukkan kata kunci.
Opsi ini juga meliputi kontrol UAC dan layar keamanan lainnya. 

#### Create Desktop Shortcut - Membuat Pintasan Desktop (ctrl+alt+n) {#toc13}

Opsi ini membuat Anda dapat memilih apakah NVDA harus membuat pintasan di desktop atau tidak untuk memulai NVDA.
Jika dibuat, pada pintasan ini akan diberikan juga sebuah tuts pintasan control+alt+n, sehingga Anda dapat memulai NVDA sewaktu-waktu dengan keystroke ini.

#### Menyalin Konfigurasi Portabel ke Akun Pengguna Saat Ini {#toc14}

Opsi ini membuat Anda dapat memilih apakah NVDA harus menyalin konfigurasi pengguna dari NVDA yang berjalan saat ini ke dalam konfigurasi untuk pengguna yang log on saat ini atau tidak, untuk salinan NVDA yang terpasang. 
Proses ini tidak akan menyalin konfigurasi untuk pengguna lain sistem ini, juga tidak ke konfigurasi sistem bagi pengguna di Windows Logon dan layar keamanan lainnya.
Opsi ini hanya tersedia ketika memasang dari salinan portabel, bukan saat memasang langsung dari paket Launcher yang diunduh. 

### Membuat Salinan Portabel {#toc15}

Jika Anda ingin membuat salinan portabel langsung dari paket unduhan NVDA, tekan saja tombol Create Portable Copy (Buat Salinan Portabel).
Jika Anda telah menutup dialog ini atau Anda menjalankan salinan NVDA yang terinstal, pilih item menu "Create Portable Copy" yang terdapat pada Tools di menu NVDA.

Dialog yang muncul membuat Anda dapat memilih apakah salinan portabel harus dibuat atau tidak.
Ini dapat berupa direktori di hard drive Anda atau lokasi di USB thumb drive atau media portabel lainnya.
Ada juga opsi untuk memilih apakah NVDA harus menyalin konfigurasi NVDA saat ini dari pengguna yang sudah log on untuk digunakan dengan salinan portabel yang baru dibuat.
 Opsi ini hanya tersedia saat membuat salinan portabel dari salinan terpasang, bukan ketika membuat salinan portabel dari paket unduhan.
Menekan Continue (Lanjutkan) akan membuat salinan portabel.
Setelah selesai, sebuah pesan akan muncul yang menyatakan bahwa pembuatan salinan portabel telah berhasil. 
Tekan OK untuk menutup dialog ini. 

## Memulai dengan NVDA {#toc16}
### Memulai NVDA {#toc17}

Jika Anda telah memasang NVDA dengan menggunakan paket instalasi, maka memulai NVDA jadi semudah menekan control+alt+n atau memilih NVDA dari menu NVDA di bawah Programs pada Start Menu.
Sebagai tambahan, Anda dapat mengetikkan NVDA ke dalam dialog Run dan menekan Enter.
Anda juga dapat melewati beberapa opsi command line (baris perintah) yang memungkinkan Anda untuk memulai kembali (restart) NVDA (-r), berhenti (quit (-q)), menonaktifkan add-on (--disable-addons), dan lain-lain.

Untuk salinan terpasang, NVDA menyimpan konfigurasi di folder roaming application data pada pengguna saat ini secara default (misal: "C:\Users\<user>\AppData\Roaming").
Hal ini dimungkinkan untuk mengubah ini dengan cara NVDA memuat konfigurasinya dari folder data aplikasi lokal.
Untuk lebih jelasnya Konsultasikan bagian tentang [system wide parameters](#SystemWideParameters).

Untuk memulai versi portabel, masuklah ke direktori tempat Anda memasang NVDA, dan tekan Enter atau klik dua kali nvda.exe.

Saat NVDA mulai, pertama-tama Anda akan mendengar serangkaian nada yang meninggi (yang memberi tahu Anda bahwa NVDA sedang dibuka).
Tergantung seberapa cepat komputer Anda, atau jika Anda sedang menjalankan NVDA pada USB key atau media lain yang lebih lamban, NVDA akan memerlukan waktu lebih lama untuk mulai.
Jika memang waktu yang dibutuhkan lebih lama, NVDA akan mengatakan "Loading NVDA. Please wait..." (Membuka NVDA. Silakan tunggu).

Jika Anda tidak mendengar pemberitahuan ini, atau jika Anda mendengar suara error Windows, atau rangkaian nada menurun, maka itu berarti NVDA mengalami error, dan Anda mungkin akan perlu melaporkan adanya bug kepada pihak yang mengembangkan program ini.
Silakan periksa situs web NVDA untuk mengetahui cara melakukan hal ini. 

Ketika NVDA mulai berjalan untuk pertama kali, Anda akan disapa oleh sebuah kotak dialog yang menyediakan informasi dasar tentang tuts modifier NVDA dan menu NVDA.
(Silakan lihat bagian selanjutnya mengenai topik ini.)
Kotak dialog juga memiliki tiga kotak centang.
Kotak kombo memungkinkan Anda memilih tata letak keyboard.
Di kotak centang pertama, Anda dapat mengontrol apakah NVDA harus menggunakan capslock sebagai tuts modifier NVDA.
Kotak centang kedua menentukan apakah NVDA dimulai secara otomatis setelah Anda log on ke Windows, dan kotak centang ini hanya tersedia untuk salinan NVDA yang sudah terpasang.
Kotak centang ketiga memungkinkan Anda untuk mengontrol apakah dialog Welcome perlu ditampilkan setiap kali NVDA mulai.  

### Tentang perintah keyboard NVDA {#toc18}
#### Tuts Modifier NVDA {#toc19}

Sebagian besar perintah keyboard spesifik NVDA berupa menekan tuts-tuts tertentu yang disebut tuts modifier NVDA sambil menekan satu atau lebih tuts lain.
Perkecualian dalam hal ini adalah perintah-perintah tinjauan teks (text review) untuk tata letak keyboard desktop yang hanya menggunakan tuts numpad itu sendiri, meskipun ada perkecualian yang lain lagi. 

NVDA dapat dikonfigurasi sehingga tuts numpad Insert, Extended Insert dan/atau capslock dapat digunakan sebagai tuts modifier NVDA. 
Secara default, baik tuts numpad Insert maupun Extended Insert merupakan tuts-tuts modifier NVDA. 

Jika Anda ingin salah satu tuts modifier NVDA berperilaku seperti biasa saat NVDA tidak berjalan (misal, Anda ingin mengaktifkan capslock setelah Anda mengatur capslock sebagai tuts modifier NVDA), Anda dapat menekan tuts dua kali secara berurutan dengan cepat. 

#### Tata Letak Keyboard {#toc20}

NVDA kini hadir dengan dua rangkaian perintah tuts (yang dikenal sebagai tata letak keyboard), yaitu: tata letak desktop dan tata letak laptop.
Secara default, NVDA diatur untuk menggunakan tata letak desktop, meskipun Anda dapat beralih ke tata letak laptop pada Keyboard Settings (Pengaturan Keyboard), yang dapat Anda temukan di bawah Preferences pada menu NVDA.

Tata letak desktop memungkinkan penggunaan numpad secara lebih maksimal (dengan numlock yang tidak aktif).
Meskipun sebagian besar laptop tidak memiliki numpad secara fisik, sebagian laptop dapat melakukan fungsi yang sama bila Anda menekan dan menahan tuts FN serta menekan huruf dan angka di sisi kanan keyboard (7, 8, 9, u, i o, j, k, l, dll.).
Jika laptop Anda tidak dapat melakukan fungsi ini atau tidak mengizinkan Anda menonaktifkan numlock, Anda mungkin ingin beralih ke tata letak laptop.

### Gestur Sentuh NVDA {#toc21}

Jika Anda sedang menjalankan NVDA pada perangkat yang memiliki layar sentuh dan menjalankan Windows 8 atau yang lebih baru, Anda juga dapat langsung mengontrol NVDA melalui layar sentuh.
Saat NVDA berjalan, semua input sentuh akan langsung memengaruhi NVDA.
Karena itu, tindakan yang dapat dilakukan secara normal tanpa NVDA tidak akan dapat dilakukan.

#### Mengeksplorasi Layar {#toc22}

Tindakan paling mendasar yang dapat Anda lakukan dengan layar sentuh adalah meminta NVDA menyebutkan control atau teks di posisi mana pun pada layar.
Untuk melakukan hal ini, sentuhkan satu jari Anda di mana pun pada layar.
Anda juga dapat menyentuhkan jari Anda pada layar dan menggerakkannya ke segala arah untuk membaca control dan teks lain yang dilewati oleh jari Anda.

#### Gestur Sentuh {#toc23}

Saat perintah NVDA dijelaskan secara lebih lanjut di dalam modul panduan pengguna ini, dalam perintah tersebut, mungkin terdapat satu gestur sentuh yang dapat digunakan untuk mengaktifkan perintah itu dengan layar sentuh.
Berikut ini adalah beberapa instruksi tentang cara melakukan berbagai gestur sentuh.

##### Tap (Ketukan) {#toc24}

Ketuk layar dengan cepat menggunakan satu atau beberapa jari.

Mengetuk satu kali dengan satu jari disebut sebagai satu tap (ketukan). 
Mengetuk dengan dua jari pada saat bersamaan disebut 2-finger tap (ketukan 2-jari), dan seterusnya.

Jika ketukan yang sama dilakukan satu atau beberapa kali lagi secara berurutan dengan cepat, NVDA akan menganggapnya sebagai satu multi-tap gesture (gestur multi-ketukan).
Mengetuk dua kali akan menghasilkan satu double tap (ketukan ganda).
Mengetuk tiga kali akan menghasilkan satu triple tap (ketukan tiga-kali) dan seterusnya.
Tentu saja, gestur multi-ketukan ini juga mengenali jumlah jari yang digunakan, jadi kita dapat membuat gestur seperti sebuah 2-finger triple tap (ketukan tiga-kali dengan 2-jari), sebuah 4-finger tap (ketukan 4-jari), dan sebagainya. 

##### Flick (Jentikan) {#toc25}

Gesekkan jari Anda dengan cepat pada layar. 

Terdapat 4 flick gesture (gestur jentik) yang dapat dilakukan berdasarkan arahnya: flick left (jentik ke kiri), flick right (jentik ke kanan), flick up (jentik ke atas) dan flick down (jentik ke bawah).

Seperti pada tap (ketukan), Anda dapat menggunakan lebih dari satu jari untuk melakukan gestur ini.
Oleh karena itu, melakukan gestur seperti 2-finger flick up (jentik ke atas dengan 2-jari) dan 4-finger flick left (jentik ke kiri dengan 4-jari) bisa saja Anda lakukan.

#### Mode Sentuh {#toc26}

Sementara terdapat lebih banyak lagi perintah NVDA dibanding touch gesture (gestur sentuh), NVDA memiliki beberapa touch mode (mode sentuh), anda dapat beralih di antara mode-mode sentuh tersebut untuk memastikan bahwa sub-rangkaian perintah tersebut tersedia.
Mode-mode tersebut adalah text mode (mode teks) dan object mode (mode objek).
Perintah NVDA tertentu yang terdapat dalam dokumen ini mungkin memiliki mode sentuh yang dituliskan di dalam kurung setelah gestur sentuh.
Misalnya, flick up (text mode) berarti bahwa perintah akan dilaksanakan ketika Anda menjentik ke atas, tapi hanya saat Anda berada dalam mode teks.
Jika suatu perintah tidak memiliki mode, maka perintah tersebut akan bekerja dalam mode apa pun.  

<!-- KC:beginInclude -->
Untuk mengaktifkan dan menonaktifkan mode sentuh, lakukan ketukan 3-jari. 
<!-- KC:endInclude -->

### Mode Input Help {#toc27}

Terdapat banyak perintah NVDA yang disebutkan dalam modul panduan pengguna ini, tapi ada satu cara mudah untuk mengeksplorasi semua perintah yang berbeda-beda tersebut, yaitu dengan mengaktifkan Input Help.

Untuk mengaktifkan Input Help, tekan NVDA+1.
Untuk menonaktifkannya, tekan NVDA+1 lagi.
Saat berada di Input Help, jika Anda melakukan gestur input apa pun (seperti menekan satu tuts atau melakukan satu gestur sentuh), NVDA akan melaporkan tindakan tersebut dan menjelaskan apa yang sedang dikerjakannya (jika ada).
Perintah yang aktual tidak akan melakukan eksekusi saat Anda berada dalam mode Input Help.  

### Menu NVDA {#toc28}

Menu NVDA memungkinkan Anda untuk mengontrol setting (pengaturan) NVDA, mengakses bantuan, menyimpan/mengembalikan konfigurasi, memodifikasi kamus pengucapan, mengakses alat tambahan dan keluar dari NVDA.

Untuk sampai ke menu NVDA dari mana pun pada Windows, saat NVDA berjalan, tekan NVDA+n pada keyboard atau lakukan 2-finger double tap (ketukan ganda dengan 2-jari) pada layar sentuh.
Anda juga dapat tiba di menu NVDA melalui system tray (baki sistem) Windows.
Klik kanan ikon NVDA pada system tray, atau akses system tray dengan menekan tuts logo Windows+B, DownArrow (panah bawah) ke ikon NVDA dan tekan tuts applications yang berada di sebelah tuts Control kanan pada sebagian besar keyboard.
Setelah menu muncul, Anda dapat menggunakan tuts panah untuk bernavigasi pada menu, dan tuts Enter untuk mengaktifkan sebuah item.

### Perintah NVDA Dasar {#toc29}

<!-- KC:beginInclude -->

| Nama |Tuts Desktop |Tuts Laptop |Sentuh |Keterangan|
|---|---|---|---|---|
|Hentikan pengucapan |Control |control |ketukan 2-jari |Menghentikan pengucapan seketika|
|Hentikan pengucapan sementara |shift |shift |Tidak ada |Menghentikan pengucapan sejenak dengan seketika. Menekan perintah ini lagi akan melanjutkan pengucapan kembali, yang dimulai dari saat pengucapan berhenti (jika penghentian pengucapan didukung oleh synthesizer yang aktif saat ini).|
|Menu NVDA |NVDA+n |NVDA+n |ketukan ganda dengan 2-jari |Membuka cepat (pop up) jendela Menu NVDA untuk memungkinkan Anda mengakses Preferences, Tools, Help, dll.|
|Men-toggle Mode Pengucapan |NVDA+s |NVDA+s |Tidak ada |Mengaktifkan dan menonaktifkan mode pengucapan, antara pengucapan, bunyi bip dan off.|
|Men-toggle Mode Input Help |NVDA+1 |NVDA+1 |Tidak ada |Menekan tuts apa saja dalam mode ini akan melaporkan tuts dan keterangan tentang perintah NVDA apa pun yang berkaitan dengannya.|
|Matikan NVDA |NVDA+q |NVDA+q |Tidak ada |Keluar dari NVDA|
|Lewatkan tuts berikutnya |NVDA+f2 |NVDA+f2 |Tidak ada |Meminta NVDA untuk melewatkan menekan tuts berikutnya dan langsung ke aplikasi yang aktif, meskipun tuts ini dianggap perintah tuts NVDA normal.|
|Men-toggle mode sleep aplikasi on dan off |NVDA+shift+s |NVDA+shift+z |Tidak ada |Mode tidur menonaktifkan semua perintah NVDA dan output pengucapan/braille untuk aplikasi yang aktif saat ini. Ini merupakan perintah yang paling bermanfaat dalam aplikasi, yang menyediakan fitur pengucapan atau pembaca layar sendiri. Tekan perintah ini lagi untuk menonaktifkan self voicing mode (mode suara sendiri).|

<!-- KC:endInclude -->

### Melaporkan Informasi Sistem {#toc30}

<!-- KC:beginInclude -->

| Nama |Tuts |Keterangan|
|---|---|---|
|Laporkan tanggal/waktu |NVDA+f12 |Menekan perintah ini satu kali akan melaporkan waktu saat ini. Menekan dua kali akan melaporkan tanggal.|
|Laporkan status baterai |NVDA+shift+b |Melaporkan status baterai, misalnya apakah AC power sedang digunakan atau berapakah prosentase pengisian daya saat ini.|
|Laporkan teks clipboard |NVDA+c |Melaporkan teks pada clipboard, jika ada.|

<!-- KC:endInclude -->

## Bernavigasi dengan NVDA {#toc31}

NVDA memungkinkan Anda untuk mengeksplorasi dan bernavigasi pada sistem dengan beberapa cara, yang meliputi interaksi normal dan tinjauan.

### Objek {#Objects}

Setiap aplikasi dan sistem operasi itu sendiri terdiri dari banyak objek.
Satu objek adalah satu item tunggal, misalnya teks, tombol (button), kotak centang (checkbox), penggulir (slider), daftar atau bidang teks yang dapat diedit (editable text field).

### Bernavigasi dengan Fokus Sistem {#SystemFocus}

Fokus sistem, yang juga biasa disebut fokus saja, adalah [objek](#Objects) yang menerima kunci yang diketikkan pada keyboard.
Contohnya, jika Anda sedang mengetik pada bidang teks yang dapat diedit, bidang teks yang dapat diedit tersebut memiliki fokus.

Cara paling umum bernavigasi pada Windows dengan NVDA adalah dengan memindahkan fokus sistem menggunakan perintah keyboard Windows standar, seperti menekan tab dan shift+tab untuk berpindah maju atau mundur di antara beberapa control, menekan alt untuk menuju menu bar (bilah menu) dan kemudian menggunakan panah untuk menavigasi menu-menu, dan menggunakan alt+tab untuk berpindah-pindah di antara beberapa aplikasi yang sedang berjalan.
Ketika Anda melakukan ini, NVDA akan melaporkan informasi tentang objek yang memiliki fokus, seperti nama, jenis, nilai, status, keterangan, pintasan keyboard dan informasi posisi. 

Terdapat beberapa perintah tuts yang berguna bagi Anda saat berpindah dengan fokus sistem:
<!-- KC:beginInclude -->

| Nama |Tuts Desktop |Tuts Laptop |Keterangan|
|---|---|---|---|
|Laporkan fokus saat ini |NVDA+tab |NVDA+tab |Menyebutkan objek atau control saat ini yang memiliki fokus sistem. Menekannya dua kali akan membuat NVDA menyebutkan informasi tentang objek atau control tersebut.|
|Laporkan judul |NVDA+t |NVDA+t |Melaporkan judul jendela yang aktif saat ini. Menekannya dua kali akan membuat NVDA menyebutkan informasi tentang jendela tersebut. Menekannya tiga kali akan membuat NVDA menyalinnya ke clipboard.|
|Bacakan jendela yang aktif |NVDA+b |NVDA+b |Membaca semua control dalam jendela yang aktif saat ini (berguna untuk dialog)|
|Laporkan Bilah Status |NVDA+end |NVDA+shift+end |Melaporkan status bar jika NVDA menemukannya.  Perintah ini juga memindahkan objek navigator ke lokasi ini. Menekannya dua kali akan membuat NVDA menyebutkan informasi tentang status bar tersebut.|

<!-- KC:endInclude -->

### Bernavigasi dengan System Caret {#SystemCaret}

Jika satu [objek](#Objects) yang mengizinkan navigasi dan/atau pengeditan teks [difokuskan](#SystemFocus), Anda akan dapat menelusuri teks dengan menggunakan system caret, yang disebut juga edit cursor (kursor edit).

Ketika fokus berada di objek yang memiliki system caret, Anda dapat menggunakan tuts panah, page up, page down, home, end, dll, untuk menelusuri teks.
Anda juga dapat mengubah teks jika control mendukung pengeditan.
NVDA akan memberi tahu saat Anda berpindah per karakter, kata atau baris, dan juga memberi tahu ketika Anda memilih dan membatalkan pilihan pada teks.

NVDA menyediakan perintah tuts yang berhubungan dengan system caret berikut ini: 
<!-- KC:beginInclude -->

| Nama |Tuts Desktop |Tuts Laptop |Keterangan|
|---|---|---|---|
|Baca semua |NVDA+downArrow |NVDA+a |Mulai membaca dari posisi system caret saat ini, memindahkannya seiring pergerakannya.|
|Baca baris saat ini |NVDA+upArrow |NVDA+l |Membaca baris tempat system caret berada saat ini.  Menekannya dua kali akan membuat NVDA menyebutkan barisnya.|
|Baca teks terpilih saat ini |NVDA+Shift+upArrow |NVDA+shift+s |Membaca teks yang terpilih saat ini|
|Kalimat berikutnya |alt+downArrow |alt+downArrow |Memindahkan caret (tanda sisipan) ke kalimat berikutnya dan menyebutkannya. (Hanya didukung di Microsoft Word dan Outlook)|
|Kalimat sebelumnya |alt+upArrow |alt+upArrow |Memindahkan caret (tanda sisipan) ke kalimat sebelumnya dan menyebutkannya. (Hanya didukung di Microsoft Word dan Outlook)|

Saat berada di dalam tabel, perintah tuts berikut ini juga tersedia: 

| Nama |Tuts |Keterangan|
|---|---|---|
|Pindah ke kolom sebelumnya |control+alt+leftArrow |Memindahkan system caret ke kolom sebelumnya (tetap di baris yang sama)|
|Pindah ke kolom berikutnya |control+alt+rightArrow |Memindahkan system caret ke kolom berikutnya (tetap di baris yang sama)|
|Pindah ke baris sebelumnya |control+alt+upArrow |Memindahkan system caret ke baris sebelumnya (tetap di kolom yang sama)|
|Pindah ke baris berikutnya |control+alt+downArrow |Memindahkan system caret ke baris berikutnya (tetap di kolom yang sama)|

<!-- KC:endInclude -->

### Navigasi Objek {#ObjectNavigation}

Sering kali, Anda bekerja dengan aplikasi menggunakan perintah yang memindahkan [fokus](#SystemFocus) dan [caret (tanda sisipan)](#SystemCaret).
Namun kadang, Anda mungkin ingin mengeksplorasi aplikasi yang aktif saat ini atau sistem operasinya tanpa memindahkan fokus atau caret.
Anda mungkin juga ingin bekerja dengan [objek](#Objects) yang tidak dapat diakses secara normal dengan menggunakan keyboard. 
Dalam kasus-kasus seperti ini, Anda dapat menggunakan navigasi objek.

Navigasi objek memungkinkan Anda untuk berpindah di antara objek-objek dan mendapatkan informasi tentang masing-masing [objek](#Objects).
Ketika Anda bergerak ke satu objek, NVDA akan melaporkannya dengan cara yang mirip dengan cara melaporkan fokus sistem.
Untuk cara meninjau seluruh teks saat teks tersebut muncul di layar, Anda dapat menggunakan [tinjauan layar](#ScreenReview).

Anda tidak harus berpindah maju dan mundur di antara setiap objek pada sistem, karena objek-objek ini disusun secara hierarkis.
Ini berarti bahwa beberapa objek berisi objek lain dan Anda harus berpindah ke dalam objek tersebut untuk mengakses objek-objek yang berada di dalamnya.
Sebagai contoh, sebuah daftar berisi beberapa list item, jadi Anda harus berpindah ke dalam daftar untuk mengakses item-itemnya.
Jika Anda telah berpindah ke satu list item, berpindah ke list item sesudah atau sebelumnya akan membawa Anda ke list item yang lain pada daftar yang sama.
Berpindah ke satu objek yang berisi (containing object) pada list item akan membawa Anda kembali ke daftar.
Anda dapat melewatkan daftar jika ingin mengakses objek-objek lain.
Serupa dengan itu, satu toolbar berisi beberapa control, jadi Anda harus berpindah ke dalam toolbar untuk mengakses control-control pada toolbar.

Objek yang saat ini sedang ditinjau disebut sebagai objek navigator.
Begitu Anda bernavigasi ke satu objek, Anda dapat meninjau kontennya dengan menggunakan [perintah tinjauan teks](#ReviewingText) saat berada di [mode object review (tinjauan objek)](#ObjectReview).
Secara default, objek navigator terus berpindah-pindah bersama dengan fokus sistem, namun perilaku ini bisa diaktifkan dan dinonaktifkan.

Perhatikanlah bahwa braille display mengikuti [fokus](#SystemFocus) dan [caret](#SystemCaret) secara default, dan bukan mengikuti navigasi objek dan tinjauan teks.
Jika Anda ingin braille display mengikuti navigasi objek dan tinjauan teks, Anda perlu [mengonfigurasi braille display untuk ditambatkan ke](#BrailleTether) tinjauan.

Untuk bernavigasi berdasarkan objek, gunakan perintah-perintah berikut ini: 

<!-- KC:beginInclude -->

| Nama |Tuts Desktop |Tuts Laptop |Sentuh |Keterangan|
|---|---|---|---|---|
|Laporkan objek saat ini |NVDA+numpad5 |NVDA+shift+o |tidak ada |Melaporkan objek navigator yang aktif saat ini.  Menekan dua kali akan membuat NVDA menyebutkan informasi, dan menekan 3 kali akan menyalin nama dan nilai objek ini ke clipboard.|
|Pindah ke objek yang berisi |NVDA+numpad8 |NVDA+shift+upArrow |jentik ke atas (mode objek) |Berpindah ke objek yang mengandung objek navigator yang aktif saat ini|
|Pindah ke objek sebelumnya |NVDA+numpad4 |NVDA+shift+leftArrow |jentik ke kiri (mode objek) |Berpindah ke objek sebelum objek navigator yang aktif saat ini|
|Pindah ke objek berikutnya |NVDA+numpad6 |NVDA+shift+rightArrow |jentik ke kanan (mode objek) |Berpindah ke objek setelah objek navigator yang aktif saat ini|
|Pindah ke objek-berisi yang pertama |NVDA+numpad2 |NVDA+shift+downArrow |jentik ke bawah (mode objek) |Berpindah ke objek pertama yang dikandung oleh objek navigator yang aktif saat ini|
|Pindah ke objek fokus |NVDA+numpadMinus |NVDA+backspace |tidak ada |Berpindah ke objek yang saat ini memiliki fokus sistem, dan juga menempatkan kursor tinjauan (review cursor) pada posisi system caret, jika diperlihatkan|
|Aktifkan objek navigator saat ini |NVDA+numpadEnter |NVDA+enter |Double tap (Ketukan ganda) |Mengaktifkan objek navigator yang aktif saat ini (mirip mengklik dengan mouse atau menekan spasi saat objek navigator memiliki fokus sistem)|
|Pindahkan fokus sistem atau caret ke posisi tinjauan saat ini |NVDA+shift+numpadMinus |NVDA+shift+backspace |tidak ada |Ditekan sekali akan memindahkan fokus sistem ke objek navigator saat ini. Ditekan dua kali akan memindahkan system caret ke posisi kursor tinjauan (review cursor).|
|Laporkan lokasi kursor tinjauan |NVDA+numpadDelete |NVDA+delete |tidak ada |Melaporkan informasi tentang lokasi teks atau objek pada kursor tinjauan.  Misalnya prosentase seluruh dokumen, jarak dari sisi halaman atau posisi layar secara tepat.  Menekan dua kali akan membuat NVDA menyediakan informasi lebih detail.|

<!-- KC:endInclude -->

Catatan: tuts numpad mensyaratkan tuts numlock dinonaktifkan agar perintah ini dapat berfungsi dengan baik.

### Meninjau Teks {#ReviewingText}

NVDA memungkinkan Anda untuk membaca konten pada [layar](#ScreenReview), [dokumen](#DocumentReview) yang aktif saat ini atau [objek](#ObjectReview) yang aktif saat ini berdasarkan karakter, kata atau baris.
Fungsi ini sangat bermanfaat di berbagai tempat (termasuk Windows command console) yang tidak memiliki [system caret](#SystemCaret).
Sebagai contoh, Anda mungkin menggunakannya untuk meninjau teks informasi yang panjang dalam sebuah dialog.

Saat memindahkan kursor tinjauan (review cursor), system caret tidak mengikutinya, jadi Anda dapat meninjau teks tanpa kehilangan posisi pengeditan Anda.
Namun, secara default, ketika system caret berpindah, kursor tinjauan akan mengikutinya.
Fungsi ini dapat diaktifkan dan dinonaktifkan. 

Perhatikanlah bahwa braille display mengikuti [fokus](#SystemFocus) dan [caret](#SystemCaret) secara default, dan bukan mengikuti navigasi objek dan tinjauan teks.
Jika Anda ingin braille display mengikuti navigasi objek dan tinjauan teks, Anda perlu [mengonfigurasi braille display untuk ditambatkan ke](#BrailleTether) tinjauan.

Perintah-perintah berikut ini tersedia untuk meninjau teks: 
<!-- KC:beginInclude -->

| Nama |Tuts Desktop |Tuts Laptop |Sentuh |Keterangan|
|---|---|---|---|---|
|Pindah ke baris teratas dalam tinjauan |shift+numpad7 |NVDA+control+home |tidak ada |Memindahkan kursor tinjauan ke baris teratas teks|
|Pindah ke baris sebelumnya dalam tinjauan |numpad7 |NVDA+upArrow |jentik ke atas (mode teks) |Memindahkan kursor tinjauan ke baris sebelumnya pada teks|
|Laporkan baris saat ini dalam tinjauan |numpad8 |NVDA+shift+. |tidak ada |Memberi tahu baris teks saat ini tempat kursor tinjauan diposisikan.  Menekannya dua kali akan membuat NVDA menyebutkan barisnya. Menekannya tiga kali akan membuat NVDA menyebutkan barisnya dengan menggunakan keterangan karakter.|
|Pindah ke baris berikutnya dalam tinjauan |numpad9 |NVDA+downArrow |jentik ke bawah (mode teks) |Memindahkan kursor tinjauan ke baris teks berikutnya.|
|Pindah ke baris terbawah dalam tinjauan |shift+numpad9 |NVDA+control+end |tidak ada |Memindahkan kursor tinjauan ke baris teks terbawah.|
|Pindah ke kata sebelumnya dalam tinjauan |numpad4 |NVDA+control+leftArrow |jentik ke kiri dengan 2-jari (mode teks) |Memindahkan kursor tinjauan ke kata sebelumnya dalam teks.|
|Laporkan kata saat ini dalam tinjauan |numpad5 |NVDA+control+. |tidak ada |Memberi tahu kata saat ini pada teks tempat kursor tinjauan diposisikan. Menekannya dua kali akan membuat NVDA menyebutkan kata tersebut. Menekannya tiga kali akan membuat NVDA menyebutkan kata tersebut dengan menggunakan keterangan karakter.|
|Pindah ke kata berikutnya dalam tinjauan |numpad6 |NVDA+control+rightArrow |jentik ke kanan dengan 2-jari (mode teks) |Memindahkan kursor tinjauan ke kata berikutnya dalam teks.|
|Pindah ke awal baris dalam tinjauan |shift+numpad1 |NVDA+home |tidak ada |Memindahkan kursor tinjauan ke awal baris saat ini dalam teks.|
|Pindah ke karakter sebelumnya dalam tinjauan |numpad1 |NVDA+leftArrow |jentik ke kiri (mode teks) |Memindahkan kursor tinjauan ke karakter sebelumnya pada baris saat ini di dalam teks.|
|Laporkan karakter saat ini dalam tinjauan |numpad2 |NVDA+. |tidak ada |Memberi tahu karakter saat ini pada baris teks tempat kursor tinjauan diposisikan. Menekannya dua kali akan membuat NVDA melaporkan keterangan atau contoh karakter tersebut.  Menekannya tiga kali akan membuat NVDA melaporkan nilai numerik karakter dalam desimal dan heksadesimal.|
|Pindah ke karakter berikutnya dalam tinjauan |numpad3 |NVDA+rightArrow |jentik ke kanan (mode teks) |Memindahkan kursor tinjauan ke karakter berikutnya pada baris saat ini di dalam teks|
|Pindah ke akhir baris dalam tinjauan |shift+numpad3 |NVDA+end |tidak ada |Memindahkan kursor tinjauan ke akhir baris saat ini dalam teks.|
|Baca semua dengan tinjauan |numpadPlus |NVDA+shift+a |jentik ke bawah dengan 3-jari (mode teks) |Membaca dari posisi kursor tinjauan saat ini, memindahkannya seiring pergerakannya.|
|Pilih lalu Salin dari kursor tinjauan |NVDA+f9 |NVDA+f9 |tidak ada |Mulai memilih lalu menyalin dari posisi kursor tinjauan saat ini.   Tindakan yang sebenarnya tidak dilakukan sampai Anda memberi tahu NVDA di mana akhir rangkaian teks.|
|Pilih lalu Salin ke kursor tinjauan |NVDA+f10 |NVDA+f10 |tidak ada |Saat Anda menekan pertama kali, teks dipilih dari posisi start marker yang sudah diatur sebelumnya sampai dengan dan termasuk posisi kursor tinjauan saat ini. Setelah Anda menekan tuts ini untuk yang kedua kalinya, teks akan disalin ke clipboard Windows.|
|Laporkan pemformatan teks |NVDA+f |NVDA+f |tidak ada |Melaporkan pemformatan teks di mana kursor tinjauan ditempatkan saat ini. Menekannya dua kali akan menampilkan informasi dalam mode jelajah.|

<!-- KC:endInclude -->

Catatan: tuts numpad mensyaratkan tuts numlock dinonaktifkan agar perintah ini dapat berfungsi dengan baik. 

Cara yang baik untuk ingat perintah tinjauan teks dasar ketika menggunakan tata letak desktop adalah dengan membayangkan bahwa perintah-perintah itu ada di dalam sebuah kisi 3x3. Dari atas ke bawah: baris teratas adalah line (baris), baris di bawahnya adalah word (kata) dan baris paling bawah adalah character (karakter). Dari kiri ke kanan: kolom paling kiri adalah previous (sebelumnya), kolom tengah adalah current (saat ini), kolom paling kanan adalah next (berikutnya).
Tata letak tersebut diilustrasikan sebagai berikut:

|Baris sebelumnya |Baris saat ini |Baris berikutnya|
|Kata sebelumnya |Kata saat ini |Kata berikutnya|
|Karakter sebelumnya |Karakter saat ini |Karakter berikutnya|

### Mode Tinjauan {#ReviewModes}

[Perintah tinjauan teks](#ReviewingText) NVDA dapat meninjau konten di dalam objek navigator saat ini, dokumen atau layar saat ini, tergantung pada mode tinjauan yang dipilih.
Mode tinjauan adalah pengganti konsep Flat Review NVDA yang ada lebih awal. 

Perintah-perintah berikut ini digunakan untuk beralih di antara mode-mode tinjauan:  
<!-- KC:beginInclude -->

| Nama |Tuts Desktop |Tuts Laptop |Sentuh |Keterangan|
|---|---|---|---|---|
|Beralih ke mode tinjauan berikutnya |NVDA+numpad7 |NVDA+pageUp |jentik ke atas dengan 2-jari |Mengalihkan ke mode tinjauan berikutnya yang tersedia|
|Beralih ke mode tinjauan sebelumnya |NVDA+numpad1 |NVDA+pageDown |jentik ke bawah dengan 2-jari |Mengalihkan ke mode tinjauan sebelumnya yang tersedia|

<!-- KC:endInclude -->

#### Tinjauan Objek {#ObjectReview}

Saat berada di mode tinjauan objek, Anda dapat meninjau hanya konten [objek navigator](#ObjectNavigation) saat ini.
Untuk objek-objek seperti bidang teks yang dapat diedit atau basic text controls (kontrol teks dasar) lain, konten ini biasanya adalah konten teks.
Untuk objek-objek lain, konten ini mungkin adalah nama dan/atau nilai. 

#### Tinjauan Dokumen {#DocumentReview}

Ketika [objek navigator](#ObjectNavigation) ada di dalam sebuah dokumen mode jelajah (misalnya laman web) atau dokumen rumit lainnya (misalnya dokumen Lotus Symphony), Anda dapat beralih ke mode tinjauan dokumen.
Mode tinjauan dokumen memungkinkan Anda untuk meninjau teks di seluruh dokumen.

Ketika beralih dari tinjauan objek ke tinjauan dokumen, kursor tinjauan ada di dalam dokumen pada posisi objek navigator.
Ketika menelusuri dokumen dengan perintah tinjauan, objek navigator secara otomatis diperbarui ke objek yang ditemukan pada posisi kursor tinjauan yang aktif saat ini.  

Perhatikanlah bahwa NVDA akan beralih ke tinjauan dokumen dari tinjauan objek secara otomatis ketika menelusuri dokumen mode jelajah.  

#### Tinjauan Layar {#ScreenReview}

Mode tinjauan layar memungkinkan Anda untuk meninjau teks pada layar ketika teks tersebut tampil secara visual dalam aplikasi yang aktif saat ini.
Ini mirip dengan tinjauan layar atau fungsi kursor mouse pada banyak pembaca layar Windows lainnya. 

Saat beralih ke mode tinjauan layar, kursor tinjauan ditempatkan pada posisi layar [objek navigator](#ObjectNavigation) yang aktif saat ini.
Ketika menelusuri layar dengan perintah tinjauan, objek navigator secara otomatis diperbarui ke objek yang ditemukan pada posisi kursor tinjauan di layar.

Perhatikanlah bahwa pada aplikasi yang lebih baru, NVDA mungkin tidak melihat sebagian atau semua teks yang ditampilkan pada layar karena menggunakan teknologi screen drawing yang lebih baru yang belum mendukung pada saat ini.  

### Bernavigasi dengan Mouse {#toc41}

Ketika Anda bergerak dengan mouse, NVDA secara default akan melaporkan teks yang tepat berada di bawah penunjuk mouse ketika penunjuk bergerak di atasnya.
Di mana didukung, NVDA akan membacakan paragraf di sekitar teks, meskipun beberapa control mungkin hanya membaca berdasarkan baris.  

NVDA dapat dikonfigurasi untuk juga memberi tahu jenis [objek](#Objects) di bawah mouse saat mouse bergerak (misalnya daftar, tombol, dll.).
Ini mungkin berguna untuk penyandang tunanetra total, karena kadang-kadang, mendengarkan teks saja tidak cukup.  

NVDA menyediakan cara bagi pengguna untuk mengetahui di mana mouse ditempatkan dalam dimensi layar dengan memperdengarkan bunyi bip untuk memberi tahu koordinat mouse saat ini.
Semakin tinggi posisi mouse pada layar, semakin tinggi pitch (nada) bunyi bip tersebut. 
Semakin mouse ditempatkan ke kiri atau kanan pada layar, semakin ke kiri atau ke kanan pula bunyi bip yang dimainkan (diasumsikan bahwa pengguna memiliki speaker stereo atau headphone).  

Fitur ekstra mouse ini tidak diaktifkan secara default dalam NVDA.
Jika Anda ingin memanfaatkannya, Anda dapat mengonfigurasinya dari dialog [Mouse settings (Pengaturan mouse)](#MouseSettings) yang dapat Anda temukan dalam menu Preferences NVDA. 

Meskipun mouse fisik atau bantalan sentuh perlu digunakan untuk bernavigasi dengan mouse, NVDA memiliki beberapa perintah tuts yang berhubungan dengan mouse:  
<!-- KC:beginInclude -->

| Nama |Tuts Desktop |Tuts Laptop |Keterangan|
|---|---|---|---|
|Klik kiri mouse |numpadDivide |NVDA+[ |Mengklik kiri mouse satu kali. Dobel klik biasa dapat dilakukan dengan menekan tuts ini dua kali secara berurutan dengan cepat.|
|Kunci klik kiri mouse |shift+numpadDivide |NVDA+control+[ |Mengunci klik kiri mouse. Tekan lagi untuk membuka kuncinya. Untuk menyeret (drag) mouse, tekan tuts ini untuk mengunci tombol kiri mouse dan kemudian gerakkan mouse secara fisik atau gunakan salah satu dari mouse routing command (perintah perutean mouse)  yang lain.|
|Klik kanan mouse |numpadMultiply |NVDA+] |Mengklik kanan mouse satu kali.|
|Kunci klik kanan mouse |shift+numpadMultiply |NVDA+control+] |Mengunci klik kanan mouse. Tekan lagi untuk membuka kuncinya. Untuk menyeret (drag) mouse, tekan tuts ini untuk mengunci tombol kanan mouse dan kemudian gerakkan mouse secara fisik atau gunakan salah satu dari mouse routing command (perintah perutean mouse) yang lain.|
|Move mouse to current navigator object (Gerakkan mouse ke objek navigator saat ini) |NVDA+numpadDivide |NVDA+shift+m |Memindahkan mouse ke lokasi objek navigator dan kursor tinjauan saat ini|
|Bernavigasi ke objek di bawah mouse |NVDA+numpadMultiply |NVDA+shift+n |Mengatur objek navigasi ke objek yang berlokasi di posisi mouse.|

<!-- KC:endInclude -->

## Mode Jelajah {#BrowseMode}

Dokumen read-only (baca-saja) yang rumit seperti laman web dijelajah dalam NVDA dengan menggunakan mode jelajah.
Ini meliputi dokumen-dokumen pada Mozilla Firefox, Microsoft Internet Explorer, Mozilla Thunderbird, pesan HTML dalam Microsoft Outlook, Google Chrome, Adobe Reader dan Adobe Flash.
Mode jelajah juga tersedia secara opsional untuk dokumen Microsoft Word. 

Dalam mode jelajah, konten dokumen tersedia dalam representasi datar yang dapat dinavigasi dengan tuts kursor seolah-olah dokumen tersebut adalah dokumen teks.
Semua perintah tuts [system caret](#SystemCaret) NVDA akan bekerja dalam mode ini, misalnya Say All (Baca Semua), Report Formatting (Laporkan Pemformatan), table navigation commands (perintah navigasi tabel), dll.
Informasi tentang apakah suatu teks adalah link (tautan), heading, dll. disebutkan bersama dengan teks ketika Anda bergerak. 

Kadang-kadang Anda perlu berinteraksi secara langsung dengan control dalam dokumen-dokumen ini.
Misalnya, Anda perlu berinteraksi dengan bidang teks yang dapat diedit serta daftar agar Anda dapat mengetik karakter dan menggunakan tuts kursor untuk bekerja dengan control.
Anda dapat melakukan ini dengan cara beralih ke mode fokus, di mana hampir semua kunci dilintaskan ke control.
Saat berada di mode jelajah, secara default, NVDA akan secara otomatis beralih ke mode fokus jika Anda menekan tab atau mengklik control tertentu yang mensyaratkannya.
Sebaliknya, menekan tab atau mengklik control yang tidak mensyaratkan mode fokus akan mengalihkan Anda kembali ke mode jelajah.
Anda juga dapat menekan Enter atau spasi untuk beralih ke mode fokus pada control yang mensyaratkannya.
Menekan Escape akan mengalihkan Anda kembali ke mode jelajah.
Sebagai tambahan, Anda dapat secara manual memaksa beralih ke mode fokus, yang mana mode ini akan tetap berlaku sampai Anda memilih untuk menonaktifkannya.  

<!-- KC:beginInclude -->

| Nama |Tuts |Keterangan|
|---|---|---|
|Men-toggle mode jelajah/fokus |NVDA+space |Mengaktifkan dan menonaktifkan antara mode fokus dan mode jelajah|
|Keluar dari mode fokus |escape |Mengalihkan kembali ke mode jelajah jika sebelumnya telah dialihkan ke mode fokus secara otomatis|
|Me-refresh dokumen mode jelajah |NVDA+f5 |Membuka kembali konten dokumen saat ini (perintah ini berguna jika konten tertentu tampaknya hilang dari dokumen.  Tidak tersedia di Microsoft Word dan Outlook).|
|Find (Temukan) |NVDA+control+f |Membuka cepat sebuah dialog yang di dalamnya Anda dapat mengetikkan teks yang dicari di dalam dokumen yang aktif saat ini.|
|Find next (Temukan yang berikutnya) |NVDA+f3 |Menemukan kata yang sama berikutnya; kata tersebut telah Anda cari sebelumnya pada teks dalam dokumen|
|Find previous (Temukan yang sebelumnya) |NVDA+shift+f3 |Menemukan kata yang sama yang terdahulu; kata tersebut telah Anda cari sebelumnya pada teks dalam dokumen|
|Open long description (Membuka keterangan yang panjang) |NVDA+d |Membuka jendela baru yang berisi keterangan panjang untuk elemen yang aktif saat ini, jika elemen tersebut memiliki keterangan tersebut.|

<!-- KC:endInclude -->

### Navigasi Satu-Huruf {#toc43}

Saat berada di mode jelajah, untuk navigasi yang lebih cepat, NVDA menyediakan kunci satu-karakter guna melompat ke bidang tertentu dalam dokumen.
Perhatikanlah bahwa tidak semua perintah ini didukung di setiap jenis dokumen. 

<!-- KC:beginInclude -->
Kunci-kunci berikut ini akan melompat dengan sendirinya ke elemen berikutnya yang tersedia, Sementara itu jika Anda menekan tuts Shift juga, kunci-kunci ini akan melompat ke elemen sebelumnya:

* h: heading
* l: list (daftar) 
* i: list item
* t: table
* k: link
* n: nonLinked text
* f: form field
* u: unvisited link
* v: visited link
* e: edit field
* b: button
* x: checkbox
* c: combo box
* r: radio button
* q: block quote
* s: separator
* m: frame
* g: graphic
* d: landmark
* o: embedded object (audio and pemutar video, aplikasi, dialog, dll.)
* 1 sampai 6: heading level 1 sampai 6 secara berturut-turut 
* a: annotation atau anotasi (komentar, revisi editor, dll.) 
* w: spelling error (kesalahan ejaan)

Untuk berpindah ke awal atau akhir elemen yang berisi (containing element), seperti daftar dan tabel: 

| Nama |Tuts |Keterangan|
|---|---|---|
|Pindah ke awal kontainer |shift+koma |Berpindah ke awal kontainer (daftar, tabel, dll.) tempat caret (tanda sisipan) diposisikan.|
|Pindah ke akhir kontainer |koma |Berpindah ke akhir kontainer (daftar, tabel, dll.) tempat caret (tanda sisipan) diposisikan.|

<!-- KC:endInclude -->
Beberapa aplikasi web seperti Gmail, Twitter dan Facebook menggunakan satu huruf sebagai tuts pintasan.
Jika Anda ingin menggunakannya sambil tetap menggunakan tuts kursor untuk membaca dalam mode jelajah, Anda dapat menonaktifkan tuts navigasi satu-huruf NVDA untuk sementara.
<!-- KC:beginInclude -->
Untuk mengaktifkan dan menonaktifkan navigasi satu-huruf pada dokumen yang aktif saat ini, tekan NVDA+shift+space.
<!-- KC:endInclude -->

### Elements List (Daftar Elemen) {#toc44}

Elements list (daftar elemen) memberikan akses ke satu daftar berisi tipe-tipe elemen dalam dokumen yang sesuai untuk aplikasi tersebut.
Misalnya, dalam web browser (penjelajah web), elements list mungkin berisi daftar link (tautan), heading atau landmark. 
Tombol radio memungkinkan Anda untuk berpindah-pindah di antara tipe-tipe elemen yang berbeda.
Edit field (Bidang edit) juga tersedia dalam dialog; ini memungkinkan Anda untuk memfilter daftar guna membantu mencari item tertentu pada halaman.
Setelah Anda memilih satu item, Anda dapat menggunakan tombol-tombol yang tersedia dalam dialog untuk berpindah ke atau mengaktivasi item tersebut.
<!-- KC:beginInclude -->

| Nama |Tuts |Keterangan|
|---|---|---|
|Daftar elemen mode jelajah |NVDA+f7 |Menampilkan daftar tipe-tipe elemen dalam dokumen saat ini.|

<!-- KC:endInclude -->

### Embedded Objects (Objek Tertanam) {#toc45}

Halaman mungkin berisi rich content (konten kaya) yang menggunakan teknologi seperti Adobe Flash dan Sun Java, serta aplikasi dan dialog.
Di tempat halaman-halaman ini ditemukan dalam mode jelajah, NVDA akan melaporkannya sebagai "embedded object" (objek tertanam), "application" (aplikasi) atau "dialog".
Anda dapat dengan cepat berpindah menggunakan objek tertanam tuts navigasi huruf tunggal o dan shift+o.
Anda dapat menekan Enter pada objek-objek ini untuk berinteraksi dengannya.
Jika objek ini dapat diakses, Anda kemudian dapat menekan tab di sekitar objek dan berinteraksi dengannya seperti aplikasi yang lain.
Satu perintah tuts disediakan untuk kembali ke halaman asli yang mengandung objek tertanam tersebut.  
<!-- KC:beginInclude -->

| Nama |Tuts |Keterangan|
|---|---|---|
|Pindah ke dokumen mode jelajah yang berisi |NVDA+control+space |Memindahkan fokus keluar dari objek tertanam saat ini dan masuk ke dalam dokumen yang mengandung objek tertanam.|

<!-- KC:endInclude -->

## Membaca Konten Matematika {#ReadingMath}

Dengan menggunakan MathPlayer 4 dari Design Science, NVDA dapat membaca dan bernavigasi secara interaktif di dalam konten matematika yang didukung.
Untuk dapat melakukan ini, Anda harus memasang MathPlayer 4 di komputer.
MathPlayer dapat diunduh secara gratis di: http://www.dessci.com/en/products/mathplayer/

NVDA mendukung tipe-tipe konten matematika berikut ini:  

* MathML pada Mozilla Firefox dan Microsoft Internet Explorer dan Google Chrome.
* Design Science MathType pada Microsoft Word dan PowerPoint.
MathType perlu dipasang agar dapat digunakan. Versi percobaan sudah cukup memadai.  
* MathML pada Adobe Reader.
Perhatikanlah bahwa ini belum menjadi standar resmi. Jadi untuk saat ini belum tersedia software untuk umum yang dapat menghasilkan konten ini.  
* Matematika di Kindle pada PC untuk buku-buku Matematika aksesibel.

Saat membaca sebuah dokumen, NVDA akan menyebutkan konten matematika yang didukung di tempat konten tersebut ditemukan.
Jika Anda menggunakan braille display, konten ini juga akan ditampilkan dalam braille.  

### Navigasi Interaktif {#toc47}

Jika Anda bekerja terutama dengan speech (pengucapan), dalam banyak kasus, Anda mungkin ingin meneliti expression (kombinasi simbol) dalam segmen yang lebih kecil, alih-alih mendengarkan keseluruhan expression dalam satu waktu.

Jika Anda berada di mode jelajah, Anda dapat melakukannya dengan memindahkan kursor ke konten matematika dan menekan Enter.

Jika Anda tidak berada di mode jelajah:  

1. pindahkan kursor tinjauan ke konten matematika.
Secara default, kursor tinjauan mengikuti system caret, jadi Anda biasanya dapat menggunakan system caret untuk pindah ke konten yang diinginkan.
1. Lalu, aktifkan perintah berikut: 

<!-- KC:beginInclude -->

| Nama |Tuts |Keterangan|
|---|---|---|
|Berinteraksi dengan konten matematika |NVDA+alt+m |Memulai interaksi dengan konten matematika|

<!-- KC:endInclude -->

Pada titik ini, Anda dapat menggunakan perintah MathPlayer seperti tuts panah untuk mengeksplorasi kombinasi simbol.
Misalnya, Anda dapat menelusuri kombinasi simbol dengan panah kiri dan kanan, serta zoom ke satu bagian kombinasi simbol, misalnya satu pecahan dengan menggunakan tuts panah bawah.
Silakan lihat [instruksi penggunaan MathPlayer](https://www.dessci.com/en/products/mathplayer/navigation_commands.htm) untuk informasi lebih lanjut. 

Jika Anda ingin kembali ke dokumen, tekan tuts Escape.  

## Braille {#toc48}

Jika Anda memiliki braille display, NVDA dapat menampilkan informasi dalam braille.
Jika braille display Anda memiliki keyboard tipe-Perkins, Anda juga bisa memasukkan braille contraction atau braille penuh. 

Silakan lihat bagian [dukungan Braille Display](#SupportedBrailleDisplays) untuk informasi tentang braille display yang didukung.
Anda dapat mengkonfigurasi braille menggunakan [Dialog pengaturan braille](#BrailleSettings).

### Tipe Kontrol, State dan singkatan Landmark {#toc49}

Agar sesuai dengan informasi sebanyak mungkin pada braille display, singkatan berikut telah didefinisikan untuk menunjukkan tipe kontrol dan state serta landmark.

| Singkatan |Tipe Kontrol|
|---|---|
|app |application (aplikasi)|
|bqt |block quote (kutipan)|
|btn |button (tombol)|
|drbtn |drop down button (tombol drop down)|
|spnbtn |spin button (tombol putaran)|
|splbtn |split button (tombol pemisah)|
|tgbtn |toggle button|
|cbo |combo box (kotak kombo)|
|chk |checkbox (kotak centang)|
|dlg |dialog|
|doc |document (dokumen)|
|edt |editable text field (bidang teks yang dapat diedit)|
|pwdedt |password edit (edit kata sandi)|
|embedded |embedded object (objek tertanam)|
|enote |end note (catatan akhir)|
|fnote |foot note (catatan kaki)|
|gra |graphic (grafik)|
|grp |grouping (pengelompokan)|
|hN |heading pada level n, misal. h1, h2.|
|hlp |help baloon (bantuan)|
|lmk |landmark|
|lnk |link (tautan)|
|vlnk |visited link (tautan yang dikunjungi)|
|lst |list (daftar)|
|mnu |menu|
|mnubar |menu bar (bilah menu)|
|mnubtn |menu button (tombol menu)|
|mnuitem |menu item|
|pnl |panel|
|prgbar |progress bar (bilah progres)|
|rbtn |radio button|
|scrlbar |scroll bar|
|sect |section|
|stbar |status bar (bilah status)|
|tabctl |tab control|
|tbl |table|
|cN |table column number n, misal. c1, c2.|
|rN |table row number n, misal. r1, r2.|
|term |terminal|
|tlbar |tool bar|
|tltip |tool tip|
|tv |tree view|
|tvbtn |tree view button|
|tvitem |tree view item|
|lv N |item tree view yang mempunyai hirarki level N||
|wnd |window|
|????? |separator (pemisah)|

Indikator status berikut juga didefinisikan:

| Singkatan |Control state (Kontrol keadaan)|
|---|---|
|... |ditampilkan saat sebuah objek mendukung pelengkapan otomatis|
|??? |ditampilkan saat objek (misal: tombol toggle) ditekan|
|??? |ditampilkan saat objek (misal: tombol toggle) tidak ditekan|
|??? |ditampilkan saat sebuah objek (misal: kotak centang) dicentang|
|??? |ditampilkan saat objek (misal: kotak centang) setengah dicentang|
|??? |ditampilkan saat objek (misal: kotak centang) tidak dicentang|
|- |ditampilkan saat objek (misal: tree view item (item tampilan pohon)) dilipat|
|+ |ditampilkan saat objek (misal: tree view item (item tampilan pohon)) diperluas|
|*** |ditampilkan saat kontrol atau dokumen yang dilindungi ditemukan|
|clk |ditampilkan saat sebuah objek dapat diklik|
|cmnt |ditampilkan saat ada komentar untuk sel spreadsheet atau teks dalam dokumen|
|frml |ditampilkan bila ada rumus pada sel spreadsheet|
|invalid (tidak valid) |ditampilkan saat entri yang tidak valid telah dilakukan|
|ldesc |ditampilkan saat objek (biasanya grafis) memiliki deskripsi panjang|
|mln |ditampilkan saat field edit memungkinkan pengetikan beberapa baris teks seperti bidang komentar di situs web|
|req |ditampilkan saat field formulir yang dibutuhkan ditemukan|
|ro |ditampilkan saat objek (misalnya bidang teks yang dapat diedit) hanya dapat dibaca|
|sel |ditampilkan saat sebuah objek dipilih|
|nsel |ditampilkan saat objek tidak dipilih|
|ditampilkan asc |ditampilkan saat objek diurutkan menaik|
|ditampilkan desc |ditampilkan saat sebuah objek diurutkan turun|
|submnu |ditampilkan saat sebuah objek memiliki popup (biasanya sub-menu)|

Akhirnya, singkatan berikut untuk tengara didefinisikan:

| Singkatan |Landmark|
|---|---|
|bnnr |banner|
|cinf |content info (info isi)|
|cmpl |complementary (pelengkap)|
|form |form|
|main |main (utama)|
|navi |navigation (navigasi)|
|srch |search (pencarian)|
|rgn |region (wilayah)|

### Input Braille {#toc50}

NVDA mendukung masuknya braille tanpa kontrak dan kontrak melalui keyboard braille.
Anda dapat memilih tabel terjemahan yang digunakan untuk menerjemahkan braille menjadi teks menggunakan pengaturan [Tabel Input](#BrailleInputTable) dalam dialog Pengaturan Braille (Braille Settings dialog).

Jika braille yang tidak disingkat sedang digunakan, teks dimasukkan segera setelah di-enter.
Jika menggunakan braille yang disingkat, teks dimasukkan saat Anda menekan spasi atau masuk di akhir kata.
Perhatikan bahwa terjemahan hanya bisa mencerminkan kata braille yang Anda ketik dan tidak dapat mempertimbangkan teks yang ada.
Misalnya, jika Anda menggunakan kode braille yang dimulai nomor dengan tanda nomor dan Anda menekan backspace untuk berpindah ke nomor terakhir, Anda perlu mengetikkan tanda nomor lagi untuk memasukkan nomor tambahan.

<!-- KC:beginInclude -->
Menekan titik 7 akan menghapus sel atau karakter braille yang terakhir masuk.
Dot 8 menerjemahkan input braille dan menekan tuts enter.
Menekan dot 7 + dot 8 menerjemahkan input braille apapun, namun tanpa menambahkan spasi atau menekan enter.
<!-- KC:endInclude -->

## Content Recognition (Pengenalan Konten) {#toc51}

Jika pengarang tidak memberikan informasi yang cukup bagi pengguna pembaca layar untuk menentukan isi sesuatu, berbagai alat dapat digunakan untuk mencoba mengenali konten dari gambar.
NVDA mendukung fungsi optical character recognition (OCR) yang dibangun pada Windows 10 untuk mengenali teks dari gambar.
Pengenal konten tambahan dapat disediakan di add-on NVDA.

Saat Anda menggunakan perintah pengenalan konten, NVDA mengenali konten dari objek navigator saat ini #ObjectNavigation].
Secara default, objek navigator mengikuti mode fokus sistem atau kursor mode jelajah, sehingga biasanya Anda hanya bisa memindahkan kursor mode fokus atau jelajah dimana diinginkan.
Misalnya, jika Anda memindahkan kursor modus penjelajahan ke grafis, pengenalan akan mengenali konten dari grafik secara default.
Namun, Anda mungkin ingin menggunakan navigasi objek secara langsung, misalnya mengenali isi keseluruhan jendela aplikasi.

Setelah pengenalan selesai, hasilnya akan disajikan dalam dokumen yang mirip dengan mode jelajah, memungkinkan Anda membaca informasi dengan tuts kursor, dll.
Menekan enter atau spasi akan mengaktifkan (biasanya klik) teks pada kursor jika memungkinkan.
Menekankan escape menolak hasil pengenalan. 

### Windows 10 OCR {#Win10Ocr}

Windows 10 menyertakan OCR untuk banyak bahasa.
NVDA dapat menggunakan ini untuk mengenali teks dari gambar atau aplikasi yang tidak dapat diakses.

Anda dapat mengatur bahasa yang akan digunakan untuk pengenalan teks dalam dialog pengaturan [Windows 10 OCR #](Win10OcrSettings).
Bahasa tambahan dapat diinstal dengan membuka menu Start, pilih Settings, pilih Time & Language -> Region & Language dan kemudian memilih "Add a language".

<!-- KC:beginInclude -->
Untuk mengenali teks pada objek navigator saat ini menggunakan Windows 10 OCR, tekan NVDA + r.
<!-- KC:endInclude -->

## Fitur Tertentu pada Aplikasi {#toc53}

NVDA menyediakan fitur tambahannya sendiri untuk beberapa aplikasi guna memastikan Anda dapat melakukan pekerjaan dengan lebih mudah, atau untuk menyediakan akses ke fungsi yang tidak aksesibel bagi pengguna program pembaca layar.

### Microsoft Word {#toc54}
#### Pembacaan Judul Kolom dan Baris secara Otomatis {#toc55}

NVDA dapat memberitahukan secara otomatis judul baris dan kolom saat bernavigasi pada tabel di Microsoft Word.
Untuk melakukan ini, pertama-tama, opsi Report Table Row/Column Headers (Laporkan Judul Baris/Kolom Tabel) pada dialog Document Formatting (Pemformatan Dokumen) di NVDA harus diaktifkan.
Kedua, NVDA perlu mengetahui baris atau kolom mana yang berisi judul pada tabel.
Setelah pindah ke sel pertama dalam kolom atau baris yang berisi judul, gunakan salah satu perintah berikut ini:  
<!-- KC:beginInclude -->

| Nama |Tuts |Keterangan|
|---|---|---|
|Set column headers (Atur judul kolom) |NVDA+shift+c |Menekan perintah ini satu kali akan memberi tahu NVDA bahwa ini adalah sel judul pertama dalam satu baris yang berisi judul kolom, yang seharusnya disebutkan secara otomatis ketika berpindah di antara kolom-kolom di bawah baris ini. Menekannya dua kali akan membatalkan pengaturan.|
|Set row headers (Atur judul baris) |NVDA+shift+r |Menekan perintah ini satu kali akan memberi tahu NVDA bahwa ini adalah sel judul pertama dalam satu kolom yang berisi judul baris, yang seharusnya disebutkan secara otomatis ketika berpindah di antara baris-baris setelah kolom ini. Menekannya dua kali akan membatalkan pengaturan.|

<!-- KC:endInclude -->
Pengaturan ini akan disimpan di dalam dokumen sebagai bookmark (marka buku) yang kompatibel dengan program pembaca layar lain seperti Jaws.
Ini berarti bahwa pengguna pembaca layar lain yang membuka dokumen ini di kemudian hari akan secara otomatis mendapatkan judul baris dan kolom yang sudah diatur. 

#### Mode Jelajah pada Microsoft Word {#toc56}

Seperti di web, mode jelajah juga dapat digunakan di Microsoft Word sehingga Anda dapat menggunakan fitur seperti Quick Navigation (Navigasi Cepat) dan Elements List (Daftar Elemen).
<!-- KC:beginInclude -->
Untuk mengaktifkan dan menonaktifkan mode jelajah pada Microsoft Word, tekan NVDA+space.
<!-- KC:endInclude -->
Untuk informasi lebih lanjut mengenai mode jelajah dan Quick Navigation, silakan lihat [bagian Mode Jelajah](#BrowseMode).

##### Elements List (Daftar Elemen) {#toc57}

<!-- KC:beginInclude -->
Saat berada dalam mode jelajah di Microsoft Word, Anda dapat mengakses Elements List (Daftar Elemen) dengan menekan NVDA+f7.
<!-- KC:endInclude -->
Elements List dapat berupa daftar heading, link (tautan) dan anotasi (yang meliputi komentar dan track changes).

#### Melaporkan Komentar {#toc58}

<!-- KC:beginInclude -->
Untuk melaporkan komentar apa pun pada posisi caret saat ini, tekan NVDA+alt+c.
<!-- KC:endInclude -->
Semua komentar untuk dokumen, bersama dengan perubahan lain yang terlacak, dapat juga dimasukkan ke dalam Elements List NVDA saat memilih Annotations sebagai tipe. 

### Microsoft Excel {#toc59}
#### Pembacaan Judul Kolom dan Baris secara Otomatis {#toc60}

NVDA juga dapat memberitahukan secara otomatis judul baris dan kolom saat bernavigasi pada lembar kerja Excel.
Untuk melakukan ini, pertama-tama, opsi Report Table Row/Column Headers (Laporkan Judul Baris/Kolom Tabel) pada dialog Document Formatting (Pemformatan Dokumen) di NVDA harus diaktifkan.
Kedua, NVDA perlu mengetahui baris atau kolom mana yang berisi judul.
Setelah pindah ke sel pertama dalam kolom atau baris yang berisi judul, gunakan salah satu perintah berikut ini: 
<!-- KC:beginInclude -->

| Nama |Tuts |Keterangan|
|---|---|---|
|Set column headers (Atur judul kolom) |NVDA+shift+c |Menekan perintah ini satu kali akan memberi tahu NVDA bahwa ini adalah sel judul pertama dalam satu baris yang berisi judul kolom, yang seharusnya disebutkan secara otomatis ketika berpindah di antara kolom-kolom di bawah baris ini. Menekannya dua kali akan membatalkan pengaturan.|
|Set row headers (Atur judul baris) |NVDA+shift+r |Menekan perintah ini satu kali akan memberi tahu NVDA bahwa ini adalah sel judul pertama dalam satu kolom yang berisi judul baris, yang seharusnya disebutkan secara otomatis ketika berpindah di antara baris-baris setelah kolom ini. Menekannya dua kali akan membatalkan pengaturan.|

<!-- KC:endInclude -->
Pengaturan ini akan disimpan di dalam workbook sebagai istilah yang telah ditentukan, yang kompatibel dengan program pembaca layar lain seperti Jaws.
Ini berarti bahwa pengguna pembaca layar lain yang membuka workbook ini di kemudian hari akan secara otomatis mendapatkan judul baris dan kolom yang sudah diatur. 

#### Elements List (Daftar Elemen) {#toc61}

Seperti di web, NVDA memiliki Elements List (Daftar Elemen) untuk Microsoft Excel yang memungkinkan Anda untuk membuat daftar dan mengakses berbagai jenis informasi.
<!-- KC:beginInclude -->
Untuk mengakses Elements List pada Excel, tekan NVDA+f7.
<!-- KC:endInclude -->
Beberapa jenis informasi yang tersedia dalam Elements List adalah: 

* Charts (Diagram): Ini memuat daftar semua diagram dalam lembar kerja yang aktif.
Memilih sebuah diagram dan menekan Enter atau tombol Move To (Pindah ke) akan memfokuskan diagram untuk navigasi dan pembacaan dengan menggunakan tuts panah. 
* Comments (Komentar):  Ini memuat daftar semua sel dalam lembar kerja aktif yang berisi komentar.
Alamat setiap sel diperlihatkan bersama dengan komentar-komentarnya. 
Menekan Enter atau tombol Move To saat berada di komentar dalam daftar akan memindahkan Anda secara langsung ke sel tersebut.
* Formulas (Rumus):  Ini memuat daftar semua sel dalam lembar kerja aktif yang berisi rumus. 
Alamat setiap sel diperlihatkan bersama dengan rumusnya.
Menekan Enter atau tombol Move To saat berada di rumus dalam daftar akan memindahkan Anda secara langsung ke sel tersebut. 
* Sheets (Lembar):  Ini memuat daftar semua sheet (lembar) dalam workbook.
Menekan f2 saat berada di sheet dalam daftar memungkinkan Anda untuk memberi nama baru sheet tersebut.
Menekan Enter atau tombol Move To saat berada di sheet dalam daftar akan mengalihkan Anda ke sheet tersebut. 
* Form Field (Bidang Formulir): Ini memuat daftar semua form field (bidang formulir) dalam lembar kerja yang aktif.
Untuk setiap bidang formulir, Elements List akan menunjukkan teks alternatif pada bidang, bersama dengan alamat sel yang dicakupnya.
Memilih satu bidang formulir dan menekan Enter atau tombol Move To akan memindahkan Anda ke bidang tersebut dalam mode jelajah. 

#### Melaporkan Komentar {#toc62}

<!-- KC:beginInclude -->
Untuk melaporkan komentar apa pun untuk sel terfokus saat ini, tekan NVDA+alt+c.
<!-- KC:endInclude -->
Semua komentar untuk lembar kerja juga dapat dimasukkan ke dalam daftar di Elements List (Daftar Elemen) NVDA.

#### Membaca Sel Terproteksi {#toc63}

Jika satu workbook telah diproteksi, tidaklah mungkin untuk memindahkan fokus ke sel tertentu yang telah dikunci untuk pengeditan.
<!-- KC:beginInclude -->
Untuk memungkinkan Anda berpindah ke sel yang terkunci, beralihlah ke Browse Mode (Mode Jelajah) dengan menekan NVDA+space, kemudian gunakan perintah pindah standar pada Excel seperti tuts panah untuk menelusuri semua sel pada lembar kerja yang aktif saat ini.
<!-- KC:endInclude -->

#### Form Field (Bidang Formulir) {#toc64}

Lembar kerja Excel bisa terdiri dari beberapa form field (bidang formulir).
Anda dapat mengaksesnya dengan menggunakan Elements List (Daftar Elemen) atau tuts navigasi satu-huruf f dan bidang formulir shift+f.
Setelah Anda berpindah ke bidang formulir dalam mode jelajah, Anda dapat menekan Enter atau spasi untuk mengaktifkannya, atau beralih ke mode fokus agar Anda dapat berinteraksi dengannya, tergantung pada control.
Untuk informasi lebih lanjut mengenai mode jelajah dan navigasi satu-huruf, silakan lihat [bagian Mode Jelajah](#BrowseMode).

### Microsoft PowerPoint {#toc65}

<!-- KC:beginInclude -->

| Nama |Tuts |Keterangan|
|---|---|---|
|Men-toggle pembacaan Notes |control+shift+s |Saat slide show dijalankan, perintah ini akan mengaktifkan dan menonaktifkan pembacaan Notes (catatan) slide dan konten slide. Perintah ini hanya memengaruhi apa yang dibaca NVDA, bukan apa yang ditampilkan pada layar.|

<!-- KC:endInclude -->

### foobar2000 {#toc66}

<!-- KC:beginInclude -->

| Nama |Tuts |Keterangan|
|---|---|---|
|Report remaining time (Laporkan waktu yang tersisa) |control+shift+r |Melaporkan waktu yang tersisa pada pemutaran track saat ini, jika ada.|

<!-- KC:endInclude -->

Catatan:  Pintasan Report Remaining Time hanya bekerja dengan string pemformatan default untuk status line (baris status) foobar. 

### Miranda IM {#toc67}

<!-- KC:beginInclude -->

| Nama |Tuts |Keterangan|
|---|---|---|
|Report recent message (Laporkan pesan saat ini) |NVDA+control+1-4 |Melaporkan salah satu dari pesan-pesan terbaru, tergantung angka yang ditekan. Misalnya, menekan NVDA+control+2 akan membuat NVDA membacakan pesan terbaru kedua.|

<!-- KC:endInclude -->

### Poedit {#toc68}

<!-- KC:beginInclude -->

| Nama |Tuts |Keterangan|
|---|---|---|
|Report Comments Window (Laporkan Jendela Komentar) |control+shift+c |Melaporkan komentar apa pun di jendela komentar.|
|Report notes for translators (Laporkan catatan untuk penerjemah) |control+shift+a |Melaporkan catatan apa pun untuk penerjemah.|

<!-- KC:endInclude -->

### Skype {#toc69}

<!-- KC:beginInclude -->
Saat dalam percakapan: 

| Nama |Tuts |Keterangan|
|---|---|---|
|Review message (Tinjau pesan) |NVDA+control+1-0 |Melaporkan dan memindahkan kursor tinjauan ke satu pesan terbaru, tergantung angka yang ditekan. Misalnya, menekan NVDA+control+2 akan membuat NVDA membacakan pesan terbaru kedua.|

<!-- KC:endInclude -->

### Kindle untuk PC {#toc70}

NVDA mendukung membaca dan menavigasi buku di Amazon Kindle untuk PC.
Fungsi ini hanya tersedia di buku Kindle yang diberi judul "Screen Reader: Supported" yang dapat Anda periksa di halaman rincian untuk buku ini.

Mode Jelajah digunakan untuk membaca buku.
Ini diaktifkan secara otomatis saat Anda membuka buku atau memfokuskan area buku.
Halaman akan diputar secara otomatis jika sesuai saat Anda memindahkan kursor atau menggunakan perintah baca semua (say all)
<!-- KC:beginInclude -->
Anda dapat secara manual beralih ke halaman berikutnya dengan tuts pageDown dan beralih ke halaman sebelumnya dengan tuts pageUp.
<!-- KC:endInclude -->

Navigasi huruf tunggal didukung untuk tautan dan grafis, namun hanya ada di dalam laman saat ini.
Navigasi dengan link juga mencakup catatan kaki.

NVDA memberikan dukungan awal untuk membaca dan navigasi interaktif konten matematis untuk buku dengan matematika yang mudah diakses.
Silakan lihat bagian [Reading Mathematical Content (Membaca isi Matematika)](#ReadingMath) untuk informasi lebih lanjut.

#### Text Selection (Seleksi Teks) {#toc71}

Kindle memungkinkan Anda untuk melakukan berbagai fungsi pada teks yang dipilih, termasuk mendapatkan definisi kamus, menambahkan catatan dan sorotan, menyalin teks ke clipboard dan mencari di web.
Untuk melakukan ini, pertama pilih teks seperti biasa dalam mode browsing; misalnya dengan menggunakan tuts shift dan  kursor.
<!-- KC:beginInclude -->
Setelah Anda memilih teks, tekan tuts aplikasi atau shift+f10 untuk menampilkan opsi yang tersedia untuk pekerjaan dengan pilihan.
<!-- KC:endInclude -->
Jika Anda melakukan ini tanpa teks yang dipilih, opsi akan ditampilkan untuk kata di posisi kursor.

#### User Notes (Catatan Pengguna) {#toc72}

Anda dapat menambahkan catatan tentang kata atau bagian teks.
Untuk melakukan ini, pertama pilih teks yang relevan dan akses pilihan pilihan seperti yang dijelaskan di atas.
Kemudian, pilih Add Note (tambah catatan).

Saat membaca di mode jelajah, NVDA mengacu pada catatan ini sebagai komentar.

Untuk melihat, mengedit atau menghapus catatan:

1. Memindahkan kursor ke teks yang berisi catatan.
1. Akses pilihan untuk pemilihan seperti dijelaskan di atas.
1. Pilih Edit Catatan.

### Azardi {#toc73}

<!-- KC:beginInclude -->
Saat melihat tabel di tambah buku:

| Nama |Tuts |Keterangan|
|---|---|---|
|Enter |enter |Membuka buku yang dipilih.|
|Context menu |applications |Membuka menu konteks untuk buku yang dipilih.|

<!-- KC:endInclude -->

## Melakukan Konfigurasi NVDA {#toc74}
### Preferences (Preferensi) {#toc75}

<!-- KC:settingsSection: || Nama | Tuts Desktop | Tuts Laptop | Keterangan | -->
Sebagian besar pengaturan NVDA dapat diubah dengan menggunakan kotak dialog yang diakses melalui sub-menu Preferences pada menu NVDA.
Dalam semua kotak dialog pengaturan NVDA, tekan tombol OK untuk menerima perubahan apa pun yang Anda buat.
Untuk membatalkan perubahan, tekan tombol Cancel atau tuts Escape.
Sebagian pengaturan juga dapat diubah dengan menggunakan tuts pintasan yang relevan, sebagaimana dicantumkan di bagian berikut ini. 

Perhatikanlah bahwa secara default, tidak semua dialog Preferences dapat diakses dengan gestur input (perintah keyboard, gestur sentuh, dll.).
Jika Anda ingin mengakses dialog yang tidak memiliki tuts pintasan, gunakanlah [dialog Input Gestures (Gestur Input)](#InputGestures) guna menambah custom gesture (gestur biasa) untuk dialog tersebut. 

#### General Settings - Pengaturan Umum (NVDA+control+g) {#toc76}

Kotak dialog General Settings (Pengaturan Umum) dapat Anda temukan di menu Preferences.  
Pengaturan ini memiliki beberapa opsi: 

##### Language (Bahasa) {#toc77}

Ini adalah kotak kombo yang memungkinkan Anda untuk memilih bahasa yang akan digunakan dalam antarmuka pengguna dan pesan.
Terdapat banyak pilihan bahasa, namun opsi default-nya adalah "User Default, Windows".
Opsi ini meminta NVDA untuk menggunakan bahasa yang diatur untuk Windows saat ini. 

Harap perhatikan bahwa NVDA harus di-restart saat Anda mengubah pilihan bahasa.
NVDA akan bertanya apakah Anda ingin me-restart jika Anda memang mengubah pilihan bahasa.
Tekan OK, dan NVDA akan melakukan restart. 

##### Save configuration on exit (Simpan konfigurasi saat keluar) {#toc78}

Opsi ini adalah kotak centang yang jika dicentang, akan meminta pada NVDA untuk secara otomatis menyimpan konfigurasi yang aktif saat ini ketika Anda keluar dari NVDA. 

##### Show exit options when exiting NVDA (Tunjukkan opsi keluar saat keluar dari NVDA) {#toc79}

Opsi ini adalah kotak centang yang memungkinkan Anda untuk memilih apakah sebuah dialog ditampilkan saat Anda keluar dari NVDA.
Dialog ini menanyakan apa tindakan yang ingin Anda lakukan, jika dicentang sebuah dialog akan muncul saat Anda berusaha keluar dari NVDA dan menanyakan apakah Anda ingin keluar, melakukan restart, atau melakukan restart dengan add-ons dinonaktifkan.
Jika tidak dicentang, Anda akan langsung keluar dari NVDA. 

##### Play sounds when starting or exiting NVDA (Perdengarkan suara saat memulai atau keluar dari NVDA) {#toc80}

Opsi ini adalah kotak centang yang jika dicentang, akan meminta pada NVDA untuk memperdengarkan suara saat Anda memulai atau keluar dari NVDA.

##### Logging level {#toc81}

Ini adalah kotak kombo yang mengizinkan Anda untuk memilih seberapa banyak NVDA akan melakukan log saat sedang dijalankan.
Biasanya, pengguna tidak perlu melakukan apa-apa dengan opsi ini karena pengguna tidak perlu banyak melakukan log.
Namun jika Anda ingin memberikan informasi dalam bug report (laporan bug), maka ini mungkin akan menjadi opsi yang bermanfaat. 

##### Automatically start NVDA after I log on to Windows (Secara otomatis memulai NVDA setelah saya log on ke Windows) {#toc82}

Jika opsi ini diaktifkan, NVDA akan mulai secara otomatis segera setelah Anda log on ke Windows. 
Opsi ini hanya tersedia untuk salinan NVDA yang di-install.

##### Use NVDA on the Windows Logon screen (requires administrator privileges) - Gunakan NVDA pada layar Logon Windows (diperlukan hak istimewa administrator) {#toc83}

Jika Anda melakukan log on ke Windows dengan menuliskan nama pengguna dan kata kunci, maka mengaktifkan opsi ini akan membuat NVDA aktif secara otomatis pada layar log on ketika Windows diaktifkan.
Opsi ini hanya tersedia untuk salinan NVDA yang di-install. 

##### Use currently saved settings on the logon and other secure screens (requires administrator privileges) - Gunakan pengaturan yang disimpan saat ini pada layar log on dan layar keamanan lain (diperlukan hak istimewa administrator) {#toc84}

Menekan tombol ini akan menyalin konfigurasi pengguna NVDA yang tersimpan saat ini ke direktori konfigurasi sistem NVDA, sehingga NVDA akan menggunakannya ketika berjalan pada layar logon, User Account Control (UAC) dan layar keamanan Windows lainnya.
Untuk memastikan bahwa semua pengaturan Anda telah ditransfer, pastikan untuk menyimpan konfigurasi Anda lebih dulu dengan control+NVDA+c atau Save configuration (Simpan konfigurasi) di dalam menu NVDA.
Opsi ini hanya tersedia untuk salinan NVDA yang di-install. 

##### Automatically check for updates to NVDA (Memeriksa pembaruan secara otomatis pada NVDA) {#toc85}

Jika opsi ini diaktifkan, NVDA akan secara otomatis memeriksa versi terbaru NVDA dan memberi tahu Anda kapan pembaruan akan tersedia.
Anda juga dapat memeriksa pembaruan secara manual dengan memilih Check for updates (Periksa pembaruan) di bawah Help pada menu NVDA. 

#### Synthesizer Selection - Pemilihan Synthesizer (NVDA+control+s) {#toc86}

Dialog Synthesizer, yang dapat Anda temukan di bawah "Synthesizer..." dalam menu Preferences memungkinkan Anda untuk memilih Synthesizer mana yang digunakan NVDA untuk berbicara.
Setelah Anda memilih synthesizer, Anda dapat menekan Ok dan NVDA akan membuka Synthesizer terpilih.
Jika terjadi error saat membuka synthesizer, NVDA akan memberi tahu Anda lewat sebuah pesan, dan meneruskan menggunakan synthesizer sebelumnya. 

##### Synthesizer {#toc87}

Opsi ini memungkinkan Anda memilih synthesizer untuk digunakan NVDA dalam output pengucapan. 

Untuk mengetahui daftar Synthesizers yang didukung NVDA, silakan lihat bagian [Speech Synthesizer yang Didukung](#SupportedSpeechSynths).

Satu item istimewa yang akan selalu tampil dalam daftar adalah "No speech" (Tanpa pengucapan) yang memungkinkan Anda untuk menggunakan NVDA tanpa output pengucapan sama sekali.
Ini mungkin berguna untuk seseorang yang ingin menggunakan NVDA hanya dengan braille display, atau mungkin bagi pengembang nontunanetra yang hanya ingin menggunakan Speech Viewer (Penampil Ucapan).

##### Output device (Perangkat output) {#toc88}

Opsi ini memungkinkan Anda untuk memilih sound card (kartu suara) yang disyaratkan NVDA untuk diaplikasikan pada synthesizer terpilih guna menghasilkan pengucapan.

<!-- KC:setting -->

##### Audio Ducking Mode (Mode Audio Ducking) {#toc89}

Tuts: NVDA+shift+d

Pada Windows 8 dan yang lebih baru, opsi ini memungkinkan Anda untuk memilih apakah NVDA harus merendahkan volume aplikasi lain saat NVDA berbicara, atau setiap waktu selama NVDA dijalankan. 

* No Ducking (Tanpa Ducking): NVDA tidak akan pernah merendahkan volume audio lain.
* Duck when outputting speech and sounds (Duck ketika memberikan output pengucapan dan suara): NVDA hanya akan merendahkan volume audio lain ketika NVDA berbicara atau memainkan suara. Ini mungkin tidak berfungsi pada setiap synthesizer. 
* Always duck (Selalu duck):  NVDA akan merendahkan volume audio lain selama NVDA aktif. 

Opsi ini hanya tersedia jika NVDA telah dipasang. 
Tidaklah mungkin untuk mendukung audio ducking untuk salinan NVDA yang portabel maupun sementara. 

#### Voice Settings - Pengaturan Suara (NVDA+control+v) {#VoiceSettings}

Dialog Voice Settings (Pengaturan Suara) yang ditemukan dalam menu Preferences memiliki beberapa opsi yang memungkinkan Anda untuk mengubah suara pengucapan.
Untuk cara alternatif yang lebih cepat dalam mengontrol parameter pengucapan dari mana pun, silakan lihat bagian [Ring Pengaturan Synth](#SynthSettingsRing).

Kotak dialog Voice Settings memiliki beberapa opsi berikut ini: 

##### Voice (Suara) {#toc91}

Opsi pertama yang Anda temukan dalam dialog ini adalah kotak kombo yang memuat daftar semua suara dari synthesizer saat ini yang telah Anda pasang.
Anda dapat menggunakan tuts panah untuk mendengarkan semua pilihan.
Panah kiri dan atas akan membawa Anda ke bagian atas daftar, sementara panah kanan dan bawah akan membawa Anda ke bagian bawah daftar.

##### Variant (Varian) {#toc92}

Jika Anda menggunakan synthesizer Espeak NG yang berada dalam paket NVDA, maka ini adalah kotak kombo yang memungkinkan Anda untuk memilih varian yang harus digunakan oleh synthesizer. 
Varian ESpeak NG agak mirip dengan suara, karena varian ini menyediakan atribut yang hanya sedikit berbeda pada suara eSpeak NG.
Sebagian varian mirip dengan suara pria, sebagian seperti suara wanita, dan sebagian lagi bahkan mirip suara kodok. 

##### Rate (Kecepatan) {#toc93}

Opsi ini memungkinkan Anda untuk mengubah rate (kecepatan) suara.
Ini adalah penggulir yang dapat digeser dari angka 0 sampai 100 (0 untuk rate paling lambat, 100 untuk yang paling cepat). 

##### Pitch (Nada) {#toc94}

Opsi ini memungkinkan Anda untuk mengubah pitch (nada) suara saat ini. 
Ini adalah penggulir yang dapat digeser dari angka 0 sampai 100 (0 untuk pitch terendah dan 100 untuk yang tertinggi).

##### Volume {#toc95}

Opsi ini adalah penggulir yang dapat digeser dari angka 0 sampai 100 (0 untuk volume terendah dan 100 untuk yang tertinggi).

##### Inflection (Infleksi) {#toc96}

Opsi ini adalah penggulir yang memungkinkan Anda untuk memilih seberapa banyak infleksi (naik dan turunnya nada) yang digunakan synthesizer untuk bicara. (Saat ini, satu-satunya synthesizer yang memberikan opsi ini adalah eSpeak NG). 

##### Automatic Language switching (Pengalihan Bahasa Secara Otomatis) {#toc97}

Kotak centang ini memungkinkan Anda untuk men-toggle apakah NVDA harus mengalihkan bahasa speech synthesizer (synthesizer pengucapan) secara otomatis jika teks yang dibaca menyebutkan bahasanya. 
Opsi ini aktif secara default. 
Saat ini hanya synthesizer eSpeak NG yang mendukung pengalihan bahasa secara otomatis.

##### Automatic Dialect switching (Pengalihan Dialek Secara Otomatis) {#toc98}

Kotak centang ini memungkinkan Anda untuk men-toggle apakah perubahan dialek perlu dibuat atau tidak, alih-alih perubahan bahasa.
Misalnya, jika bacaan adalah dalam suara berbahasa Inggris-Amerika tapi di dokumen disebutkan bahwa sebagian teks adalah dalam bahasa Inggris-British, maka synthesizer akan mengalihkan aksen pengucapan jika opsi ini diaktifkan.
Opsi ini nonaktif secara default. 

<!-- KC:setting -->

##### Punctuation/Symbol Level (Level Tanda Baca/Symbol) {#toc99}

Tuts: NVDA+p

Opsi ini memungkinkan Anda untuk memilih level tanda baca dan simbol lain yang akan diucapkan sebagai kata.
Misalnya, jika Anda memilih Set to all (Atur semua), semua simbol akan diucapkan sebagai kata.
Opsi ini berlaku pada semua synthesizer, bukan hanya synthesizer yang aktif saat ini.

##### Trust voice's language for processing symbols and characters (Pastikan bahasa suara untuk memproses simbol dan karakter) {#toc100}

Secara default, opsi ini memberi tahu NVDA apakah bahasa suara saat ini bisa dipastikan ketika memproses simbol dan karakter.
Jika NVDA membaca tanda baca dalam bahasa yang salah untuk synthesizer atau suara tertentu, Anda mungkin ingin menonaktifkan opsi ini  guna memaksa NVDA menggunakan pengaturan bahasa yang global. 

##### Capital pitch change percentage (Prosentase perubahan nada huruf kapital) {#toc101}

Bidang edit ini memungkinkan Anda untuk mengetik level perubahan nada suara ketika mengucapkan huruf besar. 
Nilai level merupakan prosentase, dengan nilai yang negatif merendahkan nada dan nilai yang positif menaikkannya. 
Jika Anda tidak ingin mengubah nada, gunakan nilai 0. 

##### Say "cap" before capitals (Sebutkan "cap" sebelum huruf kapital) {#toc102}

Pengaturan ini berupa kotak centang yang jika dicentang akan meminta NVDA untuk mengucapkan kata "cap" sebelum mengucapkan huruf kapital, ketika huruf kapital tersebut diucapkan sebagai karakter tersendiri seperti ketika mengeja.
Biasanya, NVDA menaikkan nada sedikit untuk huruf kapital, tapi sebagian synthesizer mungkin tidak mendukung ini. Jadi, mungkin opsi ini Anda gunakan. 

##### Beep for capitals (Bunyi bip untuk huruf kapital) {#toc103}

Jika kotak centang ini dicentang, NVDA akan memperdengarkan suara bip pelan dengan sendirinya, setiap kali menemui huruf kapital.
Seperti pada kotak centang "Say cap for capitals", opsi ini berguna untuk synthesizer yang tidak dapat mengubah nada huruf kapital. 

##### Use spelling functionality if supported (Gunakan fungsi pengejaan jika didukung) {#VoiceSpellingFunctionality}

Sebagian kata terdiri dari hanya satu karakter, tapi pelafalannya berbeda tergantung pada apakah karakter itu diucapkan sebagai satu karakter tersendiri (seperti ketika mengeja) atau satu kata tersendiri.
Misalnya, dalam bahasa Inggris, "a" (sebuah) adalah satu huruf sekaligus satu kata yang dilafalkan secara berbeda dalam masing-masing kasus.
Opsi ini memungkinkan synthesizer untuk membedakan antara kedua kasus jika synthesizer mendukung ini.
Sebagai informasi tambahan, sebagian besar synthesizer mendukung opsi ini. 

Opsi ini biasanya diaktifkan.
Namun, sebagian synthesizer Microsoft Speech API tidak menerapkan opsi ini secara benar dan berperilaku aneh ketika diaktifkan.
Jika Anda menemui masalah dengan pelafalan karakter secara tersendiri, cobalah menonaktifkan opsi ini. 

#### Ring Pengaturan Synth {#SynthSettingsRing}

Jika Anda ingin mengubah pengaturan pengucapan dengan cepat tanpa melalui dialog Voice Settings (Pengaturan Suara), terdapat beberapa perintah tuts NVDA yang memungkinkan Anda untuk menelusuri pengaturan pengucapan yang paling umum dari mana pun sementara Anda menjalankan NVDA: 
<!-- KC:beginInclude -->

| Nama |Tuts Desktop |Tuts Laptop |Keterangan|
|---|---|---|---|
|Pindah ke pengaturan synth berikutnya |NVDA+control+panah kanan |NVDA+shift+control+panah kanan |Berpindah ke pengaturan pengucapan berikutnya yang tersedia setelah pengaturan saat ini, kembali ke pengaturan yang pertama lagi setelah pengaturan terakhir.|
|Pindah ke pengaturan synth sebelumnya |NVDA+control+panah kiri |NVDA+shift+control+panah kiri |Berpindah ke pengaturan pengucapan berikutnya yang tersedia sebelum pengaturan saat ini, berpindah ke pengaturan yang terakhir setelah pengaturan pertama.|
|Tingkatkan pengaturan synth saat ini |NVDA+control+panah atas |NVDA+shift+control+panah atas |Meningkatkan pengaturan pengucapan yang aktif saat ini.  Misalnya, menambah rate (kecepatan), memilih suara berikutnya, menaikkan volume|
|Kurangi pengaturan synth saat ini |NVDA+control+panah bawah |NVDA+shift+control+panah bawah |Mengurangi pengaturan pengucapan yang aktif saat ini. Misalnya, mengurangi rate (kecepatan), memilih suara sebelumnya, mengurangi volume.|

<!-- KC:endInclude -->

#### Braille Settings (Pengaturan Braille) {#BrailleSettings}

Kotak dialog Braille Settings (Pengaturan Braille) dapat digunakan dengan mengakses menu Preferences, lalu opsi Braille Settings.

##### Braille Display {#toc107}

Opsi pertama yang akan Anda temukan dalam dialog Braille Settings adalah kotak kombo yang menyebutkan "braille display".
Anda akan disuguhi beberapa opsi, tergantung pada driver braille display yang tersedia di sistem Anda.
Berpindahlah di antara opsi-opsi ini dengan tuts panah.  

"No braille" (Tanpa braille) berarti Anda tidak menggunakan braille display. 

Silakan lihat bagian [Braille Display yang Didukung](#SupportedBrailleDisplays) untuk informasi lebih lanjut tentang braille display yang didukung.

##### Port {#toc108}

Opsi ini, jika tersedia, memungkinkan Anda untuk memilih port atau tipe koneksi yang akan digunakan guna berkomunikasi dengan braille display yang telah Anda pilih.
Ini adalah kotak kombo yang berisi beberapa pilihan untuk braille display Anda.

Secara default, NVDA menggunakan deteksi port otomatis, yang berarti bahwa koneksi dengan perangkat braille display akan dilakukan secara otomatis dengan memindai perangkat USB dan bluetooth yang ada pada sistem Anda.
Namun, untuk beberapa braille display, Anda mungkin bisa secara eksplisit memilih port yang akan digunakan.
Opsi-opsi yang biasanya tersedia adalah "Automatic" (yang meminta NVDA untuk menggunakan prosedur pemilihan port otomatis secara default), "USB", "Bluetooth" dan beberapa port komunikasi serial legacy jika braille display Anda mendukung jenis komunikasi ini.

Opsi ini tidak akan tersedia jika braille display Anda hanya mendukung deteksi port otomatis.

Anda dapat merujuk instruksi penggunaan braille display di bagian [Braille Display yang Didukung](#SupportedBrailleDisplays) untuk mengetahui lebih detail tentang jenis komunikasi yang didukung dan port yang tersedia.

##### Output Table (Tabel Output) {#toc109}

Opsi berikutnya yang akan Anda temukan dalam dialog ini adalah kotak kombo Output Table braille.
Dalam kotak kombo ini, Anda akan menemukan beberapa tabel braille untuk bahasa-bahasa yang berbeda, standar dan tingkatan braille.
Tabel yang dipilih akan digunakan untuk menerjemahkan teks ke dalam format braille guna ditampilkan pada braille display Anda.
Anda dapat berpindah dari satu tabel braille ke tabel braille lain di dalam daftar dengan menggunakan tuts panah. 

##### Input Table (Tabel Input) {#BrailleInputTable}

Melengkapi opsi sebelumnya, pengaturan berikutnya yang akan Anda temukan adalah kotak kombo Input Table braille.
Tabel yang dipilih akan digunakan untuk menerjemahkan huruf braille ~~yang dimasukkan ke keyboard tipe-Perkins pada braille display~~ menjadi teks.
Anda dapat berpindah dari satu tabel braille ke tabel braille lain di dalam daftar dengan menggunakan tuts panah. 

Perhatikanlah bahwa opsi ini hanya berguna jika braille display Anda memiliki keyboard tipe-Perkins dan fitur ini didukung oleh driver braille display.
Jika input tidak didukung pada display yang tidak memiliki keyboard braille, ini termasuk di dalam catatan di bagian [Braille Display yang Didukung](#SupportedBrailleDisplays).

##### Expand to computer braille for the word at the cursor (Tampilkan kata pada kursor di braille komputer) {#toc111}

Opsi ini memungkinkan kata di bawah kursor untuk ditampilkan pada braille komputer tanpa disingkat.  

##### Show Cursor (Tampilkan Kursor) {#toc112}

Opsi ini memungkinkan kursor braille diaktifkan dan dinonaktifkan. 
Ini berlaku untuk system caret dan kursor tinjauan, tapi tidak berlaku untuk Selection Indicator (Indikator Pemilihan). 

##### Blink Cursor (Kedipan Kursor) {#toc113}

Opsi ini memungkinkan kursor braille mengedip.
Jika kedipan mati, kursor braille akan berada di posisi atas.
Selection Indicator (Indikator Pemilihan) tidak dipengaruhi oleh opsi ini, itu selalu pada titik 7 dan 8 tanpa mengedip.

##### Cursor Blink Rate (ms) - Tingkat Kedipan Kursor (ms) {#toc114}

Opsi ini adalah bidang numerik yang memungkinkan Anda untuk mengubah tingkat kedipan kursor dalam milisekon.

##### Cursor Shape for Focus (Bentuk Kursor untuk fokus) {#toc115}

Opsi ini memungkinkan Anda untuk memilih bentuk (pola titik) pada kursor braille ketika braille ditambatkan ke titik pusat/fokus.
Selection Indicator (Indikator Pemilihan) tidak dipengaruhi oleh opsi ini, itu selalu pada titik 7 dan 8 tanpa mengedip.

##### Cursor Shape for Review (Bentuk Kursor untuk Tinjauan) {#toc116}

Opsi ini memungkinkan Anda untuk memilih bentuk (pola titik) pada kursor braille ketika braille ditambatkan ke titik pusat/fokus.
Selection Indicator (Indikator Pemilihan) tidak dipengaruhi oleh opsi ini, itu selalu pada titik 7 dan 8 tanpa mengedip.

##### Message Timeout (sec) - Waktu Habis untuk Pesan (detik) {#toc117}

Opsi ini adalah bidang numerik yang mengontrol seberapa lama pesan NVDA ditampilkan pada braille display.
Memilih 0 akan sepenuhnya menonaktifkan penampilan pesan.

##### Show Messages Indefinitely (Tampilan Pesan Tanpa Batas) {#toc118}

Opsi ini memungkinkan pesan NVDA ditampilkan pada tampilan braille tanpa batas.

<!-- KC:setting -->

##### Braille Tethered to (Braille Display Ditambatkan ke) {#BrailleTether}

Tuts: NVDA+control+t

Opsi ini memungkinkan Anda untuk memilih apakah braille display akan mengikuti fokus sistem, atau mengikuti objek navigator/kursor tinjauan.

##### Read by Paragraph (Baca per Paragraf) {#toc120}

Jika diaktifkan, teks braille akan ditampilkan per paragraf dan bukan per baris.
Begitu juga, perintah baris sesudahnya dan sebelumnya akan pindah per paragraf.
Ini berarti Anda tidak harus menggulir tampilan di akhir tiap baris, meskipun terdapat lebih banyak teks pada tampilan.
Ini memungkinkan Anda untuk membaca banyak teks secara lebih lancar.
Opsi ini dinonaktifkan secara default. 

##### Avoid splitting words when possible (Hindari pemisahan kata, jika mungkin) {#toc121}

Jika opsi ini diaktifkan, satu kata yang terlalu panjang untuk dimuat pada akhir tampilan braille display tidak akan dipisah.
Sebagai gantinya, akan ada spasi kosong di akhir tampilan.
Saat Anda menggulir tampilan, Anda akan dapat membaca seluruh kata.
Ini kadang disebut "word wrap".
Perhatikanlah bahwa jika satu kata terlalu panjang untuk dimuat pada tampilan, bahkan jika hanya satu kata itu sendiri yang akan ditampilkan, kata tersebut akan dipisah. 

Jika opsi ini dinonaktifkan, sebanyak mungkin kata akan ditampilkan, dan sisanya tidak akan ditampilkan.
Saat Anda menggulir tampilan, Anda akan dapat membaca sisa kata tersebut. 

Mengaktifkan opsi ini memungkinkan Anda untuk membaca dengan lebih lancar, namun umumnya opsi ini mensyaratkan Anda untuk menggulir tampilan lagi. 

##### Focus context presentation (Fokus Konteks presentasi) {#toc122}

Opsi ini memungkinkan anda memilih informasi konteks apa yang akan ditampilkan NVDA di layar braille saat objek mendapat fokus.
Informasi konteks mengacu pada hirarki objek yang berisi fokus.
Misalnya, ketika Anda memusatkan daftar item, item daftar ini adalah bagian dari daftar.
Daftar ini mungkin berisi dialog, dll.
Silakan baca bagian tentang [navigasi objek](#ObjectNavigation) untuk informasi lebih lanjut tentang hirarki yang berlaku untuk objek di NVDA.

Saat diatur untuk mengisi tampilan untuk perubahan konteks, NVDA akan mencoba menampilkan sebanyak mungkin informasi konteks pada tampilan braille, namun hanya untuk bagian-bagian dari konteks yang telah berubah.
Untuk contoh di atas, ini berarti bahwa saat mengubah fokus ke daftar, NVDA akan menampilkan item daftar pada layar braille.
Selanjutnya, jika ada cukup ruang yang tersisa pada layar braille, NVDA akan mencoba untuk menunjukkan bahwa item daftar adalah bagian dari daftar.
Jika Anda kemudian mulai bergerak melalui daftar dengan tombol panah Anda, diasumsikan Anda sadar bahwa Anda masih berada dalam daftar.
Jadi, untuk item daftar yang tersisa yang Anda fokuskan, NVDA hanya akan menampilkan item daftar fokus di layar.
Agar Anda dapat membaca konteksnya lagi (yaitu bahwa Anda berada dalam daftar dan daftar itu adalah bagian dari dialog), Anda harus menggulir kembali tampilan braille Anda.

Bila opsi ini disetel untuk selalu mengisi layar, NVDA akan mencoba menampilkan sebanyak mungkin informasi konteks pada tampilan braille, terlepas dari apakah Anda telah melihat informasi konteks yang sama sebelumnya.
Ini memiliki keuntungan bahwa NVDA akan memasukkan informasi sebanyak mungkin di layar.
Namun, sisi negatifnya adalah selalu ada perbedaan pada posisi dimana fokus dimulai pada layar braille.
Hal ini dapat membuat sulit untuk membuat daftar item yang panjang, misalnya, karena Anda perlu terus memindahkan jari Anda untuk menemukan awal item.
Ini adalah perilaku default NVDA 2017.2 dan sebelumnya.

Bila Anda menetapkan pilihan presentasi konteks fokus untuk hanya menampilkan informasi konteks saat menggulir kembali, NVDA tidak pernah menampilkan informasi konteks pada layar braille Anda secara default.
Jadi, pada contoh di atas, NVDA akan menampilkan bahwa Anda memfokuskan daftar item.
Namun, agar Anda dapat membaca konteksnya (yaitu bahwa Anda berada dalam daftar dan daftar itu adalah bagian dari dialog), Anda harus menggulir kembali tampilan braille Anda. 

Untuk mengalihkan presentasi konteks fokus dari mana saja, tolong tetapkan isyarat khusus menggunakan [dialog Input Gestures](#InputGestures).

#### Keyboard Settings - Pengaturan Keyboard (NVDA+control+k) {#toc123}

Kotak dialog ini dapat Anda temukan di menu Preferences, di bawah "Keyboard settings...".
Pengaturan ini memiliki beberapa opsi: 

##### Keyboard Layout (Tata Letak Keyboard) {#toc124}

Kotak kombo ini memungkinkan Anda untuk memilih jenis tata letak keyboard yang akan digunakan NVDA. Saat ini, terdapat dua tampilan yang dapat digunakan NVDA, yaitu Desktop dan Laptop.

##### Use capslock as an NVDA modifier key (Gunakan capslock sebagai tuts modifier NVDA) {#toc125}

Jika kotak centang ini dicentang, capslock dapat digunakan sebagai tuts modifier NVDA. 

##### Use extended insert as an NVDA modifier key (Gunakan extended insert sebagai tuts modifier NVDA) {#toc126}

Jika kotak centang ini dicentang, tuts extended insert (biasanya terdapat di atas tuts panah, di dekat Home dan End) dapat digunakan sebagai tuts modifier NVDA.

##### Use numpad insert as an NVDA modifier key (Gunakan numpad insert sebagai tuts modifier NVDA) {#toc127}

Jika kotak centang ini dicentang, tuts insert pada number pad (tuts numerik) dapat digunakan sebagai tuts modifier NVDA.

Jika tidak ada tuts yang dipilih sebagai tuts NVDA, maka Anda tidak mungkin dapat mengakses perintah NVDA tertentu.
Oleh karena itu, dialog Keyboard Settings (Pengaturan Keyboard) akan menampilkan pesan error jika tidak ada tuts yang dipilih saat Anda menekan Ok.
Setelah menutup pesan error, Anda harus memilih setidaknya satu tuts sebelum dapat menekan Ok untuk menutup dialog dengan benar. 

<!-- KC:setting -->

##### Speak Typed Characters (Ucapkan karakter yang diketik) {#toc128}

Tuts: NVDA+2

Jika diaktifkan, NVDA akan menyebutkan semua karakter yang Anda ketik pada keyboard. 

<!-- KC:setting -->

##### Speak Typed Words (Ucapkan kata yang diketik) {#toc129}

Tuts: NVDA+3

Jika diaktifkan, NVDA akan menyebutkan semua kata yang Anda ketik pada keyboard. 

##### Speech interrupt for typed characters (Interupsi pengucapan untuk karakter yang diketik) {#toc130}

Jika posisinya "on", opsi ini akan membuat pengucapan diinterupsi setiap kali satu karakter diketik. Pengaturan ini "on" secara default.

##### Speech interrupt for Enter key (Interupsi pengucapan untuk tuts Enter) {#toc131}

Jika posisinya "on", opsi ini akan membuat pengucapan diinterupsi setiap kali tuts Enter ditekan. Pengaturan ini "on" secara default.

##### Allow skim reading in Say All (Izinkan skim reading dalam Say All) {#toc132}

Jika posisinya "on", perintah navigasi tertentu (seperti navigasi cepat dalam mode jelajah, atau berpindah per baris atau paragraf) tidak akan menghentikan Say All (Baca Semua). Lebih tepatnya, Say All akan melompat ke posisi baru dan meneruskan membaca. 

##### Beep if Typing Lowercase Letters when Caps Lock is On (Perdengarkan Bip jika mengetik huruf kecil saat Caps Lock di posisi On) {#toc133}

Jika diaktifkan, suara peringatan Bip akan terdengar saat satu huruf diketik dengan menekan tuts Shift sementara Caps Lock ada di posisi on.
Umumnya, orang mengetikkan suatu huruf sambil menekan Shift dengan Caps Lock secara tidak sengaja, dan karena tidak menyadari bahwa Caps Lock diaktifkan.
Oleh karena itu, akan sangat membantu jika ada peringatan dalam hal ini. 

<!-- KC:setting -->

##### Speak Command Keys (Ucapkan tuts perintah) {#toc134}

Tuts: NVDA+4

Jika diaktifkan, NVDA akan menyebutkan semua tuts non-karakter yang Anda ketik pada keyboard. Termasuk juga kombinasi tuts, seperti control + huruf lain. 

##### Play sound for spelling errors while typing (Perdengarkan suara untuk kesalahan eja saat mengetik) {#toc135}

Jika diaktifkan, suara dengung pendek akan diperdengarkan ketika kata yang Anda ketik mengandung kesalahan eja.
Opsi ini hanya tersedia jika pelaporan kesalahan eja diaktifkan dalam dialog NVDA [Document Formatting Settings (Pengaturan Pemformatan Dokumen](#DocumentFormattingSettings).

##### Handle keys from other applications (Tangani kunci dari aplikasi lain) {#toc136}

Opsi ini memungkinkan pengguna untuk mengontrol apakah tindakan menekan kunci yang dilakukan dengan aplikasi, seperti on-screen keyboard (keyboard di layar) dan speech recognition software (software pengenalan ucapan) harus diproses oleh NVDA.
Opsi ini ada dalam posisi on secara default, meskipun sebagian pengguna tertentu mungkin ingin menonaktifkannya, misalnya mereka yang mengetik dalam bahasa Vietnam dengan software pengetikan Unikey, karena opsi ini akan menyebabkan input karakter yang keliru. 

#### Mouse Settings - Pengaturan Mouse (NVDA+control+m) {#MouseSettings}

Dialog Mouse Settings ini dapat Anda temukan di menu Preferences, di bawah "Mouse settings...".
Pengaturan ini memiliki beberapa opsi: 

##### Report Mouse Shape Changes (Laporkan Perubahan Bentuk Mouse) {#toc138}

Apabila kotak centang dicentang, maka NVDA akan memberi tahu setiap kali bentuk mouse pointer (penunjuk mouse) berubah.
Penunjuk mouse pada Windows berubah bentuk untuk menyampaikan informasi tertentu, seperti kapan sesuatu bisa diedit, atau kapan sesuatu sedang dibuka (loading), dll. 

<!-- KC:setting -->

##### Enable mouse tracking (Aktifkan pelacakan mouse) {#toc139}

Tuts: NVDA+m

Jika diaktifkan, NVDA akan memberi tahu teks yang saat ini ada di bawah mouse pointer (penunjuk mouse), saat Anda memindah-mindahkan penunjuk tersebut pada layar. Ini memungkinkan Anda untuk menemukan sesuatu pada layar dengan menggeser mouse secara fisik, alih-alih mencoba menemukan sesuatu tersebut melalui navigasi objek. 

##### Text unit resolution (Resolusi kesatuan teks) {#toc140}

Jika NVDA diatur untuk memberi tahu teks yang ada di bawah mouse saat Anda menggeser mouse, maka opsi ini memungkinkan Anda untuk memilih seberapa banyak persisnya teks yang akan diucapkan.
Opsinya adalah karakter, kata, baris dan paragraf. 

##### Report role when mouse enters object (Laporkan peran ketika mouse memasuki objek) {#toc141}

Jika kotak centang ini dicentang, NVDA akan memberi tahu peran (jenis) objek saat mouse bergerak di dalamnya. 

##### Play audio coordinates when mouse moves (Perdengarkan koordinat audio ketika mouse bergerak) {#toc142}

Mencentang kotak centang ini akan membuat NVDA memainkan bunyi bip saat mouse bergerak, sehingga pengguna dapat bekerja pada posisi mouse yang berhubungan dengan dimensi layar.
Semakin tinggi posisi mouse pada layar, semakin tinggi pitch (nada) bunyi bip tersebut.
Semakin mouse ditempatkan ke kiri atau kanan pada layar, semakin ke kiri atau ke kanan pula bunyi bip yang dimainkan (diasumsikan bahwa pengguna memiliki speaker stereo atau headphone).

##### Brightness controls audio coordinates volume (Kecerahan layar mengontrol volume koordinat audio) {#toc143}

Jika kotak centang "Play audio coordinates when mouse moves" (Perdengarkan koordinat audio saat mouse bergerak) dicentang, dan kotak centang ini juga dicentang, maka volume suara bip koordinat audio akan ditentukan oleh seberapa cerah layar di bawah mouse. 
Pengaturan ini tidak dicentang secara default.

#### Review Cursor Settings (Pengaturan Kursor Tinjauan) {#toc144}

Pengaturan ini ada pada menu Preferences di bawah "Review Cursor...".  
Dialog ini memiliki beberapa opsi sebagai berikut: 

<!-- KC:setting -->

##### Follow System Focus (Ikuti Fokus Sistem) {#toc145}

Tuts: NVDA+7

Jika diaktifkan, review cursor (kursor tinjauan) akan selalu berada di dalam objek yang sama dengan fokus sistem saat ini kapan pun fokus berubah. 

<!-- KC:setting -->

##### Follow System Caret (Ikuti System Caret) {#toc146}

Tuts: NVDA+6

Jika diaktifkan, review cursor (kursor tinjauan) akan secara otomatis dipindahkan ke posisi system caret setiap kali system caret berpindah. 

##### Follow mouse cursor (Ikuti kursor mouse) {#toc147}

Jika diaktifkan, review cursor (kursor tinjauan) akan mengikuti mouse saat mouse bergerak.

##### Simple Review Mode (Mode Tinjauan Sederhana) {#toc148}

Jika diaktifkan, NVDA akan memfilter hierarki objek yang dapat dinavigasi dengan tidak menyertakan objek yang bukan merupakan kepentingan pengguna. Misalnya, objek yang tak tampak dan objek yang digunakan hanya untuk keperluan tata letak. 

Untuk mengaktifkan dan menonaktifkan mode tinjauan sederhana dari mana pun, silakan menetapkan custom gesture (gestur biasa) dengan menggunakan [dialog Input Gestures](#InputGestures).

#### Object Presentation Settings - Pengaturan Presentasi Objek (NVDA+control+o) {#toc149}

Pengaturan ini ada pada menu Preferences di bawah "Object Presentation..." 
Kotak dialog ini memiliki beberapa opsi sebagai berikut:

##### Report Tool Tips (Laporkan Saran tentang Alat) {#toc150}

Ini adalah sebuah kotak centang yang jika dicentang akan meminta NVDA untuk melaporkan saran tentang alat ketika saran tersebut muncul.
Terdapat banyak jendela dan control yang menunjukkan sebuah pesan kecil (atau saran tentang alat) ketika Anda memindahkan penunjuk mouse ke atasnya, atau kadang-kadang ketika Anda memindahkan fokus ke sana. 

##### Report Help Balloons (Laporkan Balon Help) {#toc151}

Kotak centang ini jika dicentang akan meminta NVDA untuk melaporkan Help Balloons jika balon tersebut muncul.
Help Balloons adalah seperti tool tip, tapi biasanya dalam ukuran yang lebih besar, dan berhubungan dengan system event, misalnya kabel jaringan yang diputus dari aliran listrik. Opsi ini juga dapat memberi peringatan tentang keamanan pada Windows. 

##### Report Object Shortcut Keys (Laporkan Tuts Pintasan Objek) {#toc152}

Ketika kotak centang ini dicentang, NVDA akan menyertakan tuts pintasan yang terhubung dengan objek atau control tertentu saat tuts pintasan tersebut dilaporkan.
Misalnya, menu File pada menu bar (bilah menu) memiliki tuts pintasan alt+f. 

##### Report object position information (Laporkan informasi posisi objek) {#toc153}

Opsi ini memungkinkan Anda untuk memilih apakah Anda ingin posisi objek (misalnya, 1 dari 4) dilaporkan saat bergerak ke objek berfokus atau navigasi objek.

##### Guess Object Position Information when unavailable (Tebak Informasi Posisi Objek jika tidak tersedia) {#toc154}

Jika pelaporan informasi posisi objek diaktifkan, opsi ini memungkinkan NVDA untuk menebak informasi posisi objek saat informasi ini tidak tersedia untuk control tertentu.

Jika diaktifkan, NVDA akan melaporkan informasi posisi untuk beberapa control lain, seperti menu dan toolbar. Namun informasi ini mungkin kurang akurat. 

##### Report Object descriptions (Laporkan keterangan tentang objek) {#toc155}

Hapus centang pada kotak centang ini jika Anda tidak ingin keterangan dilaporkan bersama dengan objek.

<!-- KC:setting -->

##### Progress bar output (Output bilah progress) {#toc156}

Tuts: NVDA+u

Opsi ini mengontrol cara NVDA melaporkan pembaruan bilah progress kepada Anda. 

Pengaturan ini memiliki beberapa opsi sebagai berikut: 

* Off: Bilah progress tidak akan dilaporkan saat berubah. 
* Speak (Laporkan):  Opsi ini meminta NVDA untuk melaporkan perubahan prosentase pada bilah progress. Setiap kali bilah progress berubah, NVDA akan melaporkan nilainya.
* Beep (Bip):  Opsi ini meminta NVDA untuk memperdengarkan bip setiap kali bilah progress berubah. Semakin tinggi nada bip, semakin dekat bilah progress ke titik selesai.
* Beep and speak (Bip dan laporkan):  Opsi ini meminta NVDA untuk memperdengarkan bunyi bip sekaligus melaporkan pembaruan pada bilah progress. 

##### Report background progress bars (Laporkan bilah progress di latar belakang) {#toc157}

Ini adalah opsi yang jika dicentang akan meminta NVDA untuk tetap melaporkan bilah progress, bahkan saat bilah progress tidak nampak di latar depan.
Jika Anda meminimalkan atau beralih dari jendela yang menampilkan bilah progress, NVDA akan tetap melacaknya, sehingga memungkinkan Anda untuk melakukan hal lain saat NVDA melacak bilah progress.

<!-- KC:setting -->

##### Report dynamic content changes (Laporkan perubahan konten dinamik) {#toc158}

Tuts: NVDA+5

Mengaktifkan dan menonaktifkan pemberitahuan adanya konten baru dalam objek tertentu, seperti terminals dan history control dalam program chat (percakapan). 

##### Play a sound when auto-suggestions appear (Putar suara saat saran otomatis muncul) {#toc159}

Ucapkan pengumuman tentang munculnya saran otomatis, dan jika diaktifkan, NVDA akan memutar suara untuk menunjukkan hal ini.
Saran otomatis adalah daftar entri yang disarankan berdasarkan teks yang dimasukkan ke dalam kolom edit dan dokumen tertentu.
Misalnya saat Anda memasukkan teks ke dalam kotak pencarian di menu Start di Windows Vista dan yang lebih baru, Windows akan menampilkan daftar saran berdasarkan pada apa yang Anda ketik.
Untuk beberapa bidang edit seperti bidang pencarian di berbagai aplikasi Windows 10, NVDA dapat memberi tahu Anda bahwa daftar saran telah muncul saat Anda mengetik teks.
Daftar saran otomatis akan ditutup begitu Anda pindah dari bidang edit, dan untuk beberapa bidang, NVDA dapat memberi tahu Anda tentang hal ini saat ini terjadi.

#### Input Composition Settings (Pengaturan Komposisi Input) {#toc160}

Dialog Input Composition Settings (Pengaturan Komposisi Input) dapat Anda temukan di bawah menu Preferences.
Dialog ini memungkinkan Anda untuk mengontrol cara NVDA melaporkan karakter Asia, seperti dengan metode input IME atau Text Service.
Perhatikanlah bahwa karena metode input sangat beragam berdasarkan fitur yang ada dan berdasarkan cara metode tersebut menyampaikan informasi, maka sangat penting bagi Anda untuk mengonfigurasi opsi-opsi ini secara berbeda-beda untuk setiap metode input agar Anda dapat mengetik dengan cara yang paling efisien.

##### Automatically report all available candidates (Laporkan secara otomatis semua kandidat yang ada) {#toc161}

Opsi ini, yang berada dalam posisi "on" secara default, memungkinkan Anda untuk memilih apakah semua kandidat yang tampak harus dilaporkan secara otomatis atau tidak, ketika daftar kandidat muncul atau halamannya diganti.
Opsi ini akan terasa bermanfaat jika Anda menggunakan metode input piktografik seperti Chinese New ChangJie atau Boshiami, karena Anda dapat secara otomatis mendengar semua simbol dan nomornya dan langsung memilih salah satunya.
Namun, untuk metode input fonetik seperti Chinese New Phonetic, mungkin akan lebih bermanfaat jika Anda menonaktifkan opsi ini, karena semua simbol akan terdengar sama, dan Anda akan harus menggunakan tuts panah untuk menavigasi masing-masing list item guna mendapatkan informasi lebih banyak dari deskripsi karakter untuk setiap kandidat.

##### Announce Selected Candidate (Laporkan Kandidat Terpilih) {#toc162}

Opsi ini, yang berada dalam posisi on secara default, memungkinkan Anda untuk memilih apakah NVDA harus mengumumkan kandidat yang terpilih ketika daftar kandidat muncul atau ketika pilihannya diganti.
Untuk metode input yang cara memilihnya dapat diganti dengan tuts panah (seperti Chinese New Phonetic), hal ini penting. Tapi untuk sebagian metode input lain, mungkin akan lebih efisien jika Anda mengetik dengan menonaktifkan opsi ini.
Perhatikanlah bahwa bahkan dengan opsi ini berada dalam posisi off, kursor tinjauan tetap akan ditempatkan pada kandidat terpilih, yang memungkinkan Anda untuk menggunakan navigasi/tinjauan objek guna membaca kandidat terpilih ini atau kandidat lain secara manual.

##### Always include short character descriptions for candidates (Selalu sertakan deskripsi pendek tentang karakter untuk kandidat) {#toc163}

Opsi ini, yang on secara default, memungkinkan Anda untuk memilih apakah NVDA harus memberikan deskripsi pendek untuk setiap karakter dalam kandidat atau tidak, baik ketika karakter itu dipilih atau ketika karakter itu dibaca secara otomatis saat daftar kandidat muncul. 
Perhatikanlah bahwa untuk bahasa lokal seperti bahasa Tionghoa, pemberitahuan deskripsi karakter ekstra untuk kandidat yang dipilih tidak dipengaruhi oleh opsi ini.
Opsi ini mungkin bermanfaat untuk metode input bahasa Korea dan Jepang. 

##### Report changes to the reading string (Laporkan perubahan pada string pembacaan) {#toc164}

Beberapa metode input seperti Chinese New Phonetic dan New ChangJie memiliki satu string pembacaan (kadang dikenal sebagai satu string prekomposisi).
Anda dapat memilih apakah NVDA perlu memberi tahu karakter baru yang sedang diketik pada string pembacaan dengan opsi ini atau tidak.
Opsi ini "on" secara default.
Perhatikanlah bahwa metode input yang lebih lama seperti Chinese ChangJie mungkin tidak menggunakan string pembacaan untuk memuat karakter prekomposisi, melainkan menggunakan string komposisi secara langsung. Harap melihat opsi berikutnya untuk mengonfigurasi pelaporan string komposisi.

##### Report changes to the composition string (Laporkan perubahan pada string komposisi) {#toc165}

Setelah bacaan atau data prekomposisi digabungkan ke dalam simbol piktografik yang valid, sebagian besar metode input menempatkan simbol ini ke dalam string komposisi untuk penyimpanan sementara bersama dengan simbol-simbol lain yang digabungkan, sebelum simbol-simbol itu akhirnya disisipkan ke dalam dokumen.
Opsi ini memungkinkan Anda untuk memilih apakah NVDA harus melaporkan simbol baru atau tidak saat simbol itu muncul di string komposisi.  
Opsi ini "on" secara default.

#### Browse Mode Settings - Pengaturan Mode Jelajah (NVDA+control+b) {#toc166}

Dialog Browse Mode Settings (Pengaturan Mode Jelajah) dapat Anda temukan di menu Preferences, di bawah "Browse mode...".

Dialog ini memiliki beberapa opsi sebagai berikut: 

##### Maximum Number of Characters on One Line (Jumlah Karakter Maksimum di Satu Baris) {#toc167}

Bidang ini mengatur panjang maksimum satu baris dalam mode jelajah (dalam karakter).  

##### Maximum Lines Per Page (Jumlah Baris Maksimum per Halaman) {#toc168}

Bidang ini mengatur jumlah baris yang akan Anda jelajahi saat menekan Page Up atau Page Down selama berada dalam mode jelajah.

<!-- KC:setting -->

##### Use screen layout (Gunakan tata letak layar) {#toc169}

Tuts: NVDA+v

Opsi ini memungkinkan Anda untuk memilih apakah konten dalam mode jelajah harus menempatkan konten seperti link (tautan) dan bidang lain di barisnya sendiri, atau apakah konten ini harus mempertahankannya dalam teks sebagaimana terlihat secara visual. Jika opsi ini diaktifkan, maka segala sesuatu akan tetap tampak sebagaimana biasanya. Tapi jika tidak diaktifkan, maka bidang-bidang akan ditempatkan di barisnya sendiri. 

##### Automatic Say All on page load (Baca Semua secara Otomatis saat membuka halaman) {#toc170}

Kotak centang ini mengaktifkan dan menonaktifkan pembacaan halaman secara otomatis setelah halaman itu dimuat di mode jelajah.  
Opsi ini aktif secara default.

##### Include layout tables (Sertakan tabel tata letak) {#toc171}

Opsi ini memengaruhi cara NVDA menangani tabel yang digunakan hanya untuk tujuan tata letak.
Jika diaktifkan, NVDA akan memperlakukan tabel-tabel ini sebagai tabel yang normal, dengan melaporkannya berdasarkan Pengaturan Pemformatan Dokumen dan menempatkannya dengan perintah navigasi cepat.
Jika tidak diaktifkan, tabel-tabel ini tidak akan dilaporkan ataupun ditemukan dengan navigasi cepat.
Namun, konten tabel masih akan disertakan sebagai teks normal. 
Opsi ini tidak diaktifkan secara default.

Untuk beralih memasukkan tabel tata letak dari mana saja, tetapkan isyarat khusus menggunakan [dialog Input Gestures](#InputGestures).

##### Configuring reporting of fields such as links and headings (Mengonfigurasi pelaporan bidang seperti tautan dan judul) {#toc172}

Silakan lihat opsi-opsi pada [dialog Document Formatting Settings (Pengaturan Pemformatan Dokumen)](#DocumentFormattingSettings) untuk mengonfigurasi bidang-bidang yang dilaporkan saat bernavigasi, seperti link (tautan), judul dan tabel.

##### Automatic focus mode for focus changes (Mode fokus otomatis untuk perubahan fokus) {#toc173}

This option allows focus mode to be invoked if focus changes.
Opsi ini memungkinkan Anda untuk menggunakan mode fokus jika fokus berubah. Sebagai contoh, saat berada di laman web, jika Anda menekan tab dan mendarat di satu formulir, jika opsi ini dicentang, mode fokus akan secara otomatis digunakan.

##### Automatic focus mode for caret movement (Mode fokus otomatis untuk pergerakan tanda sisipan) {#toc174}

Opsi ini, jika dicentang, akan memungkinkan NVDA untuk masuk dan meninggalkan mode fokus saat menggunakan tuts panah. 
Sebagai contoh, jika Anda menekan panah bawah ke laman web dan mendarat di satu kotak edit, NVDA akan secara otomatis membawa Anda masuk ke mode fokus. Jika  Anda menekan panah ke luar dari kotak edit, NVDA akan membawa Anda kembali ke mode jelajah.

##### Audio indication of Focus and Browse modes (Indikasi audio mode Fokus dan Jelajah) {#toc175}

Jika opsi ini diaktifkan, NVDA akan memperdengarkan suara khusus saat beralih antara mode jelajah dan mode fokus, alih-alih mengucapkan perubahan tersebut.

##### Trap non-command gestures from reaching the document (Tahan gestur non-perintah dari mencapai dokumen) {#toc176}

Diaktifkan secara default, opsi ini memungkinkan Anda untuk memilih apakah gestur (seperti menekan tuts) yang tidak menghasilkan perintah NVDA dan tidak menjadi tuts perintah secara umum harus ditahan agar tidak menuju dokumen yang sedang memiliki fokus saat ini, atau tidak.
Sebagai contoh, jika opsi ini diaktifkan, jika huruf j ditekan, gestur ini akan ditahan sehingga tidak dapat mencapai dokumen, meskipun ini bukan perintah navigasi cepat dan boleh jadi bukan perintah dalam aplikasi itu sendiri. 

#### Document Formatting Settings - Pengaturan Pemformatan Dokumen (NVDA+control+d) {#DocumentFormattingSettings}

Kotak dialog ini dapat Anda temukan di menu Preferences, di bawah "Document Formatting...".

Sebagian besar kotak centang dalam dialog ini adalah untuk mengonfigurasi tipe pemformatan yang Anda ingin untuk dilaporkan saat Anda menggerakkan kursor pada dokumen.
Sebagai contoh, jika Anda mencentang kotak centang Report Font Name (Laporkan Nama Font), setiap kali Anda menekan panah menuju teks dengan font yang berbeda, nama font itu akan disebutkan.

Opsi pemformatan dokumen dibagi ke dalam beberapa kelompok. 
Anda dapat mengonfigurasi pelaporan: 

* Font (Bentuk Huruf) 
 * Font Name (Nama font) 
 * Font size (Ukuran font) 
 * Font attributes (Atribut font) 
 * Emphasis (Penekanan)
 * Style
 * Colors (Warna) 
* Document information (Informasi dokumen) 
 * Comments (Komentar) 
 * Editor revisions (Revisi editor)
 * Spelling errors (Kesalahan eja) 
* Pages and spacing (Halaman dan pengaturan spasi) 
 * Page numbers (Nomor halaman) 
 * Line numbers (Nomor baris) 
 * Pelaporan indentasi baris [Off, Speech, Tones, Both Speech and Tones (Mati, Ucapan, Nada, Kedua Ucapan dan nada)](#lineIndentationOptions)
 * Paragraph indentation (Indentasi paragraf (mis. indentasi gantung, indentasi baris pertama))
 * Line spacing (single, double etc) (Spasi baris (tunggal, ganda, dll.)) 
 * Alignment (Perataan) 
* Table information (Informasi tabel) 
 * Tables (Tabel) 
 * Row/column headers (Judul baris/kolom) 
 * Koordinat sel 
 * Cell borders (Batas sel) (Off, Styles, Both Colors and Styles)
* Elements
 * Headings
 * Link (Tautan) 
 * Lists (Daftar)
 * Block quote (Blok kutipan) 
 * Landmarks
 * Frame (Bingkai) 
 * Clickable

Untuk mengaktifkan dan menonaktifkan pengaturan ini dari mana pun, silakan menetapkan custom gesture (gestur biasa) dengan menggunakan [dialog Input Gestures](#InputGestures).

##### Report formatting changes after the cursor (Laporkan perubahan pemformatan setelah kursor) {#toc178}

Jika diaktifkan, pengaturan ini akan meminta NVDA untuk mencoba dan mendeteksi semua perubahan pemformatan pada satu baris ketika NVDA melaporkannya, meskipun ini akan memperlambat kinerja NVDA.

Secara default, NVDA akan mendeteksi pemformatan pada posisi System Caret / Kursor Tinjauan, dan pada beberapa contoh mungkin mendeteksi pemformatan di sisa baris, jika hal ini tidak menyebabkan penurunan kinerja.  

Aktifkan opsi ini sambil melakukan proof reading (membaca) dokumen dalam aplikasi seperti Wordpad, di mana pemformatan menjadi hal yang penting. 

##### Line indentation reporting (Pelaporan indentasi baris) {#lineIndentationOptions}

Opsi ini memungkinkan Anda untuk mengonfigurasi cara pelaporan indentasi di awal baris.  
Report line indentasi (Laporkan indentasi baris) dengan kotak kombo memiliki empat opsi:

* Off: NVDA tidak akan memperlakukan indentasi secara khusus. 
* Speech (Pengucapan): Jika Speech dipilih, ketika jumlah indentasi berubah, NVDA akan mengatakan sesuatu seperti "twelve space" atau "four tab". 
* Tones: Jika Tones dipilih, ketika jumlah indentasi berubah, Tones akan menunjukkan jumlah perubahan dalam inden. 
Tone akan meningkat dalam pitch pada setiap satu spasi. Dan untuk satu tab, tone akan naik dalam pitch yang setara dengan 4 spasi. 
* Both Speech and Tones (Pengucapan dan Tones): Opsi ini membacakan indentasi dengan menggunakan kedua metode di atas. 

#### Windows 10 OCR Settings {#Win10OcrSettings}

This dialog can be accessed from the NVDA Preferences menu and allows you to configure [Windows 10 OCR](#Win10Ocr).

##### Recognition language (Bahasa pengenal) {#toc181}

Kotak kombo ini memungkinkan Anda memilih bahasa yang akan digunakan untuk pengenalan teks.

#### Speech Dictionaries (Kamus Pengucapan) {#toc182}

Menu Speech Dictionaries (Kamus Pengucapan) yang ditemukan di menu Preferences) berisi beberapa dialog yang memungkinkan Anda untuk mengelola cara NVDA mengucapkan kata atau frasa tertentu. 
Saat ini, terdapat tiga jenis kamus pengucapan yang berbeda. 
Yaitu:

* Default: instruksi (rules) dalam kamus ini memengaruhi semua pengucapan dalam NVDA. 
* Voice: instruksi (rules) dalam kamus ini memengaruhi pengucapan untuk suara synthesizer yang saat ini digunakan. 
* Temporary: instruksi (rules) dalam kamus ini memengaruhi semua pengucapan dalam NVDA, tapi hanya untuk sesi saat ini. Instruksi-instruksi ini bersifat sementara dan akan hilang jika NVDA di-restart. 

Anda perlu menetapkan custom gestures (gestur biasa) dengan menggunakan [dialog Input Gestures](#InputGestures) jika Anda ingin membuka salah satu dialog kamus ini dari mana pun. 

Semua dialog kamus memiliki satu daftar instruksi yang akan digunakan untuk memproses pengucapan.  
Dialog ini juga memiliki tombol Add (Tambahkan), Edit, dan Remove (Hapus).

Untuk menambahkan instruksi baru ke kamus, tekan tombol Add, dan isi bidang-bidang dalam kotak dialog yang muncul, lalu tekan Ok.
Anda akan melihat instruksi baru tersebut pada daftar instruksi.
Namun untuk memastikan bahwa instruksi Anda telah benar-benar tersimpan, pastikan Anda menekan Ok untuk keluar dari dialog kamus bersamaan dengan Anda selesai menambahkan/mengedit instruksi tersebut. 

Instruksi untuk kamus pengucapan NVDA memungkinkan Anda mengubah satu string karakter menjadi satu string karakter lain.
Salah satu contoh yang mudah adalah, Anda ingin NVDA mengucapkan kata "frog" setiap kali NVDA diperkirakan akan mengucapkan kata "bird".
Dalam dialog Add Rule (Tambahkan Instruksi), cara termudah untuk melakukan hal ini adalah dengan mengetikkan kata "bird" di bidang Pattern (Pola), dan kata "frog" di bidang Replacement (Penggantian).
Anda mungkin juga ingin mengetik keterangan tentang instruksi dalam bidang Comment (seperti: ubah "bird" menjadi "frog"). 

Bagaimanapun, kamus pengucapan NVDA lebih andal daripada metode penggantian kata secara sederhana.
Dialog Add Rule juga memiliki satu kotak centang yang menanyakan apakah Anda ingin instruksi tersebut menjadi case sensitive, artinya NVDA harus memperhatikan apakah karakter-karakternya adalah huruf kapital atau huruf kecil. 
Secara default, NVDA mengabaikan hal ini. 

Akhirnya, serangkaian tombol radio memungkinkan Anda untuk meminta kepada NVDA apakah pola Anda harus cocok di mana pun, atau hanya cocok jika penggantinya merupakan kata lengkap saja, atau haruskah diperlakukan sebagai "Regular expression" (Ekspresi Reguler). 
Mengatur pola agar cocok sebagai satu kata utuh berarti bahwa penggantian kata tersebut hanya akan dilakukan jika pola tersebut bukan merupakan bagian dari satu kata yang lebih panjang. Misalnya, satu karakter selain satu karakter alfanumerik atau satu garis bawah (atau tanpa karakter sama sekali) berada langsung sebelum ataupun sesudah pola.
Jadi, jika kita menggunakan contoh penggantian kata "bird" menjadi "frog" sebelum ini, jika Anda mengaturnya sebagai penggantian satu kata utuh, maka kata "birds" atau "bluebird" tidak akan cocok. 

Regular Expression adalah satu pola yang memiliki simbol-simbol khusus yang memungkinkan Anda untuk mencocokkan, misalnya lebih dari satu karakter pada satu waktu, atau mencocokkan angkanya saja, atau hurufnya saja.
Regular Expression tidak dibahas di dalam panduan pengguna ini. Namun terdapat banyak tutorial di web yang dapat memberikan informasi lebih lanjut tentang hal ini kepada Anda. 

#### Punctuation/Symbol Pronunciation (Pelafalan Tanda Baca/Simbol) {#SymbolPronunciation}

Dialog ini memungkinkan Anda untuk mengubah cara pelafalan tanda baca dan simbol-simbol lain, serta level tempat simbol tersebut diucapkan. 

The language for which symbol pronunciation is being edited will be shown in the dialog's title.
Bahasa untuk pelafalan simbol yang sedang diedit akan ditunjukkan pada judul dialog. Perhatikanlah bahwa dialog ini menerima opsi "Trust voice's language for processing symbols and characters" (Pastikan bahasa suara untuk memproses simbol dan karakter) yang ada di [dialog Voice Settings (Pengaturan Suara)](#VoiceSettings); misalnya, opsi ini menggunakan bahasa suara alih-alih pengaturan bahasa global NVDA, jika opsi ini diaktifkan. 

Untuk mengubah satu simbol, pertama-tama pilih simbol tersebut di daftar Symbols. 

* Bidang Replacement (Penggantian) memungkinkan Anda untuk mengubah teks yang akan diucapkan pada posisi simbol ini. 
* Dengan menggunakan bidang Level, Anda dapat menyesuaikan level simbol terendah ketika simbol ini diucapkan. 
* Bidang Send Actual Symbol to Synthesizer (Kirim Simbol Aktual ke Synthesizer) menyebutkan kapan simbol itu sendiri (kebalikan dari penggantian) harus dikirimkan ke synthesizer. 
Ini berguna jika simbol menyebabkan synthesizer berhenti sejenak atau mengubah infleksi suara. 
Contohnya, koma menyebabkan synthesizer berhenti sejenak. 
Terdapat tiga opsi: 
 * never (tidak pernah): Jangan pernah mengirim simbol aktual ke synthesizer. 
 * always (selalu): Selalu kirimkan simbol aktual ke synthesizer. 
 * only below symbols' level (hanya level simbol yang lebih rendah): Kirimkan simbol aktual hanya jika level simbol pengucapan yang dikonfigurasi lebih rendah daripada level yang diatur untuk simbol ini. 
 Contohnya, Anda mungkin menggunakan opsi ini agar satu simbol diucapkan penggantiannya pada level yang lebih tinggi tanpa jeda, sambil tetap ditandai oleh jeda pada level yang lebih rendah.

Anda dapat menambahkan simbol baru dengan menekan tombol Add. 
Pada dialog yang muncul, masukkan simbol dan tekan tombol OK. 
Lalu ubah bidang-bidang untuk simbol baru sebagaimana yang Anda lakukan untuk simbol-simbol lain. 

Anda dapat menghapus satu simbol yang telah Anda tambahkan sebelumnya dengan menekan tombol Remove. 

Setelah Anda selesai, tekan tombol OK untuk menyimpan perubahan atau tombol Cancel untuk mengabaikan perubahan. 

#### Input Gestures (Gestur Input) {#InputGestures}

Dalam dialog ini, Anda dapat menyesuaikan gestur input (tuts pada keyboard, tombol pada braille display, dll.) untuk perintah NVDA.

Hanya perintah yang dapat diaplikasikan dengan segera sebelum dialog dibuka yang akan diperlihatkan.
 Misalnya, jika Anda ingin menyesuaikan perintah yang berhubungan dengan mode jelajah, Anda harus membuka dialog Input Gestures saat Anda berada di mode jelajah. 

Tiga perintah dalam dialog ini merupakan perintah NVDA yang dapat diaplikasikan yang dikelompokkan berdasarkan kategori. 
Anda dapat memfilternya dengan memasukkan satu atau beberapa kata dari nama perintah ke dalam kotak edit Filter by (Filter berdasarkan) dalam susunan bagaimanapun. 
Gestur apa pun yang berhubungan dengan satu perintah dimasukkan ke dalam daftar di bawah perintah tersebut. 

Untuk menambahkan satu gestur input ke perintah, pilih satu perintah dan tekan tombol Add. 
Lalu lakukan gestur input yang ingin Anda hubungkan. Misalnya, tekan satu tuts pada keyboard atau satu tombol pada braille display. 
Sering kali, satu gestur dapat diinterpretasikan dalam beberapa cara. 
Misalnya, jika Anda menekan satu tuts di keyboard, Anda mungkin ingin tuts ini hanya berpengaruh pada tata letak keyboard saat ini (misalnya desktop atau laptop), atau Anda mungkin ingin tuts ini berpengaruh pada semua tata letak. 
Dalam kasus ini, sebuah menu akan muncul dan mengizinkan Anda untuk memilih opsi yang diinginkan. 

Untuk menghilangkan satu gestur dari satu perintah, pilih gestur yang ingin dihilangkan dan tekan tombol Remove.

Setelah Anda selesai membuat perubahan, tekan tombol OK untuk menyimpan perubahan atau tombol Cancel untuk mengabaikan perubahan. 

### Menyimpan dan Membuka Kembali Konfigurasi {#toc185}

Secara default, NVDA akan menyimpan secara otomatis pengaturan yang Anda buat pada saat Anda keluar dari NVDA. 
Namun perhatikanlah bahwa opsi ini dapat diubah di bawah General Options (Opsi Umum) pada menu Preferences. 
Untuk menyimpan pengaturan secara manual setiap saat, pilih item Save configuration (Simpan konfigurasi) pada menu NVDA. 

Jika Anda pernah membuat kesalahan saat melakukan pengaturan dan perlu kembali ke pengaturan yang telah disimpan, pilih item "revert to saved configuration" (kembali ke konfigurasi tersimpan) pada menu NVDA.
Anda juga dapat me-reset pengaturan ke default pabrik orisinal dengan memilih Reset Configuration to Factory Defaults (Atur Ulang Konfigurasi ke Default Pabrik) yang juga dapat ditemukan pada menu NVDA. 

Perintah tuts NVDA berikut ini juga bermanfaat:
<!-- KC:beginInclude -->

| Nama |Tuts Desktop |Tuts Laptop |Keterangan|
|---|---|---|---|
|Save configuration (Simpan konfigurasi) |NVDA+control+c |NVDA+control+c |Menyimpan konfigurasi Anda saat ini agar tidak hilang saat Anda keluar dari NVDA|
|Revert configuration (Kembalikan konfigurasi) |NVDA+control+r |NVDA+control+r |Menekan satu kali akan mengatur ulang konfigurasi Anda ke keadaan saat Anda terakhir kali menyimpannya. Menekan tiga kali akan me-reset-nya kembali ke default pabrik.|

<!-- KC:endInclude -->

### Configuration Profiles (Profil Konfigurasi) {#toc186}

Kadang-kadang Anda mungkin ingin memiliki pengaturan yang berbeda untuk situasi yang berbeda.
Misalnya, Anda mungkin ingin mengaktifkan pelaporan indentasi sembari mengaktifkan pengeditan atau pelaporan atribut font saat Anda melakukan proofreading. 
NVDA memungkinkan Anda untuk melakukan ini dengan profil konfigurasi. 

Configuration profile hanya memuat pengaturan-pengaturan yang diubah ketika profil diedit.
Sebagian besar pengaturan dapat diubah di Configuration Profiles, kecuali pengaturan di dialog General Settings (Pengaturan Umum), yang berlaku untuk keseluruhan NVDA.

Configuration Profiles dapat diaktifkan secara manual.
Configuration Profiles juga dapat diaktifkan secara otomatis dengan pemicu (trigger), antara lain dengan mengalihkan ke aplikasi tertentu. 

#### Manajemen Dasar {#toc187}

Anda dapat mengelola profil konfigurasi dengan cara memilih "Configuration Profiles" pada menu NVDA. 
Anda juga dapat melakukan ini dengan menggunakan perintah tuts:
<!-- KC:beginInclude -->

* NVDA+control+p: Tampilkan dialog Configuration Profiles. 

<!-- KC:endInclude -->

Kontrol pertama dalam dialog ini adalah Profile List (Daftar Profil). Anda dapat memilih salah satu profil yang tersedia di situ. 
Saat Anda membuka dialog, profil yang sedang Anda edit telah dipilih. 
Informasi tambahan juga ditampilkan untuk profil yang aktif, yang menunjukkan apakah profil itu diaktifkan secara manual, dipicu dan/atau diedit. 

Untuk memberi nama baru atau menghapus satu profil, tekan tombol Rename atau Delete. 

Tekan tombol Close untuk menutup dialog tersebut. 

#### Membuat Profil {#toc188}

Untuk membuat profil, tekan tombol New.

Dalam dialog New Profile (Profil Baru), Anda dapat memasukkan satu nama untuk dijadikan profil.
Anda juga dapat memilih cara profil tersebut digunakan.
Jika Anda hanya ingin mengaktifkan profil secara manual, pilih Manual Activation (Aktivasi Manual), yang merupakan opsi default-nya.
Jika tidak, pilih satu trigger (pemicu) yang akan mengaktifkan profil ini secara otomatis.
Untuk memudahkan Anda, jika Anda belum memasukkan satu nama untuk profil, memilih trigger akan membuat nama profil terisi sesuai nama trigger tersebut.
Lihat [di bawah ini](#ConfigProfileTriggers) untuk informasi lebih lanjut mengenai trigger.

Menekan OK akan menciptakan profil dan menutup dialog Configuration Profiles sehingga Anda dapat mengeditnya. 

#### Manual Activation (Aktivasi Manual) {#ConfigProfileManual}

Anda dapat mengaktifkan profil secara manual dengan memilih satu profil dan menekan tombol Manual Activation. 
Setelah diaktifkan, profil-profil lain tetap dapat diaktifkan oleh trigger (pemicu), namun pengaturan apa pun di profil yang diaktifkan secara manual akan menimpa profil-profil lain tersebut. 
Misalnya, jika satu profil dipicu untuk aplikasi saat ini dan pelaporan link (tautan) diaktifkan di profil tersebut tapi dinonaktifkan di profil yang diaktifkan secara manual, maka link tidak akan dilaporkan. 
However, if you have changed the voice in the triggered profile but have never changed it in the manually activated profile, the voice from the triggered profile will be used. Namun jika Anda telah mengubah suara pada profil yang dipicu (triggered) tapi belum pernah mengubah suara di profil yang diaktifkan secara manual, maka suara dari profil yang dipicu yang akan digunakan.
Pengaturan apa pun yang Anda ubah akan disimpan di profil yang diaktifkan secara manual.   
Untuk menonaktifkan profil yang diaktifkan secara manual, pilih di dialog Configuration Profiles (Profil Konfigurasi) dan tekan tombol Manual Deactivate (Deaktivasi Manual).

#### Triggers (Pemicu) {#ConfigProfileTriggers}

Menekan tombol Triggers (Pemicu) pada dialog Configuration Profiles (Profil Konfigurasi) memungkinkan Anda untuk mengubah profil yang harus diaktifkan secara otomatis untuk berbagai trigger. 

Triggers List (Daftar Pemicu) menampilkan trigger yang tersedia, yaitu: 

* Current application (Aplikasi saat ini): Terpicu ketika Anda beralih ke aplikasi saat ini. 
* Say all (Baca semua): Terpicu ketika membaca dengan perintah Say All. 

Untuk mengubah profil yang harus diaktifkan secara otomatis untuk satu trigger, pilih trigger lalu pilih profil yang diinginkan dari Profile List (Daftar Profil). 
Anda dapat memilih (normal configuration) jika Anda tidak ingin menggunakan satu profil. 

Tekan tombol Close untuk kembali ke dialog Configuration Profiles. 

#### Mengedit Profil {#toc191}

Jika Anda telah mengaktifkan profil secara manual, pengaturan apa pun yang Anda ubah akan disimpan di profil tersebut. 
Jika tidak, pengaturan apa pun yang Anda ubah akan disimpan di profil yang paling baru dipicu. 
Misalnya, jika Anda telah menghubungkan satu profil dengan aplikasi Notepad dan Anda beralih ke Notepad, pengaturan apa pun yang diubah akan disimpan di profil tersebut. 
Pada prinsipnya, jika tidak ada profil yang diaktifkan secara manual ataupun dipicu, pengaturan apa pun yang Anda ubah akan disimpan di konfigurasi normal Anda. 

Untuk mengedit profil yang dihubungkan dengan Say All (Baca Semua), Anda harus [mengaktifkan secara manual](#ConfigProfileManual) profil tersebut. 

#### Menonaktifkan Triggers untuk Sementara {#toc192}

Kadang-kadang, kita perlu menonaktifkan semua trigger (pemicu) untuk sementara. 
Misalnya, Anda mungkin ingin mengedit profil yang diaktifkan secara manual atau konfigurasi normal Anda tanpa intervensi dari profil yang dipicu. 
Anda dapat melakukan ini dengan mengklik kotak centang Temporarily Disable All Triggers (Menonaktifkan Semua Trigger untuk Sementara) di dialog Configuration Profiles (Profil Konfigurasi). 

### Lokasi File Konfigurasi {#toc193}

Versi portabel NVDA menyimpan semua pengaturan, custom appModules (appModules biasa) dan custom driver (driver biasa) dalam satu direktori yang disebut userConfig, di dalam direktori NVDA. 

Versi install NVDA menyimpan semua pengaturan, custom appModules (appModules biasa) dan custom driver (driver biasa) dalam satu direktori khusus NVDA yang terletak di profil pengguna Windows Anda.
Ini berarti bahwa setiap pengguna pada sistem dapat memiliki pengaturan NVDA masing-masing.  
Untuk sampai di direktori pengaturan versi install NVDA, pada Start Menu, pilih Programs -> NVDA -> Explore user configuration directory (Jelajahi direktori konfigurasi pengguna).

Pengaturan untuk NVDA saat dijalankan di layar logon atau layar UAC akan disimpan di direktori systemConfig di dalam direktori instalasi NVDA. 
Biasanya, konfigurasi ini tidak boleh disentuh. 
Untuk mengubah konfigurasi NVDA pada layar logon/UAC, lakukan konfigurasi NVDA sebagaimana Anda inginkan sambil log in ke Windows, simpan konfigurasi, dan tekan tombol "Use currently saved settings on the logon and other secure screens" (Gunakan pengaturan yang disimpan saat ini pada layar log on dan layar keamanan lain) pada dialog General Settings (Pengaturan Umum).

## Extra Tools (Alat Ekstra) {#toc194}
### Log Viewer (Penampil Log) {#toc195}

Log viewer (Penampil Log) yang dapat ditemukan di bawah Tools (Alat) pada menu NVDA, memungkinkan Anda untuk melihat semua logging output yang ada sejak pertama kali Anda memulai NVDA sampai saat ini. 

Selain membaca konten, Anda juga dapat menyimpan salinan log file, atau me-refresh viewer agar menunjukkan output terkini sejak Log Viewer dibuka. 
Tindakan-tindakan ini tersedia di bawah menu Log viewer. 

### Speech Viewer (Penampil Ucapan) {#toc196}

Untuk pengembang software nontunanetra atau mereka yang mendemonstrasikan NVDA kepada orang berpenglihatan, tersedia jendela melayang yang memungkinkan Anda untuk melihat semua teks yang diucapkan NVDA saat ini. 

Untuk mengaktifkan speech viewer, centang item menu Speech Viewer di bawah Tools (Alat) pada menu NVDA. 
Hapus centang pada item menu untuk menonaktifkannya. 

Jendela speech viewer memiliki satu kotak centang yang berlabel "Show speech viewer on startup" (Tampilkan speech viewer saat startup). 
Jika dicentang, speech viewer akan terbuka ketika Anda memulai NVDA. 
Jendela speech viewer akan selalu berusaha membuka kembali dengan dimensi dan lokasi yang sama dengan saat jendela tersebut ditutup. 

Selama diaktifkan, speech viewer akan terus-menerus membuat pembaruan untuk menampilkan teks terkini yang diucapkan. 
Namun jika Anda mengklik atau fokus di dalam viewer, NVDA untuk sementara akan berhenti memperbarui teks sehingga Anda dapat dengan mudah memilih atau menyalin konten yang ada. 

Untuk mengaktifkan dan menonaktifkan speech viewer dari mana pun, silakan menetapkan custom gesture (gestur biasa) dengan menggunakan [dialog Input Gestures](#InputGestures).

### Add-ons Manager (Pengelola Add-ons) {#toc197}

Add-ons Manager (Pengelola Add-ons) diakses dengan memilih Manage add-ons (Kelola add-ons) di bawah Tools (Alat) pada menu NVDA; ini memungkinkan Anda untuk meng-install, meng-uninstall, mengaktifkan dan menonaktifkan paket add-on untuk NVDA. 
Paket ini disediakan oleh komunitas dan berisi kode custom yang dapat menambah atau mengubah fitur-fitur NVDA atau bahkan menyediakan dukungan untuk braille display atau speech synthesizer tambahan. 

Add-ons Manager berisi satu daftar yang menampilkan semua add-on yang saat ini terpasang pada konfigurasi pengguna NVDA Anda.  
Nama paket, status, versi dan penulisnya ditampilkan untuk setiap add-on, meskipun informasi lebih lanjut seperti deskripsi dan URL dapat dilihat dengan memilih add-on dan menekan tombol About add-on (Tentang add-on). 
Jika bantuan tersedia untuk add-on yang dipilih, Anda dapat mengaksesnya dengan menekan tombol Add-on help.

Untuk menjelajah dan mengunduh add-on yang tersedia secara online, tekan tombol Get add-ons (Dapatkan add-on). 
Tombol ini akan membuka [halaman Add-on NVDA](https://addons.nvda-project.org/).
Jika NVDA telah dipasang dan berjalan di sistem Anda, Anda dapat membuka add-on secara langsung dari browser untuk memulai proses instalasi sebagaimana dijelaskan di bawah ini.
 Jika belum, simpan paket add-on dan ikuti petunjuk di bawah ini. 

Untuk meng-install Add-on yang sebelumnya telah Anda dapatkan, tekan tombol Install. 
Ini memungkinkan Anda untuk menjelajah paket add-on (.nvda-addon file) di suatu tempat pada komputer atau jaringan Anda. 
Begitu Anda menekan Open, proses instalasi akan dimulai. 

Ketika add-on akan di-install, NVDA akan terlebih dulu bertanya untuk mengonfirmasi apakah Anda benar-benar ingin meng-install add-on. 
Karena fungsionalitas add-on tidak terbatas hanya untuk NVDA, yang secara teori termasuk juga mengakses data pribadi Anda atau bahkan sistem keseluruhan jika NVDA adalah salinan yang terpasang, maka sangat penting bagi Anda untuk hanya meng-install add-on dari sumber yang Anda percayai. 
Setelah add-on di-install, NVDA harus di-restart agar add-on dapat dijalankan. 
Sampai Anda melakukan hal ini, status "install" akan muncul untuk menunjukkan add-on tersebut pada daftar. 

Untuk menghapus satu add-on, pilih add-on tersebut dari daftar dan tekan tombol Remove. 
NVDA akan bertanya apakah Anda benar-benar ingin menghapusnya. 
Sebagaimana halnya saat meng-install, NVDA harus di-restart agar add-on dapat dihapus sepenuhnya. 
Sampai Anda melakukan hal ini, status "remove" akan muncul untuk menunjukkan add-on tersebut pada daftar. 

Untuk menonaktifkan satu add-on, tekan tombol Disable. 
Untuk mengaktifkan add-on yang sebelumnya tidak aktif, tekan tombol Enable. 
Anda dapat menonaktifkan satu add-on jika status add-on menunjukkan add-on tersebut sedang berjalan atau diaktifkan. Atau aktifkan jika add-on tersebut dihentikan atau dinonaktifkan.  
Setiap kali Anda menekan tombol Enable/Disable (Aktifkan/Nonaktifkan), status add-on akan berganti untuk menunjukkan apa yang akan terjadi saat NVDA di-restart. 
Seperti ketika Anda meng-install atau menghapus add-on, Anda perlu me-restart NVDA agar perubahan tersebut berlaku.

Fitur Manager juga memiliki tombol Close untuk menutup dialog. 
Jika Anda telah meng-install, menghapus atau mengubah status suatu add-on, NVDA akan menanyakan apakah Anda ingin melakukan restart agar perubahan tersebut dapat berlaku. 

Di masa lalu, Anda dapat memperluas fungsionalitas NVDA dengan menyalin plugin dan driver tersendiri pada direktori User Configuration (Konfigurasi Pengguna) NVDA Anda. 
Meskipun versi NVDA ini mungkin masih dapat membukanya, plugin dan driver ini tidak akan ditampilkan pada Add-on Manager. 
Cara terbaik adalah menghapus file-file ini dari konfigurasi Anda dan meng-install add-on yang sesuai jika ada. 

Untuk mengakses Add-ons Manager dari mana pun, silakan menetapkan custom gesture (gestur biasa) dengan menggunakan [dialog Input Gestures (Gestur Input)](#InputGestures).

### Python Console (Konsol Python) {#toc198}

Python Console (Konsol Python) NVDA yang berada di bawah Tools (Alat) pada menu NVDA adalah alat pengembangan yang berguna untuk melakukan pencarian dan pengurangan kerusakan program (debugging), pemeriksaan umum internal NVDA atau pemeriksaan hierarki aksesibilitas dari suatu aplikasi. 
Untuk informasi lebih lanjut, silakan lihat Panduan Pengembang yang tersedia di bagian [Pengembangan situs web NVDA](https://www.nvaccess.org/files/nvda/documentation/developerGuide.html).

### Reload plugins (Membuka ulang plugin) {#toc199}

Setelah diaktifkan, item ini akan membuka ulang modul aplikasi dan plugin global tanpa me-restart NVDA. Hal ini berguna untuk para pengembang. 

## Speech Synthesizer yang Didukung {#SupportedSpeechSynths}

Bagian ini memuat informasi tentang speech synthesizer yang didukung oleh NVDA. 
Untuk informasi lebih jauh tentang synthesizer, baik komersial maupun gratis, yang dapat Anda beli dan unduh untuk digunakan bersama NVDA, silakan lihat di [laman tambahan suara](https://github.com/nvaccess/nvda/wiki/ExtraVoices).

### eSpeak NG {#toc201}

Synthesizer [eSpeak NG](https://github.com/espeak-ng/espeak-ng) disatukan secara langsung ke dalam NVDA dan tidak membutuhkan driver atau komponen khusus lain untuk instalasi. 
NVDA di-start dengan menggunakan eSpeak NG secara default. 
Karena synthesizer ini disatukan ke dalam NVDA, ini adalah pilihan yang sangat baik saat Anda menjalankan NVDA tanpa USB thumb drive pada sistem lain. 

Setiap suara yang hadir bersama eSpeak NG berbicara dalam bahasa yang berbeda. 
Terdapat lebih dari 43 bahasa yng didukung oleh eSpeak NG.

Terdapat juga berbagai varian yang dapat dipilih untuk mengubah bunyi pada suara. 

### Microsoft Speech API versi 4 (SAPI 4) {#toc202}

SAPI 4 adalah standar Microsoft yang lebih awal untuk speech synthesizer software. 
NVDA masih mendukung versi ini bagi pengguna yang telah memasang synthesizer SAPI 4. 
Namun Microsoft tidak lagi mendukung versi ini, dan komponen yang diperlukan tidak lagi disediakan oleh Microsoft. 

Saat menggunakan synthesizer ini bersama NVDA, suara-suara yang tersedia (yang diakses dari [dialog Voice Settings (Pengaturan Suara)](#VoiceSettings) atau oleh [Synth Settings Ring (Ring Pengaturan Synth)](#SynthSettingsRing)) akan berisi semua suara dari semua mesin SAPI 4 yang terpasang dalam sistem Anda. 

### Microsoft Speech API versi 5 (SAPI 5) {#toc203}

SAPI 5 adalah standar Microsoft untuk speech synthesizer software. 
Sebagian besar speech synthesizer yang mengikuti standar ini dapat dibeli atau diunduh secara gratis dari berbagai perusahaan dan situs web, meskipun sistem Anda mungkin telah dilengkapi setidaknya oleh suara SAPI 5 yang telah dipasang sebelumnya. 
Saat menggunakan synthesizer ini bersama NVDA, suara-suara yang tersedia (yang diakses dari [dialog Voice Settings (Pengaturan Suara)](#VoiceSettings) atau oleh [Synth Settings Ring (Ring Pengaturan Synth)](#SynthSettingsRing)) akan berisi semua suara dari semua mesin SAPI 5 yang terpasang dalam sistem Anda.

### Microsoft Speech Platform {#toc204}

Microsoft Speech Platform menyediakan suara untuk banyak bahasa yang biasa digunakan dalam pengembangan aplikasi speech (pengucapan) berbasis server. 
Suara-suara ini juga dapat digunakan bersama NVDA. 

Untuk menggunakan suara-suara ini, Anda perlu memasang dua komponen: 

* Microsoft Speech Platform - Runtime (Versi 11) , x86: http://www.microsoft.com/download/en/details.aspx?id=27225
* Microsoft Speech Platform - Runtime Languages (Versi 11): http://www.microsoft.com/download/en/details.aspx?id=27224
 * Laman ini memuat banyak file, baik untuk speech recognition (pengenalan ucapan) maupun text-to-speech (teks ke ucapan). 
 Pilih file yang mengandung data TTS untuk bahasa/suara yang diinginkan.  
 Misalnya, file MSSpeech_TTS_en-US_ZiraPro.msi adalah file dengan suara berdialek Inggris-Amerika.

### Windows OneCore Voices {#toc205}

Windows 10 menyertakan suara baru yang dikenal sebagai "OneCore" atau suara "mobile (ponsel)".
Suara disediakan untuk banyak bahasa, dan lebih responsif daripada suara Microsoft yang tersedia menggunakan Microsoft Speech API versi 5.

Silakan lihat artikel Microsoft ini untuk daftar suara dan instruksi yang ada untuk menginstal: https://support.microsoft.com/en-us/help/22797/windows-10-narrator-tts-voices

Perlu diketahui bahwa rate kecepatan yang tersedia pada Narator saat ini tidak tersedia dengan NVDA.
Selain itu, kecepatan yang Anda pilih di Setelan Windows memengaruhi pengaturan kecepatan di NVDA.
Ini adalah masalah yang tidak dapat kami selesaikan tanpa perubahan pada Windows.
Kami berharap bahwa ini akan dibahas dalam update Windows masa depan.

### Audiologic Tts3 {#toc206}

Ini adalah speech synthesizer komersial khusus untuk bahasa Italia. 
Synthesizer ini harus sudah dipasang di sistem Anda agar dapat digunakan bersama NVDA. 
Untuk informasi lebih lanjut, silakan kunjungi situs web Audiologic di [www.audiologic.it](http://www.audiologic.it).

Synthesizer ini tidak mendukung [fungsionalitas pengejaan](#VoiceSpellingFunctionality).

### Nuance Vocalizer for NVDA {#toc207}

Nuance Vocalizer adalah voice synthesizer komersial berkualitas tinggi yang dikembangkan oleh Nuance Communications, Inc. dan dikemas khusus untuk NVDA oleh Tiflotecnia, Lda. 
Synthesizer ini menyediakan 50 suara berbeda yang dapat Anda install, dan berbicara dalam lebih dari 30 bahasa. 
Semua komponen synthesizer dan suara dibundel dalam paket add-on, yang memungkinkan Anda untuk menggunakan secara penuh salinan NVDA yang portabel. 

Anda dapat memperoleh informasi lebih jauh tentang Nuance Vocalizer for NVDA dan cara membelinya di situs web [www.vocalizer-nvda.com](http://www.vocalizer-nvda.com/).
Satu persen hasil penjualan produk ini akan didonasikan ke NV Access guna mendanai pengembangan NVDA Screen Reader.

## Braille Display yang Didukung {#SupportedBrailleDisplays}

Bagian ini memuat informasi tentang tipe-tipe braille display yang didukung oleh NVDA. 

### Freedom Scientific Focus/PAC Mate Series {#toc209}

Semua braille display Focus dan PAC Mate dari [Freedom Scientific](http://www.freedomscientific.com/) didukung jika terkoneksi via USB atau bluetooth.
Driver braille display Freedom Scientific harus sudah dipasang di sistem Anda.
Jika Anda belum memilikinya, Anda dapat memperolehnya di http://www2.freedomscientific.com/downloads/focus-40-blue/focus-40-14-blue-downloads.asp.
Meskipun laman ini hanya menyebut display Focus Blue, driver-nya mendukung semua display Freedom Scientific Focus dan Pacmate. 
Meski sistem Anda menjalankan Windows 64 bit dan driver telah di-install oleh pembaca layar lain, Anda mungkin tetap perlu meng-install driver dari link (tautan) ini, karena file-file yang disyaratkan oleh NVDA mungkin tidak di-install oleh pembaca layar lain.

Secara default, NVDA dapat mendeteksi dan terhubung secara otomatis ke display, baik melalui USB ataupun bluetooth. 
Namun, saat mengonfigurasi display, Anda dapat secara eksplisit memilih port "USB" atau "Bluetooth" untuk membatasi tipe koneksi yang digunakan. 
Ini mungkin berguna jika Anda ingin menghubungkan focus display ke NVDA dengan menggunakan bluetooth, sambil mengisi daya dengan menggunakan USB power dari komputer Anda. 

Berikut adalah penggunaan tuts untuk mengoperasikan braille display ini dengan NVDA. 
Silakan lihat instruksi penggunaan braille display untuk mendapatkan penjelasan di mana posisi tuts-tuts ini. 
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |topRouting1 (sel pertama pada display)|
|Scroll braille display forward (Gulir braille display ke depan) |topRouting20/40/80 (sel terakhir pada display)|
|Scroll braille display back (Gulir braille display ke belakang) |leftAdvanceBar|
|Scroll braille display forward (Gulir braille display ke depan) |rightAdvanceBar|
|Toggle braille tethered to (Men-toggle braille display yang ditambatkan ke) |leftGDFButton+rightGDFButton|
|Toggle left wiz wheel action (Men-toggle tindakan wiz wheel kiri) |leftWizWheelPress|
|Move back using left wiz wheel action (Pindah ke belakang menggunakan tindakan wiz wheel kiri) |leftWizWheelUp|
|Move forward using left wiz wheel action (Pindah ke depan menggunakan tindakan wiz wheel kiri) |leftWizWheelDown|
|Toggle right wiz wheel action (Men-toggle tindakan wiz wheel kanan) |rightWizWheelPress|
|Move back using right wiz wheel action (Pindah ke belakang menggunakan tindakan wiz wheel kanan) |rightWizWheelUp|
|Move forward using right wiz wheel action (Pindah ke depan menggunakan tindakan wiz wheel kanan) |rightWizWheelDown|
|Route to braille cell (Rute ke sel braille) |routing|
|shift+tab key (shift + tuts tab) |brailleSpaceBar+dot1+dot2|
|tab key (tuts tab) |brailleSpaceBar+dot4+dot5|
|upArrow key (tuts panah atas) |brailleSpaceBar+dot1|
|downArrow key (tuts panah bawah) |brailleSpaceBar+dot4|
|control+leftArrow key (control+ tuts panah kiri) |brailleSpaceBar+dot2|
|control+rightArrow key (control+ tuts panah kanan) |brailleSpaceBar+dot5|
|leftArrow (panah kiri) |brailleSpaceBar+dot3|
|rightArrow key (tuts panah kanan) |brailleSpaceBar+dot6|
|home key (tuts Home) |brailleSpaceBar+dot1+dot3|
|end key (tuts End) |brailleSpaceBar+dot4+dot6|
|control+home key (control+ tuts Home) |brailleSpaceBar+dot1+dot2+dot3|
|control+end key (control+ tuts End) |brailleSpaceBar+dot4+dot5+dot6|
|alt key (tuts Alt) |brailleSpaceBar+dot1+dot3+dot4|
|alt+tab key (alt + tuts tab) |brailleSpaceBar+dot2+dot3+dot4+dot5|
|escape key (tuts Escape) |brailleSpaceBar+dot1+dot5|
|windows key (tuts Windows) |brailleSpaceBar+dot2+dot4+dot5+dot6|
|space key (tuts space) |brailleSpaceBar|
|windows+d key (minimize all applications) - Windows+tuts d (minimalkan semua aplikasi) |brailleSpaceBar+dot1+dot2+dot3+dot4+dot5+dot6|
|Report Current Line (Laporkan Baris Saat Ini) |brailleSpaceBar+dot1+dot4|
|NVDA Menu (Menu NVDA) |brailleSpaceBar+dot1+dot3+dot4+dot5|

Untuk model Focus yang lebih baru yang memiliki tuts rocker bar (focus 40, focus 80 dan focus blue):

| Nama |Tuts|
|---|---|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |leftRockerBarUp, rightRockerBarUp|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |leftRockerBarDown, rightRockerBarDown|

Hanya untuk Focus 80: 

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |leftBumperBarUp, rightBumperBarUp|
|Scroll braille display forward (Gulir braille display ke depan) |leftBumperBarDown, rightBumperBarDown|

<!-- KC:endInclude -->

### Optelec ALVA BC640/680 {#toc210}

Braille display ALVA BC640 dan BC680 dari [Optelec](http://www.optelec.com/) didukung saat terkoneksi via USB atau bluetooth. 
Anda tidak perlu meng-install driver khusus untuk menggunakan display ini. 
Cukup sambungkan display dan lakukan konfigurasi NVDA untuk menggunakannya. 

Kedua display ini memiliki keyboard braille dan dapat menerjemahkan dari braille ke teks. 
Oleh karena itu, pengaturan tabel input braille NVDA tidaklah relevan. 

Berikut ini adalah penggunaan tuts untuk display dengan NVDA. 
Silakan lihat instruksi penggunaan display untuk mendapatkan penjelasan di mana posisi tuts-tuts ini. 
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |t1 or etouch1|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |t2|
|Move to current focus (Pindah ke fokus saat ini) |t3|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |t4|
|Scroll braille display forward (Gulir braille display ke depan) |t5 or etouch3|
|Route to braille cell (Rute ke sel braille) |routing|
|Move to top line in review (Pindah ke baris teratas dalam tinjauan) |t1+t2|
|Move to bottom line in review (Pindah ke baris terbawah dalam tinjauan) |t4+t5|
|Toggle braille tethered to (Men-toggle braille display yang ditambatkan ke) |t1+t3|
|Report title (Laporkan judul) |etouch2|
|Report status bar (Laporkan bilah status) |etouch4|
|shift+tab key (shift+tuts tab) |sp1|
|alt key (tuts Alt) |sp2|
|escape key (tuts Escape) |sp3|
|tab key (tuts tab) |sp4|
|upArrow key (tuts panah atas) |spUp|
|downArrow key (tuts panah bawah) |spDown|
|leftArrow key (tuts panah kiri) |spLeft|
|rightArrow key (tuts panah kanan) |spRight|
|enter key (tuts Enter) |spEnter|
|Report date/time (Laporkan tanggal/waktu) |sp1+sp2|
|NVDA Menu (Menu NVDA) |sp1+sp3|
|windows+d key (minimize all applications) - Windows+tuts d (minimalkan semua aplikasi) |sp1+sp4|
|windows+b key (focus system tray) - Windows+ tuts b (baki sistem fokus) |sp3+sp4|
|windows key (tuts Windows) |sp2+sp3|
|alt+tab key (alt + tuts tab) |sp2+sp4|
|control+home key (control+ tuts Home) |t3+spUp|
|control+end key (control+ tuts End) |t3+spDown|
|home key (tuts Home) |t3+spLeft|
|end key (tuts End) |t3+spRight|

<!-- KC:endInclude -->

### Braille Display dari Handy Tech {#toc211}

NVDA mendukung semua braille display dari [Handy Tech](http://www.handytech.de/) saat dihubungkan via USB atau bluetooth. 
Untuk display USB versi yang lebih lama, Anda perlu meng-install driver USB dari Handy Tech di sistem Anda. 
Input braille belum didukung. 
Berikut ini display braille yang tidak didukung, tetapi dapat digunakan melalui [Handy Tech's universal driver](https://handytech.de/en/service/downloads-and-manuals/handy-tech-software/braille-display-drivers) dan add-on NVDA:

* Braillino
* Bookworm
* Tampilan modular dengan firmware versi 1.13 atau lebih rendah. Perlu diketahui bahwa firmware display ini bisa di update.

Berikut ini adalah penggunaan tuts untuk display dengan NVDA. 
Silakan lihat instruksi penggunaan display untuk mendapatkan penjelasan di mana posisi tuts-tuts ini. 
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |kiri, atas, b3|
|Scroll braille display forward (Gulir braille display ke depan) |kanan, bawah, b6|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |b4|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |b5|
|Route to braille cell (Rute ke sel braille) |routing (perutean)|
|shift+tab key (shift+tuts tab) |esc, tuts aksi tiga kiri atas+bawah|
|alt key (tuts Alt) |b2+b4+b5|
|escape key (tuts Escape) |b4+b6|
|tab key (tuts tab) |enter, tuts aksi tiga kanan atas+bawah|
|enter key (tuts Enter) |esc+enter, kiri+kanan tuts aksi tiga atas+bawah, joystickAction|
|upArrow key (tuts panah atas) |joystickUp|
|downArrow key (tuts panah bawah) |joystickDown|
|leftArrow key (tuts panah kiri) |joystickLeft|
|rightArrow key (tuts panah kanan) |joystickRight|
|Menu NVDA |b2+b4+b5+b6|
|Toggle braille tethered to (Toggle braille ditambatkan ke) |b2|
|Toggle the braille cursor (Toggle kursor braille) |b1|
|Toggle focus context presentation (Toggle fokus presentasi konteks)| b7|
|Toggle braille input (Toggle braille masukan) |space+b1+b3+b4 (space+capital B)|

<!-- KC:endInclude -->

### MDV Lilli {#toc212}

Braille display Lilli dari [MDV](http://www.mdvbologna.it/) juga didukung.
Anda tidak perlu meng-install driver khusus untuk menggunakan display ini. 
Cukup sambungkan display dan konfigurasikan NVDA untuk menggunakannya.

Berikut adalah penggunaan tuts untuk mengoperasikan braille display ini dengan NVDA.  
Silakan lihat instruksi penggunaan display untuk mendapatkan penjelasan di mana posisi tuts-tuts ini.
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display backward (Gulir braille display ke belakang) |LF|
|Scroll braille display forward (Gulir braille display ke depan) |RG|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |UP|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |DN|
|Route to braille cell (Rute ke sel braille) |route|
|shift+tab key (shift+tuts tab) |SLF|
|tab key (tuts tab) |SRG|
|alt+tab key (alt + tuts tab) |SDN|
|alt+shift+tab key (alt+shift+tuts tab) |SUP|

<!-- KC:endInclude -->

### Baum/Humanware/APH/Orbit Braille Displays {#toc213}

Braille display dari [Baum](http://www.baum.de/cms/en/), [HumanWare](http://www.humanware.com/), [APH](http://www.aph.org/) and [Orbit](http://www.orbitresearch.com/) didukung ketika disambungkan via USB, bluetooth atau serial. 
Jenis-jenisnya meliputi: 

* Baum: SuperVario, PocketVario, VarioUltra, Pronto!, SuperVario2, Vario 340
* HumanWare: Brailliant, BrailleConnect, Brailliant2
* APH: Refreshabraille
* Orbit: Orbit Reader 20

Beberapa display lain yang dibuat oleh Baum juga mungkin dapat digunakan. Namun display yang lain ini belum diuji. 

Jika Anda menghubungkannya via USB ke display yang tidak menggunakan HID, Anda harus terlebih dulu meng-install driver USB yang disediakan oleh produsen. 
VarioUltra dan Pronto! menggunakan HID. 
Refreshabraille dan Orbit Reader 20 dapat menggunakan HID jika dikonfigurasi dengan tepat. 

USB serial mode dari Orbit Reader 20 saat ini hanya didukung di Windows 10. 
Maka, yang biasa digunakan adalah USB HID.

Berikut adalah penggunaan tuts untuk mengoperasikan braille display ini dengan NVDA.  
Silakan lihat instruksi penggunaan display untuk mendapatkan penjelasan di mana posisi tuts-tuts ini.
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |d2|
|Scroll braille display forward (Gulir braille display ke depan) |d5|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |d1|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |d3|
|Route to braille cell (Rute ke sel braille) |routing (perutean)|

Untuk display yang dilengkapi joystick: 

| Nama |Tuts|
|---|---|
|upArrow key (tuts panah atas) |up (atas)|
|downArrow key (tuts panah bawah) |down (bawah)|
|leftArrow key (tuts panah kiri) |left (kiri)|
|rightArrow key (tuts panah kanan) |right (kanan)|
|enter key (tuts Enter) |select (pilih)|

<!-- KC:endInclude -->

### hedo ProfiLine USB {#toc214}

Hedo ProfiLine USB dari [hedo Reha-Technik](http://www.hedo.de/) juga didukung. 
Pertama-tama Anda harus meng-install driver USB yang disediakan oleh produsen. 

Berikut adalah penggunaan tuts untuk mengoperasikan braille display ini dengan NVDA.  
Silakan lihat instruksi penggunaan display untuk mendapatkan penjelasan di mana posisi tuts-tuts ini.
<!-- KC:beginInclude -->

| Nama| Tuts|
|---|
|Scroll braille display back (Gulir braille display ke belakang) |K1|
|Scroll braille display forward (Gulir braille display ke depan) |K3|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |B2|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |B5|
|Route to braille cell (Rute ke sel braille) |routing (perutean)|
|Toggle braille tethered to (Men-toggle braille display yang ditambatkan ke) |K2|
|Say all (Baca semua) |B6|

<!-- KC:endInclude -->

### hedo MobilLine USB {#toc215}

Hedo MobilLine USB dari [hedo Reha-Technik](http://www.hedo.de/) juga didukung.
Pertama-tama Anda harus meng-install driver USB yang disediakan oleh produsen. 

Berikut adalah penggunaan tuts untuk mengoperasikan display ini dengan NVDA. 
Silakan lihat instruksi penggunaan display untuk mendapatkan penjelasan di mana posisi tuts-tuts ini. 
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |K1|
|Scroll braille display forward (Gulir braille display ke depan) |K3|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |B2|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |B5|
|Route to braille cell (Rute ke sel braille) |routing (perutean)|
|Toggle braille tethered to (Men-toggle braille display yang ditambatkan ke) |K2|
|Say all (Baca semua) |B6|

<!-- KC:endInclude -->

### HumanWare Brailliant BI/B Series {#toc216}

Rangkaian braille display Brailliant BI dan B dari [HumanWare](http://www.humanware.com/), termasuk BI 32, BI 40 dan B 80, didukung ketika dihubungkan via USB atau bluetooth.
Jika Anda menghubungkannya via USB dengan protocol set ke HumanWare, Anda harus terlebih dulu meng-install driver USB yang disediakan oleh produsen.
Driver USB tidak diperlukan jika protocol diatur ke OpenBraille.

Berikut adalah penggunaan tuts untuk mengoperasikan braille display ini dengan NVDA.  
Silakan lihat instruksi penggunaan display untuk mendapatkan penjelasan di mana posisi tuts-tuts ini.
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |left (kiri)|
|Scroll braille display forward (Gulir braille display ke depan) |right (kanan)|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |up (atas)|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |down (bawah)|
|Route to braille cell (Rute ke sel braille) |routing (perutean)|
|Toggle braille tethered to (Men-toggle braille display yang ditambatkan ke) |up+down (atas+bawah)|
|upArrow key (tuts panah atas) |space+dot1|
|downArrow key (tuts panah bawah) |space+dot4|
|leftArrow key (tuts panah kiri) |space+dot3|
|rightArrow key (tuts panah kanan) |space+dot6|
|Menu NVDA |c1+c3+c4+c5 (perintah n)|
|shift+tab key (shift+tuts tab) |space+dot1+dot3|
|tab key (tuts tab) |space+dot4+dot6|
|alt key (tuts Alt) |space+dot1+dot3+dot4 (space+m)|
|escape key (tuts Escape) |space+dot1+dot5 (space+e)|
|enter key (tuts Enter) |dot8|
|windows+d key (minimize all applications) - Windows+tuts d (minimalkan semua aplikasi) |c1+c4+c5 (perintah d)|
|windows key (tuts Windows) |space+dot3+dot4|
|alt+tab key (alt + tuts tab) |space+dot2+dot3+dot4+dot5 (space+t)|
|Say all (Baca semua) |c1+c2+c3+c4+c5+c6|

<!-- KC:endInclude -->

### HIMS Braille Sense/Braille EDGE/Smart Beetle Series {#toc217}

NVDA mendukung display Braille Sense, Braille EDGE dan Smart Beetle dari [Hims](http://www.hims-inc.com/) ketika dihubungkan via USB atau bluetooth. 
Jika Anda menghubungkan via USB, Anda perlu meng-install driver USB dari HIMS di sistem Anda.
Anda dapat mengunduhnya dari laman ini: http://www.himsintl.com/?c=2/13&uid=2319

Berikut ini adalah penggunaan tuts untuk mengoperasikan display ini dengan NVDA. 
Silakan lihat instruksi penggunaan display untuk mendapatkan penjelasan di mana posisi tuts-tuts ini.
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |gulir bawah sisi kiri|
|Scroll braille display forward (Gulir braille display ke depan) |gulir bawah sisi kanan|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |gulir atas sisi kiri|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |gulir atas sisi kanan|
|Route to braille cell (Rute ke sel braille) |routing (perutean)|
|shift+tab key (shift+tuts tab) |dot1+dot2+space|
|alt key (tuts Alt) |dot1+dot3+dot4+Space|
|escape key (tuts Escape) |dot1+dot5+Space|
|tab key (tuts tab) |dot4+dot5+Space|
|upArrow key (tuts panah atas) |dot1+Space|
|downArrow key (tuts panah bawah) |dot4+Space|
|capsLock |dot1+dot3+dot6+space|
|shift+alt+tab key (shift+alt+tuts tab) |advance2+advance3+advance1|
|alt+tab key (alt + tuts tab) |advance2+advance3|
|end key (tuts End) |dot4+dot6+space|
|control+end key (control+ tuts End) |dot4+dot5+dot6+space|
|home key (tuts Home) |dot1+dot3+space|
|control+home key (control+ tuts Home) |dot1+dot2+dot3+space|
|leftArrow key (tuts panah kiri) |dot3+space|
|control+shift+leftArrow key (control + shift + tuts panah kiri) |dot2+dot8+space+advance1|
|control+leftArrow key (control+ tuts panah kiri) |dot2+space|
|shift+alt+leftArrow key (shift+alt+tuts panah kiri) |dot2+dot7+advance1|

|alt+leftArrow key (alt+tuts panah kiri) | dot2+dot7 |

|rightArrow key (tuts panah kanan) |dot6+space|
|control+shift+rightArrow key (control + shift + tuts panah kanan) |dot5+dot8+space+advance1|
|control+rightArrow key (control + tuts panah kanan) |dot5+space|
|shift+alt+rightArrow key (shift+alt+tuts panah kanan) |dot5+dot7+advance1|
|alt+rightArrow key (alt+tuts panah kanan) |dot5+dot7|
|pageUp key (tuts pageUp) |dot1+dot2+dot6+space|
|control+pageUp key (control+ tuts pageUp) |dot1+dot2+dot6+dot8+space|
|control+shift+upArrow key (control + shift + tuts panah atas) |dot2+dot3+dot8+space+advance1|
|control+upArrow key (control + tuts panah atas) |dot2+dot3+space|
|shift+alt+upArrow key (shift+alt+tuts panah atas) |dot2+dot3+dot7+advance1|
|alt+upArrow key (alt+tuts panah atas) |dot2+dot3+dot7|
|shift+upArrow key (shift+tuts panah atas) |left side scroll down + space|
|pageDown key (tuts pageDown) |dot3+dot4+dot5+space|
|control+pagedown key (control + tuts page down) |dot3+dot4+dot5+dot8+space|
|control+shift+downArrow key (control + shift + tuts panah bawah) |dot5+dot6+dot8+space+advance1|
|control+downArrow key (control + tuts panah bawah) |dot5+dot6+space|
|shift+alt+downArrow key (shift+alt+tuts panah bawah) |dot5+dot6+dot7+advance1|
|alt+downArrow key (alt+tuts panah bawah) |dot5+dot6+dot7|
|shift+downArrow key (shift+tuts panah bawah) |gulir bawah sisi kanan + space|
|delete key (tuts Delete) |dot1+dot3+dot5+space|
|f1 key (tuts f1) |dot1+dot2+dot5+space|
|f3 key (tuts f3) |dot1+dot2+dot4+dot8|
|f4 key (tuts f4) |dot7+advance3|
|windows+b key (Windows + tuts b) |dot1+dot2+advance1|
|windows+d key (Windows + tuts d) |dot1+dot4+dot5+advance1|

<!-- KC:endInclude -->

### HIMS SyncBraille {#toc218}

NVDA mendukung SyncBraille Display dari [HIMS](http://www.hims-inc.com/).
Anda perlu meng-install driver USB dari HIMS di sistem Anda.

Berikut ini adalah penggunaan tuts untuk mengoperasikan display ini dengan NVDA.
Silakan lihat instruksi penggunaan display untuk mendapatkan penjelasan di mana posisi tuts-tuts ini. 
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |gulir bawah sisi kiri|
|Scroll braille display forward (Gulir braille display ke depan) |gulir bawah sisi kanan|
|Route to braille cell (Rute ke ke sel braille) |routing (perutean)|

<!-- KC:endInclude -->

### Seika Braille Displays {#toc219}

Seika Versi 3, 4 dan 5 (40 sel) dan Seika80 (80 sel) dari [Nippon Telesoft](http://www.nippontelesoft.com/) adalah braille display yang didukung.
nda dapat memperoleh informasi lebih lanjut tentang display ini di http://www.seika-braille.com/.
Pertama-tama Anda harus meng-install driver USB yang disediakan oleh produsen. 

Berikut ini adalah penggunaan tuts untuk mengoperasikan display ini dengan NVDA.
Silakan lihat instruksi penggunaan display untuk mendapatkan penjelasan di mana posisi tuts-tuts ini. 
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |kiri|
|Scroll braille display forward (Gulir braille display ke depan) |kanan|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |b3|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |b4|
|Toggle braille tethered to (Men-toggle braille display yang ditambatkan ke) |b5|
|Say all (Baca semua) |b6|
|tab |b1|
|shift+tab |b2|
|alt+tab |b1+b2|
|Menu NVDA |kiri+kanan|
|RRoute to braille cell (Rute ke sel braille) |routing (perutean)|

<!-- KC:endInclude -->

### Papenmeier BRAILLEX Model Baru {#toc220}

Berikut ini adalah beberapa braille display yang didukung:

* BRAILLEX EL 40c, EL 80c, EL 20c, EL 60c (USB)
* BRAILLEX EL 40s, EL 80s, EL 2d80s, EL 70s, EL 66s (USB)
* BRAILLEX Trio (USB and bluetooth)
* BRAILLEX Live 20, BRAILLEX Live and BRAILLEX Live Plus (USB and bluetooth)

Jika BrxCom sudah di-install, NVDA akan menggunakan BrxCom.
BrxCom adalah alat yang memungkinkan input keyboard dari braille display untuk berfungsi secara mandiri dari pembaca layar.
Versi baru BrxCom yang bekerja dengan NVDA akan segera dirilis oleh Papenmeier.
Input keyboard dapat dilakukan dengan model Trio dan BRAILLEX Live. 

Sebagian besar perangkat memiliki sebuah Easy Access Bar (EAB) yang memungkinkan Anda melakukan pengoperasian secara intuitif dan cepat.
EAB dapat digerakkan ke empat arah. Biasanya, setiap arah memiliki dua switch.
Seri C dan Live adalah pengecualian dalam hal ini. 

Seri C dan beberapa display lain memiliki dua routing row (baris perutean); baris atas digunakan untuk melaporkan informasi pemformatan.
Menahan salah satu tuts perutean (routing key) atas dan menekan EAB pada perangkat seri C akan menyamai status switch kedua.
Display seri Live hanya memiliki satu routing row dan EAB-nya dapat melakukan satu langkah per arah.
Langkah kedua dapat disamai dengan menekan salah satu routing key dan menekan EAB dalam arah yang sesuai.
Menekan dan menahan tuts atas, bawah, kanan dan kiri (atau EAB) akan mengulang tindakan yang sesuai. 

Biasanya, tuts-tuts berikut ini tersedia di braille display tersebut: 

| Nama |Tuts|
|---|---|
|l1 |Left front key (tuts kiri depan)|
|l2 |Left rear key (tuts kiri belakang)|
|r1 |Right front key (tuts kanan depan)|
|r2 |Right rear key (tuts kanan belakang)|
|up (atas) |1 langkah ke atas|
|up2 |2 langkah ke atas|
|left (kiri) |1 langkah ke kiri|
|left2 |2 langkah ke kiri|
|right (kanan) |1 langkah ke kanan|
|right2 |2 langkah ke kanan|
|dn |1 langkah ke bawah|
|dn2 |2 langkah ke bawah|

Berikut adalah penggunaan perintah Papenmeier untuk NVDA: 
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |left (kiri)|
|Scroll braille display forward (Gulir braille display ke depan) |right (kanan)|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |up (atas)|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |dn|
|Route to braille cell (Rute ke sel braille) |routing (perutean)|
|Report current character in review (Laporkan karakter saat ini dalam tinjauan) |l1|
|Activate current navigator object (Aktifkan objek navigator saat ini) |l2|
|Toggle braille tethered to (Men-toggle braille display yang ditambatkan ke) |r2|
|Report title (Laporkan judul) |l1+up|
|Report Status Bar (Laporkan Bilah Status) |l2+down|
|Move to containing object (Pindah ke objek yang berisi) |up2|
|Move to first contained object (Pindah ke objek berisi yang pertama) |dn2|
|Move to previous object (Pindah ke objek sebelumnya) |left2|
|Move to next object (Pindah ke objek berikutnya) |right2|
|Report text formatting (Laporkan pemformatan teks) |Upper routing row (baris perutean atas)|

<!-- KC:endInclude -->

Model Trio memiliki empat tuts tambahan yang berada di depan keyboard braille.
Yaitu (dari kiri ke kanan): 

* left thumb key (lt)
* space
* space
* right thumb key (rt)

Saat ini, tuts right thumb tidak digunakan. 
Tuts-tuts di sebelah dalam adalah space. 

| Nama |Tuts|
|---|---|

<!-- KC:beginInclude -->

|escape key (tuts Escape) |space dengan dot 7|
|upArrow key (tuts panah atas) |space dengan dot 2|
|leftArrow key (tuts panah kiri) |space dengan dot 1|
|rightArrow key (tuts panah kanan) |space dengan dot 4|
|downArrow (panah bawah) |space dengan dot 5|
|control key (tuts Control) |lt+dot2|
|alt key (tuts Alt) |lt+dot3|
|control+escape key (tuts control+escape) |space dengan dot 1 2 3 4 5 6|
|tab key (tuts tab) |space dengan dot 3 7|

<!-- KC:endInclude  -->

### Papenmeier Braille BRAILLEX Model Lama {#toc221}

Berikut ini adalah beberapa braille display yang didukung: 

* BRAILLEX EL 80, EL 2D-80, EL 40 P
* BRAILLEX Tiny, 2D Screen

Perhatikanlah bahwa model-model display ini hanya dapat dihubungkan via port serial.
Oleh karena itu, Anda harus memilih port yang akan dihubungkan dengan display setelah Anda memilih driver ini pada dialog Braille Settings (Pengaturan Braille). 

Sebagian dari perangkat ini memiliki sebuah Easy Access Bar (EAB) yang memungkinkan Anda melakukan pengoperasian secara intuitif dan cepat.
EAB dapat digerakkan ke empat arah. Biasanya, setiap arah memiliki dua switch.
Menekan dan menahan tuts atas, bawah, kanan dan kiri (atau EAB) akan mengulang tindakan yang sesuai.
Perangkat-perangkat model lama tidak memiliki EAB, oleh karena itu front key (tuts depan) digunakan. 

Biasanya, tuts-tuts berikut ini tersedia di braille display tersebut: 

| Nama |Tuts|
|---|---|
|l1 |Left front key (tuts kiri depan)|
|l2 |Left rear key (tuts kiri belakang)|
|r1 |Right front key (tuts kanan depan)|
|r2 |Right rear key (tuts kanan belakang)|
|up (atas) |1 langkah ke atas|
|up2 |2 langkah ke atas|
|left (kiri) |1 langkah ke kiri|
|left2 |2 langkah ke kiri|
|right (kanan) |1 langkah ke kanan|
|right2 |2 langkah ke kanan|
|dn |1 langkah ke bawah|
|dn2 |2 langkah ke bawah|

Berikut adalah penggunaan perintah Papenmeier untuk NVDA: 

<!-- KC:beginInclude -->
Perangkat dengan EAB: 

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |left (kiri)|
|Scroll braille display forward (Gulir braille display ke depan) |right (kanan)|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |up (atas)|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |dn|
|Route to braille cell (Rute ke sel braille) |routing (perutean)|
|Report current character in review (Laporkan karakter saat ini dalam tinjauan) |l1|
|Activate current navigator object (Aktifkan objek navigator saat ini) |l2|
|Report title (Laporkan judul) |l1up|
|Report Status Bar (Laporkan Bilah Status) |l2down|
|Move to containing object (Pindah ke objek yang berisi) |up2|
|Move to first contained object (Pindah ke objek berisi yang pertama) |dn2|
|Move to next object (Pindah ke objek berikutnya) |right2|
|Move to previous object (Pindah ke objek sebelumnya) |left2|
|Report text formatting (Laporkan pemformatan teks) |Upper routing strip (Lajur perutean atas)|

BRAILLEX Tiny:

| Nama |Tuts|
|---|---|
|Report current character in review (Laporkan karakter saat ini dalam tinjauan) |l1|
|Activate current navigator object (Aktifkan objek navigator saat ini) |l2|
|Scroll braille display back (Gulir braille display ke belakang) |left (kiri)|
|Scroll braille display forward (Gulir braille display ke depan) |right (kanan)|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |up (atas)|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |dn|
|Toggle braille tethered to (Men-toggle braille display yang ditambatkan ke) |r2|
|Move to containing object (Pindah ke objek yang berisi) |r1+up|
|Move to first contained object (Pindah ke objek berisi yang pertama) |r1+dn|
|Move to previous object (Pindah ke objek sebelumnya) |r1+left|
|Move to next object (Pindah ke objek berikutnya) |r1+right|
|Report text formatting (Laporkan pemformatan teks) |reportf|
|Report title (Laporkan judul) |l1+up|
|Report status bar (Laporkan bilah status) |l2+down|

BRAILLEX 2D Screen:

| Nama |Tuts|
|---|---|
|Report current character in review (Laporkan karakter saat ini dalam tinjauan) |l1|
|Activate current navigator object (Aktifkan objek navigator saat ini) |l2|
|Toggle braille tethered to (Men-toggle braille display yang ditambatkan ke) |r2|
|Report text formatting (Laporkan pemformatan teks) |reportf|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |up (atas)|
|Scroll braille display back (Gulir braille display ke belakang) |left (kiri)|
|Scroll braille display forward (Gulir braille display ke depan) |right (kanan)|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |dn|
|Move to next object (Pindah ke objek berikutnya) |left2|
|Move to containing object (Pindah ke objek yang berisi) |up2|
|Move to first contained object (Pindah ke objek berisi yang pertama) |dn2|
|Move to previous object (Pindah ke objek sebelumnya) |right2|

<!-- KC:endInclude -->

### HumanWare BrailleNote {#toc222}

(Pindah ke objek sebelumnya) [Humanware](http://www.humanware.com) saat berfungsi sebagai display terminal untuk pembaca layar.
Model-model berikut ini adalah yang didukung: 

* BrailleNote Classic (hanya koneksi serial)
* BrailleNote PK (koneksi serial dan bluetooth)
* BrailleNote MPower (koneksi serial dan bluetooth)
* BrailleNote Apex (koneksi USB dan Bluetooth)

Jika perangkat Anda mendukung lebih dari satu tipe koneksi, saat menghubungkan BrailleNote ke NVDA, Anda harus mengatur braille terminal port pada opsi Braille Terminal.
Silakan pelajari buku panduan BrailleNote untuk informasi lebih detail.
Di NVDA, Anda mungkin juga perlu mengatur port pada dialog Braille Settings (Pengaturan Braille).
Jika Anda menghubungkan via USB atau bluetooth, Anda dapat mengatur port ke "Automatic", "USB" atau "Bluetooth", tergantung pilihan yang tersedia.
Jika Anda menghubungkan dengan menggunakan port seri legacy (atau USB ke konverter seri) atau jika tidak ada opsi sebelumnya yang muncul, Anda harus secara eksplisit memilih port komunikasi yang akan digunakan dari daftar port hardware. 

Sebelum menghubungkan BrailleNote Apex dengan menggunakan antarmuka klien USB, Anda harus meng-install driver yang disediakan oleh HumanWare. 

Berikut adalah penggunaan perintah BrailleNote untuk NVDA.
Silakan baca instruksi penggunaan BrailleNote untuk menemukan posisi tuts-tuts ini. 

<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |back (belakang)|
|Scroll braille display forward (Gulir braille display ke depan) |advance (depan)|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |previous (sebelumnya)|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |next (berikutnya)|
|Route to braille cell (Rute ke sel braille) |routing (perutean)|
|Toggle braille tethered to (Men-toggle braille display yang ditambatkan ke) |previous+next (sebelumnya+berikutnya)|
|Up arrow key (Tuts panah atas) |space+dot1|
|Down arrow key (Tuts panah bawah) |space+dot4|
|Left Arrow key (Tuts panah kiri) |space+dot3|
|Right arrow key (Tuts panah kanan) |space+dot6|
|Page up key (Tuts Page up) |space+dot1+dot3|
|Page down key (Tuts Page down) |space+dot4+dot6|
|Home key (tuts Home) |space+dot1+dot2|
|End key (tuts End) |space+dot4+dot5|
|Control+home keys (Tuts Control+Home) |space+dot1+dot2+dot3|
|Control+end keys (Tuts Control+End) |space+dot4+dot5+dot6|
|Space key (Tuts Space) |space|
|Enter key (tuts Enter) |space+dot8|
|Backspace |space+dot7|
|Tuts Tab |space+dot2+dot3+dot4+dot5 (space+t)|
|Tuts Shift+tab |space+dot1+dot2+dot5+dot6|
|Tuts Windows |space+dot2+dot4+dot5+dot6 (space+w)|
|Tuts Alt |space+dot1+dot3+dot4 (space+m)|
|Toggle input help (Men-toggle Mode Input Help) |space+dot2+dot3+dot6 (space+lower h)|

<!-- KC:endInclude -->

### EcoBraille {#toc223}

NVDA mendukung braille display EcoBraille dari [ONCE](http://www.once.es/).
Model-model berikut ini adalah yang didukung: 

* EcoBraille 20
* EcoBraille 40
* EcoBraille 80
* EcoBraille Plus

Di NVDA, Anda dapat mengatur port seri yang dihubungkan ke display dalam dialog Braille Settings (Pengaturan Braille). 

Berikut ini adalah penggunaan tuts untuk display EcoBraille. 
Silakan lihat [instruksi penggunaan EcoBraille](ftp://ftp.once.es/pub/utt/bibliotecnia/Lineas_Braille/ECO/) untuk mendapatkan penjelasan di mana posisi tuts-tuts ini. 

<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |T2|
|Scroll braille display forward (Gulir braille display ke depan) |T4|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |T1|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |T5|
|Route to braille cell (Rute ke sel braille) |Routing (perutean)|
|Activate current navigator object (Aktifkan objek navigator saat ini) |T3|
|Switch to next review mode (Beralih ke mode tinjauan berikutnya) |F1|
|Move to containing object (Pindah ke objek yang berisi) |F2|
|Switch to previous review mode (Beralih ke mode tinjauan sebelumnya) |F3|
|Move to previous object (Pindah ke objek sebelumnya) |F4|
|Report current object (Laporkan objek saat ini) |F5|
|Move to next object (Pindah ke objek berikutnya) |F6|
|Move to focus object (Pindah ke objek fokus) |F7|
|Move to first contained object (Pindah ke objek berisi yang pertama) |F8|
|Move System focus or caret to current review position (Pindahkan fokus sistem atau caret ke posisi tinjauan saat ini) |F9|
|Report review cursor location (Laporkan lokasi kursor tinjauan) |F0|
|Toggle braille tethered to (Men-toggle braille display yang ditambatkan ke) |A|

<!-- KC:endInclude -->

### SuperBraille {#toc224}

Perangkat SuperBraille, yang kebanyakan tersedia di Taiwan, dapat dihubungkan dengan USB atau serial.
Karena SuperBraille tidak memiliki tombol pengetikan fisik atau tombol bergulir, semua input harus dilakukan melalui keyboard komputer standar.
Karena ini, dan untuk menjaga kompatibilitas dengan pembaca layar lainnya di Taiwan, dua binding kunci untuk menggulir tampilan braille telah disediakan:
<!-- KC:beginInclude -->

| Nama |Tuts|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |numpadMinus|
|Scroll braille display forward (Gulir braille display ke depan) |numpadPlus|

<!-- KC:endInclude -->

### BRLTTY {#toc225}

[BRLTTY](http://www.brltty.com/) adalah program terpisah yang dapat digunakan untuk mendukung lebih banyak lagi braille display.
Untuk menggunakannya, Anda perlu meng-install [BRLTTY for Windows](http://www.brltty.com/download.html).
Anda harus mengunduh dan meng-install paket instalasi terkini, yang akan dinamai, misalnya brltty-win-4.2-2.exe.
Saat mengonfigurasi display dan port yang akan digunakan, pastikan Anda memperhatikan instruksinya, terutama jika Anda menggunakan display USB dan memiliki driver yang telah ter-install dari produsen. 

Untuk display yang memiliki keyboard braille, BRLTTY kini telah menangani input braille sendiri.
Oleh karena itu, pengaturan tabel input braille NVDA tidaklah relevan. 

Berikut adalah penggunaan perintah BRLTTY untuk NVDA.
Silakan lihat [BRLTTY key binding lists](http://mielke.cc/brltty/doc/KeyBindings/) untuk informasi tentang bagaimana perintah BRLTTY dipetakan untuk mengontrol braille display. 
<!-- KC:beginInclude -->

| Nama |Perintah BRLTTY|
|---|---|
|Scroll braille display back (Gulir braille display ke belakang) |fwinlt (ke kiri satu jendela)|
|Scroll braille display forward (Gulir braille display ke depan) |fwinrt (ke kanan satu jendela)|
|Move braille display to previous line (Pindahkan braille display ke baris sebelumnya) |lnup (ke atas satu baris)|
|Move braille display to next line (Pindahkan braille display ke baris berikutnya) |lndn (ke bawah satu baris)|
|Route to braille cell (Rute ke sel braille) |route (bawa kursor ke karakter)|

<!-- KC:endInclude -->

## Topik Lanjutan {#toc226}
### Opsi Command Line (Baris Perintah) {#CommandLineOptions}

NVDA dapat menerima satu atau lebih opsi tambahan ketika di-start sehingga mengubah perilakunya.
Anda dapat menyetujui sebanyak mungkin opsi yang Anda perlukan.
Opsi-opsi ini dapat disetujui ketika dimulai dari satu pintasan (dalam Shortcut Properties), dari dialog Run (Start Menu -> Run atau Windows+r) atau dari Windows command console. 
Opsi-opsi harus dipisahkan dari nama file NVDA yang dapat dieksekusi dan dari opsi-opsi lain berdasarkan space.
Misalnya, pintasan Desktop yang dibuat NVDA selama instalasi memiliki opsi -r yang meminta NVDA untuk menutup salinan yang saat ini sedang berjalan sebelum memulai yang baru.
Opsi lain yang berguna adalah --disable-addons, yang meminta NVDA untuk menangguhkan semua add-on yang sedang berjalan.
Ini memungkinkan Anda untuk menentukan apakah satu masalah disebabkan oleh satu add-on, dan untuk memulihkan komputer dari masalah serius yang disebabkan oleh add-on. 

Sebagai contoh, Anda dapat keluar dari salinan NVDA yang saat ini sedang berjalan dengan memasuki yang berikut ini pada dialog Run: 

nvda -q

Sebagian opsi baris perintah memiliki satu versi pendek dan satu versi panjang, sementara sebagian lagi hanya memiliki versi panjang. 
Untuk opsi yang memiliki versi pendek, Anda dapat menggabungkannya seperti ini: 

|nvda -rm |Ini akan membawa Anda keluar dari salinan NVDA yang sedang berjalan dan akan memulai salinan baru dengan suara startup dinonaktifkan, dll.|
|nvda -rm --disable-addons |Sama seperti di atas, tapi dengan add-on dinonaktfikan|

Sebagian opsi baris perintah menerima parameter tambahan, mis. seberapa detail seharusnya suatu logging atau jalan menuju direktori User Configuration (Konfigurasi Pengguna).
Parameter ini harus ditempatkan setelah opsi tersebut, terpisah dari opsi berdasarkan space ketika menggunakan versi pendek, atau tanda sama dengan (=) ketika menggunakan versi panjang, mis: 

|nvda -l 10 |Meminta NVDA untuk mulai dengan log level yang diatur untuk melakukan debug|
|nvda --log-file=c:\nvda.log |Meminta NVDA untuk menuliskan log-nya ke c:\nvda.log|
|nvda --log-level=20 -f c:\nvda.log |Meminta NVDA untuk mulai dengan log level yang diatur untuk info dan untuk menuliskan log-nya ke c:\nvda.log|

Berikut ini adalah opsi baris perintah untuk NVDA: 

| Pendek |Panjang |Keterangan|
|---|---|---|
|-h |--help |Menampilkan baris perintah Help dan Exit|
|-q |--quit |Menghentikan salinan NVDA yang sedang berjalan|
|-r |--replace |Menghentikan salinan NVDA yang sedang berjalan dan memulai yang satu ini|
|-k |--check-running |Melaporkan apakah NVDA sedang berjalan via exit code (sinyal keluar); 0 jika berjalan, 1 jika tidak berjalan|
|-f LOGFILENAME |--log-file=LOGFILENAME |File tempat log message harus dituliskan|
|-l LOGLEVEL |--log-level=LOGLEVEL |Level terendah untuk pesan yang di-log (debug 10, info 20, warning 30, error 40, critical 50), default-nya adalah warning|
|-c CONFIGPATH |--config-path=CONFIGPATH |Lokasi tempat semua pengaturan NVDA disimpan|
|-m |--minimal |Tanpa suara, tampa antarmuka, tanpa pesan Start, dll.|
|-s |--secure |Secure mode (nonaktifkan Python console)|
|None |--disable-addons |Add-on tidak akan berpengaruh|
|None |--debug-logging |Aktifkan debug level logging hanya untuk menjalankan ini. Pengaturan ini akan menggantikan tingkat log lainnya (--loglevel, -l) argumen yang diberikan.|
|None |--no-sr-flag |Jangan ubah bendera pembaca layar sistem global|
|None |--install |Meng-install NVDA (memulai salinan yang baru ter-install)|
|None |--install-silent |Meng-install NVDA secara diam-diam (tidak memulai salinan yang baru ter-install)|
|None |--create-portable |Membuat salinan portabel NVDA (memulai salinan yang baru dibuat). Membutuhkan --portable-path untuk ditentukan|
|None |--create-portable-silent |Membuat salinan portabel NVDA (tidak memulai salinan yang baru diinstal). Membutuhkan --portable-path untuk ditentukan|
|None |--portable-path=PORTABLEPATH |Path dimana salinan portabel akan dibuat|

### System Wide Parameters {#SystemWideParameters}

NVDA memungkinkan beberapa nilai untuk ditetapkan dalam sistem registry yang mengubah perilaku sistem NVDA yang luas.
Nilai ini disimpan di registri di bawah salah satu kunci berikut:

* Sistem 32-bit: "HKEY_LOCAL_MACHINE\SOFTWARE\nvda"
* Sistem 64-bit: "HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\nvda"

Nilai berikut dapat diatur di bawah kunci registri ini:

| Nama |Tipe |Nilai yang mungkin |Keterangan|
|---|---|---|---|
|configInLocalAppData |DWORD |0 (default) untuk menonaktifkan, 1 untuk mengaktifkan |Jika diaktifkan, simpan konfigurasi pengguna NVDA di data aplikasi lokal dan bukan data aplikasi roaming|
|serviceDebug |DWORD |0 (default) untuk menonaktifkan, 1 untuk mengaktifkan |Jika diaktifkan, nonaktifkan mode aman pada windows secure desktops, yang memungkinkan penggunaan konsol Python dan Log viewer. Karena beberapa implikasi keamanan utama, penggunaan opsi ini sangat tidak dianjurkan|

## Informasi Lebih Lanjut {#toc229}

Jika Anda memerlukan informasi atau bantuan lebih lanjut mengenai NVDA, silakan berkunjung ke situs web NVDA di NVDA_URL.
Di sini, Anda dapat menemukan lebih banyak petunjuk penggunaan serta dukungan teknis dan sumber daya komunitas.
Situs ini juga menyediakan informasi dan sumber daya yang berkaitan dengan pengembangan NVDA. 

