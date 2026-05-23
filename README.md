# KINGDOM - Uzaktan Bilgisayar Yönetim Sistemi

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-Educational%20Use%20Only-red.svg)](LICENSE)

**KINGDOM**, eğitim ve test ortamlarında kullanılmak üzere geliştirilmiş, uzaktan bilgisayar yönetimi sağlayan bir yazılımdır. Özellikle bilişim laboratuvarlarında öğretmenlerin öğrenci bilgisayarlarını yönetebilmesi, ekranlarını izleyebilmesi ve dosya transferi yapabilmesi amacıyla tasarlanmıştır.

> ⚠️ **Uyarı**: Bu yazılım yalnızca eğitim amaçlıdır ve yalnızca sahibi olduğunuz veya yazılı izin aldığınız cihazlarda kullanılmalıdır. Yetkisiz kullanım yasa dışıdır.

---

## 🚀 Özellikler

| Özellik | Açıklama |
|---------|----------|
| 🖥️ **Uzaktan Ekran İzleme** | Öğrenci bilgisayarlarının ekranını gerçek zamanlı izleme |
| 🖱️ **Uzaktan Fare ve Klavye Kontrolü** | İzlenen bilgisayara uzaktan müdahale edebilme |
| 📁 **Dosya Transferi** | Öğrenci bilgisayarlarına dosya gönderme ve alma |
| 🔐 **SSH Şifreli İletişim** | Paramiko kütüphanesi ile güvenli şifreli bağlantı |
| 👥 **Çoklu İstemci Desteği** | Aynı anda birden fazla bilgisayarı yönetebilme |
| 🔄 **Otomatik Yeniden Bağlanma** | Bağlantı koptuğunda otomatik yeniden bağlanma |
| 📝 **Kullanıcı Kimlik Doğrulama** | Firebase entegrasyonu ile güvenli giriş |

---

## 📦 Gereksinimler

- Python 3.8 veya üzeri
- Windows / Linux / macOS (Sunucu için GUI gerekli)

### Kütüphaneler

```bash
pip install paramiko pillow pyautogui requests
