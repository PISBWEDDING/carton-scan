# Manual Pengguna — PISB Carton Tracker

**Untuk:** semua staf Outlet, Gudang, E-commerce, Pemandu dan Pengurus PISB
**Versi:** 18 November 2026

> **Peraturan utama:** Setiap kotak mesti ada label. Setiap kali kotak bertukar tangan, kotak itu mesti diimbas.

---

## Kandungan

- A. Mula guna: pasang di telefon / komputer dan log masuk
- B. Ikut tugas anda (Outlet / Gudang, **Pulangkan barang (Return)**, Pemandu, **Gudang PI02 — barang transit**, Pengurus)
- C. Cara mengimbas kotak dengan kamera
- D. **Telefon tidak dapat imbas kod bar — apa perlu buat**
- E. Amaran merah di skrin
- F. Dashboard (laporan) — termasuk **cara membaca Dashboard**
- G. Masalah lain
- H. Peraturan emas

---

## A. Mula guna

### A1. Pasang di telefon & komputer (sekali sahaja)

Imbas QR pada poster **Carton Tracker** dengan kamera telefon, atau taip **pisbwedding.github.io/carton-scan/app**.

**Telefon Android (Chrome):**

1. Imbas QR. Buka dengan **Chrome**.
2. Tekan **⋮** (tiga titik) di atas sebelah kanan.
3. Tekan **Add to Home screen**.
4. Tekan **Add**.

**iPhone (Safari):**

1. Buka **Kamera**, imbas QR. Buka dengan **Safari**.
2. Tekan butang **Kongsi** (kotak dengan anak panah ke atas) di bawah skrin.
3. Tekan **Add to Home Screen**.
4. Tekan **Add**.

> **iPhone: tambah di halaman pertama.** Tambah ke skrin utama **sebelum** tekan **Open Carton Tracker**. Jika tidak, ikon jadi huruf "P" kelabu. Bila buka dari ikon, tekan **Open Carton Tracker**.

Sekarang ada ikon **Carton Tracker** (logo PISB) di skrin telefon. Lepas ini, tekan ikon itu sahaja.

**Komputer (Chrome / Edge) — sesuai untuk Register & Dashboard:**

1. Buka **pisbwedding.github.io/carton-scan/app** dengan **Chrome** atau **Edge**.
2. **Chrome:** tekan **⋮** → **Cast, save and share** → **Create shortcut** (atau **Install page as app**).
   **Edge:** tekan **···** → **Apps** → **Install this site as an app**.
3. Tandakan **Open as window** → tekan **Create** / **Install**.
4. Ikon PISB keluar di desktop. Klik kanan ikon → **Pin to taskbar**.

Mac (Safari): **File** → **Add to Dock**. Cetak label lebih mudah dari komputer: **Create label PDF** → **Open PDF to print** → kertas A4.

### A2. Log masuk

1. Tekan ikon **Carton Tracker**.
2. Tekan **Log in with Google**.
3. Pilih Gmail yang betul:
   - **Staf outlet / gudang / e-commerce:** Gmail outlet anda.
   - **Pemandu / pengurus:** Gmail peribadi anda (yang didaftarkan oleh HQ).
4. **Kali pertama sahaja:** keluar skrin Google **"PISB Carton Tracker"** → tekan **Review permissions** → pilih Gmail anda → tekan **Allow**.

**Staff ID**

- Pemandu dan pengurus: Staff ID keluar sendiri. Tidak perlu isi.
- Staf outlet: isi **Staff ID anda sendiri** setiap kali (contoh S003). Jangan guna Staff ID orang lain.

---

## B. Ikut tugas anda

### B1. Staf Outlet / Gudang / E-commerce

**Hantar barang ke tempat lain (buat sebelum pemandu sampai):**

1. Tekan tab **Register**.
2. **Transfer ID:** taip nombor nota pindahan (contoh 9000087).
3. **To:** pilih tempat yang akan terima barang.
4. **Total cartons:** berapa kotak (tekan **−** atau **+**).
5. Tekan **Next**. Semak semua betul. Tekan **Register**.
6. Tekan **Create label PDF (A4, 4 per page)** → **Open PDF to print** → cetak.
7. Tampal **satu label pada setiap kotak**. Label mesti rata dan tidak berlipat.
8. Serahkan kotak kepada pemandu. **Pemandu yang imbas Pickup**, bukan staf outlet.

**Terima barang:**

1. Tekan tab **Scan** → tekan **Receive**.
2. Tekan butang hijau **Live camera scan** → **Start camera**.
3. Imbas **setiap kotak** sebelum masuk ke kedai. Selepas kotak hijau, tekan **SCAN NEXT ▶** untuk kotak seterusnya.
4. Jika keluar amaran merah **"Wrong carton! Do not accept"** → **jangan terima kotak itu**. Pulangkan kepada pemandu.

**Pulangkan barang miscellaneous (Return):**

Barang yang outlet pulangkan (contoh ke gudang PI02) **juga mesti ada label**. Sistem buat Transfer ID sendiri.

1. Tab **Register** → tekan **Return** (butang ungu).
2. **Transfer ID** keluar sendiri: **kod outlet + tarikh hari ini**, contoh `PI05-20261118`. Pulangan kedua hari yang sama: `PI05-20261118B`.
3. **Return reason**: pilih sebab (jadual di bawah). **RETURN SUPPLIER WITHOUT BILL**: isi juga **Supplier DO number**.
4. **To**: biasanya **PI02 · WAREHOUSE** (sudah dipilih). Tukar jika perlu.
5. **Total cartons**: berapa kotak / beg.
6. **Notes**: tulis barang apa dan sebab (contoh "2 pasu pecah"). **Wajib** untuk OTHER dan RETURN SUPPLIER WITHOUT BILL.
7. **Next** → semak → **Register** → **Create label PDF** → cetak → tampal **satu label setiap kotak**.
8. Serah kepada pemandu. Pemandu imbas **Pickup** seperti biasa; penerima imbas **Receive**.

| Reason | Bila guna |
|---|---|
| **REPLACE** | Barang rosak / salah — perlu ganti barang baru |
| **REPAIR** | Barang rosak — hantar untuk dibaiki, kemudian dipulangkan semula |
| **REJECT** | Barang ditolak / tidak mahu — pulangkan sahaja |
| **RETURN SUPPLIER WITHOUT BILL** | Pulang kepada supplier tanpa bil. **Wajib** isi **DO number** + sebab dalam Notes. DO number keluar pada label |
| **OTHER** | Sebab lain — tulis dalam Notes |

Label pulangan tertulis **OUTLET RETURN** dan **REASON**. Pulangan **tidak dikira dalam Dashboard** — semak di tab **Transfers** (tanda ungu **RETURN**) atau **Lookup**.

> **Mulai sekarang: tiada label = pemandu tidak ambil.** Semua barang yang keluar dari outlet — termasuk barang pulangan / miscellaneous — mesti ada label Carton Tracker.

### B2. Pemandu

**Ambil barang dari outlet / gudang:**

1. Tekan tab **Scan** → tekan **Pickup**.
2. Tekan **Live camera scan**.
3. Isi **Lorry No.** (nombor plat lori, contoh JPK1234). Sistem tambah tarikh hari ini sendiri.
4. Tekan **Start camera**. Imbas kotak → **✓ SCAN SUCCESSFUL** → tekan **SCAN NEXT ▶**. Ulang untuk **setiap kotak** yang anda ambil.
5. Sebelum bertolak, semak **Dashboard → Cartons with you now**.

> **Tiada label Carton Tracker = jangan ambil.** Termasuk barang pulangan / miscellaneous. Minta outlet daftar **Return** dan tampal label dahulu.

**Terima kotak daripada pemandu / pengurus lain:**

1. Tekan **Scan** → tekan **Take over** → **Live camera scan**.
2. Imbas setiap kotak yang anda terima.
3. Ingat: **selagi anda belum imbas, kotak itu masih tanggungjawab orang yang menyerahkan.**

**Hantar ke outlet:** staf outlet imbas **Receive**. Tunggu sehingga semua kotak diimbas.

### B2b. Gudang PI02 — barang transit

Barang dari outlet A yang **singgah di gudang PI02** sebelum ke outlet B. Setiap tempat imbas sekali — supaya kita tahu siapa pegang kotak.

| Langkah | Tempat | Siapa imbas | Imbas apa | Status |
|---|---|---|---|---|
| 1 | Outlet A | Staf outlet | Tiada imbasan (Register + label) | Not picked up |
| 2 | Outlet A | Pemandu | **PICKUP** (isi Lorry No.) | On the way |
| 3 | Masuk PI02 | Staf PI02 / admin pejabat | **RECEIVE** | At PI02 warehouse — pemandu tidak lagi bertanggungjawab |
| 4 | Keluar PI02 | **Pemandu yang hantar** (bukan staf gudang) | **PICKUP** (isi Lorry No. hari ini) | On the way |
| 5 | Outlet B | Staf outlet | **RECEIVE** | Received — selesai |

**Masuk PI02 (langkah 3):**

1. Staf PI02 buka **Scan** → **Receive** → **Live camera scan**.
2. Imbas **setiap kotak** semasa diturunkan dari lori.
3. Skrin tunjuk **"Received at PI02 (transit). Final destination PIxx"**. Ini betul — **bukan** salah tempat.
4. Simpan kotak ikut destinasi (lihat **TO** pada label).

> **Jangan imbas Pickup** bila barang masuk PI02. Pickup di sini tidak mengubah apa-apa — sistem masih sangka kotak di atas lori.

**Keluar PI02 (langkah 4):**

1. Staf gudang serahkan kotak kepada pemandu. **Staf gudang tidak imbas.**
2. **Pemandu sendiri** imbas **Pickup** setiap kotak (isi Lorry No.).
3. Staf gudang lihat setiap kotak keluar **✓ SCAN SUCCESSFUL** sebelum lori bertolak.

**Keadaan khas:**

| Keadaan | Apa perlu buat |
|---|---|
| Kotak **tidak diturunkan** di PI02 — terus ditukar ke lori / pemandu lain | Pemandu baru imbas **Take over**. PI02 tidak perlu imbas |
| Kotak masuk PI02 tetapi **lupa imbas Receive** | Pemandu seterusnya akan nampak **"already with trip …"** bila imbas Pickup. Staf PI02 imbas **Receive** dahulu, kemudian pemandu imbas **Pickup** |
| Kotak memang **untuk PI02** (TO = PI02, contoh barang pulangan) | PI02 imbas **Receive** → status **Received**. Selesai |
| Admin pejabat ialah **Pengurus / HQ** | Pilih **Scan location = PI02** dahulu, kemudian imbas **Receive** |

> **Akaun PI02:** staf PI02 perlu Gmail dalam **08_User_Master** — Role **WAREHOUSE**, AssignedLocationID **PI02**. Tanpa akaun ini, PI02 tidak boleh imbas Receive.

### B3. Pengurus

Pengurus boleh buat semua kerja di atas, dan juga:

- pilih **Scan location** (tempat anda mengimbas) sebelum imbas;
- bawa kotak sendiri tanpa lori (biarkan Lorry No. kosong semasa Pickup);
- **taip nombor kotak** jika label tidak dapat diimbas (lihat bahagian D);
- tab **Issues**: semak masalah, tulis tindakan, tekan **Resolve**;
- tab **Dashboard**: semua outlet, kotak di tangan anda, siapa pegang, dan pindahan yang **Overdue** (lebih 10 hari belum sampai).

---

## C. Cara mengimbas kotak dengan kamera

1. Tekan tab **Scan**. Pilih **Pickup**, **Take over** atau **Receive**.
2. Tekan butang hijau **Live camera scan**.
3. Tekan **Start camera**. Kali pertama, tekan **Allow** untuk benarkan kamera.
4. Halakan kamera ke **kod bar** (garisan hitam) supaya kod bar berada dalam kotak putih di skrin.
5. Pegang telefon **15–25 cm** dari label. Bila berjaya, telefon berbunyi dan keluar **kotak hijau besar "✓ SCAN SUCCESSFUL"** dengan nombor kotak (contoh "Pickup OK"). Kamera berhenti sekejap.
6. Tekan **SCAN NEXT ▶**, kemudian halakan kamera ke kotak seterusnya.

**Maksud keputusan di senarai:**

| Keputusan | Maksud |
|---|---|
| **OK** (kotak hijau "SCAN SUCCESSFUL") | Berjaya disimpan. Tekan **SCAN NEXT ▶** |
| **ALREADY DONE** (kotak oren "ALREADY SCANNED") | Kotak ini sudah diimbas tadi. Tidak apa-apa. Tekan **SCAN NEXT ▶** |
| **REJECTED** (merah) | Tidak diterima. Baca amaran, tekan **OK, got it** (bahagian E) |
| **NOT SAVED** (kotak kelabu) | Internet putus. Tekan **SCAN NEXT ▶** dan imbas kotak itu sekali lagi |

---

## D. Telefon tidak dapat imbas kod bar — apa perlu buat

Staf biasa **tidak boleh taip** nombor kotak. Ini supaya setiap kotak benar-benar diperiksa. Ikut langkah ini mengikut turutan:

### Langkah 1 — Cuba sekali lagi dengan betul

- Tekan butang **Light** (lampu suluh) di skrin kamera.
- Ratakan label. Lap jika kotor atau basah.
- Pegang telefon **15–25 cm** dari label, tegak, jangan goyang.
- Pastikan seluruh kod bar masuk dalam kotak putih di skrin.
- Cuba di tempat yang lebih terang.

### Langkah 2 — Masih tidak boleh: panggil pengurus

Pengurus akan **taip nombor kotak** menggunakan telefon pengurus:

1. Pengurus buka **Carton Tracker** → tab **Scan**.
2. Pilih jenis yang sama (**Pickup** / **Take over** / **Receive**).
   - Untuk **Pickup**: isi **Lorry No.** lori pemandu.
   - Untuk **Receive**: pilih **Scan location** = outlet yang menerima.
3. Tekan **Live camera scan**.
4. Turun ke bahagian **"Can't scan the barcode?"**.
5. Di kotak **"Manager: key in Carton ID"**, taip **nombor kotak** yang tertulis **di bawah kod bar** pada label (contoh **9000087-01**).
6. Tekan **Save**.
7. Senarai akan tunjuk **OK … (keyed in by manager)**. Sistem merekod nama pengurus.

**Di mana nombor kotak?** Nombor besar di bawah kod bar pada label, contoh `9000087-01` (nombor Transfer + nombor kotak).

### Langkah 3 — Label koyak, hilang atau tidak dapat dibaca langsung: cetak semula

1. **Satu kotak sahaja:** tab **Lookup** → taip nombor kotak → **Find** → **Reprint 9000087-01** → buka PDF → cetak.
2. **Semua kotak satu pindahan:** tab **Transfers** → **Reprint all**.
3. Tampal label baru pada kotak yang betul (lihat **CARTON 1 / 5** pada label).
4. Imbas semula.

---

## E. Amaran merah di skrin

Bila ada masalah, skrin menjadi merah atau kuning dengan bunyi dan getaran. **Baca dahulu**, kemudian tekan **OK, got it**.

| Amaran di skrin | Maksudnya | Apa anda perlu buat |
|---|---|---|
| **Wrong carton! Do not accept** | Kotak ini untuk tempat lain | **Jangan terima.** Pulangkan kepada pemandu. Pejabat sudah dimaklumkan |
| **Received - but no pickup scan** | Kotak sampai tetapi pemandu tidak imbas Pickup | Simpan kotak. Pejabat sudah dimaklumkan. Pengurus akan semak |
| **This carton is not here** | Sistem kata kotak ini di tempat lain | Jangan serahkan. Tanya pengurus |
| **Already delivered** | Kotak ini sudah diterima sebelum ini | Jangan ambil. Tanya pengurus |
| **Not sent out yet** | Pemandu belum imbas Pickup | Minta pemandu imbas Pickup dahulu |
| **Cannot take over** | Tidak boleh Take over (contoh kotak sudah dengan anda) | Baca mesej. Tanya pengurus jika tidak faham |
| **Carton ID not found** | Nombor kotak tiada dalam sistem | Semak label. Imbas sekali lagi. Jika masih sama, beritahu pengurus |

---

## F. Dashboard (laporan)

Tab **Dashboard** ada untuk semua orang. Tiada pilihan tarikh — ia terus tunjuk semua yang belum selesai.

**Staf outlet / gudang / e-commerce:**

- Hanya nampak **outlet sendiri**.
- **Sending out** = kotak yang anda hantar, belum diterima di sana.
- **Coming in** = kotak yang dalam perjalanan ke outlet anda.

**Pemandu / pengurus / pejabat:**

- Nampak **semua outlet**.
- Kotak hijau di atas: **Cartons with you now** = kotak yang anda imbas Pickup / Take over dan belum diterima.

**Tekan mana-mana kotak, baris atau pindahan** untuk lihat nombor kotak di dalamnya. Tekan nombor kotak untuk buka sejarah penuh di Lookup.

### F1. Cara membaca Dashboard

Baca dari atas ke bawah: **kotak nombor → Where are the cartons now? → By destination → Transfers**. Semua nombor ialah kiraan **kotak (carton)**, kecuali "Transfers".

**A. Kotak nombor di atas**

| Kotak | Maksud |
|---|---|
| **Cartons with you now** (hijau) | Kotak yang **anda** imbas Pickup / Take over dan belum diterima. Anda masih bertanggungjawab. (Pemandu / pengurus / pejabat sahaja) |
| **Sending out** / **Coming in** | Outlet sahaja: kotak yang anda hantar keluar / kotak yang akan sampai ke outlet anda. |
| **Transfers** | Bilangan pindahan (nombor Transfer ID), bukan kotak. |
| **Cartons** | Jumlah kotak dalam semua pindahan itu. |
| **Not picked up** | Label sudah dicetak, pemandu belum imbas Pickup. Kotak masih di outlet penghantar. |
| **On the way** | Di atas lori atau dibawa oleh seseorang. |
| **At PI02 warehouse** | Singgah di gudang PI02, belum dihantar ke destinasi. |
| **Received** | Sudah diimbas Receive di destinasi. Selesai. |
| **Outstanding** (oren) | Semua kotak yang **belum diterima** (Not picked up + On the way + At PI02). Peratus = bahagian daripada semua kotak. |
| **Overdue > 10 days** (merah) | Kotak belum sampai lebih 10 hari selepas Register. **Perlu tindakan segera.** |
| **Open issues** | Masalah imbasan yang belum diselesaikan oleh pengurus (tab Issues). |

> **Mudah ingat:** **Outstanding = 0** bermakna semua kotak sudah sampai. Nombor merah = ada masalah, tekan untuk lihat kotak mana.

**B. Where are the cartons now? & By destination**

*Where are the cartons now?* — di mana kotak yang belum diterima berada sekarang:

- **Lorry trip · 20261117-JPK1234** = di atas lori (tarikh-nombor lori).
- **With · nama** = dibawa sendiri oleh orang itu (tanpa lori).
- **PI06 SB MALL** = masih di outlet itu (belum Pickup).
- Bar **biru** = bilangan kotak. Bahagian **berjalur merah** = kotak Overdue.

*By destination* — setiap outlet destinasi: **Outstanding** = kotak belum sampai ke outlet itu, **Overdue** = yang lebih 10 hari. Tekan baris untuk lihat nombor kotak.

**C. Jadual Transfers (setiap pindahan)**

| Lajur | Maksud |
|---|---|
| **Transfer** | Nombor Transfer ID. Outlet nampak tanda **Sending out / Coming in**. Tanda merah **OVERDUE** = lebih 10 hari. |
| **From → To** | Outlet penghantar → outlet penerima (huruf tebal). **VIA PI02** = melalui gudang. |
| **Registered** | Tarikh & masa Register, dan sudah berapa hari. |
| **Progress** | Status pindahan + bar hijau + "**1 / 3 received**" (1 kotak diterima daripada 3). |
| **Not received - now at** | Kotak yang belum diterima berada di mana. Contoh: **Trip 20261117-JPK1234 ×1 · PI03 ×1** = 1 kotak atas lori, 1 masih di PI03. |
| **Last scan** | Masa imbasan terakhir untuk pindahan ini. |
| **Issues** | Bilangan masalah terbuka. Tekan **›** untuk lihat semua kotak dalam pindahan. |

**D. Status pindahan**

| Status | Maksud |
|---|---|
| **Not picked up** | Belum ada kotak yang diambil pemandu. |
| **Partly picked up** | Sebahagian kotak sudah diambil, sebahagian masih di outlet. **Semak kotak yang tertinggal.** |
| **In transit** | Semua kotak sudah keluar, belum ada yang diterima. |
| **Partly received** | Sebahagian kotak sudah sampai. Yang lain masih dalam perjalanan. |
| **Completed** | Semua kotak sudah diterima. Selesai. |

**E. Penapis (bar di atas)**

| Penapis | Guna untuk |
|---|---|
| **Search** & **Status** | Cari Transfer ID / Carton ID / outlet, atau pilih satu status sahaja. |
| **From** & **To** | Pilih outlet penghantar dan / atau penerima. (Pemandu / pengurus / pejabat sahaja) |
| **Lorry trip / person** | Lihat kotak dalam satu lori atau dengan seorang sahaja. |
| **Open only** | Bertanda = sembunyikan pindahan yang Completed. Buang tanda untuk lihat semua. |
| **Refresh** | Muat semula. "Updated …" menunjukkan masa data terakhir. |

> **Apa perlu buat?** Overdue atau Partly picked up lama → telefon outlet / pemandu, cari kotak itu. Kotak hilang → beritahu pengurus.

---

## G. Masalah lain

| Masalah | Penyelesaian |
|---|---|
| Keluar **"Sorry, unable to open the file"** | Telefon ada banyak akaun Google. Log keluar akaun lain, atau buka dengan pelayar lain |
| Keluar akaun tidak dikenali | Gmail anda belum didaftarkan. Beritahu pengurus / HQ |
| Kamera tidak keluar | Buka **Tetapan** telefon → benarkan kamera untuk Chrome / Safari → buka semula |
| Keluar **"Scanning is paused"** | Tekan butang di skrin untuk sambung |
| Keluar **"Session expired"** | Tutup dan buka semula Carton Tracker, log masuk semula |
| Tiada butang **Pickup** | Hanya pemandu dan pengurus boleh imbas Pickup |
| Mahu semak di mana kotak | Tab **Lookup** → taip Transfer ID atau nombor kotak → **Find** |

---

## H. Peraturan emas

1. **Setiap kotak mesti ada label** sebelum keluar — termasuk barang pulangan.
2. **Tiada label = pemandu tidak ambil.**
3. **Pemandu imbas Pickup sendiri.** Outlet tidak boleh imbas bagi pihak pemandu.
4. **Setiap serahan mesti diimbas.** Selagi penerima belum imbas, penyerah masih bertanggungjawab.
5. **Imbas Receive sebelum kotak masuk kedai.**
6. **Wrong carton = jangan terima.**
7. **Tidak dapat imbas = panggil pengurus.** Staf biasa tidak taip nombor kotak.
8. Pindahan lebih 10 hari belum sampai akan ditanda **Overdue**.

**Perlu bantuan?** Hubungi pengurus anda atau Office Operation.
