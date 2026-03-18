# Kütüphane Yönetim Sistemi
Java ve Spring Boot kullanılarak geliştirilen SOLID prensiplerine uyumlu, mikro servis tabanlı bir kütüphane yönetim sistemidir. Her servis REST API ile iletişim kurar ve SQLite veritabanı kullanır.

### Özellikler
* Kullanici Yönetimi ( GirisYap, KayıtOl )
* Kitap Yönetimi ( KitapEkle, KitapGuncelle, KitapAra )
* Ödünç İşlemleri (KitapOdunçAl, KitapIadeEt, OdunçListesiniGöster )
* Bildirim Sistemi ( BildirimGonder )
* Veritabanı ( VeritabanıBaglantisi )

`Projedeki kullanılan veritabanı dosyasının adı kutuphane.db dır.`

### Kullanılan Teknolojiler
* Java 24
* SQLite
* Spring Boot
* Maven
* RESTful API

### Projeyi Çalıştırma
1. Eclipse IDE'yi açın.
2. `File > Open Projects from File System...` yolunu izleyin.
3. `Directory` kısmından proje klasörünü seçin (`KutuphaneYonetimSistemi`).
4. Proje açıldıktan sonra istediğiniz servisi (örneğin `kullanici-servisi`) seçin.
5. `src/main/java` klasöründen `main` sınıfına sağ tıklayın (`KullaniciServisiApplication.java` gibi).
6. `Run As > Java Application` seçeneğine tıklayarak servisi başlatın.
7. Başarıyla çalıştıysa terminalde `Started` yazısını görürsünüz.
