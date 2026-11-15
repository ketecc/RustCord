# RustCord

Rust + Tauri 2 ile geliştirilen Discord benzeri masaüstü sohbet uygulaması.

## Gereksinimler

- Windows 10/11
- Rust (rustup)
- Node.js LTS ve npm
- Tauri Windows geliştirme gereksinimleri: Microsoft C++ Build Tools ve WebView2

## Çalıştırma

Proje klasöründe terminal aç:

```powershell
npm install
npm run tauri dev
```

## İlk sürümde

- Discord esintili koyu masaüstü arayüzü
- Sunucu ve kanal kenar çubukları
- Yerel arayüzde mesaj gönderme
- Kanal seçimi
- Mesajlarda arama

Not: Bu başlangıç sürümü henüz internete bağlı değildir. Mesajlar gerçek kullanıcılara gönderilmez ve sesli sohbet henüz eklenmemiştir. Sonraki aşamada sunucu, kullanıcı doğrulama, WebSocket mesajlaşması ve WebRTC ses altyapısı kurulacaktır.
