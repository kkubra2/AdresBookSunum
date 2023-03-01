# AdresBookSunum

PROJE HAKKINDA TEKNİK BİLGİLER:

- Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
- Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
- Projede AspnetCore Identity kullanarak üyelik sistemini yazdık.
- Projeyi 5 katman (EL,DAL,BLL,UI, AddressBookNeighborhoodsLoad) olarak yazdık. -AddressBookNeighborhoodsLoad katmanı Console uygulaması olup Mahalle datasını eklemektedir. (70bin data bulunuyor)
- Projede İlleri ve İlçeleri Excel dosyasını back-endde okuyarak veritabanına proje ilk ayağa kalktığında ekledik.
- Projede Adres listesi ve Adres Ekle - Adres Sil ekranları bulunuyor.
- Adres Ekle sayfasındaki işlemleri AJAX ile yapmaktayız. Örneğin; ili seçtiğinde ilçeler sayfa yenilenmeden gelir. İlçeyi seçtiğinde mahalleler sayfa yenilenmeden gelir.
- Mahalleyi seçince o mahallenin posta kodunu APi'den çektik. https://api.ubilisim.com/postakodu/il/34
- Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.
- Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz .

<img width="953" alt="219572540-abd005fc-65f3-4be0-b576-0d21f0902b80" src="https://user-images.githubusercontent.com/94785926/222117766-c298002b-923a-4012-bbb2-bafe9d9c0440.png">

<img width="960" alt="219572552-edf5e923-5112-4529-93b3-a99fe2b277b3" src="https://user-images.githubusercontent.com/94785926/222117791-5bd3e674-e2cb-4a78-8329-8ff437a71f33.png">

<img width="960" alt="219572558-1bc3befc-494b-498a-95ce-6ee726aa3e69" src="https://user-images.githubusercontent.com/94785926/222117846-77b44b43-6d9a-42f0-a5ee-71789b67fc91.png">

<img width="254" alt="219574439-6f3c596d-6916-4fda-8b35-e23da3ddbc48" src="https://user-images.githubusercontent.com/94785926/222117869-71542198-4c3d-4fc4-89c4-8483858e6eb6.png">

<img width="956" alt="219574456-075c80bd-eb93-4e6e-813e-6fa4de9292f8" src="https://user-images.githubusercontent.com/94785926/222117904-841d9ddf-2902-4855-ba9a-fd54a0091fe2.png">

<img width="959" alt="219574469-ec16aeee-8e9c-44ad-ac3d-0c7973c37eff" src="https://user-images.githubusercontent.com/94785926/222117940-3e807ef4-0edc-41aa-b703-12850a0ad466.png">
