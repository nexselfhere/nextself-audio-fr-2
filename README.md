# nextself-audio-fr-2

NextSelf uygulamasının Fransızca indirilen ses paketi: B1+ ders sesleri, sözlük kelimeleri ve örnek cümleleri, okuma metinleri ve oyun sesleri
(A1–A2 ders sesleri uygulamanın içine gömülüdür) — anahtarı 8…f ile başlayan kayıtlar (dilin sesleri nextself-audio-fr · nextself-audio-fr-2 depolarına bölünmüştür). Uygulama bu dosyaları tek tek indirir
(`fr/<ilk iki hex>/<anahtar>.mp3`, mono mp3); anahtar, seslendirilen metnin
sha1 özetinin ilk 16 hanesidir.

Yayın adresi: https://nextselfhere.github.io/nextself-audio-fr-2

## Ses modeli ve lisans

- **Kokoro-82M** (hexgrad) — Apache 2.0 — https://huggingface.co/hexgrad/Kokoro-82M
- Fransızca ses **SIWIS French Speech Synthesis Database**'den türetilmiştir —
  Pierre-Edouard Honnet, Alexandros Lazaridis, Philip N. Garner, Junichi Yamagishi
  (Idiap Research Institute, 2017) — CC BY 4.0 — https://creativecommons.org/licenses/by/4.0/

Kayıtlar bu ses modeliyle üretilmiştir; metinler NextSelf müfredatına aittir.

## Doğrulama

`SHA256SUMS.txt` tüm dosyaların özetini taşır: `shasum -c SHA256SUMS.txt`
