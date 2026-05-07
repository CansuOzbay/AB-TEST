# AB-TEST
# A/B Testi ile Dönüşüm Oranı Analizi (E-ticaret)

Bu proje, bir e-ticaret uygulamasında sunulan %50 indirim teklifinin kullanıcıların satın alma (conversion) davranışları üzerindeki etkisini istatistiksel yöntemlerle analiz eder.

## 📊 Proje Özeti
- **Amaç:** İndirim teklifinin dönüşüm oranlarını anlamlı derecede artırıp artırmadığını test etmek.
- **Yöntem:** Python, Pandas, Statsmodels (Z-Testi), Matplotlib & Seaborn.
- **Veri Seti:** 20,000 kullanıcı kaydı (Grup A: Kontrol, Grup B: Test).

## 📈 Bulgular
- **Grup A Dönüşüm Oranı:** %6.10
- **Grup B Dönüşüm Oranı:** %8.90
- **İstatistiksel Sonuç:** p-value < 0.05 (H0 reddedildi).

## 🖼️ Görselleştirmeler
[Dönüşüm Oranları](./1.96.png)
[Zaman Trendi](daily.png)

## 💡 Karar
İndirimli varyant, istatistiksel olarak anlamlı bir başarı sergilemiştir (%46 relatif artış). Stratejinin tüm kullanıcılara açılması önerilir.
