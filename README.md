# HayDayTestBackend
Proje Adı: Unity Oyun Verisi Yönetim Sistemi
Açıklama
Bu proje, Unity tabanlı bir oyunun oyuncu verilerini SQLite veritabanında saklamak, yüklemek ve yönetmek için geliştirilmiştir. Kullanıcılar, oyun ilerlemelerini kaydedebilir, tekrar yükleyebilir ve verilerini sıfırlayabilir. Aynı zamanda çevrimdışı kaynak üretimi gibi özellikleri destekler.

Kullanılan Teknolojiler
Unity: Oyun motoru olarak kullanılmıştır.
C#: Tüm kod yapısı C# programlama dili ile yazılmıştır.
SQLite: Oyuncu verilerini saklamak için kullanılmıştır.
Singleton Design Pattern: GameManager gibi sınıflarda kullanılmıştır.
Unity UI (TMP, Button, InputField): Kullanıcı arayüzü geliştirmek için kullanılmıştır.
Sistem Mimarisi
UIManager: Kullanıcı arayüzü ile etkileşimi yönetir.
DatabaseManager: SQLite veritabanına bağlanarak veri saklama, yükleme ve sıfırlama işlemlerini gerçekleştirir.
GameManager: Oyunun temel yönetimini sağlar ve Singleton olarak çalışır.
ResourceProduction: Oyuncunun çevrimdışı kaldığı süre boyunca kaynak üretimini hesaplar.
PlayerData: Oyuncu bilgilerini içeren model sınıfıdır.
Kurulum ve Kullanım
Unity Projesine SQLite kütüphanesi eklenmelidir.
DatabaseManager, GameManager ve UIManager bileşenleri sahneye eklenmelidir.
UIManager üzerinden veri kaydetme, yükleme ve sıfırlama işlemleri yapılabilir.
Oyuncu oyundan çıktığında kaynak üretimi hesaplanarak veri güncellenir.
Güvenlik Önlemleri
Bu sistemde veri güvenliğini artırmak için ek koruma önlemleri eklenebilir. Veri şifreleme, yetkisiz erişime karşı koruma ve hack girişimlerine karşı güvenlik katmanları ekleyerek oyuncu verilerini daha güvenli hale getirebilirim. Bunun dışında, özel güvenlik çözümleri de uygulanabilir ve gerektiğinde sistemde iyileştirmeler yapılabilir.
