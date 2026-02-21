<div align="center">
  
# cmdAI

<img width="80" height="80" alt="icon" src="https://github.com/user-attachments/assets/4ac66fd9-8363-433e-9d9f-8cc144d72825" />

**Akıllı Terminal Asistanı**

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
&nbsp;
[![Java](https://img.shields.io/badge/Java-17+-007396?style=for-the-badge&logo=java&logoColor=white)](https://java.com)
&nbsp;
[![AI Models](https://img.shields.io/badge/AI_Models-Gemini%20%7C%20Ollama%20%7C%20Groq-4285F4?style=for-the-badge&logo=google&logoColor=white)](/)

[![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-lightgrey?style=for-the-badge)](/)
&nbsp;
[![License](https://img.shields.io/badge/License-GPLv3-red?style=for-the-badge)](LICENSE)

---

Geleneksel terminalin zorluklarını ortadan kaldırarak bilgisayarınızı kendi dilinizde yönetin.

</div>

---

## 📋 İçindekiler

- [🎯 Proje Hakkında](#-proje-hakkında)
- [✨ Özellikler](#-özellikler)
- [🖥️ Ekran Görüntüleri](#️-ekran-görüntüleri)
- [🛠️ Teknolojiler](#️-teknolojiler)
- [🚀 Kurulum & Kullanım](#-kurulum--kullanım)
- [📖 Temel Komutlar](#-temel-komutlar)
- [👤 Geliştirici](#-geliştirici)

---

## � Proje Hakkında

**cmdAI**, doğal dilde yazdığınız komutları algılayarak bilgisayarınızda işlemleri yerine getiren, yapay zeka destekli akıllı bir terminal asistanıdır. "Masaüstündeki tüm PDF'leri Belgelerim klasörüne taşı" gibi cümlelerle doğrudan işletim sistemini yönetmenizi sağlar.

Hem Windows hem de macOS üzerinde çalışır; bulut tabanlı veya tamamen yerel AI modellerini kullanma özgürlüğü sunar.

---

## ✨ Özellikler

| Özellik | Açıklama |
|---------|----------|
| 💬 **Doğal Dil İşleme** | Türkçe veya İngilizce cümlelerle bilgisayarınızı komuta edin. |
| 🧠 **Çoklu Model Desteği** | Google Gemini, Groq Cloud ve tamamen yerel Ollama modellerini destekler. |
| 🛠️ **Auto-Fix** | Hatalı çalışan komutları algılar, kendi kendini düzeltir ve tekrar dener. |
| 📚 **Context Memory** | Sohbetinizin son 10 mesajını hafızasında tutarak kesintisiz bir iletişim kurar. |
| ⚙️ **Kolay Arayüz** | Gelişmiş GUI tabanlı Ayarlar menüsünden API ve model tanımlarını yapabilirsiniz. |
| 💻 **Çapraz Platform** | Windows (.exe) ve macOS (.app) destekli sürümler içerir. |

---

## �️ Ekran Görüntüleri

<div align="center">

#### 📊 Ana Ekran
<p align="center">
  <img width="800" src="https://symdevai.com/api/v1/store/public/images/2ba35e22-d5bf-4ad1-99dc-1dcf5809d253_img_1.png" />
</p>

#### ℹ️ Yardım Menüsü
<p align="center">
  <img width="800" src="https://symdevai.com/api/v1/store/public/images/6c577a40-80e0-4b28-a092-cc21a25eda86_img_2.png" />
</p>

#### ⚙️ Ayarlar Arayüzü
<p align="center">
  <img width="600" src="https://github.com/user-attachments/assets/0803d10d-74e2-423f-b90d-2dd5b4c76170" />
</p>

</div>

---

## 🛠️ Teknolojiler

<div align="center">

| Kategori | Teknoloji |
|:--------:|:---------:|
| **Dil** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white) |
| **Yapay Zeka** | ![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=google&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-Local_AI-lightgrey?style=flat-square) ![Groq](https://img.shields.io/badge/Groq_Cloud-F55036?style=flat-square) |
| **Platform** | ![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white) ![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white) |

</div>

---

## 🚀 Kurulum & Kullanım

Proje klasörü platformlara göre ayrılmıştır:

### 1. Windows Kurulumu
- `cmdAI (Windows)` klasörüne girin.
- `cmdAI.exe` dosyasına tıklayarak başlatın.

### 2. macOS Kurulumu
- `cmdAI (macOS)` klasörüne girin.
- `cmdAI.app` uygulamasını başlatın.

### Ayarların Yapılandırılması
Programı ilk çalıştırdığınızda komut satırına `ayarlar` yazarak yapılandırma panelini açın. İlgili AI modelini seçip geçerli API anahtarınızı (veya Ollama için lokal yapılandırmayı) yapın. Bu konuda detaylı bilgi edinmek için komut satırına `yardim` yazabilirsiniz.

---

## 📖 Temel Komutlar

Aşağıdaki komutları doğrudan terminal içinden başlatabilirsiniz:

- `> yardim`    : Kurulum ve API rehberini gösterir.
- `> ayarlar`   : API ve Model ayarları penceresini açar.
- `> yonetici`  : Admin (Sudo) yetkisi almanızı sağlar.
- `> temizle`   : Ekranı temizler.
- `> unut`      : Hafızadaki konuşma geçmişini sıfırlar (Yeni Sohbet).
- `> cikis`     : Uygulamayı kapatır.
          
---

## � Geliştirici

<div align="left">

**Berkkan KAYA**

[![GitHub](https://img.shields.io/badge/GitHub-kayaberkkan-181717?style=for-the-badge&logo=github)](https://github.com/kayaberkkan)

</div>

---
