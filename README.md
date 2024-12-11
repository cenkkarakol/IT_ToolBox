# IT Toolbox - Ver 1.0

**IT Toolbox**, günlük BT işlerini hızlandırmak ve kolaylaştırmak için tasarlanmış bir komut dosyasıdır. Proje, çeşitli yönetimsel ve tanılama işlemlerini kullanıcı dostu bir menü üzerinden sunar. Sistem yönetimi ve kullanıcı desteği süreçlerinde ihtiyaç duyabileceğiniz birçok aracı tek bir yerde toplar.

---

## 📋 Özellikler

IT Toolbox, toplamda **40'tan fazla işlem** sunmaktadır. Başlıca özellikler şunlardır:

1. **Bilgisayar ve Aktif Kullanıcı Adını Göster**
2. **Bilgisayar Seri Numarasını Göster (Yönetici Yetkisi Gerekir)**
3. **Bilgisayarın Marka ve Model Bilgisi**
4. **Donanım ve Sistem Bilgileri (systeminfo)**
5. **Windows Lisans Durumu ve Etkin Lisans Bilgisi**
6. **Windows Sürüm ve Güncelleme Bilgileri**
7. **Disk Temizliği ve Gereksiz Dosyaları Silme**
8. **Ağ ve IP Ayarları Yönetimi**
9. **Wi-Fi Şifresi Görüntüleme (Yönetici Yetkisi Gerekir)**
10. **Yazıcı Yönetimi (Durum Görüntüleme, Kuyruk Temizleme, Yeniden Başlatma)**
11. **Sistem Dosyalarını Onarma ve Disk Sağlığını Kontrol Etme**
12. **Sistemi Güvenli Modda Yeniden Başlatma**
13. **Grup Politikalarını Güncelleme**
14. **Bilgisayarı Kapatma veya Yeniden Başlatma**

Ve daha fazlası...

---

## 🛠️ Kurulum

### Gerekli Şartlar
- **Windows işletim sistemi** (Windows 7 ve üzeri)
- Yönetici yetkileri, belirli komutların çalışması için gereklidir.
- CMD ortamında çalışır.

### Adımlar
1. [Bu depoyu indir](https://github.com/cenkkarakol/IT_ToolBox/archive/refs/heads/main.zip) veya `git clone` ile yerel makinenize klonlayın:
   ```bash
   git clone https://github.com/cenkkarakol/IT_ToolBox.git
İndirdiğiniz klasöre gidin ve IT-Toolbox.bat dosyasını çalıştırın.
Menüden yapmak istediğiniz işlemi seçin.

---

## 🎮 Kullanım

1. `IT-Toolbox.bat` dosyasını çift tıklayarak çalıştırın.
2. Menüde yer alan işlem numarasını yazıp `Enter` tuşuna basın.
3. Seçtiğiniz işlem otomatik olarak tamamlanacaktır.
4. Menüye dönmek için `Enter` tuşuna basabilirsiniz.

**Not:** Bazı işlemler için yönetici izni gerekebilir. Örneğin, Wi-Fi şifresini görüntüleme veya sistem dosyalarını onarma gibi işlemler yönetici yetkisi gerektirir.

---

## 💡 Projeye Katkıda Bulunun

Projeyi geliştirmek isteyenler için kaynak kodlar GitHub üzerinde herkese açıktır. Katkıda bulunmak için aşağıdaki adımları izleyebilirsiniz:

1. Depoyu forklayın ve değişikliklerinizi yerel bir dalda yapın.
2. Kodunuzu test edin ve yeni bir özellik ekliyorsanız README dosyasını güncellemeyi unutmayın.
3. Değişikliklerinizi içeren bir **Pull Request (PR)** oluşturun.

---

## ✨ Özelleştirme ve Genişletme

**IT Toolbox**, açık kaynak bir projedir ve kolayca genişletilebilir. Yeni özellik eklemek için `menu` bölümüne yeni bir seçenek ekleyebilir ve ilgili komutu tanımlayabilirsiniz. Örnek bir kod:

```batch
echo 42. Örnek Yeni Özellik
if "%choice%"=="42" (echo Yeni Özellik Çalıştırıldı && pause)
```

---

## 👤 Yazar

**Cenk Karakol**  
Proje, IT süreçlerini kolaylaştırmak amacıyla Cenk Karakol tarafından geliştirilmiştir.

Herhangi bir sorunuz, öneriniz veya geri bildiriminiz varsa lütfen GitHub üzerinden iletişime geçmekten çekinmeyin! 😊


