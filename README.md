# akbank-ai-text-analyzer
Google Gemini API’sini kullanarak kullanıcıdan alınan Türkçe bir metni analiz eden bir yapay zeka aracıdır. Sistem, verilen metni 2–3 cümleyle özetler, 5 kelimeyi geçmeyen bir başlık üretir ve 5–8 adet anahtar kelime çıkarır. Akbank Generative AI Bootcamp kapsamında geliştirilmiştir.
# 🤖 Akbank AI – Metin Analizi Aracı

Bu proje, **Google Gemini API** kullanılarak oluşturulmuş yapay zeka destekli bir metin analiz aracıdır.  
Kullanıcıdan alınan Türkçe metni otomatik olarak **özetler**, **başlık önerir** ve **anahtar kelimeler** çıkarır.  
Akbank Generative AI Bootcamp kapsamında geliştirilmiştir.

---

## 🚀 Özellikler
- Girilen metni 2–3 cümleyle tarafsız bir dille özetler.  
- Metin içeriğine uygun, 5 kelimeyi geçmeyen ilgi çekici bir başlık üretir.  
- 5–8 adet anlamlı anahtar kelime belirler.  
- Arayüz, **Gradio** kütüphanesi kullanılarak oluşturulmuştur.  

---

## 🧠 Kullanılan Teknolojiler
- Python  
- Google Gemini API (`gemini-2.5-flash` modeli)  
- Gradio  

---

## ⚙️ Çalıştırma Adımları
1. Gerekli kütüphaneleri yükle:
   ```python
   !pip install -q google-generativeai gradio

   import os
os.environ["GOOGLE_API_KEY"] = "SENİN_ANAHTARIN"

