# Rangkuman Insight Survei Gen Z × PayLater × Kredivo
**Tim StacyTwo · DBCC 2026 Semifinal · Bahan pitch deck WOW Strategy**

Sumber angka: `analisis-survei-genz-kredivo.ipynb` (n = 103 responden Gen Z usia 18–26). Semua grafik yang dirujuk ada di `outputs/figures/`.

> ⚠️ **Catatan data sebelum dipakai di slide.** Dataset saat ini terindikasi berisi **100 respons simulasi + 3 respons observasi** (pola tanggal 26–28 Sep 2026 sesuai `docs/context.md` poin 25; korelasi antar-pertanyaan hampir nol, Cronbach's α ≈ 0,08–0,15). Gunakan dokumen ini untuk **menyusun storyline, struktur slide, dan desain chart**. Sebelum presentasi, jalankan ulang notebook dengan respons asli. Angka di bawah akan berubah, tetapi strukturnya tetap. Jangan menulis "103 responden riil" selama flag `DATA_MENGANDUNG_SIMULASI = True`.
>
> Label sumber yang disarankan di slide (setelah data riil): *Primary Survey StacyTwo, n = XX, Gen Z, 2026*.

**Definisi singkat**
- **T2B (Top-2-Box)** = % responden yang menjawab 4 (setuju) atau 5 (sangat setuju) pada skala 1–5.
- **TOM (unaided top-of-mind)** = brand yang pertama kali disebut saat mendengar kata "PayLater", tanpa diberi pilihan.
- **pp** = poin persentase (selisih dua persentase).

---

## 1. Ringkasan Eksekutif (untuk slide Executive Summary)

1. **Kredivo dikenal, tetapi tidak diingat pertama.** 79,6% Gen Z familiar dengan Kredivo, tetapi hanya **20,4%** yang menyebutnya pertama kali. SPayLater memimpin dengan 41,7%.
2. **Gen Z tidak menolak PayLater karena kurang fitur, melainkan karena cemas soal biaya.** 65% hambatan terkait bunga, kejelasan biaya, dan takut boros. Hanya 5,8% yang mengeluhkan merchant/promo.
3. **Trust dan kejelasan biaya adalah medan pertempuran utama.** 89,3% menyatakan transparansi biaya menentukan kepercayaan, tetapi hanya 48,5% yang paham biaya & risikonya (**Clarity Gap 41 pp**).
4. **Promo menarik perhatian kategori, tetapi tidak memenangkan Kredivo.** 79,6% terdorong promo, sementara niat memakai Kredivo dalam 6 bulan hanya 46,6%.
5. **Dari "kenal" sampai "berniat pakai", hanya 7,8% yang lolos seluruh funnel.** Kebocoran terjadi di tiga titik (Remember → Prefer → Act), persis sesuai diagnosis WOW Strategy.

> **One-liner:** *Kredivo is seen, but not yet remembered, chosen, and used.*

---

## 2. Hero Numbers — Angka Paling Kuat untuk Slide

| # | Angka | Makna | Slide yang cocok |
|---|---|---|---|
| 1 | **79,6% → 20,4%** | Familiar dengan Kredivo → menyebut Kredivo pertama (unaided) | The Paradox |
| 2 | **41,7% vs 20,4%** | TOM SPayLater vs Kredivo; Kredivo sejajar GoPayLater (20,4%) | The Paradox / Competitive Landscape |
| 3 | **10%** | TOM Kredivo di kalangan **karyawan** (4 dari 39 orang); SPayLater 46% | Root Cause — Salience Gap |
| 4 | **89,3% vs 48,5%** | Transparansi penting vs paham biaya & risiko → **Clarity Gap 41 pp** | Root Cause — Preference Gap / Smart Choice |
| 5 | **65%** | Hambatan terkait biaya, kejelasan & kontrol finansial | Consumer Research / Smart Choice |
| 6 | **38,1% vs 70,7%** | Trust pada Kredivo di antara yang **mengingat Kredivo pertama** vs responden lain | Root Cause — "Diingat ≠ dipercaya" |
| 7 | **79,6% vs 46,6%** | Terdorong promo vs berniat memakai Kredivo 6 bulan | Root Cause — Activation Gap |
| 8 | **7,8%** | Lolos seluruh funnel kumulatif (kenal → diingat → percaya → pertimbangkan → berniat) | Root Cause summary |
| 9 | **58,3%** | Alasan #1 memakai PayLater: mengatur cash flow (promo hanya 37,9%) | Positioning — Responsible Financial Flexibility |
| 10 | **76,7% vs 50,8%** | Non-pengguna yang tertarik mencoba vs benchmark nasional (Laporan PayLater Indonesia 2024) | Opportunity / Market |
| 11 | **26,7%** | Pengguna PayLater yang sudah berhenti (16 dari 60) | WOW Loop |
| 12 | **24 orang (23,3%)** | Sudah mempertimbangkan Kredivo, tetapi belum berniat memakai → pool aktivasi | Kredivo NOW |

---

## 3. Top 10 Insight

### Insight 1 — The Salience Paradox: Kredivo dikenal, tetapi bukan yang pertama diingat
**Slide headline:** *Known by most, remembered first by few.*

| Tingkat ingatan | % responden |
|---|---|
| Familiar dengan Kredivo (aided, T2B) | **79,6%** |
| Kredivo salah satu brand pertama yang diingat (aided, T2B) | **49,5%** |
| Kredivo = brand PERTAMA yang disebut (unaided TOM) | **20,4%** |

- Unaided TOM: **SPayLater 41,7%**, GoPayLater 20,4%, **Kredivo 20,4%**, Akulaku 10,7%, Atome 3,9%, Traveloka PayLater 2,9%.
- Kebocoran dari "kenal" ke "diingat pertama": **−59 pp**. Selisih familiar vs aided recall signifikan secara statistik (Wilcoxon, p < 0,001).
- **So what:** Masalah Kredivo bukan awareness, tetapi **mental availability**. SPayLater dan GoPayLater menempel pada ekosistem yang dibuka setiap hari, sedangkan Kredivo tidak punya "rumah" ekosistem seperti itu. Karena itu Kredivo butuh **distinctive brand asset** sendiri.
- **WOW:** *Widening the Mindshare* → **WOW Content** (lagu ikonik + hero video + short-form).
- Grafik: `08a_top_of_mind.png`, `08b_salience_ladder.png`

### Insight 2 — Salience Gap paling tajam justru di segmen yang paling monetizable
**Slide headline:** *Kredivo is weakest where the money is.*

| Segmen | TOM Kredivo | TOM SPayLater | TOM GoPayLater |
|---|---|---|---|
| Pelajar/Mahasiswa (n=40) | **30%** | 35% | 15% |
| Freelancer/Wirausaha (n=15) | 33% | 47% | 20% |
| **Karyawan (n=39)** | **10%** | 46% | 26% |
| Penghasilan Rp1–<4 jt (n=32) | 31% | 44% | 9% |
| **Penghasilan ≥ Rp4 jt (n=44)** | **14%** | 45% | 27% |

- Karyawan juga paling rendah familiaritasnya (72% vs 85% mahasiswa) dan niat pakainya (38% vs 48% mahasiswa).
- **So what:** Segmen yang **sudah berpenghasilan dan eligible kredit** paling jarang memikirkan Kredivo. Mereka justru mengingat brand ekosistem (SPayLater + GoPayLater = 72% di kalangan karyawan). Konten Kredivo harus menjangkau momen *first job, payday, dan early career*, bukan hanya kampus.
- **WOW:** WOW Content dengan tema *payday & first job*, plus **Kredivo Spots** di titik kerja/mall, bukan hanya di kampus.
- Grafik: `08c_tom_per_segmen.png`, `09c_funnel_per_segmen.png`

### Insight 3 — Brand diingat lewat konten & kehadiran, bukan lewat "kata teman"
**Slide headline:** *Content and presence build memory; word-of-mouth alone doesn't.*

| Pernyataan | T2B | Tidak setuju (1–2) |
|---|---|---|
| Konten lifestyle Gen Z membuat brand mudah diingat | **75,7%** | 8,7% |
| Kehadiran di kampus/mall/merchant/event membuat brand mudah diingat | **70,9%** | 10,7% |
| Rekomendasi creator/komunitas membuat saya tertarik | 56,3% | 14,6% |
| Rekomendasi teman/keluarga memengaruhi pilihan | **46,6%** | **31,1%** |

- Rekomendasi teman adalah driver **terlemah** dari 12 faktor, dan hampir 1 dari 3 responden menolaknya.
- **So what:** Ini memvalidasi **urutan prioritas** di pilar Widening: **WOW Content sebagai flagship** (bobot terbesar), **Spots dan Community sebagai amplifier**. Creator (56%) lebih efektif daripada teman (47%), jadi Community sebaiknya berbasis **creator & komunitas terkurasi**, bukan program referral generik.
- **WOW:** WOW Content (flagship) + Kredivo Spots + Kredivo Community.
- Grafik: `07a_likert_sikap_paylater.png`, `07b_ranking_driver.png`

### Insight 4 — Trust adalah tiket masuk; fitur fungsional sudah menjadi hygiene factor
**Slide headline:** *Speed gets you considered. Trust gets you chosen.*

| Decision driver | T2B |
|---|---|
| Transparansi biaya, bunga & cicilan memengaruhi kepercayaan | **89,3%** |
| Keamanan data & kredibilitas penyedia memengaruhi pilihan | **88,3%** |
| Proses daftar & transaksi cepat | 81,6% |
| Promo, cashback & deals | 79,6% |
| Banyaknya merchant online/offline | 77,7% |

- Hanya 1,9% responden yang tidak setuju bahwa transparansi penting, dan 3,9% untuk keamanan. Ini hampir konsensus.
- Importance–Performance Analysis: kecepatan, merchant, dan keamanan tinggi di sisi *stated importance*, tetapi lemah hubungannya dengan niat memakai Kredivo. Artinya faktor-faktor ini **wajib ada** (hygiene), tetapi **tidak membedakan** karena semua pemain PayLater sudah memilikinya.
- **So what:** Mengulang pesan "cepat & mudah" tidak akan memenangkan Gen Z. Pesan Kredivo harus bergeser ke **transparent, secure, and in control**, sesuai root cause *Low Functional Differentiation*.
- **WOW:** *Owning the Preference* → positioning **Responsible Financial Flexibility**.
- Grafik: `07b_ranking_driver.png`, `12c_importance_performance.png`

### Insight 5 — Clarity Gap 41 poin: Gen Z menuntut transparansi, tetapi belum paham biayanya
**Slide headline:** *Gen Z demands clarity they don't yet have.*

| Segmen | Transparansi penting | Paham biaya & risiko | Clarity Gap |
|---|---|---|---|
| **Total** | 89,3% | 48,5% | **41 pp** |
| Pelajar/Mahasiswa | 90% | 40% | **50 pp** |
| Calon Pengguna | 91% | 45% | 45 pp |
| **Target Inti (Persona Raka)** | 92,9% | 45,2% | **48 pp** |
| Karyawan | 85% | 49% | 36 pp |

- 22,3% responden secara eksplisit **tidak paham** biaya, bunga, jatuh tempo & risiko (skor 1–2).
- Selisih ini signifikan secara statistik (Wilcoxon, p < 0,001).
- Benchmark: Laporan PayLater Indonesia 2024 mencatat 86,7% konsumen *tahu* ada bunga. Survei ini menunjukkan bahwa **tahu ada bunga ≠ paham total biayanya**.
- **So what:** Kebutuhan terbesar yang belum terpenuhi bukan limit atau promo, tetapi **kejelasan sebelum memutuskan**. Inilah celah yang diisi **Kredivo Smart Choice**.
- **WOW:** **Kredivo Smart Choice** (flagship Owning).
- Grafik: `07c_clarity_gap.png`

### Insight 6 — Hambatan utama adalah kecemasan finansial, bukan kurangnya fitur
**Slide headline:** *The barrier isn't access — it's anxiety.*

| Hambatan utama (1 pilihan) | % | Tema |
|---|---|---|
| Khawatir bunga atau biaya tambahan | **35,9%** | Biaya & Kejelasan |
| Khawatir boros / berutang berlebihan | 15,5% | Kontrol Finansial |
| Biaya dan ketentuan belum cukup jelas | 13,6% | Biaya & Kejelasan |
| Belum membutuhkan PayLater | 11,7% | Relevansi & Momen |
| Khawatir keamanan data pribadi | 8,7% | Keamanan & Trust |
| Khawatir tidak memenuhi kelayakan kredit | 8,7% | Kelayakan |
| Merchant/promo relevan masih terbatas | **5,8%** | Relevansi & Momen |

- **Biaya & Kejelasan = 49,5%**; ditambah Kontrol Finansial = **65%** hambatan dapat dijawab langsung oleh Smart Choice.
- Kata **"khawatir"** muncul di 69% jawaban hambatan (word cloud).
- Di antara **non-pengguna** (n=43): 46,5% menyebut bunga/biaya sebagai hambatan utama.
- Benchmark nasional: alasan non-pengguna PayLater terbesar adalah *tidak mau menambah utang* (53,7%) dan *takut denda telat bayar* (35,3%). Polanya konsisten.
- **So what:** Menambah merchant atau promo hanya menyentuh 5,8% hambatan. Mengurangi **ketidakpastian biaya** menyentuh 2/3 hambatan.
- **WOW:** Smart Choice + Kredivo Proof.
- Grafik: `10a_hambatan.png`, `15a_word_cloud.png`

### Insight 7 — Diingat ≠ dipercaya ≠ dipilih
**Slide headline:** *Remembering Kredivo doesn't mean trusting Kredivo.*

| Kelompok | Percaya Kredivo aman & andal (T2B) |
|---|---|
| Menyebut Kredivo pertama (n=21) | **38,1%** |
| Menyebut brand lain (n=82) | **70,7%** |

Selisih ini signifikan (Mann-Whitney, p = 0,010).

| Target Inti (Persona Raka, n=42) vs responden lain (n=61) | Target Inti | Lainnya |
|---|---|---|
| Kredivo diingat (aided recall) | **61,9%** | 41,0% |
| Percaya Kredivo | 73,8% | 57,4% |
| **Mempertimbangkan Kredivo** | **38,1%** | **63,9%** |
| Berniat memakai | 52,4% | 42,6% |

Selisih pertimbangan ini signifikan (Mann-Whitney, p = 0,002).
- **So what:** Awareness yang tinggi tidak otomatis menjadi preferensi. Bahkan persona Raka, yang paling mengingat Kredivo, justru paling rendah pertimbangannya. **Widening tanpa Owning akan bocor.** Ini argumen terkuat mengapa WOW harus menjadi **sistem terintegrasi**, bukan kampanye awareness saja.
- **WOW:** Widening → Owning (Smart Choice + Proof + Fit) → Winning.
- Grafik: `10c_diingat_vs_dipercaya.png`, `14a_target_inti_vs_lain.png`

### Insight 8 — PayLater adalah alat kontrol cash flow; promo tidak memenangkan Kredivo
**Slide headline:** *Gen Z doesn't want more spending power — they want control.*

| Alasan memakai PayLater (pilih 3) | % |
|---|---|
| Mengatur cash flow/pengeluaran | **58,3%** |
| Fleksibilitas waktu pembayaran | **56,3%** |
| Memenuhi kebutuhan mendesak | 44,7% |
| Tersedia di merchant yang digunakan | 37,9% |
| Promo, cashback, atau diskon | **37,9%** |
| Mencicil pembelian bernilai besar | 30,1% |
| Lebih mudah daripada kartu kredit | 25,2% |

- Promo mendorong 79,6% responden untuk *mencoba PayLater*, tetapi **niat memakai Kredivo hanya 46,6%** (Wilcoxon, p < 0,001).
- Niat memakai Kredivo di antara yang sangat terdorong promo (47,6%) **hampir sama** dengan yang tidak (42,9%). Promo generik tidak menggerakkan niat.
- Pada Mantan Pengguna, alasan "mengatur cash flow" mencapai **88%** dan "fleksibilitas" 81%. Kebutuhan fungsionalnya masih ada, hanya belum dijawab dengan tepat.
- **So what:** Diskon massal hanya membeli *trial* kategori. Yang memenangkan Kredivo adalah **penawaran kontekstual di momen yang tepat**, dibingkai sebagai kontrol cash flow.
- **WOW:** Kredivo NOW (occasion-based) + Kredivo Deals (contextual), bukan diskon generik.
- Grafik: `06a_alasan_paylater.png`, `11a_activation_gap.png`

### Insight 9 — Funnel bocor di tiga titik; ada 24 orang yang "tinggal didorong"
**Slide headline:** *From 80% aware to 8% ready to act.*

| Tahap (kumulatif: lolos tahap ini DAN semua sebelumnya) | % | Orang | Hilang dari tahap sebelumnya |
|---|---|---|---|
| Familiar | 79,6% | 82 | — |
| Diingat (aided) | 38,8% | 40 | **−51%** → Salience Gap |
| Percaya | 24,3% | 25 | −38% |
| Mempertimbangkan | 11,7% | 12 | **−52%** → Preference Gap |
| Berniat pakai (6 bulan) | **7,8%** | 8 | −33% → Activation Gap |

**Status aktivasi Kredivo:**

| Status | Orang | % |
|---|---|---|
| Siap aktivasi (pertimbangkan & berniat) | 31 | 30,1% |
| **Mempertimbangkan, belum berniat** | **24** | **23,3%** |
| Berniat, belum yakin memilih | 17 | 16,5% |
| Belum terbentuk | 31 | 30,1% |

- Pool aktivasi (24 orang) terdiri dari 10 calon pengguna, 10 pengguna aktif PayLater, dan 4 mantan pengguna. Hambatan utama mereka: bunga/biaya (10), ketentuan tidak jelas (4).
- Kebutuhan mereka: **pendidikan/kerja 58%**, darurat 50%, gadget 46%.
- **So what:** Angka funnel kumulatif ini adalah **pengganti berbasis data primer** untuk ilustrasi funnel 74/28/13/7 di proposal yang belum tertrace sumbernya. Pool 24 orang adalah target paling efisien untuk Kredivo NOW: preferensinya sudah ada, tinggal pemicu dan kejelasan biaya.
- **WOW:** Kredivo NOW + Smart Choice di titik checkout.
- Grafik: `09a_funnel_per_tahap.png`, `09b_funnel_kumulatif.png`, `11c_pool_aktivasi.png`

### Insight 10 — Momen kebutuhan jelas, pasar masih terbuka, tetapi retensi bocor
**Slide headline:** *Right moment, open market, leaky bucket.*

| Kebutuhan PayLater (pilih 3) | % | Momen Kredivo NOW |
|---|---|---|
| Gadget & elektronik | **55,3%** | Gadget upgrade · payday |
| Pendidikan/kebutuhan kerja | **51,5%** | Semester baru · first job |
| Kebutuhan darurat | **45,6%** | Urgent purchase |
| Makanan & minuman | 37,9% | Weekend hangout |
| Fashion | 32,0% | Payday · lifestyle |
| Beauty/personal care | 30,1% | Self-care |
| Transportasi/travel | 25,2% | Liburan · mudik |
| Token listrik | 22,3% | Tagihan rutin · tanggal tua |

- Bundle kebutuhan tersering: **darurat + pendidikan/kerja (26%)**, pendidikan/kerja + gadget (24%), darurat + gadget (24%).
- Kebutuhan berbeda per segmen: karyawan fokus **gadget 62%** dan pendidikan/kerja 56%; freelancer fokus **F&B 67%**; pelajar lebih sering memilih token listrik (35%).
- **Pasar terbuka:** 76,7% non-pengguna tertarik mencoba PayLater, jauh di atas benchmark nasional 50,8%.
- **Retensi bocor:** 26,7% dari yang pernah memakai PayLater sudah berhenti. Mantan pengguna paling banyak menyebut **"belum membutuhkan" (38%)** dan **"ketentuan belum jelas" (31%)**. Tidak ada yang menyebut bunga. Mereka pergi karena **kehilangan relevansi**, bukan karena biaya.
- **So what:** Akuisisi saja tidak cukup. Kredivo harus hadir kembali di **momen kebutuhan berikutnya** (next relevant offer).
- **WOW:** Kredivo NOW + Kredivo Fit + **WOW Loop** (repeat, win-back, referral).
- Grafik: `06b_kebutuhan_momen.png`, `06d_bundle_kebutuhan.png`, `05a_adopsi_paylater.png`

---

## 4. Kenapa Orang Tidak Mau Pakai PayLater / Kredivo?

### 4.1 Lima alasan utama (diurutkan dari dampak terbesar)
1. **Takut biaya tersembunyi & bunga (35,9%).** Gen Z tidak tahu total yang harus dibayar di akhir. Ini hambatan #1 di hampir semua segmen dan mencapai **48% pada pelajar/mahasiswa** dan **48% pada calon pengguna**.
2. **Takut kehilangan kendali: boros & terjerat utang (15,5%).** Hambatan ini paling tinggi pada **pengguna aktif (18%)** dan target inti Raka (21%). Artinya justru yang sudah memakai PayLater merasakan risikonya.
3. **Ketentuan tidak jelas (13,6%).** Hambatan ini mencapai **31% pada mantan pengguna** dan 30% pada kelompok tidak tertarik. Pengalaman memakai PayLater tidak membuat ketentuannya lebih jelas.
4. **Tidak merasa butuh / tidak relevan (11,7%).** Hambatan ini mencapai **38% pada mantan pengguna**. PayLater dilupakan setelah kebutuhan awal selesai.
5. **Keamanan data & kelayakan kredit (masing-masing 8,7%).** Keduanya lebih tinggi pada karyawan (13%) dan pengguna aktif (14%). Kekhawatiran eligibility tertinggi di penghasilan Rp1–<4 jt (16%).

### 4.2 Hambatan berbeda di setiap grup (Chi-square p = 0,003)

| Grup | n | Hambatan #1 | Hambatan #2 | Jawaban WOW |
|---|---|---|---|---|
| **Calon Pengguna** (belum pernah, tertarik) | 33 | Bunga/biaya **48%** | Boros 15% | Smart Choice: simulasi total biaya |
| **Pengguna Aktif** | 44 | Bunga/biaya **39%** | Boros 18%; data & eligibility masing-masing 14% | Smart Choice + Proof |
| **Mantan Pengguna** | 16 | Belum butuh **38%** | Ketentuan tidak jelas **31%** | Kredivo Fit + NOW + WOW Loop (win-back) |
| **Tidak Tertarik** | 10 | Bunga/biaya 40% | Ketentuan tidak jelas 30% | Proof & edukasi; bukan prioritas akuisisi |

> **Takeaway slide:** *Every group hesitates for a different reason — one message won't convert them all.*

---

## 5. Apa yang Harus Ditingkatkan Kredivo (Prioritas)

| Prioritas | Area | Bukti survei | Baseline (untuk KPI) | Pilar WOW |
|---|---|---|---|---|
| **1** | **Kejelasan biaya sebelum keputusan** | Clarity Gap 41 pp; 49,5% hambatan = biaya & kejelasan | Paham biaya T2B **48,5%** | Owning — Smart Choice |
| **2** | **Trust & bukti keamanan** | 88,3% keamanan menentukan pilihan; yang mengingat Kredivo trust-nya hanya 38,1% | Trust Kredivo T2B **64,1%** | Owning — Kredivo Proof |
| **3** | **Top-of-mind di segmen berpenghasilan** | TOM karyawan 10%; ≥ Rp4 jt 14% | TOM unaided **20,4%** | Widening — WOW Content |
| **4** | **Relevansi personal** | Relevansi = satu-satunya faktor sikap yang signifikan terkait niat pakai (ρ = 0,21; p = 0,03) | Relevansi T2B **64,1%** | Owning — Kredivo Fit |
| **5** | **Aktivasi di momen yang tepat** | Promo 79,6% vs niat 46,6%; pool aktivasi 24 orang | Niat pakai T2B **46,6%** | Winning — Kredivo NOW + Deals |
| **6** | **Retensi & win-back** | 26,7% pengguna berhenti; 38% mantan merasa "belum butuh" | Churn **26,7%** | Winning — WOW Loop |

---

## 6. Apa yang Harus Ada di Kredivo (Must-Have dalam Kerangka WOW)

Semua poin di bawah **berada di dalam mekanisme WOW yang sudah locked** (1 flagship + 2 support per pilar). Poin-poin ini bukan fitur baru terpisah.

### Owning the Preference — Kredivo Smart Choice (flagship)
- **Simulasi total biaya sebelum checkout**: cicilan per bulan, total bayar, dan bunga dalam Rupiah (bukan hanya %) untuk setiap pilihan tenor. *Menjawab 35,9% "khawatir bunga" dan 13,6% "ketentuan tidak jelas".*
- **Rekomendasi tenor sesuai kebutuhan dan kemampuan bayar**: "tenor paling hemat" vs "cicilan paling ringan". *Menjawab 15,5% "takut boros" dan Clarity Gap 41 pp.*
- **Ringkasan ketentuan 1 layar**: jatuh tempo, denda, biaya admin. *Menjawab 31% mantan pengguna yang merasa ketentuan tidak jelas.*

### Owning — Kredivo Proof (support)
- **Trust signal yang terlihat**: status berizin & diawasi OJK, perlindungan data, rating, dan real user stories. *Menjawab 88,3% yang menjadikan keamanan penentu pilihan dan 8,7% yang khawatir data pribadi.*
- **Creator review yang jujur tentang biaya**, bukan sekadar endorsement. *Creator 56,3% lebih dipercaya daripada teman 46,6%.*

### Owning — Kredivo Fit (support)
- **Use-case packs per momen hidup**: semester/kuliah, first job, gadget upgrade, kebutuhan darurat. *Relevansi adalah driver sikap terkuat untuk niat pakai.*
- **Komunikasi eligibility yang jelas sejak awal** (siapa yang bisa daftar & syaratnya). *Menjawab 8,7% yang khawatir tidak lolos kelayakan; 16% di penghasilan Rp1–<4 jt.*

### Widening the Mindshare — WOW Content (flagship) + Community + Spots
- **Satu distinctive brand asset** (lagu ikonik + hero video + 18 short-form) dengan tema *payday, first job, gadget, campus*. *75,7% setuju konten lifestyle membuat brand mudah diingat.*
- **Kehadiran fisik di kampus, mall, dan area kerja**. *70,9% setuju; karyawan TOM hanya 10%, jadi Spots tidak boleh hanya di kampus.*
- **Community berbasis creator & komunitas terkurasi**, bukan referral generik.

### Winning the Market — Kredivo NOW (flagship) + Deals + WOW Loop
- **Trigger berbasis momen**: payday, semester baru, peluncuran gadget, kebutuhan darurat. *Top-3 kebutuhan: gadget 55,3%, pendidikan/kerja 51,5%, darurat 45,6%.*
- **Deals kontekstual & bundle momen**: misalnya paket darurat + pendidikan/kerja (26% memilih keduanya). *Bukan diskon massal: niat pakai tidak berbeda antara yang terdorong promo dan yang tidak.*
- **WOW Loop untuk repeat & win-back**: *next relevant offer* setelah transaksi pertama, reminder di momen kebutuhan berikutnya, dan referral. *Menjawab churn 26,7% dan 38% mantan yang merasa "belum butuh".*

---

## 7. Opportunity Map

| Peluang | Ukuran dalam sampel | Kenapa menarik | Mekanisme WOW |
|---|---|---|---|
| **Calon pengguna yang tertarik** | 33 orang (32,0%) | 76,7% non-pengguna terbuka vs 50,8% nasional | Smart Choice + NOW |
| **Pool aktivasi** | 24 orang (23,3%) | Sudah mempertimbangkan Kredivo; hambatan utama = biaya | NOW + Smart Choice di checkout |
| **Siap aktivasi** | 31 orang (30,1%) | Mempertimbangkan & berniat → jaga agar transaksi pertama terjadi | NOW + Deals |
| **Mantan pengguna (win-back)** | 16 orang (15,5%) | Kebutuhan cash flow masih tinggi (88%); pergi karena relevansi, bukan biaya | WOW Loop + Fit |
| **Karyawan / first-jobber** | 39 orang (37,9%) | Paling eligible, tetapi TOM Kredivo hanya 10% | WOW Content (payday/first job) + Spots |
| **Target Inti Raka** (Surabaya, penghasilan ≥ Rp1 jt) | 42 orang (40,8%) | Recall tinggi (61,9%), pertimbangan rendah (38,1%) | Smart Choice + Proof |

> Angka di atas adalah proporsi **dalam sampel survei**, bukan proyeksi pasar. Untuk sizing pasar, tetap gunakan TAM–SAM–SOM di proposal.

---

## 8. Validasi Persona Raka (Target Inti)

**Definisi di survei:** berdomisili di Surabaya + penghasilan pribadi ≥ Rp1 juta/bulan → **42 responden (40,8%)**. Komposisinya 17 karyawan, 16 pelajar/mahasiswa (magang/part-time), 8 freelancer. Kelompok usia terbesar 21–23 tahun (50%).

| Pain point Raka di proposal | Bukti survei (Target Inti) |
|---|---|
| Khawatir bunga & biaya tambahan | 21,4% hambatan #1 (seri) |
| Khawatir overspending | 21,4% hambatan #1 (seri) |
| Tidak selalu paham tenor & biaya | Paham biaya hanya 45,2%; Clarity Gap **48 pp** (tertinggi) |
| Butuh layanan aman & terpercaya | Keamanan penting 90,5%; khawatir data 14,3% |
| Kebutuhan tidak menunggu payday | Pendidikan/kerja 60%, gadget 55%, darurat 50% |

> **Quote persona tervalidasi:** *"I want more financial flexibility without losing control of my spending."* Hambatan teratas Raka adalah kombinasi **biaya + boros**, persis inti *Responsible Financial Flexibility*.

---

## 9. Empat Segmen Sikap Gen Z (K-Means, indikatif)

| Segmen | % | Ciri utama | TOM Kredivo | Niat pakai | Pendekatan WOW |
|---|---|---|---|---|---|
| **Social Deal Seeker** | 43% | Terpengaruh teman & promo, merasa PayLater relevan | 18% | 52% | Deals + WOW Loop (referral) + Community |
| **Independent Planner** | 24% | Rasional: fokus cepat, cash flow & transparansi; tidak ikut teman | **12%** | 40% | Smart Choice + NOW di momen cash flow |
| **Content & Credibility Seeker** | 21% | Tidak tergerak promo; responsif pada konten & creator | **36%** | 50% | WOW Content + Spots + Proof |
| **Trust Skeptic** | 12% | Ragu keamanan, kurang paham biaya | 17% | **33%** | Proof + Smart Choice; hindari promo agresif |

- Content & Credibility Seeker memiliki TOM Kredivo tertinggi (36%). Ini bukti bahwa **konten bekerja** untuk membangun ingatan.
- Independent Planner (dominan karyawan) memiliki TOM terendah (12%). Mereka adalah sasaran Smart Choice.
- Catatan: silhouette score 0,09 (struktur cluster lemah). Gunakan sebagai **kerangka persona & pesan**, bukan pembagian pasar yang kaku.

---

## 10. Mapping ke Slide Pitch Deck

| Slide | Insight | Angka utama | Grafik |
|---|---|---|---|
| 4. The Paradox | #1 | 79,6% → 20,4%; SPayLater 41,7% | `03_snapshot_eksekutif.png`, `08b_salience_ladder.png` |
| 7. Competitive Landscape | #1 | TOM share 6 brand | `08a_top_of_mind.png` |
| 8. Consumer Research | #6, #8, #10 | 65% hambatan biaya; 58,3% cash flow; 76,7% terbuka | `04a_profil_responden.png`, `10a_hambatan.png`, `06a_alasan_paylater.png` |
| 9. Root Cause Analysis | #2, #4, #5, #9 | Funnel 79,6 → 7,8%; Clarity Gap 41 pp | `09b_funnel_kumulatif.png`, `07c_clarity_gap.png` |
| 10–11. Persona & Journey Raka | Bagian 8 | 42 responden; Clarity Gap 48 pp | `14a_target_inti_vs_lain.png` |
| 13. Widening | #1, #2, #3 | Konten 75,7%, fisik 70,9%; karyawan TOM 10% | `07b_ranking_driver.png`, `08c_tom_per_segmen.png` |
| 14. Owning | #4, #5, #6, #7 | 89,3% vs 48,5%; trust 38,1% vs 70,7% | `07c_clarity_gap.png`, `10c_diingat_vs_dipercaya.png` |
| 15. Winning | #8, #9, #10 | Promo 79,6% vs niat 46,6%; pool 24; churn 26,7% | `11a_activation_gap.png`, `11c_pool_aktivasi.png`, `06b_kebutuhan_momen.png` |
| Lampiran | Semua | Evidence board | `16_wow_evidence_board.png` |

---

## 11. Headline Bank (siap copy ke slide)

- *Known by most. Remembered first by few.*
- *Kredivo is seen, but not yet remembered, chosen, and used.*
- *The barrier isn't access — it's anxiety.*
- *Gen Z demands clarity they don't yet have.*
- *Speed gets you considered. Trust gets you chosen.*
- *Remembering Kredivo doesn't mean trusting Kredivo.*
- *Gen Z doesn't want more spending power — they want control.*
- *From 80% aware to 8% ready to act.*
- *Every group hesitates for a different reason.*
- *Right moment, open market, leaky bucket.*
- *Win the Mind → Win the Choice → Win the Market.*

---

## 12. Catatan Metodologi & Batasan

- **n = 103**, margin of error ±9,7 pp (95%, proporsi 50%). Subsegmen kecil (misalnya *sedang mencari kerja*, n = 9; *tidak tertarik*, n = 10) hanya indikatif.
- **Uji statistik yang mendukung klaim utama:**
  - Wilcoxon familiar vs recall: p < 0,001
  - Wilcoxon transparansi vs paham: p < 0,001
  - Wilcoxon promo vs niat pakai: p < 0,001
  - Mann-Whitney trust berdasarkan TOM: p = 0,010
  - Mann-Whitney pertimbangan Target Inti vs lainnya: p = 0,002
  - Chi-square hambatan × status PayLater: p = 0,003
- **Benchmark eksternal:** *Laporan Perilaku Pengguna PayLater Indonesia 2024* (Kredivo × Katadata Insight Center, n = 6.815). Angka yang dipakai: minat non-pengguna 50,8%; tidak mau menambah utang 53,7%; takut denda 35,3%; 86,7% tahu ada bunga.
- **Data self-reported & non-probability sampling**: survei mengukur persepsi & niat, bukan transaksi aktual.
- **Status data:** lihat catatan di bagian atas. Ganti `dataset.csv` dengan respons riil dan jalankan ulang notebook sebelum angka dipresentasikan.
