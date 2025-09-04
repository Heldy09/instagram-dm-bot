# instagram-dm-bot
Instagram API dan Batasan Instagram tidak menyediakan API publik yang mendukung pengiriman pesan langsung ke grup (Direct Message Group) untuk aplikasi pihak ketiga. Fitur DM Instagram umumnya dibatasi untuk keperluan bisnis melalui Instagram Graph API dan hanya mendukung pesan ke pengguna yang telah berinteraksi dengan akun bisnis. .
Alternatif: Bot Berbasis Web Automation
Jika tujuan kamu adalah belajar atau untuk penggunaan pribadi, kamu bisa menggunakan otomatisasi dengan perpustakaan seperti Selenium (Python) atau Puppeteer (Node.js) untuk meniru interaksi pengguna di web Instagram.
3. Contoh Sederhana Bot Kirim Pesan ke Grup Instagram dengan Selenium (Python)
Berikut contoh skrip Python yang menggunakan Selenium untuk login dan mengirim pesan ke grup DM Instagram. (Pastikan kamu sudah install seleniumdan driver browser seperti ChromeDriver):
# Instagram DM Bot

Bot sederhana untuk mengirim pesan ke grup Instagram Messenger menggunakan Selenium.

## Fitur
- Login otomatis ke Instagram
- Kirim pesan ke grup DM

## Cara Install

1. Clone repo:
   ```
   git clone https://github.com/Heldy09/instagram-dm-bot.git
   cd instagram-dm-bot
   ```

2. Install dependency:
   ```
   pip install -r requirements.txt
   ```

3. Download [ChromeDriver](https://chromedriver.chromium.org/downloads) sesuai versi Chrome-mu. Pastikan file chromedriver ada di PATH.

4. Jalankan bot:
   - Edit variabel di `instagram_dm_bot.py` atau gunakan environment variable:
     ```
     export IG_USERNAME='username'
     export IG_PASSWORD='password'
     export IG_GROUP_NAME='Nama Grup'
     export IG_MESSAGE='Pesan Bot!'
     python instagram_dm_bot.py
     ```

## Catatan
- Gunakan hanya untuk pembelajaran/personal. Jangan spam!
- Instagram dapat memblokir akun jika terdeteksi aktivitas mencurigakan.

## Kontribusi
Pull request & issue dipersilakan!

## Lisensi
MIT
