# Bir Kelime Bir İşlem

Okulda projeksiyona yansıtarak oynanan sınıf içi yarışma sayfası. Tek bir HTML dosyasıdır; `bir-kelime-bir-islem.html` dosyasını tarayıcıda açmanız yeterlidir, kurulum ve sunucu gerektirmez.

## Özellikler

- Kelime turu: 8 harf + joker, en uzun geçerli kelime (3→3, 4→4, 5→5, 6→7, 7→9, 8→11, 9→15 puan)
- İşlem turu: 6 sayı ile dört işlemle hedef sayıya ulaşma (tam sonuç 10, 1–5 yakın 7, 6–10 yakın 5 puan)
- Yalnızca kelime, yalnızca işlem ya da karışık yarışma
- Zorluğa göre işlem turu sayısı (Çok kolay → Uzman), kolaydan zora sıralı
- 1–40 yarışmacı, canlı puan tablosu, podyum
- Harfler/sayılar açılınca kendiliğinden başlayan geri sayım, son 10 saniyede uyarı sesi
- Olası çözümü adım adım gösterme
- Projeksiyon için tek ekrana sığan büyük düzen, açık/koyu tema, tam ekran
- Sayfa kapansa bile yarışma kaldığı yerden devam eder (tarayıcı belleği)

## Kullanım

1. Dosyayı açın, yarışmacı sayısını ve tur düzenini seçin.
2. "Yarışmayı başlat" → her turda "Harfleri aç" / "Sayıları aç".
3. Süre bitince "Sonuçları gir": öğrencilerin kâğıtlarındaki sonuçları yazın, geçersiz olanların işaretini kaldırın.
4. "Puanları işle" ile sonraki tura geçin.

Kelimenin sözlükte olup olmadığına öğretmen karar verir; sayfa yalnızca harflerin uygunluğunu denetler.

## Kaynak

Sayı üretim mantığı [Zeka Pusulası — Bir İşlem](https://www.zekapusulasi.com/bir-i%C5%9Flem) oyunundan uyarlanmıştır.
