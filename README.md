# 🖥️ Hacker Terminal Simülasyonu

Gerçekçi bir siber güvenlik terminali!  
Kendinizi bir hacker gibi hissedin, görevleri tamamlayın, verilerinizi koruyun ve zamana karşı yarışın.

<!-- Demo veya GIF eklemek için aşağıdaki satırı kullanın -->
<!-- ![Demo](docs/demo.gif) -->

---

## 🚀 Özellikler

- **7 Farklı Görev:** Gerçek dünya siber güvenlik senaryoları
- **Süre Sınırı:** 10 dakika içinde tüm görevleri tamamlama
- **Veri Koruma:** 5 kritik veri türü (WhatsApp, Instagram, Galeri, Rehber, Banka)
- **Dinamik İpucu Sistemi:** Her görev için rastgele ve tekrar etmeyen ipuçları
- **Gerçekçi Terminal Arayüzü:** Matrix animasyonları, efektler ve nano editör simülasyonu
- **Parola Kırma ve Sızma Animasyonları:** Görev bazlı özel efektler
- **Responsive Tasarım:** Tüm cihazlarda oynanabilir

---

## 🎮 Oynanış

1. Terminalde verilen görevi dikkatlice okuyun.
2. Doğru komutları girerek görevi tamamlayın.
3. Takıldığınızda `ipucu` komutunu kullanın (her 2 ipucunda 1 veri kaybı!).
4. Yanlış komutlardan kaçının (her yanlış komut 1 veri kaybı!).
5. Tüm görevleri veriler sızmadan ve süre dolmadan tamamlamaya çalışın.

---

## ⌨️ Temel Komutlar

| Komut              | Açıklama                                 |
|--------------------|------------------------------------------|
| `ipucu`            | Mevcut görev için rastgele ipucu gösterir|
| `görevi tekrar et` | Aktif görevi tekrar görüntüler           |
| `Tab`              | Komut önerilerini listeler               |
| `↑/↓`              | Komut geçmişinde gezinir                 |
| `Ctrl + G`         | Aktif görevi otomatik doldurur           |

---

## 🛠️ Teknik Detaylar

- **Frontend:** HTML5, CSS3, JavaScript
- **Yazı Tipi:** Fira Code (monospace)
- **İkonlar:** Font Awesome
- **Efektler:** Matrix arka plan, animasyonlu terminal, nano editör simülasyonu

---

## 📥 Kurulum

```bash
git clone https://github.com/kullaniciadi/hacker-terminal.git
cd hacker-terminal
```
- `index.html` dosyasını modern bir tarayıcıda açın.
- Tam ekran (F11) modunda oynayın.

---

## 📊 Oyun Mekanikleri

- **Süre:** 10 dakika
- **Başlangıç Verisi:** 5
- **Veri Kaybı:** Her yanlış komut veya her 2 ipucu = -1 veri
- **Oyun Sonu:**
  - Tüm verilerin sızması
  - Sürenin dolması
  - Tüm görevlerin başarıyla tamamlanması

---

## 🖼️ Ekran Görüntüsü

<!-- Ekran görüntüsü eklemek için aşağıdaki satırı kullanın -->
<!-- ![Ekran Görüntüsü](docs/screenshot.png) -->

---

## 🤝 Katkı

Katkıda bulunmak isterseniz lütfen bir pull request gönderin veya issue açın.

---

## ⚠️ Yasal Uyarı

Bu simülasyon yalnızca eğitim amaçlıdır. Gerçek sistemler üzerinde izinsiz penetrasyon testleri veya sızma girişimleri yasalara aykırıdır.

## 🔄 Güncellemeler

- İpucu sistemi güncellendi (Her 2 ipucu kullanımı 1 veri sızıntısına neden olur)
- Ctrl + G ile görev otomatik doldurma özelliği eklendi
- 5. görev yeniden düzenlendi ve iyileştirildi
- Görev ilerleme çubuğu 0'dan başlayacak şekilde düzeltildi
