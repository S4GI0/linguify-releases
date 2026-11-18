# Linguify Subtitle Engine

### Oyunları kendi dilinde deneyimle.

**Linguify Subtitle Engine**, oyunlardaki İngilizce altyazıları gerçek zamanlı olarak algılayıp Türkçeye çeviren bir uygulamadır.

Optik Karakter Tanıma (OCR) teknolojisini kullanan Linguify, oyun ekranındaki İngilizce altyazıları tespit eder, Türkçeye çevirir ve oyun deneyimini mümkün olduğunca kesintiye uğratmadan görüntüler.

**Oyun dosyalarını değiştirmen, Türkçe yama yüklemen veya oyuna müdahale etmen gerekmez.**

İster bilgisayarda ister konsolda oyna, Linguify oyunların hikâyelerini kendi dilinde takip edebilmen için tasarlandı.

---

## Linguify Nasıl Çalışır?

Linguify dört temel aşamada çalışır:

**1. Görüntüyü yakalar**

Bilgisayar ekranından veya desteklenen görüntü kaynaklarından gelen oyun görüntüsünü takip eder.

**2. Altyazıları algılar**

OCR ve altyazı tanıma sistemi sayesinde ekrandaki İngilizce altyazıları tespit etmeye çalışır.

**3. Türkçeye çevirir**

Algılanan metni mevcut çevrimdışı çeviri paketleri veya bağladığın çeviri servisi aracılığıyla Türkçeye çevirir.

**4. Altyazıyı görüntüler**

Çevrilen altyazıları seçtiğin görüntüleme modunda, özelleştirebildiğin görünüm ve zamanlama ayarlarıyla ekrana yansıtır.

Tüm bunlar oyun dosyalarına müdahale edilmeden gerçekleştirilir.

---

## Nasıl Oynarsan Oyna

### Bilgisayarda Oyun

Bilgisayarında oyun oynuyorsan Linguify, Türkçe altyazıları doğrudan oyunun üzerine bindirebilir.

Böylece başka bir pencereye geçmeden diyalogları takip edebilirsin.

### Google TV / Android TV

Linguify'ın Android TV uygulaması, desteklenen TV ve HDMI kurulumlarında konsol oyunları oynarken Türkçe altyazıları görüntülemek için tasarlanmıştır.

Bu sayede bilgisayardaki klasik altyazı bindirme yöntemlerinin kullanılamadığı konsol oyunlarında da Linguify'dan yararlanabilirsin.

*TV uyumluluğu ve kullanılabilen özellikler cihazın donanımına, HDMI yapılandırmasına ve sistem desteğine bağlıdır.*

### Google TV'n Yok mu?

Sorun değil!

**Tam Ekran Altyazı Modu** sayesinde Türkçe altyazıları bilgisayarında ayrı bir tam ekran görünümünde görüntüleyebilirsin.

Bu özellik, desteklenmeyen bir televizyonda veya farklı bir ekranda oyun oynarken altyazıları bilgisayarından takip edebilmeni sağlar.

*Tam Ekran Altyazı Modu, desteklenmeyen televizyonların görüntüsü üzerine doğrudan altyazı bindirmez.*

---

## Çeviri Seçenekleri

Linguify, farklı ihtiyaçlara yönelik birden fazla çeviri yöntemi sunar.

### Çevrimdışı Çeviri Paketleri

Linguify, yüklü çeviri paketlerinde bulunan İngilizce–Türkçe altyazı eşleşmelerinden yararlanabilir.

Uygun bir eşleşme bulunduğunda yeniden çevrimiçi çeviri yapılmasına gerek kalmaz.

Bu yöntem:

- Çeviri gecikmesini azaltabilir.
- API kullanımını ve maliyetini düşürebilir.
- Desteklenen diyaloglarda internet bağlantısına bağımlılığı azaltabilir.

### DeepL API — Önerilen

**Gerçek zamanlı altyazı çevirisi için DeepL kullanılması önemle tavsiye edilir.**

DeepL, düşük gecikme ve çeviri kalitesi arasındaki dengesi sayesinde Linguify'ın kullanım senaryosu için önerilen çeviri servisidir.

Kendi DeepL API anahtarını ilk kurulum sırasında veya daha sonra uygulama ayarlarından bağlayabilirsin.

### LLM Sağlayıcıları

Linguify, alternatif olarak desteklenen büyük dil modeli (LLM) sağlayıcıları üzerinden de çeviri yapabilir.

Kullanmak istediğin sağlayıcıyı ve modeli seçerek kendi API anahtarınla bağlantı kurabilirsin.

Çeviri hızı, kalitesi ve API maliyetleri seçilen sağlayıcıya ve modele göre değişebilir.

**API anahtarı bağlamak zorunlu değildir ancak önerilir.** Çevrimdışı paketlerin kapsamadığı altyazıların çevrilebilmesi için bir çevrimiçi çeviri servisine ihtiyaç duyulabilir.

---

## Altyazılar Senin Kontrolünde

Linguify, farklı oyunlara ve kişisel tercihlere uyum sağlayabilmek için çeşitli altyazı özelleştirme seçenekleri sunar:

- Altyazı görünümü ve konumlandırma
- Farklı altyazı zamanlama modları
- Tam ekran altyazı görüntüleme
- Önceki altyazıları görüntüleme seçenekleri
- Desteklenen TV kurulumlarında canlı görüntü üzerinden altyazı düzenleme

Amaç, Türkçe altyazıların oyun deneyiminin doğal bir parçası gibi hissettirmesidir.

---

## Resmî Sürümler ve Güncellemeler

**Bu GitHub deposu, Linguify Subtitle Engine'in resmî sürüm dağıtım ve güncelleme kontrol deposudur.**

Uygulamanın yayımlanan sürümleri, kurulum dosyaları ve sürüm notları burada paylaşılır.

### Desteklenen Platformlar

| Platform | Dağıtım biçimi |
|---|---|
| Windows | `.exe` |
| macOS | `.zip` (macOS uygulaması) |
| Android TV / Google TV | `.apk` |

### Ortak Sürüm Numarası

Linguify'ın bütün platformları ortak bir sürüm numarası kullanır.

Örneğin `v0.2.0` sürümü Windows, macOS ve Android TV için aynı Linguify sürümünü temsil eder.

Her platform kendisine uygun kurulum paketini kullanır.

### Güncellemeler Nasıl Çalışır?

Linguify, yeni bir sürümün yayımlanıp yayımlanmadığını öğrenmek için bu deponun GitHub Releases bilgilerini kontrol eder.

**Windows ve macOS**

Masaüstü uygulaması, kullanıcı tarafından başlatılan veya isteğe bağlı olarak etkinleştirilen güncelleme kontrolleriyle yeni sürümleri tespit edebilir.

Yeni bir sürüm bulunduğunda kullanıcıyı bilgilendirir ve resmî indirme sayfasına yönlendirir.

Masaüstü sürümünde otomatik indirme veya kurulum yapılmaz.

**Android TV / Google TV**

TV uygulaması, manuel güncelleme kontrolünü ve isteğe bağlı otomatik güncelleme kontrolü ile indirmeyi destekleyecek şekilde tasarlanmıştır.

Otomatik güncellemeler varsayılan olarak kapalıdır.

**Otomatik güncellemeler açık olsa bile kurulum öncesinde kullanıcı onayı gerekir.** Kurulum, Android'in standart paket yükleme mekanizması üzerinden gerçekleştirilir.

Güncelleme davranışları kullanılan uygulama sürümüne göre farklılık gösterebilir.

### Linguify'ı İndir

En güncel yayımlanmış sürüme ulaşmak için:

**[Linguify Subtitle Engine — Releases](../../releases)**

Kullandığın platforma uygun dosyayı indirerek kurulumu gerçekleştirebilirsin.

Güvenliğin için yalnızca bu resmî depoda yayımlanan kurulum dosyalarını kullanmanı öneriyoruz.

### Bu Depoda Neler Bulunur?

Bu depo, Linguify'ın **uygulama dosyalarını ve güncelleme bilgilerini dağıtmak** amacıyla oluşturulmuştur.

Ana kaynak kod deposu değildir.

Uygulamanın kaynak kodları, geliştirme geçmişi ve dahili proje dosyaları burada yayımlanmaz.

Yeni sürümler proje geliştiricisi tarafından hazırlanıp manuel olarak yayımlanabilir. GitHub Actions kullanımı zorunlu değildir.

---

## Altyazı Tanıma Hakkında

Linguify, oyunların dahili altyazı verilerine erişmek yerine ekranda görüntülenen yazıları OCR aracılığıyla tanır.

Bu nedenle altyazı algılama ve çeviri her zaman kusursuz olmayabilir.

Oyun içindeki tabelalar, plakalar, arayüz metinleri veya diğer yazılar zaman zaman altyazı olarak algılanabilir.

Algılama başarısı; oyunun altyazı tasarımına, görüntü kalitesine, seçilen algılama bölgesine ve kullanılan çeviri yöntemine bağlı olarak değişebilir.

Linguify'ın önceliği, gerçek diyalogları mümkün olduğunca düşük gecikmeyle Türkçeye aktarabilmektir.

---

## Geliştirme Durumu

**Linguify Subtitle Engine aktif geliştirme aşamasındadır.**

Yeni özellikler, performans iyileştirmeleri ve uyumluluk güncellemeleri üzerinde çalışmalar devam etmektedir.

Özellikler ve desteklenen cihazlar sürümler arasında değişebilir.

Hata bildirimleri ve geri bildirimler, etkinleştirilmişse bu deponun **Issues** bölümünden paylaşılabilir.

---

### Linguify Subtitle Engine

**Her hikâye anlaşılmayı hak eder.**
