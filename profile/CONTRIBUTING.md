# Katkı Rehberi - MKA-K  

Öncelikle projeye ilgi gösterdiğiniz için teşekkür ederiz! MKA-K, ekstrem çevre koşullarında çalışabilen modüler ve su geçirmez bir insansız kara aracı geliştirmeyi hedefleyen açık kaynaklı bir projedir. Projeye katkıda bulunmak için aşağıdaki yönergeleri takip edebilirsiniz.  

---

## 📌 Katkıda Bulunmadan Önce  

Lütfen katkıda bulunmadan önce aşağıdaki adımları takip edin:  

1. **Mevcut Konuları İnceleyin**  
   - [GitHub Issues](https://github.com/orgs/MKA-K/discussions) sekmesinden açık konuları inceleyin.  
   - Çözmek istediğiniz bir konu varsa, yorum yaparak veya yeni bir konu açarak katkınızı belirtin.  

2. **Kod Standartlarını İnceleyin**  
   - Projede **GO** ve **Rust** dilleri kullanılmaktadır.  
   - Kodlama standartları için [CODING_GUIDELINES.md](CODING_GUIDELINES.md) dosyasını inceleyin.  

3. **Geliştirme Ortamını Kurun**  
   - Proje bağımlılıklarını yüklemek için [SETUP.md](SETUP.md) dosyasındaki adımları takip edin.  

---

## 🚀 Nasıl Katkıda Bulunabilirsiniz?  

### 🛠️ Hata Bildirimi (Bug Report)  
- Bir hata bulduysanız, [GitHub Issues](https://github.com/MKA-K/issues) sekmesinden yeni bir hata bildirimi oluşturabilirsiniz.  
- Hata raporunuzda şu bilgileri eklemelisiniz:  
  - Hatanın açık bir tanımı  
  - Tekrar üretme adımları  
  - Beklenen ve alınan sonuçlar  
  - Gerekli ekran görüntüleri veya log çıktıları  

### 💡 Yeni Özellik Önerisi  
- Yeni bir özellik öneriniz varsa, [GitHub Discussions](https://github.com/MKA-K/discussions) veya **Issues** sekmesi üzerinden paylaşabilirsiniz.  
- Önerinizin proje hedeflerine uygun olup olmadığını değerlendirmek için geliştirici ekibi ile iletişim kurabilirsiniz.  

### 🔧 Kod Katkısı (Pull Request)  
Kod katkısı yapmak için aşağıdaki adımları takip edebilirsiniz:  

1. **Projeyi Fork’layın ve Yerel Ortamınıza Kopyalayın**  
   ```sh
   git clone https://github.com/your-username/MKA-K.git
   cd MKA-K
   git checkout -b feature-branch
   ```  
2. **Geliştirme ve Test**  
   - Yeni kod eklemeleri yapmadan önce mevcut kodları test edin.  
   - Değişikliklerinizi yaptıktan sonra testlerinizi çalıştırın.  

3. **Kod Standartlarına Uygunluğu Kontrol Edin**  
   - **Python** için `flake8` ve `black` kullanabilirsiniz.  
   - **C++** kodları için `clang-format` kullanabilirsiniz.  

4. **Commit Mesajı Yazımı**  
   - Açık ve anlaşılır commit mesajları kullanın.  
   - Örnek:  
     ```sh
     git commit -m "Rover sürüş algoritmasında hata düzeltildi"
     ```
     
5. **Pull Request (PR) Gönderme**  
   - Değişikliklerinizi kendi **Fork** deposuna gönderin:  
     ```sh
     git push origin feature-branch
     ```  
   - GitHub üzerinden **Pull Request** (PR) oluşturun.  
   - Açıklama kısmında yaptığınız değişiklikleri özetleyin.  
   - PR’ınız proje yöneticileri tarafından incelenecek ve gerekli görüldüğünde geri bildirim alacaksınız.  

---

## 📜 Katkı Kuralları  

- Kodlarınızın **dökümantasyonunu** eksiksiz tutun.  
- Büyük değişiklikler öncesinde **tartışma başlatın**.  
- Açık ve okunabilir kod yazın.  
- Geliştirme sürecinde proje yönetim ekibiyle **iletişimde kalın**.  
- **Lisans uyumluluğunu** kontrol edin (MIT Lisansı).  

---

## 📬 İletişim  

Herhangi bir sorunuz veya öneriniz olursa [egekilic@proton.me](mailto:egekilic@proton.me) adresinden bizimle iletişime geçebilirsiniz.  

Teşekkürler ve iyi katkılar! 🚀
