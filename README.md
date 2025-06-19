# 🦠 COVID-19 Research Paper Analysis (CORD-19 Dataset)

Bu proje, Allen Institute for AI tarafından sağlanan [CORD-19: COVID-19 Open Research Dataset](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge) veri seti kullanılarak yapılan temel veri analizi ve içerik incelemesini kapsamaktadır.

## 📌 Amaç

COVID-19 hakkında yayımlanan bilimsel makaleleri analiz ederek:

- Yayınların zaman içindeki dağılımını,
- Makalelerin en sık odaklandığı konuları,
- En çok yayın yapan kaynakları,
- Yazar, başlık, öz (abstract) gibi metin bazlı alanlarda temel metin işleme işlemlerini (NLP),
- Anahtar kelime ve konu yoğunluklarını

anlamaya çalışmak.

---

## 📁 Kullanılan Dosyalar

- `metadata.csv` — Makalelere ait başlık, yazar, tarih, özet ve kaynak bilgilerini içerir.
- `cord_uid`, `title`, `abstract`, `publish_time`, `journal`, `authors` gibi önemli sütunlar üzerinde çalışıldı.

---

## 🔍 Yapılan Analizler

### 1. 📅 **Yıllara Göre Yayın Sayısı**
COVID-19 salgını ile birlikte bilimsel yayınların zamanla nasıl arttığı görselleştirildi.

### 2. 📰 **En Fazla Yayınlanan Kaynaklar**
En çok yayına sahip akademik dergiler listelendi.

### 3. 🧪 **En Sık Geçen Kelimeler**
Başlık ve özet (abstract) alanlarında sık geçen kelimeler `wordcloud` kullanılarak görselleştirildi.

### 4. 🧠 **Anahtar Konuların Belirlenmesi (Topic Modeling)**
LDA algoritması kullanılarak makalelerdeki özetlerden ana konu başlıkları çıkarıldı.

### 5. 🔤 **Text Preprocessing**
- Noktalama temizleme
- Stopword kaldırma
- Lemmatization
- Tokenization

işlemleri uygulandı.

---

## 📦 Kullanılan Kütüphaneler

- `pandas`, `numpy` — veri işleme
- `matplotlib`, `seaborn` — görselleştirme
- `wordcloud` — kelime bulutu
- `nltk`, `spaCy`, `gensim` — doğal dil işleme (NLP)

---

## 🧪 İlginç Bulgular

- En sık geçen terimler: *COVID*, *infection*, *SARS-CoV-2*, *treatment*, *vaccine*
- 2020'nin ilk aylarında literatürdeki yayın sayısı patlama yaptı.
- Çoğu çalışma klinik tedavi, bulaş yolları ve aşı geliştirme üzerineydi.



