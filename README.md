# 📨 Anlık Chat App - C# TCP Server

Bu proje, C# ile geliştirilmiş bir **anlık mesajlaşma sunucusudur**. TCP soketleri kullanarak istemciler arasında gerçek zamanlı mesajlaşma sağlar. Basit bir GUI arayüzü ve çoklu istemci desteği içerir.

## 🚀 Özellikler

- Birden fazla istemciyi aynı anda destekler.
- TCP/IP soket bağlantısı ile çalışır.
- Kullanıcıdan gelen verileri işleyip diğer kullanıcılara iletir.
- JSON formatında mesaj iletimi.
- Basit, anlaşılır ve genişletilebilir C# kod yapısı.

## 🧰 Kullanılan Teknolojiler

- C# (.NET Framework / Windows Forms)
- `System.Net.Sockets`
- `System.Threading`
- `System.Web.Script.Serialization` (JSON serileştirme)



## 📂 Kurulum

1. Bu repoyu klonla:
   ```bash
   git clone https://github.com/deniizesra/anlik-chat-app.git
2.Visual Studio ile MsgAppServer.sln dosyasını aç.

Derle ve çalıştır:

Server uygulamasını başlat.

İstemciler bağlantı kurdukça sunucu üzerinden mesajlaşma gerçekleşir.

🧪 Test
Projeyi test etmek için basit bir TCP istemcisi kullanabilir ya da kendi istemci uygulamanı yazabilirsin.
💡 Katkıda Bulun
Katkı sağlamak istersen:

Fork yap

Yeni bir branch oluştur: feature/yeniozellik

Değişiklikleri commit et

Pull Request gönder
