# README-BigData-Kel3
Laporan README Kelompok 3 Kelas Big Data A

LAPORAN PROJECT AKHIR (EAS) "Simulasi Rekayasa Data Real-Time dan Pemodelan Prediktif Saham Unggulan AS Menggunakan PySpark"
# 📊 Big Data Project - Kelompok 3

Proyek ini dibuat sebagai bagian dari tugas akhir mata kuliah **Big Data (EAS)** dengan topik:

> **REAL-TIME DATA ENGINEERING AND PREDICTIVE MODELING FOR TOP LEADING COMPANY**

---

## 👥 Kelompok 3
- Sigit Triyono (23083010071)
- Raditya Hylmi Maulana Putra (23083010083)  
- Muhammad Maulana Yusuf (23083010094)  
- Daffa Maulana Briliansyah (23083010098)

---

## 🎯 Tujuan Proyek
Membangun sistem end-to-end yang mampu:
- Mengalirkan data historikal saham secara simulasi real-time menggunakan Kafka.
- Memproses data tersebut dengan PySpark Structured Streaming.
- Memprediksi pergerakan harga saham menggunakan model time series.
- Menampilkan hasil dalam bentuk dashboard interaktif.

---
## 🧱 Arsitektur Sistem

1. **Data Ingestion:** Yahoo Finance API → Kafka (simulasi real-time)
2. **Real-Time Processing:** PySpark Structured Streaming
3. **Storage:** PostgreSQL
4. **Machine Learning:** Model ARIMA / regresi (PySpark MLlib)
5. **Visualization:** Metabase & Streamlit Dashboard

---
## 🧰 Teknologi yang Digunakan
| Komponen            | Teknologi                      |
|---------------------|-------------------------------|
| Data Ingestion      | Yahoo Finance API, Apache Kafka |
| Stream Processing   | PySpark Structured Streaming   |
| Data Storage        | PostgreSQL                     |
| Machine Learning    | PySpark MLlib (Regression)     |
| Visualisasi         | Metabase, Streamlit            |
| Infrastruktur       | Docker, Python                 |

---

## 🧪 Metodologi

1. **Pengambilan Data:**  
   Mengambil data historikal saham (50 top US companies) dari Yahoo Finance selama 1 bulan terakhir.

2. **Simulasi Streaming:**  
   Data dikirim bertahap ke Kafka agar seolah-olah real-time.

3. **Stream Processing:**  
   PySpark melakukan cleaning dan transformasi lalu menyimpan ke PostgreSQL.

4. **Modeling:**  
   Membangun model prediksi harga saham dengan regresi atau ARIMA.

5. **Visualisasi:**  
   Dashboard interaktif menggunakan Metabase & Streamlit.

---

## 📁 Struktur Folder
