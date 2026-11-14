> Bu depo yalnız NetAnalytic'in gizlilik metnini içerir. / This repository only holds the NetAnalytic privacy policy.
> Sürüm / Version 1.2.0 · 2026-11-14

# NetAnalytic — Gizlilik metni


**Kısaca:** NetAnalytic bize hiçbir veri göndermez. Ölçümleriniz, ayarlarınız ve ev planınız yalnız bu bilgisayarda durur.
Dışarıya giden istekler ölçümün kendisidir.

## 1. Veri sorumlusu

Ahmet Ünal Uzun (bireysel geliştirici). İletişim: ahmetunaluzun@gmail.com

## 2. Bilgisayarınızda saklananlar

| Ne | Nerede | Neden |
|---|---|---|
| Ölçümler (gecikme, hız testi, modem sinyali, ev ağı trafiği, ağdaki cihazların adı ve MAC adresi, olaylar) | `%LOCALAPPDATA%\NetAnalizer\data` | Grafik, rapor ve izleme |
| Ayarlar, modem/router adresi ve kullanıcı adı | `%APPDATA%\NetAnalizer\config.json` | Modemden sinyal okumak |
| Modem/router şifresi | Aynı dosyada, Windows'un kullanıcıya özel şifrelemesiyle (DPAPI) | Modeme giriş |
| Ev planı (oda ölçüleri, cihaz yerleri, Wi-Fi ölçümleri) | `%LOCALAPPDATA%\NetAnalizer\app` | Kapsama tahmini ve öneriler |
| Raporlar | Siz kaydettiğinizde seçtiğiniz klasör | Sizin kullanımınız |

Bunların hiçbiri bize ya da üçüncü bir tarafa gönderilmez. Uygulamada hesap, reklam, analitik ve uzaktan hata raporu yoktur.

"Wi-Fi şifrelerini dışa aktar" düğmesi, bu bilgisayarda kayıtlı Wi-Fi profillerini ve şifrelerini sizin onayınızla
`Belgeler\NetAnalizer\` altına **şifresiz** dosya olarak yazar. Bu dosyaları siz yönetirsiniz.

## 3. Dışarıya giden istekler

Bu hizmetler isteğin geldiği IP adresini görür; bazıları yurt dışındadır.

| Hizmet | Ne zaman | Ne gider |
|---|---|---|
| Cloudflare (speed.cloudflare.com) | Hız testi | Test verisi |
| Ookla Speedtest (install.speedtest.net ve Ookla sunucuları) | Yalnız GitHub sürümünde, hız testinde; araç ilk testte indirilir. Microsoft Store sürümü Ookla kullanmaz | Test verisi |
| Bilgisayarınızın kullandığı DNS sunucusu (çoğunlukla modem ya da operatör) | Bilgisayar bağlantıları ve Ağdaki cihazlar sayfalarında adres adlarını göstermek için | Ad sorgusu (IP adresi) |
| api.ipify.org | Dış IP adresinizi göstermek için | Yalnız istek |
| 1.1.1.1 (Cloudflare), 8.8.8.8 (Google) | Gecikme, DNS ve iz sürme (tracert) ölçümü; izleme hedeflerini İzleme sayfasından değiştirebilirsiniz | Bağlantı denemesi / DNS sorgusu |
| www.msftconnecttest.com (Microsoft) | Windows'un internet denetimiyle aynı adres; internetin gerçekten açık olup olmadığını ölçmek | Yalnız istek |

Ev ağındaki modem, router ve cihaz taramaları yalnız ev ağınızda yapılır.

## 4. Haklarınız ve verinin silinmesi

Veriler yalnız sizde olduğu için onları siz kontrol edersiniz: uygulamayı kaldırıp yukarıdaki klasörleri silmeniz
yeterlidir. Uygulama sizin hakkınızda bize ulaşan bir veri tutmadığı için bizden istenecek bir kayıt yoktur;
sorularınız için e-posta adresi yukarıdadır (KVKK m.11 başvuruları dahil).

## 5. Değişiklikler

Yeni bir özellik dışarıya yeni bir istek eklerse bu metin güncellenir ve tarihi değişir.

---

# NetAnalytic — Privacy policy

**In short:** NetAnalytic sends no data to us. Your measurements, settings and home plan stay on this computer.
The only outgoing requests are the measurements themselves.

## 1. Controller

Ahmet Ünal Uzun (individual developer). Contact: ahmetunaluzun@gmail.com

## 2. What is stored on your computer

| What | Where | Why |
|---|---|---|
| Measurements (latency, speed tests, modem signal, home network traffic, names and MAC addresses of devices on your network, events) | `%LOCALAPPDATA%\NetAnalizer\data` | Charts, reports and monitoring |
| Settings, modem/router address and user name | `%APPDATA%\NetAnalizer\config.json` | Reading the modem's signal |
| Modem/router password | Same file, encrypted with Windows per-user encryption (DPAPI) | Signing in to the modem |
| Home plan (room sizes, device positions, Wi-Fi readings) | `%LOCALAPPDATA%\NetAnalizer\app` | Coverage estimate and suggestions |
| Reports | The folder you choose when saving | Your own use |

None of this is sent to us or to any third party. The app has no account, no ads, no analytics and no remote crash reporting.

The "Export Wi-Fi passwords" button writes the Wi-Fi profiles and passwords saved on this computer, after you confirm,
to **unencrypted** files under `Documents\NetAnalizer\`. You manage those files.

## 3. Outgoing requests

These services see the IP address the request comes from; some are outside your country.

| Service | When | What is sent |
|---|---|---|
| Cloudflare (speed.cloudflare.com) | Speed test | Test data |
| Ookla Speedtest (install.speedtest.net and Ookla servers) | GitHub edition only, during the speed test; the tool is downloaded on the first test. The Microsoft Store edition does not use Ookla | Test data |
| The DNS server your computer uses (usually your modem or provider) | To show names of addresses on the Computer connections and Devices on network pages | Name lookup (IP address) |
| api.ipify.org | To show your public IP address | The request only |
| 1.1.1.1 (Cloudflare), 8.8.8.8 (Google) | Latency, DNS and traceroute checks; monitoring targets can be changed on the Monitoring page | Connection attempt / DNS query |
| www.msftconnecttest.com (Microsoft) | Same address Windows uses to check internet access | The request only |

Modem, router and device scans stay on your home network.

## 4. Your rights and deleting data

Because the data stays with you, you control it: uninstall the app and delete the folders above. We hold no data
about you, so there is nothing to request from us; for questions use the e-mail address above.

## 5. Changes

If a new feature adds a new outgoing request, this policy is updated and its date changes.

---

## Sürüm geçmişi / Version history

| Sürüm / Version | Tarih / Date | Değişen alan / Changed | Eski / Old | Yeni / New | Neden / Reason |
|---|---|---|---|---|---|
| 1.2.0 | 2026-11-14 | Uygulama adı / App name | NetAnalizer | NetAnalytic | Microsoft Store adı / Microsoft Store name |
| 1.1.0 | 2026-11-14 | §3 Ookla | Ookla motoru seçiliyse / When the Ookla engine is used | Yalnız GitHub sürümünde / GitHub edition only | Microsoft Store sürümü hız testini Cloudflare ile yapar / The Store edition measures speed with Cloudflare |
| 1.1.0 | 2026-11-14 | §3 DNS | — | DNS sunucusuna ad sorgusu / Name lookup at your DNS server | Eksik satır eklendi / Missing row added |
| 1.1.0 | 2026-11-14 | §2 | — | Ev ağı trafiği, cihaz adı ve MAC / Home network traffic, device names and MAC | Yeni özellikler / New features |
| 1.0.0 | 2026-11-10 | Belgenin tamamı / Whole document | — | İlk sürüm / First version | — |
