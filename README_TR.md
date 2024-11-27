Basit 2D Hareketli Oyun ve Sınırlar

Bu Python oyunu, Pygame kütüphanesi kullanılarak oluşturulmuştur. Oyunda bir karakter, bir pencere içinde hareket eder ve sınırlar tarafından kısıtlanır. Eğer karakter ekranın kenarına dokunursa, kısa bir süre için bir mesaj görünür ve karakterin sınırı çarptığı belirtilir.

Özellikler:

Karakter, ok tuşları veya W, A, S, D tuşlarıyla yukarı, aşağı, sola ve sağa hareket edebilir.
Karakter ekranın kenarlarına çarptığında, çarpma mesajı görünür.
Hareket, ivme ile etkilenir ve karakterin hızı, tuş basılmadığında yavaşlar.
Oyun, ekranı günceller ve girişleri gerçek zamanlı olarak işler.

Nasıl Çalışır:

Karakter Hareketi:

Karakter, ok tuşları veya W, A, S, D tuşlarıyla hareket eder.
Hareket, ivme ve yavaşlama etkileriyle yumuşak bir şekilde gerçekleştirilir; tuş basılmadığında hız azalır.

Sınır Çarpma:
Eğer karakter ekranın kenarlarına (sol, sağ, üst veya alt) dokunursa, sınırda durur ve 2 saniye boyunca "Sınıra Çarptın!" mesajı görünür.

Hız Kontrolü:
Karakterin her yöndeki hızı, ivme ile kontrol edilir. Tuşlar basıldıkça hız artar, bırakıldıkça ise yavaşlar.
