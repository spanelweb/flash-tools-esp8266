# Flash Tools ESP8266
Flash Tools ESP8266 tampilan terminal dipersembahkan oleh Suryo Dwijayanto untuk windows "Based esptool".

## Unduh
[FlashToolsESP8266.exe](https://github.com/spanelweb/flash-tools-esp8266/releases/download/1.0.0.0/FlashToolsESP8266.exe)

## Sumbangan
Terimakasih untuk orang baik.

<img width="180" height="180" alt="image" src="https://github.com/user-attachments/assets/650c28ef-0807-4404-8a1c-c1cc7d0bf734" />
<hr />

## Guide
Unduh dan pasang [CH304](https://www.wemos.cc/en/latest/ch340_driver.html) jika belum. Colokan USB dari papan ke komputer lalu Buka/jalankan FlashToolESP8266.exe lihat catatan dibawah untuk detailnya.

``` txt


  ███████╗██╗      █████╗ ███████╗██╗  ██╗
  ██╔════╝██║     ██╔══██╗██╔════╝██║  ██║
  █████╗  ██║     ███████║███████╗███████║
  ██╔══╝  ██║     ██╔══██║╚════██║██╔══██║
  ██║     ███████╗██║  ██║███████║██║  ██║
  ╚═╝     ╚══════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝

==================================================
[+] Board  : Wemos D1 Mini ESP8266
[+] Author : Suryo Dwijayanto
==================================================

[*] Port COM terdeteksi otomatis: COM5
Masukkan Port COM (Default: COM5): COM5

--- Konfigurasi File & Hardware ---
Masukkan path/lokasi file .bin (Contoh: C:/firmware.bin): C:\Users\IyoRTML\Documents\Arduino\JoyStick_ESP8266\JoyStick.bin

Pilih Konfigurasi (Tekan Enter untuk menggunakan default):
Upload Speed [1] 115200 [2] 230400 [3] 460800 [4] 921600 (Default 115200): 1
CPU Freq [1] 80Mhz [2] 160Mhz (Default 80Mhz): 1
Flash Mode [1] DOUT [2] DIO [3] QIO [4] QOUT (Default DOUT): 1
Flash Freq [1] 40Mhz [2] 80Mhz (Default 40Mhz): 1
Erase all flash content sebelum flash? (y/n, Default n): y

==================================================
 Port        : COM5
 File        : C:\Users\IyoRTML\Documents\Arduino\JoyStick_ESP8266\JoyStick.bin
 Upload Spd  : 115200
 CPU Freq    : 80Mhz | Mode: DOUT | Freq: 40m
 Erase All   : True
==================================================

Mulai proses flash? (y/n): y

[*] Melakukan Erase All Flash Content...
esptool v5.6.0
Connected to ESP8266 on COM5:
Chip type:          ESP8266EX
Features:           Wi-Fi, 160MHz
Crystal frequency:  26MHz
MAC:                X4:dX:X5:3X:X4:3X

Stub flasher running.

Flash memory erased successfully in 0.0 seconds.

Hard resetting via RTS pin...
[+] Erase Flash Berhasil!

[*] Menjalankan esptool ke COM5 (Baud: 115200)...
esptool v5.6.0
Connected to ESP8266 on COM5:
Chip type:          ESP8266EX
Features:           Wi-Fi, 160MHz
Crystal frequency:  26MHz
MAC:                X4:dX:X5:3X:X4:3X

Stub flasher running.

Configuring flash size...
Auto-detected flash size: 4MB
Flash will be erased from 0x00000000 to 0x0004ffff...
Wrote 326416 bytes (232409 compressed) at 0x00000000 in 36.5 seconds (71.6 kbit/s).
Hash of data verified.

Hard resetting via RTS pin...

[+] FLASHING BERHASIL SELESAI!

Tekan Enter untuk keluar...
```

<b>Terimakasih</b>

Salam, ~ <b>Suryo DwiJayanto</b>
