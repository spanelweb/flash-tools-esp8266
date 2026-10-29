# Flash Tools ESP8266
Flash Tools ESP8266 tampilan terminal dipersembahkan oleh Suryo Dwijayanto untuk windows "Based esptool".

``` termux


  ███████╗██╗      █████╗ ███████╗██╗  ██╗
  ██╔════╝██║     ██╔══██╗██╔════╝██║  ██║
  █████╗  ██║     ███████║███████║███████║
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
Masukkan path/lokasi file .bin (Contoh: C:/firmware.bin): JoyStick.bin

Pilih Konfigurasi (Tekan Enter untuk menggunakan default):
Upload Speed [1] 115200 [2] 230400 [3] 460800 [4] 921600 (Default 115200): 1
CPU Freq [1] 80Mhz [2] 160Mhz (Default 80Mhz): 1
Flash Mode [1] DOUT [2] DIO [3] QIO [4] QOUT (Default DOUT): 1
Flash Freq [1] 40Mhz [2] 80Mhz (Default 40Mhz): 1
Erase all flash content sebelum flash? (y/n, Default n): y

==================================================
 Port        : COM5
 File        : JoyStick.bin
 Upload Spd  : 115200
 CPU Freq    : 80MHz | Mode: DOUT | Freq: 40m
 Erase All   : True
==================================================

Mulai proses flash? (y/n): y

[*] Melakukan Erase All Flash Content...
esptool v5.6.0
Connected to ESP8266 on COM5:
Chip type:          ESP8266EX
Features:           Wi-Fi, 160MHz
Crystal frequency:  26MHz
MAC:                c4:d8:d5:3d:44:3c

Stub flasher running.

Flash memory erased successfully in 0.1 seconds.

Hard resetting via RTS pin...
[+] Erase Flash Berhasil!

[*] Menjalankan perintah esptool ke COM5 (Baud: 115200)...
esptool v5.6.0
Serial port COM5:
Connecting....
Detecting chip type... ESP8266
Connected to ESP8266 on COM5:
Chip type:          ESP8266EX
Features:           Wi-Fi, 160MHz
Crystal frequency:  26MHz
MAC:                c4:d8:d5:3d:44:3c

Uploading stub flasher...
Running stub flasher...
Stub flasher running.

Configuring flash size...
Auto-detected flash size: 4MB
Flash will be erased from 0x00000000 to 0x0004ffff...
Compressed 326416 bytes to 232409...
Writing at 0x00005926 ==                               7.0% 16.00kB/226.96kB [1s]
Writing at 0x0000b8d4 ====                            14.1% 32.00kB/226.96kB [3s]
Writing at 0x0001122e ======                          21.1% 48.00kB/226.96kB [5s]
Writing at 0x00016a08 ========                        28.2% 64.00kB/226.96kB [7s]
Writing at 0x0001c10a ==========>                     35.2% 80.00kB/226.96kB [9s]
Writing at 0x00021427 ============>                   42.3% 96.00kB/226.96kB [11s]
Writing at 0x000263f8 ==============>                 49.3% 112.00kB/226.96kB [13s]
Writing at 0x0002b4ee ================>               56.4% 128.00kB/226.96kB [15s]
Writing at 0x00030e0a ===================             63.4% 144.00kB/226.96kB [17s]
Writing at 0x00036437 =====================           70.5% 160.00kB/226.96kB [19s]
Writing at 0x0003b825 =======================         77.5% 176.00kB/226.96kB [21s]
Writing at 0x00040e27 =========================       84.6% 192.00kB/226.96kB [23s]
Writing at 0x0004924f ===========================     91.6% 208.00kB/226.96kB [24s]
Writing at 0x0004e489 =============================>  98.7% 224.00kB/226.96kB [26s]
Writing at 0x0004fb10 ============================== 100.0% 226.96kB/226.96kB [27s]
Wrote 326416 bytes (232409 compressed) at 0x00000000 in 27.4 seconds (95.2 kbit/s).
Verifying written data...
Hash of data verified.

Hard resetting via RTS pin...

[+] FLASHING BERHASIL SELESAI!

Tekan Enter untuk keluar...
```
