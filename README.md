# InstagramCloneWithFirebase

## Özet
Firebase Cloud veritabanı kullanarak yaptığım instagram klonunun ilk versiyonu. Firebase Auth kullanarak e-mail ve şifre parametreleri ile 
kullanıcı kayıt ve giriş yapma gibi gereksinimleri gerçekleştirdim. Ardından bizi Tab Bar Controller yapısına bağlı 3 adet View Controller
karşılıyor. FeedVC kullanıcılar tarafından yüklenmiş postları gösteren bir akış sayfası burada veriler firebase üzerinden çekiliyor ve
yayınlanma tarihine bağlı olarak listeleniyor. Ayrıca basit bir post beğenme modülüde ekledim ancak henüz tam verimli çalışmıyor. UploadVC
kullanıcıları kendi cihazlarında ki local veritabanından veri çekmelerine ve yine VC üzerinde göstermelerine olanak sağlıyor ardından upload
butonu ile paylaşılmak istenilen postun yorumu ile birlikte Firebase Firestore üzerine kayıt olmasını sağladım. Local veri tabanından
aldığımız dataları firebase storage üzerinde kayıt edip verilen linkleri string yapısı ile firestore da kaydettim. Son olarak SettingsVC
üzerinde şimdilik sadece kullanıcının  çıkış yapması için konumlandırılan bir adet log-out butonu bulunmakta.

<img src="https://i.hizliresim.com/o9yal17.png" width="280" height="500"> <img src="https://i.hizliresim.com/2qkbvat.png" width="280" height="500">
<img src="https://i.hizliresim.com/odrq9q4.png" width="280" height="500"> <img src="https://i.hizliresim.com/cninigf.png" width="280" height="500">
<img src="https://i.hizliresim.com/pmetlru.png" width="280" height="500"> 
