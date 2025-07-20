COVID‑19 Veri Analizi ve Görselleştirme
Bu proje, COVID‑19 pandemisine ait verilerin keşifsel veri analizi (EDA) ve görselleştirilmesini içermektedir. Çalışma Jupyter Notebook ortamında hazırlanmıştır.

📌 İçindekiler
Genel Bakış

Kurulum

Kullanılan Kütüphaneler

Analiz Adımları

Görseller

Geliştirme ve Katkı

Lisans

Genel Bakış
covid19.ipynb dosyasında:

COVID‑19 vaka, ölüm ve iyileşme verileri incelenmiştir.

Zaman serisi verileri üzerinden trendler ve ülkeler arası karşılaştırmalar yapılmıştır.

Grafiklerle pandeminin seyri görselleştirilmiştir.

(Varsa) Temel tahminleme modelleri uygulanmıştır.

Kurulum
Projeyi bilgisayarına klonladıktan sonra:

bash
Kopyala
git clone https://github.com/edaydin1/covid-19.git
cd covid-19
pip install -r requirements.txt  # eğer requirements dosyan varsa
jupyter notebook covid19.ipynb
Eğer requirements.txt yoksa, en az şu kütüphaneler gereklidir:

bash
Kopyala
pip install pandas numpy matplotlib seaborn
Modelleme varsa ek olarak:

bash
Kopyala
pip install scikit-learn
Kullanılan Kütüphaneler
Pandas → Veri işleme ve tablo yönetimi

NumPy → Matematiksel işlemler

Matplotlib & Seaborn → Grafik ve görselleştirme

Scikit-learn (varsa) → Temel makine öğrenmesi modelleri

Analiz Adımları
Veri Yükleme ve Ön İşleme

Eksik verilerin doldurulması, tarih formatlarının düzenlenmesi

Keşifsel Veri Analizi (EDA)

Ülke ve tarih bazlı vaka, ölüm ve iyileşme sayılarının analizi

Görselleştirme

Vaka artış eğrileri, ülkeler arası karşılaştırmalı grafikler
