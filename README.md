# Türk Dili Vize Kampı

Üniversite **Türk Dili I** ara sınavı için hazırlanmış, tek dosyalık (`index.html`) statik çalışma sitesi. Çerçeve, sunucu, hesap veya giriş yoktur; telefon ve bilgisayarda çalışır.

**Canlı:** https://turk-dili-vize-kampi.vercel.app · https://njtbcrn.github.io/turk-dili-vize-kampi/

## Özellikler
- 📘 **Konu notları:** dil ve kuramlar, dilin işlevleri, anlatım bozuklukları (anlama ve yapıya dayalı), yazım kuralları (6. ve 7. hafta), son dakika özeti
- ✅ **Konu testleri:** anında geri bildirim ve açıklama, "yanlışlarım" testi
- 📝 **Deneme sınavı:** 20 soru = **5 dil + 8 anlatım bozukluğu + 7 yazım**, soru ve şık sırası karışık, 100 üzerinden puan ve konu dökümü, yanlış inceleme
- 🔎 **Soru bankası:** arama, kaynak ve doğrulama etiketi
- 🃏 Bilgi kartları, 📊 ilerleme takibi (tarayıcıda `localStorage`)

## Sorular
`data/questions.json` içinde 300 soru vardır (187 anlatım, 67 yazım, 46 dil). Her soruda konu, şıklar, doğru cevap, açıklama, kaynak (dosya ve soru/slayt numarası) ve doğrulama durumu bulunur:

| Durum | Anlamı |
|---|---|
| `dogrulandi` | Kaynakta cevap anahtarı var ve bağımsız çözümle uyuşuyor |
| `anahtarsiz` | Kaynakta anahtar yok (ör. eski sınav fotoğrafları); bağımsız çözüm, sitede etiketli |
| `orijinal` | Ders slaytlarına dayanan özgün soru |

Kaynak anahtarı çelişkili ya da şüpheli bulunan sorular (ör. 3. hafta PDF'inde 16, 36, 40, 45, 52, 54, 71, 72, 73, 89, 94 ve bazı Klasikhoca yazım soruları) siteye **alınmamıştır**. Soru metni eksik olan kaynaklar ile yalnızca bağlantı içeren dosyalar atlanmıştır.

## Çalıştırma
`index.html` dosyasını tarayıcıda açmanız yeterlidir. Veriler dosyanın içine gömülüdür.

## Notlar
- Geçici bir sınav çalışma aracıdır; sınavda çıkacak sorular garanti edilmez, ders notlarıyla birlikte kullanın.
- Slayt PDF'lerindeki açılır ("GÖSTER") içerikler taranmış görüntülerden okunamadığı için bazı örnekler TDK yazımına göre tamamlanmıştır.
- Soruların bir kısmı üçüncü kişilerin soru derlemelerinden alınmıştır; telif hakları sahiplerine aittir.

Hazırlayan: **Nejat Beceren**
