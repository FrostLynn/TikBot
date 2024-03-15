
# TikBot

TikBot adalah skrip Python yang dirancang untuk mengotomatisasi berbagai interaksi dengan profil TikTok melalui Zefoy. Ini menyediakan cara yang efisien untuk melakukan tindakan seperti menonton video, menyukai konten, dan lainnya, dengan menggunakan Selenium WebDriver untuk otomatisasi peramban.

## Prasyarat

Sebelum Anda dapat menjalankan TikBot, Anda perlu menginstal hal-hal berikut di sistem Anda:

- Python 3.6 atau versi yang lebih baru
- pip (Penginstal paket Python)
- Git (untuk mengkloning repositori)
- Peramban Google Chrome atau Chromium
- ChromeDriver (sesuai dengan versi peramban Anda)

## Instalasi

Ikuti langkah-langkah ini untuk menjalankan TikBot di mesin Anda:

1. **Kloning repository:**

   ```sh
   git clone https://github.com/FrostLynn/TikBot.git
   cd TikBot
   ```

2. **Siapkan lingkungan virtual (opsional tetapi disarankan):**

   - Untuk Unix/macOS:

     ```sh
     python3 -m venv venv
     source venv/bin/activate
     ```

   - Untuk Windows:

     ```sh
     python -m venv venv
     .\venv\Scripts\activate
     ```

3. **Menginstal paket yang diperlukan:**

   ```sh
   pip install -r requirements.txt
   ```

## Penggunaan

Untuk menjalankan TikBot, jalankan skrip dari baris perintah. Pastikan Anda berada di direktori proyek dan lingkungan virtual Anda diaktifkan (jika Anda membuatnya).

```sh
python bot.py
```

Ikuti petunjuk di layar untuk menyelesaikan captcha di Zefoy dan pilih layanan yang ingin Anda otomatisasi.

## Fitur

- Mengotomatisasi berbagai interaksi dengan profil TikTok melalui Zefoy.com.
- Antarmuka baris perintah yang ramah pengguna untuk interaksi yang mudah.
- Mendukung beberapa URL, berganti-ganti melalui masing-masing untuk tindakan otomatis.
- Pemeriksaan status layanan dinamis memastikan bahwa hanya layanan yang tersedia yang diinteraksikan.
- Penanganan yang mulus terhadap masalah koneksi internet dan gangguan skrip.
  

Terima kasih kepada [Zefoy](https://zefoy.com/) atas layanan mereka, yang membuat proyek ini menjadi mungkin. Dan kepada pengguna [TeraFear](https://github.com/terafear). Skrip ini dimaksudkan untuk tujuan pendidikan dan harus digunakan secara bertanggung jawab dan etis.

## Disclaimer

Proyek ini tidak berafiliasi dengan [TikTok](https://www.tiktok.com/), [Zefoy](https://zefoy.com/). Ini dibuat untuk tujuan pendidikan dan penelitian saja. Pengguna disarankan untuk memastikan mereka mematuhi ketentuan layanan TikTok dan menggunakan skrip secara etis.
