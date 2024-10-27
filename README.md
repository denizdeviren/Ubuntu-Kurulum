Ubuntu Kurulum Rehberi
  Bu rehberde, Ubuntu 24.04.1 sürümünü kurarken dikkat etmeniz gereken noktalar ve adım adım kurulum süreci yer almaktadır.


1. Ubuntu Sistem Gereksinimleri
  Ubuntu'yu kurmadan önce cihazınızın gereksinimlere uygun olduğundan emin olun.
  
  Minimum Sistem Gereksinimleri:
  İşlemci: 2 GHz çift çekirdekli işlemci
  RAM: 4 GB
  Depolama Alanı: 50 GB (minimal kurulum için 8.6 GB yeterlidir)
  İnternet Bağlantısı: Gerekli
  Kurulum İçin Gerekli Hazırlıklar:
  En az 25 GB boş alan (minimal kurulum için en az 5 GB)
  Ubuntu yükleme dosyasını yazmak için bir harici depolama aygıtı (USB, SSD, HDD)
  Verilerinizi yedekleyin: Kurulum sırasında olası bir veri kaybına karşı hazırlıklı olun.





2. Ubuntu Kurulum Hazırlıkları
   
![image](https://github.com/user-attachments/assets/4dec2fbd-805e-4e35-8e32-ff10c91f36e5)


2.1 Ubuntu Görüntüsünü İndirme
  Ubuntu resmi internet sitesine giderek "Desktop" sürüm görüntüsünü indirin.


2.2 USB’ye Görüntü Yazma
  İndirdiğiniz Ubuntu ISO dosyasını bir USB'ye yazdırmanız gerekiyor. Windows kullanıyorsanız Rufus yazılımını kullanarak USB'yi yükleme medyası olarak hazırlayabilirsiniz.


2.3 BIOS Ayarları
  Bilgisayarınız USB’den otomatik olarak başlamıyorsa BIOS ayarlarınıza girin. BIOS ekranına giriş için genellikle F12, F2, F10 veya Escape tuşları kullanılır. BIOS'ta Boot sekmesinde USB sürücünüzü ilk sıraya taşıyarak kaydedip çıkın.

  ![image](https://github.com/user-attachments/assets/05c22145-8f0b-410e-86dc-ef7213911cbd)





3. Ubuntu 24.04.1 Kurulumu
  USB belleği takarak bilgisayarınızı yeniden başlatın; sistem USB’den başlayacak ve kurulum ekranı açılacaktır.


3.1 Dil Seçimi
  Kurulum ekranında istediğiniz dili seçin veya İngilizce kurulumla devam edin.

 ![image](https://github.com/user-attachments/assets/643a29dc-5dc5-42f5-80bd-2372044be0f9)


3.2 Kurulum Türü
  "Ubuntu'yu Yükle" seçeneğine tıklayarak yüklemeye başlayın.

   ![image](https://github.com/user-attachments/assets/2c28cd32-49f6-40a7-895a-8f601543c92a)
   

3.3 Klavye Düzeni
  Klavye düzeninizi seçin. Eğer farklı bir klavye kullanıyorsanız listeden seçebilir veya Klavyeyi Algıla seçeneğiyle otomatik olarak ayarlayabilirsiniz.

![image](https://github.com/user-attachments/assets/eecc141b-94f4-4cee-9108-7b6b554c38cc)


3.4 Yazılım Seçenekleri
  Kurulum tipi olarak iki seçenek bulunur:
  
  Normal Kurulum: Standart uygulamalar ve yardımcı programları içerir.
  Minimal Kurulum: Daha az depolama alanı kullanır, temel uygulamaları içerir.
  Güncellemeleri indirmek ve üçüncü taraf yazılımları yüklemek için seçenekleri etkinleştirmenizi öneririz.

 ![image](https://github.com/user-attachments/assets/238c5b90-a425-4ecf-93a0-8d189b3ed406)


3.5 Disk Bölümlendirme
  Ubuntu'yu mevcut bir işletim sistemi ile birlikte mi yoksa tek başına mı kuracağınızı seçin:
  
  Yan Yana Kurulum: Mevcut bir işletim sistemi ile Ubuntu’yu birlikte kurar.
  Diski Sil ve Ubuntu’yu Kur: Mevcut diski silip sadece Ubuntu kurulumunu gerçekleştirir.
  Something Else: Manuel bölümleme için gelişmiş seçenekler sunar.


3.6 Bölümler Oluşturma
  Linux üzerinde önerilen bölümler:
  
  /boot: Önyükleyici dosyaları için (300 MB)
  / (kök dizin): İşletim sistemi dosyaları için (50 GB veya daha fazla)
  /home: Kullanıcı dosyaları için maksimum alan
  Her bir alanı oluşturduktan sonra Şimdi Yükle seçeneğine tıklayarak bölümlendirmeyi tamamlayın.

![image](https://github.com/user-attachments/assets/bc665c4f-1255-4a24-9329-fb8a7e255481)


3.7 Saat Dilimi Ayarı
  Eğer cihazınız internete bağlı ise saat diliminiz otomatik olarak belirlenecektir. Doğru değilse, yaşadığınız bölgeyi seçin.

 ![image](https://github.com/user-attachments/assets/eaac039b-a289-4888-aaf1-0f62a40a0bed)


3.8 Kullanıcı Bilgileri
  Adınızı, kullanıcı adınızı ve güçlü bir şifrenizi girin. Bu bilgiler, Ubuntu’ya her giriş yaptığınızda kullanılacaktır.

   ![image](https://github.com/user-attachments/assets/b90bf754-9890-4506-9a3f-3e08168a3214)


3.9 Kurulum ve Yeniden Başlatma
  Kurulum tamamlandığında bilgisayarınızın yeniden başlatılması istenecektir. “Şimdi Yeniden Başlat” tuşuna tıklayarak kurulumu tamamlayın ve USB belleği çıkarın.

  ![image](https://github.com/user-attachments/assets/ae19cf73-feed-496e-8ff5-80732f71caa7)
  ![image](https://github.com/user-attachments/assets/acbcd8d1-a037-4a71-b8f1-f2303939f915)





4. Sonuç
  Tebrikler! Ubuntu’yu başarıyla kurdunuz. Artık sisteminizi keşfetmeye ve kullanmaya başlayabilirsiniz. Diğer Ubuntu sürümleri de benzer adımlarla kurulabilir.
  
  Ubuntu'nun keyfini çıkarın!

Bu rehberin Ubuntu yüklemesini adım adım gerçekleştirmek isteyenler için faydalı olacağını umuyoruz.
