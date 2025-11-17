# Cobi Static Website 🚀 - TEK DOSYALI MİNİMAL ŞABLON

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=F7DF1E)
![Status](https://img.shields.io/badge/status-active-success.svg)

**Cobi Static Website**, kişisel veya kurumsal tanıtım için tasarlanmış, **tüm yapısal unsurları tek bir HTML dosyasında barındıran** (inlined CSS/JS) minimalist bir web sitesi şablonudur.

## 🌟 Özellikler

* **Tek Dosya Yapısı:** Tüm tasarım (CSS) ve işlevsellik (JavaScript) kodları `index.html` içerisinde yer alır, bu da dağıtımı (deployment) son derece kolaylaştırır.
* **Dahili İstek Depolama:** Sayfadaki JavaScript, kullanıcıdan gelen verileri veya istekleri işler ve `/admin` path'inde görüntülenmek üzere yerel olarak depolayabilir (örn: `localStorage` kullanarak).
* **Tamamen Duyarlı (Responsive):** Mobil uyumlu tasarım.

## ⚠️ ÖNEMLİ GÜVENLİK NOTU

Bu şablonun mevcut JavaScript yapısı, `/admin` yoluna yapılan isteklere **oturum açma (login) işlemi gerektirmeden** doğrudan erişim sağlar.

> **Tavsiye:** Bu repoyu kullanarak bir canlı proje geliştirecekseniz, `/admin` alanını korumak için mutlaka bir **yetkilendirme (authentication)** sistemi ekleyin veya sunucu tabanlı bir çözüm kullanın. Mevcut yapı, hassas verilerinizi ifşa edebilir.

## 📂 Proje Yapısı

Projenin tüm içeriği tek bir ana dosyada toplanmıştır:

```text
Codexia_cobi_static/
├── index.html             # HTML, Inline CSS ve Inline JavaScript kodlarının tamamını içerir.
└── README.md              # Proje dokümantasyonu
