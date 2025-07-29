# translateManga Manga Çeviri Aracı - Kullanım Kılavuzu

*Dil Seçimi: [English](README.md) | [繁體中文](README_TC.md) | [العربية](README_AR.md) | [Magyar](README_HU.md) | [ไทย](README_TH.md) | [한국어](README_KO.md) | [Türkçe](README_TR.md) | [Polski](README_PL.md) | [Français](README_FR.md) | [Русский](README_RU.md) | [Español](README_ES.md)*

![Manga Çeviri Görseli](./images/宣传图001.png)

## 📚 İçindekiler

- [🌟 Proje Tanıtımı](#proje-tanıtımı)
- [🔍 Teknik Prensipler](#teknik-prensipler)
- [✨ Özellikler](#özellikler)
- [🚀 Kullanım Kılavuzu](#kullanım-kılavuzu)
- [🌎 Bölgesel Adaptasyon](#bölgesel-adaptasyon)
- [📊 Örnek Vakalar](#örnek-vakalar)
- [❓ Sıkça Sorulan Sorular](#sıkça-sorulan-sorular)

## 🌟 Proje Tanıtımı

**translateManga**, manga içindeki metni akıllıca tanıyabilen ve orijinal manganın sanatsal stilini ve düzenini mükemmel şekilde korurken yüksek kaliteli çok dilli çeviriler sağlayan gelişmiş bir yapay zeka destekli manga içerik çeviri aracıdır. Japon mangası, Kore manhwası veya Batı çizgi romanları olsun, dillerarası bir okuma deneyimini kolayca yaşayabilirsiniz.

Resmi Web Sitesi: [https://translatemanga.online](https://translatemanga.online)

### Temel Avantajlar

- **Akıllı Tanıma**: Gelişmiş OCR teknolojisi çeşitli yazı tipleri ve düzenlemelerde manga metnini doğru şekilde tanımlar
- **Hassas Çeviri**: En son büyük dil modellerine (GPT-4, Claude, vb.) dayalı bağlam duyarlı çeviri
- **Düzen Koruması**: Çevrilen metin orijinal konuşma balonlarına ve düzene mükemmel şekilde entegre olur
- **Çok Dilli Destek**: 100'den fazla dil arasında çeviri desteği
- **Toplu İşleme**: Tüm manga ciltlerinin toplu çevirisini destekler

![Temel Avantajlar](./images/宣传图002.png)

## 🔍 Teknik Prensipler

### Yapay Zeka Destekli Çeviri Motoru

Bu araç, sadece kelimelerin anlamlarını değil, aynı zamanda bağlamsal nüansları da yakalayan, doğal ve akıcı çeviri sonuçları sağlayan en gelişmiş sinir ağı çeviri sistemlerini kullanır. Sistem önce tüm mangayı "okur", genel tarzı ve karakter özelliklerini kavrar, ardından uyumlu ve tutarlı çeviriler üretir.

![Çeviri Motoru Mimarisi](./images/宣传图003.png)

### OCR Metin Tanıma Teknolojisi

Mangadaki benzersiz düzen zorluklarını ele almak için, şunları tam olarak tanımlayabilen özel bir Çizgi Roman Metin Dedektörü geliştirdik:

- Dikey ve yatay metin
- El yazısı stili yazı tipleri
- Özel efekt yazı tipleri ve ses taklidi ifadeler
- Küçük arka plan metinleri ve açıklamalar
- Süslü konuşma balonları

Tanıma doğruluğu, karmaşık arka planlarda bile metni doğru bir şekilde çıkararak sektörde lider olan %99 seviyesine ulaşır.

### Düzen Koruma Mekanizması

Çeviriden sonra, sistem çevrilen metnin orijinal balonlara ve düzene mükemmel şekilde entegre olmasını sağlamak için yazı tipi boyutunu, satır aralığını ve düzeni akıllıca ayarlar. Temel teknolojiler şunları içerir:

1. **Akıllı Dizgi Algoritması**: Hedef dil metin uzunluğuna bağlı olarak yazı tipi boyutunu ve satır aralığını otomatik olarak ayarlar
2. **Arka Plan Restorasyon Teknolojisi**: Orijinal metin kaldırıldıktan sonra arka planı akıllıca geri yükler
3. **Stil Eşleştirme**: Orijinal manga ile tutarlı yazı tipi stili ve ifade gücünü korur

![Düzen Koruma Efekti](./images/漫画翻译对比1.webp)

## ✨ Özellikler

### Toplu Çeviri

Tüm manga ciltlerinin veya birden fazla sayfanın toplu işlenmesini destekler, 300 MB'a kadar PDF'ler veya görüntü koleksiyonları yüklemeye olanak tanır. Sistem her sayfayı otomatik olarak işler ve eksiksiz bir çeviri sürümü oluşturur.

![Toplu Çeviri Demosu](./images/宣传图004.png)

### Gerçek Zamanlı Çeviri

Tarayıcı uzantıları aracılığıyla web mangalarının gerçek zamanlı çevirisini gerçekleştirin. Desteklenen manga web sitelerinde gezinirken, uzantı orijinal görüntüleri indirmeye gerek kalmadan sayfadaki manga içeriğini otomatik olarak algılar ve çevirir.

Desteklenen web siteleri arasında şunlar bulunur:
- MangaDex
- MangaFire
- ManhuaRen
- WebToonScan
- Ve 100'den fazla diğer manga web siteleri

![Gerçek Zamanlı Çeviri Demosu](./images/Auto-translator.mp4)

### Çok Dilli Destek

Aşağıdaki diller arasında kapsamlı çeviri desteği:

- İngilizce, Fransızca, Almanca, İspanyolca vb. Avrupa dilleri
- Çince (Basitleştirilmiş/Geleneksel), Japonca, Korece vb. Asya dilleri
- Arapça ve İbranice gibi RTL yazı sistemleri
- Rusça ve Lehçe gibi Slav dilleri

Sistem, farklı dillerin özelliklerine göre metin düzenini ve yönünü otomatik olarak ayarlar.

### Ekran Görüntüsü Çeviri Özelliği

Otomatik çeviri desteklemeyen fiziksel manga kitapları veya web siteleri için, güçlü bir ekran görüntüsü çeviri özelliği sunuyoruz:

1. Uzantıdaki ekran görüntüsü düğmesine tıklayın
2. Çevirmek istediğiniz manga alanını seçin
3. Sistem metni otomatik olarak tanır ve çevirir
4. Çeviri sonuçları doğrudan orijinal görüntü üzerinde gösterilir

![Ekran Görüntüsü Çeviri Özelliği](./images/截图翻译.png)

### Terminoloji Özelleştirme

Belirli manga eserleri için, karakter adları, özel yetenek adları ve diğer özel isimlerin çevirisinde tutarlılık sağlamak amacıyla özel terminoloji sözlükleri oluşturabilirsiniz. Bu özellikle uzun seriler veya manga franchise'ları için önemlidir.

## 🚀 Kullanım Kılavuzu

### Hızlı Başlangıç - Manga Çevirisi İçin Üç Adım

#### Adım 1: Manga Yükleme
1. Manga çeviri platformunu ziyaret edin [https://translatemanga.online](https://translatemanga.online)
2. "Yükle" düğmesine tıklayın
3. Manga dosyalarını seçin (desteklenen formatlar JPG, PNG, PDF vb. içerir)

#### Adım 2: Dil ve Ayarları Seçin
1. Manganın kaynak dilini seçin
2. Hedef çeviri dilini seçin
3. Çeviri ayarlarını yapın (isteğe bağlı):
   - Yazı tipi stili
   - Metin tanıma modu
   - Terminoloji sözlüğü ayarları

#### Adım 3: Çeviri Sonuçlarını Alın
1. "Çeviriye Başla" düğmesine tıklayın
2. Çeviri işleminin tamamlanmasını bekleyin (yaklaşık 1-2 dakika)
3. Çevrilen mangayı önizleyin ve indirin

![Çeviri Sonuçları](./images/manga-translator%20演示.mp4)

### Gelişmiş Kullanım İpuçları

#### Tarayıcı Uzantısının Kullanımı

1. Tarayıcı uzantısını indirmek ve kurmak için resmi web sitesini ziyaret edin: [https://translatemanga.online](https://translatemanga.online)
2. Desteklenen tarayıcılar Chrome, Firefox ve Edge'i içerir:
   ![Desteklenen Tarayıcılar](./images/chrome.svg) ![Firefox](./images/firefox.svg) ![Edge](./images/edge.svg)
3. Uzantı ayarlarında varsayılan çeviri dilini seçin
4. Desteklenen manga web sitelerini görüntülerken, çeviriyi etkinleştirmek için uzantı simgesine tıklayın
5. Herhangi bir manga panelini çevirmek için ekran görüntüsü çeviri özelliğini kullanın

![Tarayıcı Uzantısı](./images/截图翻译演示.mp4)

#### Büyük Manga Hacimlerini İşleme

1. Tüm mangayı PDF olarak kaydedin veya ZIP/CBZ dosyası olarak paketleyin
2. Toplu işleme sayfasına yükleyin
3. Global çeviri parametrelerini ayarlayın
4. Toplu çeviriye başlayın; işlem süresi sayfa sayısına bağlıdır
5. Tam çevrilmiş sürümü indirin veya çevrimiçi olarak okuyun

#### Okuma İlerleme Takibi

Daha eksiksiz bir manga okuma deneyimi sağlamak için, translateManga uzantısı ayrıca platformlar arası okuma ilerleme takibi de sunar:

1. Okuma ilerleme senkronizasyon özelliğini etkinleştirin
2. Sistem farklı web sitelerinde okuduğunuz manga bölümlerini kaydeder
3. Herhangi bir cihazdan giriş yaptığınızda kaldığınız yerden devam edin
4. Özel kategorizasyon ve favoriler desteği

![Okuma İlerleme Takibi](./images/manga-tracker%20演示.mp4)

#### Çeviri Kalitesini Optimize Etme

1. **Terminoloji Sözlükleri Oluşturun**: Belirli mangalardaki özel isimler için çeviri çiftleri ekleyin
2. **Tanıma Hassasiyetini Ayarlayın**: Özel yazı tiplerine sahip mangalar için metin algılama parametrelerini ince ayarlayın
3. **Manuel Düzenleme**: Sistem çeviri sonrası manuel düzeltme ve iyileştirmeyi destekler

## 🌎 Bölgesel Adaptasyon

### Batı Pazarı İçin Özel Özellikler

Batılı manga okuyucularının okuma alışkanlıkları için translateManga aşağıdaki özel özellikleri sunar:

1. **Soldan Sağa Okuma Modu**: Batı okuma alışkanlıklarına uyum sağlamak için Japon ve Kore mangası okuma yönünü otomatik olarak ayarlar
2. **Batı Yazı Tipi Optimizasyonu**: Çeviri sonrası sanatsal tutarlılığı korumak için çeşitli Batı çizgi roman tarzı yazı tipleri sağlar
3. **Argo ve Kültürel Referans Yerelleştirmesi**: Çevirileri hedef kitleye daha uygun hale getirmek için kültüre özgü ifadeleri akıllıca dönüştürür

![Batı Adaptasyon Özellikleri](./images/宣传图006.png)

### Çoklu Platform Desteği

Farklı bölgelerdeki kullanıcıların alışkanlıklarını karşılamak için, translateManga çeşitli kullanım seçenekleri sunar:

1. **Web Uygulaması**: Kurulum gerektirmeden doğrudan tarayıcı üzerinden kullanın
2. **Tarayıcı Uzantıları**: Chrome, Firefox ve Edge dahil olmak üzere ana akım tarayıcılar için destek
3. **Mobil Uygulamalar**: iOS ve Android platformları için özel uygulamalar, çevrimdışı çeviri desteği sunar
4. **Masaüstü Yazılımı**: Windows ve macOS sistemleri için profesyonel versiyonlar, daha güçlü toplu işleme yetenekleri sağlar

### Yerelleştirme Desteği

Farklı bölgelerin özel ihtiyaçları için translateManga aşağıdaki yerelleştirme desteğini sunar:

1. **Arayüz Dilleri**: 14 ana dilde arayüz yerelleştirmesi
2. **Müşteri Hizmetleri**: Çok dilli müşteri desteği ve yerelleştirilmiş yardım belgeleri
3. **Uyumluluk**: Farklı bölgelerde GDPR ve CCPA gibi veri koruma düzenlemelerine uyum

## 📊 Örnek Vakalar

### Japon Manga Çeviri Örneği

**"SPY×FAMILY" Çeviri Etkisi**

Çeviri özellikleri:
- Orijinal mizahı korur
- Karakter sesini ve tonunu doğru şekilde iletir
- Özel terminolojiyi hassas bir şekilde çevirir
- Ses taklidi ifadeleri yerelleştirir

### Kore Manhwa (Webtoon) Çeviri Örneği

**"Tower of God" Çeviri Etkisi**

Çeviri özellikleri:
- Dikey şerit düzeni mükemmel şekilde korur
- Özel yazı tipi görsel efektlerini korur
- Terminoloji tutarlılığını sürdürür
- Uzun diyalog balonu düzenini optimize eder

### Batı Çizgi Roman Çeviri Örneği

**"Avengers" Çeviri Etkisi**

Çeviri özellikleri:
- Batı diyalog kutusu düzenini korur
- Ses efekti sanatsal ifadesini yeniden yaratır
- İngilizce argoyu uygun şekilde yerelleştirir
- Özel yazı tipi stillerine uyar

## ❓ Sıkça Sorulan Sorular

### Çeviri Doğruluğu İle İlgili

**S: Çeviri kalitesi nasıl sağlanır?**
C: Manga senaryolarında doğruluğu önemli ölçüde artırmak için manga özel alan eğitimiyle birleştirilmiş sektörün en gelişmiş yapay zeka büyük modellerini (GPT-4o, Claude vb.) çeviri için kullanıyoruz. Çeviriden önce, sistem önce bağlamı anlamak için tüm mangayı "okuyarak", uyumlu ve tutarlı çeviri sonuçları sağlar.

**S: Özel kültürel memleri ve kelime oyunlarını işleyebilir mi?**
C: Sistem, çoğu yaygın kültürel referansı ve kelime oyununu tanımlayarak hedef dilde eşdeğer ifadeler bulmaya çalışır. Çok özel kültürel referanslar için, sistem orijinal anlamı korur ve gerektiğinde kısa açıklamalar ekler.

### Teknik Sorular

**S: Hangi dosya formatları desteklenir?**
C: Yaygın görüntü formatları (JPG, PNG, WEBP), manga özel formatları (CBR, CBZ) ve ayrıca PDF ve EPUB e-kitap formatları 300 MB'lık tek dosya boyutu sınırıyla desteklenir.

**S: Çok uzun manga sayfaları nasıl işlenir?**
C: Sistem 10.000 piksele kadar çok uzun şerit manga sayfalarını destekler, genel düzen tutarlılığını korurken bunları otomatik olarak segmentler halinde işler.

**S: Çevrilen dosyaları nasıl kaydedebilirim?**
C: Çeviri sonuçları orijinal formatta kaydedilebilir (örn. PDF PDF olarak kalır) veya kolay paylaşım ve farklı cihazlarda okuma için görüntü koleksiyonları veya çevrimiçi okuma bağlantıları olarak dışa aktarılabilir.

## İlgili Bağlantılar ve İletişim Bilgileri

- [Resmi Web Sitesi](https://translatemanga.online)
- **E-posta**: support@translatemanga.online
- **Discord**: [Discord Topluluğumuza Katılın](https://discord.gg/translatemanga)

Herhangi bir sorunuz veya öneriniz varsa, lütfen bizimle istediğiniz zaman iletişime geçmekten çekinmeyin!

---

*Bu belge en son Haziran 2024'te güncellenmiştir* 