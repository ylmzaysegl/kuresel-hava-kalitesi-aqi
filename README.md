# Küresel Hava Kalitesi İndeksi (AQI) Analizi ve Makine Öğrenmesi ile Hava Kirliliği Sınıflandırma Sistemi

**Ders:** Araştırma Yöntem ve Teknikleri  
**Öğrenci:** Ayşegül Yılmaz (361526091)  

## Proje Özeti
Bu proje, küresel ölçekteki şehirlerin temel hava kirletici parametrelerini (CO, Ozon, NO2, PM2.5) analiz ederek şehirlerin Hava Kalitesi İndeksi (AQI) kategorilerini denetimli makine öğrenmesi algoritmaları (Gaussian Naive Bayes, Decision Tree, Random Forest) ile sınıflandırmayı amaçlamaktadır.

## Klasör Yapısı
- `analiz/` : Google Colab veri analizi ve modelleme notebook dosyası (`AQI_Siniflandirma_Analizi.ipynb`)
- `rapor/` : Vize ve final akademik proje raporları
- `diyagramlar/` : Use Case, Class ve Activity UML diyagramları

## Veri Seti
- **Kaynak:** Kaggle – *Global Air Pollution Dataset* (23.463 gözlem, 12 değişken)
- **Hedef Değişken:** `AQI Category` (Good, Moderate, Unhealthy for Sensitive Groups, Unhealthy, Very Unhealthy, Hazardous)
