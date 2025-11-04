<h1 align="center">🧠 Text Mining UKM Orbit UIN Bukittinggi</h1>

<p align="center">
  <i>Analisis teks dan eksplorasi tema artikel pada situs resmi UKM Orbit UIN Bukittinggi</i><br>
  <a href="https://ukmorbituinbkt.com/">🌐 Kunjungi Situs</a>
</p>

---

## 🌟 Deskripsi Proyek

Proyek ini merupakan implementasi **text mining** untuk menganalisis dan mengekstraksi informasi dari artikel-artikel yang dipublikasikan di situs resmi [UKM Orbit UIN Bukittinggi](https://ukmorbituinbkt.com/).

Tujuan utama proyek ini adalah untuk **mengumpulkan, membersihkan, dan menganalisis data teks** guna menemukan tema utama, kata kunci dominan, serta pola penyebaran konten dalam kegiatan UKM Orbit.

---

## 🎯 Tujuan Proyek

1. Melakukan **web scraping** terhadap artikel dari situs UKM Orbit.  
2. Menyimpan hasil scraping berupa:
   - Judul  
   - Tanggal publikasi  
   - Penulis  
   - Isi artikel  
   - Tautan sumber  
3. Melakukan **preprocessing teks**, meliputi:
   - Tokenisasi  
   - Stopword removal  
   - Stemming menggunakan *Sastrawi*  
4. Melakukan **analisis teks** untuk menemukan:
   - Frekuensi kata dominan  
   - Visualisasi *word cloud*  
   - Analisis sentimen (opsional)  
   - *Topic modeling* dengan LDA  

---

## ⚙️ Teknologi yang Digunakan

| Kebutuhan         | Library / Tools |
|-------------------|-----------------|
| Scraping Data     | `requests`, `BeautifulSoup4` |
| Analisis Data     | `pandas`, `numpy` |
| Pemrosesan Teks   | `nltk`, `Sastrawi` |
| Visualisasi       | `matplotlib`, `wordcloud` |
| Topic Modeling    | `gensim` |
| Lingkungan        | Python 3.10+ |

---

