## Title Project 
Mental Health Analyze - Capturing global patterns in mental health & work
## Project Overview
Mental Health memengaruhi orang di semua usia, negara, dan industri.
Memahami pola kesehatan mental di tempat kerja, akses ke perawatan, dan
stigma seputar pengungkapan sangat penting untuk membentuk kebijakan dan
intervensi di tempat kerja yang lebih baik. Analisa klasifikasi dan kesimpulan
dari dataset ini bertujuan untuk menganalisa dan mendapatkan insight terkait
mental health sehingga bisa dijadikan acuan untuk tindakan selanjutnya dalam
menangani permasalahan kesehatan mental.
## Raw Dataset Link
Dataset dari Kaggle dengan link:
https://www.kaggle.com/datasets/mahdimashayekhi/mental-health
## Insight & findings (and visualization)
- Usia rata-rata dari responden adalah 41
- Ada 3988 orang yang mencari perawatan
kesehatan mental dan 6012 orang yang tidak
mencari perawatan kesehatan mental.
- Nilai unik pada kolom 'Jenis Kelamin' adalah
'Laki-laki', 'Perempuan', 'Non-biner', dan 'Lebih
suka tidak mengatakan'.
- Diagram lingkaran (Pie Chart) yang
menunjukkan proporsi individu dalam setiap
kategori risiko kesehatan mental.
Conclusion & recommendations
Mental Health merupakan hal yang penting untuk diperhatikan, berdasarkan
hasil analisa, didapatkan insight bahwa usia rata-rata dari responden mental
health di 41 menunjukkan bahwa tidak terbatas pada remaja saja namun bisa
dari orang dewasa juga.
Kemudian presentase orang yang melakukan treatment mental health sebanyak
39.88% dari total keseluruhan pengisi survey menunjukkan banyak orang yang
juga melakukan treatment kesehatan mental.
Selanjutnya terdapat diagram visualisasi yang menunjukkan proporsi individu
dalam setiap kategori risiko kesehatan mental dengan total 58.9% medium,
23.7% high dan 17.4% low.
## AI support explanation
1. _AI Model Used_: 
IBM Granite 3.3 8B (via Replicate + LangChain)
Digunakan untuk insight generation, summarization, dan rekomendasi berbasis hasil analisis
2. _How AI Helped_:
Membantu menganalisis pola yang tidak langsung terlihat.
Menghasilkan ringkasan naratif yang cocok untuk laporan HR
Mempercepat interpretasi visualisasi
3. _Limitations_:
Model tidak memproses seluruh dataset secara langsung.
Jika data yang digunakan dalam sample dataset terlalu banyak (use case dicoba 10.000 row data) rawan terkena error out of memory / permasalahan terkait batasan memori.
