# Magisk Documentation

- [Installation Instructions](install.md)
- [Frequently Asked Questions](faq.md)
- [Release Notes](releases/index.md)
- [Magisk Changelog](changes.md)

The following sections are for developers

- [Developer Guides](guides.md)
- [Magisk Tools](tools.md)
- [Internal Details](details.md)
- [Android Booting Shenanigans](boot.md)
- [Deployment](deploy.md)
Aplikasi Magisk menggunakan metode persembunyian yang lebih canggih yang akan menginstal APK "rintisan" yang tidak memiliki apa pun di dalamnya. Satu-satunya fungsi yang dimiliki aplikasi rintisan ini adalah mengunduh APK aplikasi Magisk lengkap ke penyimpanan internalnya dan memuatnya secara dinamis. Karena fakta bahwa APK benar - benar kosong , itu tidak berisi sumber daya gambar untuk ikon aplikasi.
