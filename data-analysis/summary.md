# Panduan Isi Slide — Consumer Research Summary (berdasarkan `data-slide.png`)

Dokumen ini menjelaskan **teks apa yang harus mengganti setiap elemen template** di `data-slide.png` (template berasal dari case Livin' Merchant) agar isinya sesuai dengan hasil survei Gen Z × PayLater × Kredivo di `analisis-survei-genz-kredivo.ipynb`.

> ⚠️ **Sebelum slide final:** dataset saat ini terindikasi masih berisi respons simulasi (lihat Bagian 2.4 notebook). Susun layout dan copy slide dengan angka di bawah. Setelah respons asli masuk, ganti `dataset.csv`, *Run All*, lalu perbarui angka di slide memakai `outputs/ringkasan_angka_pitchdeck.csv` dan dokumen ini. Semua angka di bawah dihitung langsung dari dataset (n = 103).

**Bahasa slide:** copy di bawah ditulis dalam **bahasa Inggris** agar konsisten dengan template dan deck. Penjelasan alasan setiap pilihan ditulis dalam bahasa Indonesia.

---

## 0. Gambaran Layout Baru (sekilas)

```
┌─────────────────────────────────────────────────────────────────────────────────────────┐
│ APPENDIX X.                                                                             │
│ Consumer Research: What Gen Z Needs Before Choosing Kredivo                             │
├───────────────────────────┬─────────────────────────────┬───────────────────────────────┤
│ Respondent Profile        │ Students (n = 40)           │ Working Gen Z (n = 54)        │
│ (n = 103)                 │ 55% already earn ≥ Rp1 jt   │ 98% earn ≥ Rp1 jt             │
│ [Domicile]  Surabaya 56%  │ Why They Use PayLater       │ Why They Use PayLater         │
│ [Income]    ≥Rp1 jt 74%   │  4 bars                     │  4 bars                       │
│ [PayLater]  Used it 58%   │ What Makes Them Choose...   │ What Makes Them Choose...     │
│                           │  4 bars                     │  4 bars                       │
│ 65% Cost-Anxious Gen Z    │                             │                               │
│ [80% → 20% Salience Gap]  │                             │                               │
├───────────────────────────┴─────────────────────────────┴───────────────────────────────┤
│ Footnote: survey method, n, definisi Top-2-Box                                          │
└─────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 1. Header Slide

| Elemen template | Teks template | **Ganti menjadi** |
|---|---|---|
| Label appendix | APPENDIX 1. | **APPENDIX [nomor sesuai urutan deck].** |
| Judul | WOW with Kredivo Impact and Conclusion | **Consumer Research: What Gen Z Needs Before Choosing Kredivo** |

**Alternatif judul** (pilih satu, jangan dua-duanya):
- *Gen Z PayLater Survey: Known, but Not Yet Chosen*
- *Who We Surveyed and What Wins Them*

**Alasan:** Judul template berbicara tentang "impact & conclusion", padahal isi slide ini adalah **bukti konsumen**. Judul yang disarankan langsung menyiratkan pesan utama: Gen Z butuh sesuatu (kejelasan & trust) sebelum memilih Kredivo. Ini jembatan ke Smart Choice.

---

## 2. Kolom Kiri — Respondent Profile

### 2.1 Judul kotak
| Template | **Ganti menjadi** |
|---|---|
| Respondent Segmentation Profile (53) | **Respondent Profile (n = 103)** |

Opsional: tambahkan subjudul kecil *"Gen Z, aged 18–26"*. Semua responden berada di rentang usia ini, dan kelompok terbesar 21–23 tahun (49%).

### 2.2 Tiga kotak profil (label oranye | isi)

| Label template | Isi template | **Label baru** | **Isi baru** |
|---|---|---|---|
| Business | F&B & Grocery · N = 44 (83%) | **Domicile** | **Surabaya** · N = 58 Respondents (56%) |
| Years Running | 1+ year in business · N = 42 (79%) | **Income** | **Earning ≥ Rp1 jt/month** · N = 76 Respondents (74%) |
| Accept QRIS? | Yes, QRIS available · N = 50 (94%) | **PayLater Use** | **Have used PayLater** · N = 60 Respondents (58%) |

**Alasan pemilihan tiga kotak ini.** Setiap kotak memvalidasi satu pilar strategi:
- **Domicile → Why Surabaya.** Mayoritas sampel dari kota fokus WOW. Jika ingin angka lebih besar: *East Java incl. Surabaya · N = 84 (82%)*.
- **Income → Target "entering financial independence".** 74% sudah berpenghasilan sendiri, sehingga relevan dan eligible untuk produk kredit. Fakta pendukung (untuk speaker notes): 55% mahasiswa pun sudah berpenghasilan ≥ Rp1 jt.
- **PayLater Use → kategori sudah familiar.** Tantangannya bukan edukasi kategori, tetapi memenangkan pilihan brand.

**Cadangan** (jika ingin mengganti salah satu kotak):
- **Digital Habit** | *Transact digitally almost every day* · N = 64 (62%)
- **Age** | *21–23 years old* · N = 50 (49%)

### 2.3 Big stat (pengganti "89% Wallet-First Merchants")

Template memakai pola: **angka besar + label miring + satu paragraf penjelas dengan 2–3 angka pendukung**. Versi Kredivo:

> # 65% *Cost-Anxious Gen Z*
> **respondents hesitate to use PayLater because of cost:** interest & extra fees (36%), unclear terms (14%), or fear of overspending (16%). **89% say fee transparency drives their trust, yet only 49% truly understand PayLater costs.**

**Sumber angka:**

| Angka | Asal |
|---|---|
| 65% | Tema hambatan Biaya & Kejelasan 49,5% + Kontrol Finansial 15,5% (Notebook Bagian 10) |
| 36% | "Khawatir bunga atau biaya tambahan" 35,9% |
| 14% | "Biaya dan ketentuan belum cukup jelas" 13,6% |
| 16% | "Khawatir boros atau berutang berlebihan" 15,5% |
| 89% vs 49% | T2B transparansi 89,3% vs T2B paham biaya 48,5% → Clarity Gap 41 pp (Notebook Bagian 7.1) |

**Alasan:** Ini adalah insight **"why not"** paling kuat. Angka ini menunjukkan masalahnya kecemasan soal biaya, bukan kurang fitur. Hanya 5,8% yang mengeluhkan merchant/promo. Big stat ini langsung membenarkan **Kredivo Smart Choice**.

**Alternatif big stat** (jika slide lain sudah memakai 65%):
> # 80% *Ecosystem-First Gen Z*
> **name another PayLater first when they hear "PayLater":** SPayLater (42%) or GoPayLater (20%), both built into apps they open every day. Only 20% name Kredivo first.

### 2.4 Callout box bergaris putus-putus (pengganti "68% → 0% Activation Gap")

Pola template: **angka A → angka B + nama gap + dua kalimat (fakta tebal + kalimat punchline)**. Versi Kredivo:

> # 80% → 20% *Salience Gap*
> **80% of Gen Z are familiar with Kredivo, but only 20% name it first.**
> Awareness is not the bottleneck, recall is.

| Angka | Asal |
|---|---|
| 80% | T2B "Saya familiar dengan Kredivo" = 79,6% |
| 20% | Unaided top-of-mind Kredivo = 20,4% (21 dari 103) |

**Alasan:** Callout ini meniru struktur template (awareness tinggi → konversi rendah). Ini juga identik dengan tesis WOW, *"Kredivo is seen, but not yet remembered"*, dan menjadi pintu masuk ke pilar **Widening the Mindshare**.

**Alternatif callout** (lebih "conversion", mirip template asli):
> # 80% → 8% *Conversion Gap*
> **80% know Kredivo, but only 8% pass every stage from recall to trust, consideration, and intent to use.**
> The funnel leaks at every step. WOW closes all three.

(8% = funnel kumulatif 7,8% → Notebook Bagian 9, grafik `09b_funnel_kumulatif.png`.)

> Jangan memakai kedua callout sekaligus di slide yang sama. Pilih **80% → 20%** jika slide ini mendahului Root Cause, atau **80% → 8%** jika slide ini merangkum keseluruhan funnel.

---

## 3. Kolom Tengah & Kanan — Dua Segmen Responden

### 3.1 Pilihan segmentasi (rekomendasi)

Template membagi merchant berdasarkan volume transaksi. Untuk Kredivo, pembagian yang paling tajam dan paling sesuai dengan persona Raka (*Gen Z entering financial independence*) adalah:

| Kolom | Header baru | Sub-label (pengganti "≤ 25 transactions/day") |
|---|---|---|
| Tengah | **Students (n = 40)** | *Pelajar/Mahasiswa · 55% already earn ≥ Rp1 jt* |
| Kanan | **Working Gen Z (n = 54)** | *Employees & freelancers · 98% earn ≥ Rp1 jt* |

**Kenapa pembagian ini:**
- Pembagian ini menggambarkan **transisi Raka**: dari mahasiswa (sudah mulai berpenghasilan) menuju first-jobber.
- Kontras antarsegmen paling kuat: mahasiswa memilih berdasarkan **trust**, sementara Gen Z bekerja memilih berdasarkan **value + trust** (lihat bar di bawah).
- Pembagian ini membuka insight penting: **Kredivo paling lemah di segmen bekerja** (top-of-mind 16,7%; karyawan saja 10,3%), padahal segmen inilah yang paling eligible kredit.

> 9 responden berstatus *sedang mencari kerja* tidak masuk kedua kolom (40 + 54 = 94). Sebutkan di footnote. Template asli juga tidak menjumlahkan kolomnya ke total.

### 3.2 Section 1 per kolom — pengganti "What They Want to Know About Their Business"

**Judul section baru:** **Why They Use PayLater**

Sumber: pertanyaan *"Apa alasan utama Anda menggunakan atau tertarik menggunakan PayLater? (pilih 3)"*. Angka = % responden di segmen tersebut.

| Students (n = 40) | % | Working Gen Z (n = 54) | % |
|---|---|---|---|
| Payment flexibility | **63%** | Managing cash flow | **65%** |
| Managing cash flow | 50% | Payment flexibility | 50% |
| Urgent needs | 45% | Urgent needs | 44% |
| Promo & cashback | 38% | Promo & cashback | 39% |

**Pesan yang terbaca:** Kedua segmen memakai PayLater sebagai **alat kontrol keuangan**, bukan alat belanja lebih banyak. Promo hanya di peringkat ke-4. Mahasiswa butuh **fleksibilitas waktu bayar**; Gen Z bekerja butuh **pengaturan cash flow**. Ini memvalidasi positioning **Responsible Financial Flexibility**.

### 3.3 Section 2 per kolom — pengganti "What Would Make Them Choose Livin' Merchant..."

**Judul section baru:** **What Makes Them Choose a PayLater**

Sumber: pernyataan Likert tentang faktor pilihan. Angka = Top-2-Box (% setuju + sangat setuju). Hanya faktor *pilihan* yang dipakai (konten & kehadiran fisik tidak dimasukkan karena mengukur ingatan, bukan pilihan).

| Students (n = 40) | T2B | Working Gen Z (n = 54) | T2B |
|---|---|---|---|
| Data security & credibility | **93%** | Promo, cashback & deals | **93%** |
| Fee & installment transparency | 90% | Fee & installment transparency | 87% |
| Fast & easy process | 80% | Data security & credibility | 85% |
| Wide merchant network | 73% | Fast & easy process | 83% |

**Pesan yang terbaca:**
- **Mahasiswa = trust-first.** Keamanan (93%) dan transparansi (90%) di puncak; promo hanya 63%. → *Kredivo Proof + Smart Choice.*
- **Gen Z bekerja = value + trust.** Promo melonjak ke 93% (vs 63% di mahasiswa), tetapi transparansi tetap 87%. → *Kredivo Deals kontekstual + Smart Choice*, bukan diskon generik.
- **Transparansi biaya ada di top-2 kedua segmen.** Ini benang merah yang mengikat seluruh slide ke big stat "Cost-Anxious" di kiri.

### 3.4 (Opsional) Chip kecil di bawah header kolom
Jika masih ada ruang di bawah sub-label, tambahkan satu baris kecil untuk memperkuat Salience Gap per segmen:

| Students | Working Gen Z |
|---|---|
| *Name Kredivo first: 30%* | *Name Kredivo first: 17% (employees: 10%)* |

---

## 4. Footnote Slide

| Template | **Ganti menjadi** |
|---|---|
| The survey was conducted independently by the team and distributed primarily to MSMEs in Jabodetabek. | **The survey was conducted independently by the team via Google Form and distributed primarily to Gen Z (18–26) in Surabaya & East Java (n = 103, September 2026). Likert items shown as Top-2-Box (agree + strongly agree). Segment columns exclude 9 job-seeking respondents.** |

Setelah data riil masuk, sesuaikan tanggal dan n. Selama data masih simulasi, **jangan** pakai footnote ini di deck final.

---

## 5. Ringkasan: Tabel Pengganti Lengkap (checklist edit slide)

| # | Elemen | Teks template | Teks baru |
|---|---|---|---|
| 1 | Judul | WOW with Kredivo Impact and Conclusion | Consumer Research: What Gen Z Needs Before Choosing Kredivo |
| 2 | Judul profil | Respondent Segmentation Profile (53) | Respondent Profile (n = 103) |
| 3 | Kotak 1 | Business · F&B & Grocery · N = 44 (83%) | Domicile · Surabaya · N = 58 Respondents (56%) |
| 4 | Kotak 2 | Years Running · 1+ year · N = 42 (79%) | Income · Earning ≥ Rp1 jt/month · N = 76 Respondents (74%) |
| 5 | Kotak 3 | Accept QRIS? · Yes · N = 50 (94%) | PayLater Use · Have used PayLater · N = 60 Respondents (58%) |
| 6 | Big stat | 89% Wallet-First Merchants + paragraf | 65% Cost-Anxious Gen Z + paragraf (Bagian 2.3) |
| 7 | Callout | 68% → 0% Activation Gap | 80% → 20% Salience Gap + "Awareness is not the bottleneck, recall is." |
| 8 | Header kolom tengah | Small-Volume Merchants (n = 26) | Students (n = 40) |
| 9 | Sub-label tengah | ≤ 25 transactions/day | 55% already earn ≥ Rp1 jt |
| 10 | Header kolom kanan | Frequent Flyers (n = 19) | Working Gen Z (n = 54) |
| 11 | Sub-label kanan | > 25 transactions/day | Employees & freelancers · 98% earn ≥ Rp1 jt |
| 12 | Section 1 (2 kolom) | What They Want to Know About Their Business | Why They Use PayLater |
| 13 | Bar section 1 — tengah | Growth rec. 92 / Sales 85 / Cash flow 69 / Best-selling 58 | Payment flexibility 63 / Managing cash flow 50 / Urgent needs 45 / Promo & cashback 38 |
| 14 | Bar section 1 — kanan | Sales 81 / Growth rec. 74 / Cash flow 63 / Period 44 | Managing cash flow 65 / Payment flexibility 50 / Urgent needs 44 / Promo & cashback 39 |
| 15 | Section 2 (2 kolom) | What Would Make Them Choose Livin' Merchant... | What Makes Them Choose a PayLater |
| 16 | Bar section 2 — tengah | Analytics 81 / Personalized 46 / Growth Score 38 / POS 27 | Data security & credibility 93 / Fee transparency 90 / Fast & easy process 80 / Wide merchant network 73 |
| 17 | Bar section 2 — kanan | Analytics 59 / Promotion 41 / Growth Score 33 / Reward 33 | Promo, cashback & deals 93 / Fee transparency 87 / Data security & credibility 85 / Fast & easy process 83 |
| 18 | Footnote | …MSMEs in Jabodetabek. | …Gen Z (18–26) in Surabaya & East Java (n = 103)… |

---

## 6. Catatan Desain

- **Warna:** ganti kuning template dengan palet Kredivo. Biru **#45B7E1** untuk bar/header utama, oranye **#ED7D2A** untuk label kotak profil dan angka big stat. Track bar yang hijau muda sebaiknya diganti abu-abu muda agar tidak terbaca sebagai "status baik".
- **Skala bar:** pakai skala 0–100% yang sama di semua bar agar 93% vs 63% (promo mahasiswa vs bekerja) terlihat jelas bedanya.
- **Highlight:** beri warna oranye (bukan biru) pada bar **Promo 93%** di kolom Working Gen Z. Itu satu-satunya kontras besar antarsegmen dan layak ditonjolkan.
- **Satu pesan per slide:** jika slide terasa padat, section 1 (*Why They Use PayLater*) boleh dipangkas menjadi 3 bar. Section 2 jangan dipangkas karena kontras trust vs value ada di sana.

---

## 7. Speaker Notes (±30 detik)

> "We surveyed 103 Gen Z respondents, mostly in Surabaya, and three-quarters of them already earn their own income. The category is familiar, since 58% have used PayLater. But two problems stand out. First, 80% know Kredivo, yet only 20% name it first. That's our Salience Gap. Second, 65% hesitate because of cost anxiety: 89% say fee transparency drives trust, but only half actually understand PayLater costs. Students choose on trust; working Gen Z choose on value and trust. Both use PayLater to control their cash flow, not to spend more. That's why WOW positions Kredivo as Responsible Financial Flexibility."

---

## 8. Alternatif Segmentasi (jika ingin fokus akuisisi vs retensi)

Jika tim lebih ingin menunjukkan **siapa yang harus diakuisisi vs dipertahankan**, kolom bisa diganti menjadi **PayLater Users** vs **Non-Users**. Semua angka sudah dihitung:

| | **PayLater Users (n = 60)** · *44 active + 16 lapsed* | **Non-Users (n = 43)** · *33 interested + 10 not interested* |
|---|---|---|
| **Why They Use PayLater** | Managing cash flow **70%** · Payment flexibility 65% · Urgent needs 43% · Available at favorite merchants 38% | Promo & cashback **47%** · Urgent needs 47% · Payment flexibility 44% · Managing cash flow 42% |
| **What Makes Them Choose** | Data security **90%** · Fee transparency 88% · Promo 78% · Wide merchant network 77% | Fee transparency **91%** · Fast & easy process 91% · Data security 86% · Promo 81% |
| **Top barrier** | Interest & fees 28% · Overspending 18% | Interest & fees **47%** |
| **Intent to use Kredivo (T2B)** | 52% | 40% |

**Pesan:** Non-user masuk lewat **promo & kecepatan** tetapi tertahan oleh **bunga (47%)** → Smart Choice + Deals. User bertahan karena **kontrol cash flow (70%)** dan menuntut **keamanan (90%)** → Proof + WOW Loop.

Rekomendasi tetap **Students vs Working Gen Z** untuk slide ini, karena lebih sesuai dengan persona Raka dan memperlihatkan Salience Gap di segmen yang paling monetizable.
