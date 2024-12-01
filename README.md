# Remove-Bloatware
_______________________________
## Cara menggunakan
1. Download aplikasi "<a href="https://play.google.com/store/apps/details?id=com.jgba.appinspector&hl=id&pli=1">app inspector</a>" di playstore
2. Extract file `Minimal_ADB_Fastboot_v1.4.3.zip`
3. Install aplikasi `Minimal ADB Fastboot v1.4.3.exe` di PC/Leptop anda
4. Hidupkan mode developer di handphone yang ingin di hapus aplikasi bloatwarenya
5. Hidupkan usb debuging
6. Sambungkan PC/Leptop anda ke handphone dengan menggunakan kabel usb
7. Buka cmd atau aplikasi yang sudah di install di PC/Leptop anda
8. Ketikan `adb shell` untuk masuk kedalam handphone dengan terminal cmd
9. Buka aplikasi `app inspector` untuk melihat package dari aplikasi yang ingin dihapus
10. Ketikan perintah `pm uninstall -k --user 0 package name` untuk "package name" disesuaikan nama dari package yang tertera pada app inspector
11. Contoh `pm uninstall -k --user 0 com.google.chrome`
12. Tunggu hingga proses selesai dan terminal memberikan pesan feedback `Success`


## Packed by www.androidmtk.com
_______________________________

Check out our Download Hub:

1. Stock Firmware Downloads: https://androidmtk.com/category/download
2. USB Driver Downloads: https://androidmtk.com/category/drivers
3. Basic Tools: https://androidmtk.com/category/tools
