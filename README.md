# 🎮 Hacker Games - Siber Güvenlik Simülasyonu

## 📖 Hikaye
Düzce Üniversitesi'nin bilgi sistemlerine sızan bir hacker, öğrenci notlarını değiştirmeye çalışmaktadır. Siz, üniversitenin siber güvenlik ekibinin bir üyesisiniz ve bu saldırıyı durdurmak için görevlendirildiniz. 10 dakika içinde hacker'ı durdurmanız ve sistemleri güvenli hale getirmeniz gerekiyor. Her yanlış hamlenizde bir veri sızdırılacak ve tüm verileriniz sızdığında oyun sona erecek.

## 📝 Proje Hakkında
Bu proje, siber güvenlik kavramlarını öğrenmek ve pratik yapmak için tasarlanmış interaktif bir web tabanlı simülasyon oyunudur. Kullanıcılar, gerçek dünya senaryolarına dayalı görevleri tamamlayarak siber güvenlik becerilerini geliştirebilirler.

## 🎯 Özellikler
- 🕹️ 7 farklı görev ve senaryo
- ⏱️ Gerçek zamanlı süre takibi (10 dakika)
- 📊 İlerleme göstergesi
- 💾 Veri sızıntısı simülasyonu (5 kritik veri)
- 🎯 Hedef odaklı görevler
- 💡 İpucu sistemi (Her 2 ipucu 1 veri kaybı)
- 🎨 Gerçekçi terminal arayüzü
- 🎭 Matrix tarzı animasyonlar
- 🎮 Nano editör simülasyonu
- 🔐 Parola kırma animasyonu

## 🎮 Oyun Mekanikleri
- **Süre**: 10 dakika
- **Başlangıç Veri Sayısı**: 5 (WhatsApp, Instagram, Galeri, Rehber, Banka)
- **Veri Kaybı Koşulları**:
  - Her yanlış komut: -1 veri
  - Her 2 ipucu kullanımı: -1 veri
- **Oyun Sonu Koşulları**:
  - Tüm verilerin sızması
  - Sürenin dolması
  - Tüm görevlerin başarıyla tamamlanması

## 🚀 Başlangıç
1. Projeyi klonlayın:
```bash
git clone https://github.com/kullanici/hacker-games.git
```

2. Proje dizinine gidin:
```bash
cd hacker-games
```

3. `index.html` dosyasını bir web tarayıcısında açın.
4. Tam ekran (F11) modunda oynamanız önerilir.

## 🎮 Oyun İçeriği

### Görev 1: Yerel Ağa Sızma
- DHCP protokolü kullanarak ağa sızma
- IP adresi alma simülasyonu
- Hedef: 10.16.23.48 IP adresini elde etme

### Görev 2: Ağ Taraması
- nbtscan ile ağdaki cihazları tespit etme
- Ağ topolojisi analizi
- Hedef: t.timucin kullanıcısının bilgisayarını bulma

### Görev 3: Parola Kırma
- Hydra ile SSH parola kırma
- Brute force saldırısı simülasyonu
- Hedef: SSH şifresini kırma

### Görev 4: SSH Bağlantısı
- sshpass ile otomatik bağlantı
- Güvenli bağlantı kurulumu
- Hedef: Hedef sisteme bağlanma

### Görev 5: Dosya Keşfi
- Dizin navigasyonu
- Dosya arama ve bulma
- nano editör kullanımı
- Hedef: organizasyon_vize.txt dosyasını bulma

### Görev 6: Dosya Düzenleme
- Metin editörü kullanımı
- Dosya içeriği değiştirme
- Değişiklikleri kaydetme
- Hedef: Notları düzeltme

### Görev 7: Log Temizleme
- sed komutu ile log dosyalarını düzenleme
- İz silme simülasyonu
- Hedef: Saldırı izlerini temizleme

## ⌨️ Temel Komutlar
| Komut | Açıklama |
|-------|----------|
| `ipucu` | Mevcut görev için ipucu gösterir |
| `görevi tekrar et` | Aktif görevi tekrar görüntüler |
| `Tab` | Komut önerilerini listeler |
| `↑/↓` | Komut geçmişinde gezinir |
| `Ctrl + G` | Aktif görevi otomatik doldurur |

## 🛠️ Kullanılan Teknolojiler
- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome
- Google Fonts (Fira Code)
- Matrix Animasyonları
- Terminal Simülasyonu

## 📚 Öğrenilen Kavramlar
- Ağ güvenliği
- Parola kırma
- Dosya sistemi
- Log yönetimi
- Terminal komutları
- SSH protokolü
- DHCP protokolü
- Dizin navigasyonu
- Dosya düzenleme
- Log temizleme

## ⚠️ Güvenlik Uyarısı
Bu proje sadece eğitim amaçlıdır. Öğrenilen tekniklerin kötüye kullanımı yasal sorunlara yol açabilir. Gerçek sistemler üzerinde izinsiz penetrasyon testleri veya sızma girişimleri yasalara aykırıdır.

## 🤝 Katkıda Bulunma
1. Bu depoyu fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/yeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik: Açıklama'`)
4. Branch'inizi push edin (`git push origin feature/yeniOzellik`)
5. Pull Request oluşturun


## 👥 İletişim
- Proje Sahibi: [Arif Yarencik]
- E-posta: [arifyarencik@gmail.com]
- GitHub: [https://github.com/Arfyrnck]

## 🙏 Teşekkürler
- Tüm katkıda bulunanlara
- Açık kaynak topluluğuna
- Test edenlere ve geri bildirim verenlere

## 🔄 Güncellemeler
- İpucu sistemi güncellendi (Her 2 ipucu kullanımı 1 veri sızıntısına neden olur)
- Ctrl + G ile görev otomatik doldurma özelliği eklendi
- 5. görev yeniden düzenlendi ve iyileştirildi
- Görev ilerleme çubuğu 0'dan başlayacak şekilde düzeltildi
- Matrix animasyonları eklendi
- Terminal arayüzü geliştirildi
