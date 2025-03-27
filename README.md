# GoodbyeDPI - DNS Redirection Scripts

## Türkçe Açıklama
Bu repo, [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) aracını kullanarak DNS yönlendirmesi sağlayan betikleri içerir. Aşağıda her dosyanın ne işe yaradığını bulabilirsiniz:

### Dosya Açıklamaları
- **`2_any_country_dnsredir.cmd`**
  - Bu dosya, GoodbyeDPI'yi tek seferlik çalıştırarak DNS yönlendirme işlemini gerçekleştirir.
  - Terminal üzerinden manuel olarak çalıştırılması gerekir.

- **`00_service_install_automatic_start_dnsredir.cmd`**
  - Bu dosya, GoodbyeDPI'yi bir servis olarak yükleyerek bilgisayar her açıldığında otomatik olarak arka planda çalışmasını sağlar.
  - Yönetici olarak çalıştırılmalıdır (Sağ tıklayıp "Yönetici olarak çalıştır" seçeneği ile).

- **`service_remove.cmd`**
  - Eğer GoodbyeDPI'nin otomatik olarak çalışmasını istemiyorsanız, bu dosya servisi kaldıracaktır.
  - Yönetici olarak çalıştırılması gereklidir.

---

## English Description
This repository contains scripts for using [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) with DNS redirection. Below is an explanation of each script:

### File Descriptions
- **`2_any_country_dnsredir.cmd`**
  - Runs GoodbyeDPI for a one-time session to enable DNS redirection.
  - Needs to be executed manually via terminal.

- **`00_service_install_automatic_start_dnsredir.cmd`**
  - Installs GoodbyeDPI as a service, allowing it to run automatically in the background whenever the computer starts.
  - Must be run as administrator (Right-click > "Run as administrator").

- **`service_remove.cmd`**
  - If you no longer want GoodbyeDPI to run automatically, this script removes the service.
  - Requires administrator privileges.

---

## Telif Hakkı & Kaynak
Bu repo, [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) projesinden çatallanmıştır ve orijinal projenin tüm hakları orijinal geliştiricisine aittir.

This repository is forked from [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI), and all rights belong to the original developer.
