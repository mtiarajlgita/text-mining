# 🧠 Text Mining UKM Orbit UIN Bukittinggi

Proyek ini merupakan implementasi **text mining** untuk menganalisis dan mengekstraksi informasi dari artikel-artikel yang dipublikasikan di situs resmi [UKM Orbit UIN Bukittinggi](https://ukmorbituinbkt.com/).

Tujuan utamanya adalah untuk **mengumpulkan, membersihkan, dan menganalisis data teks** agar dapat menemukan tema, kata kunci dominan, serta tren konten yang disebarkan oleh organisasi mahasiswa ini.

---

## 🎯 Tujuan Proyek

1. Melakukan **web scraping** terhadap artikel dari situs UKM Orbit.  
2. Menyimpan hasil scraping (judul, tanggal, penulis, isi artikel, dan tautan).  
3. Melakukan **preprocessing teks**, meliputi:
   - Tokenisasi  
   - Stopword removal  
   - Lemmatization / stemming  
4. Melakukan **analisis teks** seperti:
   - Frekuensi kata  
   - Visualisasi *word cloud*  
   - Analisis sentimen (opsional)  
   - *Topic modeling* menggunakan LDA

---

## ⚙️ Teknologi yang Digunakan

| Kebutuhan | Library / Tools |
|------------|-----------------|
| Scraping Data | `requests`, `BeautifulSoup4` |
| Analisis Data | `pandas`, `numpy` |
| Pemrosesan Teks | `nltk`, `Sastrawi` |
| Visualisasi | `matplotlib`, `wordcloud` |
| Topic Modeling | `gensim` |
| Lingkungan | Python 3.10+ |

---

## 📁 Struktur Folder

---


---

## 🚀 Cara Menjalankan Proyek

**Clone repository :**
   ```bash
   git clone https://github.com/mtiarajlgita/text-mining-ukm-orbit.git
   cd text-mining-ukm-orbit

---

📊 Hasil dan Insight

Beberapa hasil utama dari proyek ini antara lain :

Identifikasi kata-kata paling sering digunakan dalam publikasi UKM Orbit.

Pemetaan tema konten dominan seperti kegiatan mahasiswa, prestasi, dan pengembangan diri.

Dasar untuk analisis media organisasi kampus berbasis data.

Visualisasi hasil analisis kata:

---

📚 Lisensi

Proyek ini dilisensikan di bawah lisensi MIT.
Silakan digunakan, dimodifikasi, dan dikembangkan kembali untuk keperluan edukasi dan riset.

---

✨ Kontributor

Dikembangkan oleh Mutiara Joni Legita (mtiarajlgita)
Mahasiswa dan peneliti muda dalam bidang Text Mining & Data Analysis.

“From text, we extract meaning; from meaning, we build insight.”


