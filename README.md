# iPUB — İndir

PDF kitaplarınızı (dijital ya da taranmış) Kindle ve diğer e-okuyucular için düzgün okunan EPUB'a dönüştüren **iPUB**'un macOS ve Windows kurulum dosyaları burada yayımlanır. Her şey kendi bilgisayarınızda çalışır; kitaplarınız hiçbir yere gönderilmez.

**[Son sürümü indir →](https://github.com/Ulas-Yilmaz/iPUB-releases/releases/latest)**

| Sistem | Dosya |
|---|---|
| macOS (Apple Silicon ve Intel) | `iPUB-x.y.z-universal.dmg` |
| Windows (64 bit) | `iPUB-Setup-x.y.z.exe` |

## İlk açılış

iPUB henüz imzalı (noter onaylı) bir uygulama değildir; bu yüzden ilk açılışta işletim sistemi bir uyarı gösterebilir.

- **macOS:** `.dmg`'yi açıp iPUB'u Uygulamalar klasörüne sürükleyin. Uygulama açılmazsa Sistem Ayarları → Gizlilik ve Güvenlik → **"Yine de Aç"**'a tıklayın (bu seçenek, uygulamayı bir kez açmayı denedikten sonra görünür). Hâlâ açılmazsa Terminal'de `xattr -cr /Applications/iPUB.app` komutunu çalıştırıp yeniden deneyin.
- **Windows:** Kurulum dosyasını çalıştırın. "Windows bilgisayarınızı korudu" uyarısında **Ek bilgi → Yine de çalıştır**'a tıklayın.

## Güncelleme

iPUB açılışta yeni sürüm olup olmadığına bakar; sağ alttaki sürüm numarasına tıklayıp **"Güncellemeyi denetle"** ile elle de denetleyebilirsiniz.

- **Windows:** Güncelleme uygulama içinden indirilir; **"Yeniden başlat ve güncelle"** ile kurulur.
- **macOS:** **"İndir"** yeni `.dmg`'yi indirir. Önce iPUB'tan çıkın, sonra `.dmg`'yi açıp iPUB'u Uygulamalar'a sürükleyin ve "Değiştir"i seçin. Yeni sürüm ilk açılışta yine "Yine de Aç" onayı isteyebilir.
