# 📊 Customer Feedback & Satisfaction Analysis

Proyek ini menganalisis data **kepuasan pelanggan** berdasarkan feedback mereka terhadap kualitas produk, kualitas layanan, frekuensi pembelian, serta faktor demografis seperti usia dan pendapatan.  
Analisis dilakukan menggunakan **Python (Pandas, Matplotlib)** dan divisualisasikan kembali dalam bentuk **dashboard interaktif di Looker Studio**.

---

## 🎯 Tujuan
- Memahami faktor-faktor yang memengaruhi **Customer Satisfaction Score**.  
- Menjawab pertanyaan:
  - Apakah kualitas produk lebih berpengaruh daripada kualitas layanan?
  - Bagaimana pola kepuasan berdasarkan usia dan pendapatan pelanggan?
  - Apakah pelanggan yang sering berbelanja lebih puas?  

---

## 🛠️ Tools & Library
- **Python**: Pandas, Matplotlib  
- **Google Looker Studio** untuk dashboard interaktif  
- Dataset: *Customer Feedback Satisfaction (CSV)*  

---

## 📌 Analisis Utama
1. **Distribusi Kepuasan Pelanggan**  
   - Sebagian besar pelanggan puas dengan produk dan layanan.  
2. **Faktor yang Mempengaruhi Kepuasan**  
   - `ProductQuality` dan `ServiceQuality` punya korelasi positif paling kuat terhadap kepuasan.  
   - `PurchaseFrequency` berpengaruh, tetapi lebih lemah.  
   - `Income` dan `Age` cenderung netral, lebih berguna untuk segmentasi.  
3. **Visualisasi**  
   - Histogram & bar chart untuk distribusi.  
   - Scatter plot untuk hubungan faktor dengan kepuasan.  
   - Dashboard Looker Studio untuk monitoring interaktif.  

---

## 📊 Dashboard Interaktif
Proyek ini juga memiliki dashboard di Looker Studio yang menampilkan:
- Rata-rata **Customer Satisfaction Score**  
- Perbandingan kepuasan berdasarkan **Product Quality** & **Service Quality**  
- Segmentasi kepuasan berdasarkan **Age & Income**  
- Tren frekuensi pembelian dan hubungannya dengan kepuasan  

*[Link Dasboard](https://lookerstudio.google.com/reporting/74e2d822-d086-41c6-a44e-e41bf8f67913)*

---
