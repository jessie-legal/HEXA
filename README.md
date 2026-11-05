**HEXA**Heavy Equipment Expansion & Segment Analysis

[Beranda](#x)[Sumber Data AOL](#x) [Dashboard SegmentasiBARU](#x) [Pengaturan Target](#x)

Terhubung ke AOL

# HEXA · Segmentasi Usaha Customer Heavy Equipment

MOCKUP · data dummy · aplikasi terpisah dari AOL (agar AOL tetap ringan), data terintegrasi otomatis

Data terintegrasi dengan AOL · sinkron otomatis (dummy)

Tampilan sebagai

Cakupan

Wilayah

Periode

Status aplikasi

Ukuran

### Komposisi segmen vs target

Bar biru = share aktual · garis merah = target share segmen

### Peluang segmen berikutnya

Peluang = segmen dengan gap terbesar terhadap target. Rekomendasi leads menyusul saat data tersedia.

### Rincian per segmen

### Matriks wilayah × segmen (% dari total wilayah)

### Daftar aplikasi pada cakupan terpilih

Klik baris (di versi nyata) membuka detail aplikasi di AOL. Tombol Export untuk Dept. Head.

### Catatan analisis untuk AO

### Catatan saya

Mockup: catatan belum tersimpan permanen.

### Komponen/kolom yang perlu ada di AOL (usulan)

| Kolom | Sumber | Keterangan |
| --- | --- | --- |
| No. Aplikasi | AOL | Kunci data |
| Nama Customer / ID Customer | AOL | Hitung unik customer |
| Segmen Usaha | Master segmentasi | Dropdown wajib diisi AO saat input aplikasi |
| Sub-segmen / Kode KBLI | Master segmentasi | Opsional, untuk pemetaan lebih detail |
| Nama AO (Sales) | AOL | Filter level Sales |
| Wilayah / Cabang AO | AOL (struktur tim) | Palembang, Medan, DKI, Balikpapan, Banjarmasin, Samarinda |
| Koordinator (Barat/Timur) / HE Head / Division Head | AOL (struktur tim) | Filter level atasan; Timur kosong → mapping ke Barat / HE Head |
| Tanggal Aplikasi | AOL | Filter periode & tren |
| Status Aplikasi | AOL | Reject / Process / Valid |
| L9MV (Last 9 Month Valid) | AOL | Jumlah aplikasi valid dalam 9 bulan terakhir (pembagi F9PD Compre) |
| F9PD Compre (flag per aplikasi) | Sistem pembiayaan | Overdue >30 hari tiap bulan selama 9 bulan angsuran pertama; dihitung dari tanggal jatuh tempo. Formula — AO: unit OVD >30 selama 9 bulan periode angsuran ÷ L9MV; Coordinator: sama, per team; Dept. Head: jumlah unit ever 30 ÷ jumlah unit valid (s/d angsuran ke-9) |
| Alasan flag Compre hilang | Sistem pembiayaan | Bayar current + denda; untung saat tarik & lelang; atau lewat masa F9PD (9 bulan) |
| Balance >30 (bucket overdue) | Sistem pembiayaan | Overdue 31 hari s.d. write-off (150 hari). Bucket 31–60 ditangani ARRO; bucket 61–150 ditangani REMO |
| Amount Finance (AF) | AOL | Pokok hutang yang dibiayai ACC. AF = OTR − (DP + Bunga + Asuransi Kendaraan (Kredit) + ACP) |
| Account Receivable (AR) | AOL / sistem pembiayaan | Total piutang (pokok hutang, admin, asuransi, dll) |
| Average Selling Rate (ASR) | AOL | Rata-rata rate/bunga yang dijual ke customer |
| Jenis Unit (excavator, dump truck, dll) | AOL | Opsional, analisis lanjutan |
| Target share per segmen | Master target | Diatur manajemen, bisa disesuaikan |
