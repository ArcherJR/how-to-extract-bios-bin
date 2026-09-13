# how-to-extract-bios-bin
Guide to extracting BIN files from BIOS update EXEs for flashing onto BIOS chips

BIOS çiplerine yüklenmek üzere, BIOS güncelleme EXE dosyalarından BIN dosyalarını çıkarma rehberi

## Programs and tools used in this project:
 **Terminal:**                                                (Any Terminal)

 **[UEFITool](https://github.com/LongSoft/UEFITool):**        UEFI firmware image parser / UEFI firmware imaj analiz aracı

 **[7zip](https://github.com/p7zip-project/p7zip):**          Archive extractor / Arşiv ayıklayıcı

 **[innoextract](https://github.com/dscharrer/innoextract):** Inno Setup unpacker / Inno Setup paket açıcı

 **[binwalk](https://github.com/ReFirmLabs/binwalk):**        Firmware extraction tool / Firmware analiz aracı


###  Legal Disclaimer & Copyright Notice / Yasal Uyarı ve Telif Hakkı Bildirimi
This repository is strictly for **educational, research, and technical documentation purposes**.
Bu depo yalnızca **eğitim, teknik araştırma ve dokümantasyon** amacıyla hazırlanmıştır.

* **Proprietary Files & Copyright:** In compliance with copyright laws and intellectual property rights, this repository **does not host, distribute, or re-upload** any original BIOS update executable binaries (`.exe`) or extracted firmware/ROM files (`.bin`, `.fd`, `.rom`) owned by Lenovo or other original equipment manufacturers (OEMs).
* **Fikri Mülkiyet ve Dosya Dağıtımı:** Telif hakkı yasaları ve fikri mülkiyet hakları gereğince; mülkiyeti Lenovo veya diğer orijinal ekipman üreticilerine (OEM) ait olan BIOS güncelleme dosyaları (`.exe`) ile bu dosyalardan ayrıştırılan ham BIOS/ROM imajları (`.bin`, `.fd`, `.rom`) bu depoda **barındırılmamakta, dağıtılmamakta ve yayınlanmamaktadır**.
<br>
* **Trademarks:** All product names, trademarks, registered trademarks, and logos mentioned in this project are the property of their respective owners.
* **Ticari Markalar:** Bu projede adı geçen tüm ürün adları, ticari markalar ve logolar ilgili hak sahiplerinin mülkiyetindedir.
<br>  
* **User Responsibility:** Users must obtain original BIOS update installers directly from official manufacturer support portals.
* **Kullanıcı Sorumluluğu:** Kullanıcılar orijinal BIOS güncelleme paketlerini doğrudan üreticinin resmi destek kanallarından temin etmekle yükümlüdür.
