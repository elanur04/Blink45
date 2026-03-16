# STM32F103C8T6 (Blue Pill) - Blink ve Debug Projesi

Bu proje, STM32F103C8T6 (Blue Pill) mikrodenetleyicisi kullanılarak gerçekleştirilmiş temel bir LED yakıp söndürme (Blink) ve hata ayıklama (Debug) uygulamasıdır. 
▶️ **Proje Uygulama Videosu:** [Buraya Tıklayarak İzleyebilirsiniz (YouTube)](https://www.youtube.com/watch?v=AqFCqYYYG8Q)

## 📌 Proje Özellikleri
* **Mikrodenetleyici:** STM32F103C8T6 (ARM Cortex-M3)
* **Kullanılan Pin:** `PC13` (Blue Pill üzerindeki dahili User LED)
* **Çalışma Mantığı:** PC13 pini ters mantıkla (Active-LOW) çalıştığı için `LOW` durumunda yanar, `HIGH` durumunda söner.
* **Periyot:** LED 500 milisaniye yanık, 500 milisaniye sönük kalarak toplam 1 saniyelik periyotlarla çalışır.

## 🛠️ Kullanılan Araçlar ve Geliştirme Ortamı
* **Konfigürasyon:** STM32CubeMX
* **IDE / Editör:** Visual Studio Code (VS Code)
* **Derleyici (Toolchain):** ARM GCC & `mingw32-make` (Makefile)
* **Programlayıcı:** ST-Link V2
* **Hata Ayıklama (Debugger):** OpenOCD / GDB



## 🚀 Derleme (Build) ve Yükleme (Flash)
Proje dizininde terminal açılarak aşağıdaki komut ile derleme işlemi (Build) gerçekleştirilebilir:
```bash
mingw32-make





