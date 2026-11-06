# Değişiklik Günlüğü (Changelog)

Bu projedeki tüm önemli değişiklikler bu dosyada belgelenecektir.
Biçim [Keep a Changelog](https://keepachangelog.com/tr/1.1.0/) standardına dayanır ve bu proje [Semantik Sürümleme (SemVer)](https://semver.org/lang/tr/) kurallarına uyar.

---

## [0.1.1](https://github.com/xdaxer/koy/compare/v0.1.0...v0.1.1) (2026-11-06)


### Eklenenler

* çentiğe sekmeler ve Wi-Fi / Bluetooth durum simgeleri ekle ([eb50182](https://github.com/xdaxer/koy/commit/eb50182cbee95ba5985a6c19de73435116e6958b))
* dock'a sistem tepsisi ekle ([e763ee5](https://github.com/xdaxer/koy/commit/e763ee594f9454fce7fab7f7f0d19da6de1ec732))
* tepsi penceresi yalnız görev çubuğu gizliyken kurulur, bütün dock'lar sayaçlı tek örneği paylaşır ve kapanışta Windows tepsisi geri gelir ([a55ee88](https://github.com/xdaxer/koy/commit/a55ee88abc0da4dde1ac4749346441c392ea0d2a))


### Düzeltmeler

* açık paneller değişince (ör. Raf'a sürükle-bırak) çentik sekmelerini yeniden kur ([59f86f2](https://github.com/xdaxer/koy/commit/59f86f2cd1633ca3a56fd0700e2fd9297a23d58e))
* açılışta kapalı çentiğin zeminini çiz ([2f21718](https://github.com/xdaxer/koy/commit/2f2171886d81aa605d45daa8ae39b3104037c010))
* Ayarları sıfırlayınca kurulum sihirbazı tekrar açılmasın, çalışan özellikler yeni varsayılanla yeniden kurulsun ([3217785](https://github.com/xdaxer/koy/commit/3217785dd075d1d3e59f546dbd7a10d306f36e37))
* betiklerde native komutlarin cikis kodunu denetle ([90a43a9](https://github.com/xdaxer/koy/commit/90a43a90c41b8f5d30bf1ae42a9bd8203b3d0a84))
* boşta görünüm Yalnız saat ve Hiçbiri iken Wi-Fi / Bluetooth simgelerini gizle ([b4db5b6](https://github.com/xdaxer/koy/commit/b4db5b6dab17bb42ac9f247f54fd022784be59a8))
* boşta pil göstergesini HasBattery'ye bağla, HasBattery değişince ShowIdleBattery bildir ([5b0bafd](https://github.com/xdaxer/koy/commit/5b0bafd771259ad8db9317eb82d92c58d601614b))
* çentik ayarı açık her monitörde ayrı pencere olarak kurulsun ve ekranın kendi DPI'ına göre yerleşsin ([c283f78](https://github.com/xdaxer/koy/commit/c283f783e401fad3615072cb4a09f413d01df2ca))
* Çentik ayarlarını davranışa bağla: tam ekranda gizle, boşta gösterim, müzik dalgası, açılma davranışı, tekerlek eylemi ([061ba4a](https://github.com/xdaxer/koy/commit/061ba4a9d107bb9942bc3e9e9f7e658af9225770))
* Çentik ve dock sağ tık menülerinden Çıkış'ı kaldır; çıkış yalnız Koy penceresi ve sağ alt menüden ([b6ccc52](https://github.com/xdaxer/koy/commit/b6ccc5227edd6e2efc12b06e88b01d9812252fc8))
* çökme işleyicilerinde Koy'un tepsi penceresini de kapat ([b0d2f1d](https://github.com/xdaxer/koy/commit/b0d2f1dbdae65b968cc918c620f50ffaf0e5c3c9))
* dock ayarı açık her monitörde kurulsun, AppBar payı ve görev çubuğu gizleme her ekranda doğru çalışsın ([0af2701](https://github.com/xdaxer/koy/commit/0af2701d6de97e2b07cc14c173a361e4fb8edc5d))
* Dock orta tık eylemini ve çalışan göstergesi stilini (nokta/çizgi) ayara bağla ([44a85fb](https://github.com/xdaxer/koy/commit/44a85fbe08588a3d2aa441204e153d86a03e90df))
* dock pencere önizlemesini üst düzey pencereye kaydet ([894be8b](https://github.com/xdaxer/koy/commit/894be8bd2903ca3180f9007421c8f21eef2ea9c9))
* dock Stop'ta görev çubuğu geri yüklemesi try/finally ile garanti, ölü tepsi tutamacı yeniden kurulur, elle geri getirmede tepsi bırakılır ([6a42bfa](https://github.com/xdaxer/koy/commit/6a42bfae01b51e11b181824552053e1790aaa7fe))
* Dock varsayılanını Aşağı yapış yap, DockDown'u Çekil'e çeviren zorla göçü kaldır ([0fd1121](https://github.com/xdaxer/koy/commit/0fd1121988db8aaf79090489ac29b024b42a34c8))
* DWM önizleme güncellemesi başarısız olursa kutuyu hatırlama, sonraki düzen geçişinde yeniden dene ([455884c](https://github.com/xdaxer/koy/commit/455884c8cf6d3893455f5bed05286b8c95e23d16))
* Explorer yeniden başlayınca tepsi simgesini ekle ve görev çubuğu gizlemesini yeniden uygula ([dad923b](https://github.com/xdaxer/koy/commit/dad923b7bba813cda7970c76b4014ec917ce71da))
* Explorer yeniden başlayınca Yer ayır modunda AppBar kaydını yeniden yap ([13e879d](https://github.com/xdaxer/koy/commit/13e879de65500d3bdb097004b278978598549b01))
* global hata yakalamayı sağlamlaştır (CrashLog, UnobservedTaskException, WndProc ve WinEvent korumaları) ([4291852](https://github.com/xdaxer/koy/commit/4291852e00d356d2b684c0af94c9c586beb23a05))
* güncelleme ve kaldırma kancalarında görev çubuğunu hata toleranslı biçimde geri getir ([275bce5](https://github.com/xdaxer/koy/commit/275bce59a86214ca07755b5df139ecef784856ab))
* Güncellemeleri otomatik denetle ayarını bağla (açılıştan sonra arka planda indir, kapanırken uygula) ([0211323](https://github.com/xdaxer/koy/commit/021132365a5b51e47a1af50770fda00e569a4719))
* Hakkında sayfasına Koy'u kaldır düğmesi ve onay görünümü ekle ([30e1b19](https://github.com/xdaxer/koy/commit/30e1b197632665d3c1d22d14c70c3a7969bafe99))
* Hava durumu yenileme sıklığını ve Pomodoro sürelerini ayara bağla ([f2b1cfd](https://github.com/xdaxer/koy/commit/f2b1cfdfd50f67dd3659496b3096546a9ffba678))
* kenar gözetleme zamanlayıcılarını ve Core olaylarını UI thread'ine taşı (VerifyAccess çökmesi) ([f3cc88f](https://github.com/xdaxer/koy/commit/f3cc88f3159cc95d4e30ca2f839aea72a48caa57))
* Kontrol Merkezi'nde Wi-Fi ve Bluetooth'u gerçekten yönet ([0c2f878](https://github.com/xdaxer/koy/commit/0c2f8785de9f487168ce01096e7530c5ad4191c3))
* köşe varsayılanı değişikliğine göre ayar testlerini güncelle ([b25018a](https://github.com/xdaxer/koy/commit/b25018a827b2c9d333ef6d62073482f9ab1d4e3b))
* kurulum sihirbazı tamamlanmadan kapatılırsa dock açılıp görev çubuğu gizlenmesin ([24acf78](https://github.com/xdaxer/koy/commit/24acf78e49fe93c1acdd4eb7022c82a8a84b38ae))
* panel geçiş animasyonu animasyon hızına, azaltılmış harekete ve pil tasarrufuna uysun ([51ec7d8](https://github.com/xdaxer/koy/commit/51ec7d85df8d44019a2807d1958d6e745b4c4827))
* parça yokken fareyle çentiğe girince Wi-Fi / Bluetooth simgeleri kaybolmasın (tıklama ve ipucu erişilebilir olsun) ([19c4f62](https://github.com/xdaxer/koy/commit/19c4f6213c0d35de7656f395e0ae483f2f9e7dca))
* pil olmayan bilgisayarda çentikteki pil göstergesini gizle ([f03dc07](https://github.com/xdaxer/koy/commit/f03dc07f993ce9607809aa060ddc8451a31a3d32))
* Pil tasarrufunda animasyonları azalt ayarını çentik ve dock'a bağla; Dock seçenekleri değişince dock yeniden kurulsun ([6240ef4](https://github.com/xdaxer/koy/commit/6240ef4d18340d75d959a175cc219dab2f62da17))
* PinnedAppsService kısayol çözerken COM nesnesini serbest bırak ([584bb77](https://github.com/xdaxer/koy/commit/584bb775b534fef5e272ba45705a7361d48c3479))
* radyo taramasında bayat erişim durumunu sıfırla, görev ve abone hatalarını günlüğe yaz, birleşimde kaybolan parlaklık başlatmasını geri getir ([b2d58a3](https://github.com/xdaxer/koy/commit/b2d58a3443798bcb37c5e10389b0559a884e243d))
* Sağ alt menüdeki 1 saat duraklat gerçekten çalışsın (çentik ve dock durur, görev çubuğu döner, süre bitince devam) ([0680b1c](https://github.com/xdaxer/koy/commit/0680b1c2cefa2eb2ae55cec6f3a0a99ab73fa7f5))
* sağ alt menüdeki ekran sayısı metnini yerelleştir ([0feda6b](https://github.com/xdaxer/koy/commit/0feda6ba5f1dc405e5b6ea8b7e0504ee60333fec))
* sağ alt menüyü HWND oluşmadan ölçerken olan FailFast çökmesini gider ([18dd966](https://github.com/xdaxer/koy/commit/18dd96680a027b7d6db474d4fd1f48cfb83bef19))
* Ses ve parlaklık göstergesini (OSD) çentiğe bağla ve ayarlara uydur ([c3055fd](https://github.com/xdaxer/koy/commit/c3055fda0c4993f3a6c9e2cab70441076c0f904e))
* sihirbaz metinlerini resx'e taşı, çıkışa onay ekle, görünürlük açıklaması ve düğme/boşluk cilası ([2986590](https://github.com/xdaxer/koy/commit/29865906b3204c04ce8ae6c449a6fcacf5ad0171))
* tam ekran algısı odak başka ekrandayken de her monitörün kendi en üst penceresine baksın ([b6272d6](https://github.com/xdaxer/koy/commit/b6272d6d48052724881043fa19a0c001d48df9d6))
* TaskbarService.Hide idempotent olsun, önceki görev çubuğu durumu AUTOHIDE ile ezilmesin ([8c5996f](https://github.com/xdaxer/koy/commit/8c5996f47717462954a06e950affed2e56c96a55))
* tepsi ayarının metnini görev çubuğu gizliyken geçerli olduğunu söyleyecek şekilde güncelle ([a879bfd](https://github.com/xdaxer/koy/commit/a879bfda60586fcdce8a8f89a4db9ca72f934068))
* tepsi düğmesinin kullandığı SystemTray metin anahtarını İngilizce ve Türkçe kaynaklara ekle ([e9147a9](https://github.com/xdaxer/koy/commit/e9147a9ecc4c1829a7f932597483e6370ff089e1))
* tepsi kapanışta arayüz iş parçacığını 3 sn bekletmesin, uygulama adı çözümü (disk G/Ç) arka plana alındı ([b44ceaf](https://github.com/xdaxer/koy/commit/b44ceaf56b5f59d560778fdbab1c5cecd28aaab4))
* tepsi kayıtlarını kaçırma ve çift pencereyi gider ([640ffb9](https://github.com/xdaxer/koy/commit/640ffb914bd4e6b7bc40206abbac613b5fcb4dd4))
* tepsi penceresinin gölge rengini Freezable içinde StaticResource ile bağla ([ccb3a96](https://github.com/xdaxer/koy/commit/ccb3a96006778e02be4d2f5d537dbff5993d9bbc))
* tepsi servisinde GDI işini kilit dışına al, pencere tanıtıcısını iş parçacığı güvenli yap, hataları CrashLog'a yaz ([8a706ac](https://github.com/xdaxer/koy/commit/8a706ac0e58651759a9f40dc5d5f067f339edf91))
* tepsi WM_COPYDATA boyut denetimleri, simge sayısına üst sınır ve Koy-süreç filtresi Core'a taşındı ([739c9b0](https://github.com/xdaxer/koy/commit/739c9b01e6152e9d4897e257411171e04da93e93))
* UWP penceresinde Sonlandır ApplicationFrameHost'u değil gerçek uygulama sürecini hedeflesin ([e626516](https://github.com/xdaxer/koy/commit/e6265161e5633565a1727bd2c6873ce76a01fc23))
* Windows görev çubuğunu gizle anahtarı kapalıyken dock görev çubuğuna dokunmasın ([fc7eeb3](https://github.com/xdaxer/koy/commit/fc7eeb3e8e52bc3608c26bab4f30b963740168b2))
* Windows'tan kaldırmada başlatma kaydını ve durum dosyalarını temizle, ayarları koru ([f728f1c](https://github.com/xdaxer/koy/commit/f728f1ce4f0544834576a6ba8587cbfc82b1eecf))


### Performans

* pencere olaylarında DockController yenilemesini ertele ve birleştir ([08af2fd](https://github.com/xdaxer/koy/commit/08af2fdb802776f962384175a58ff0bcbab923bf))

## [Unreleased]

<!-- release-please sürüm girdisini kendisi üretir. Bu bölüm elle yazılmış ayrıntılı özettir: sürüm PR'ında bu bölümün içeriği yeni sürüm başlığının altına taşınır ve [Unreleased] başlığı silinir (bkz. CONTRIBUTING.md, "Sürüm Nasıl Çıkar"). -->

0.1.0'dan sonraki revizyon: kod incelemesinden çıkan çökmelerin giderilmesi, etkisiz ayarların gerçekten bağlanması, çoklu ekran, kısayollar, Koyu/Açık tema ve kaldırma ekranı.

### Düzeltmeler (Fixed)
- **0.1.0'da çalışmayan, artık çalışanlar:**
  - Kısayollar sayfası yalnızca görüntüydü; artık `RegisterHotKey` ile gerçekten kayıtlı ve değiştirilebilir.
  - Ses ve parlaklık göstergesi (OSD HUD) çentiğe hiç bağlı değildi; artık sistem ses ve parlaklık değişimlerinde açılıyor.
  - Çoklu ekran kullanıcı tarafından açılamıyordu (yalnız birincil ekran); artık Ekranlar sayfasından ekran başına seçiliyor.
  - "1 saat duraklat" yalnızca bir bayrağı değiştiriyordu; artık çentik ve dock'u durduruyor, görev çubuğunu geri getiriyor ve süre bitince devam ediyor.
  - Dock'un varsayılanı "Aşağı yapış" olarak belgelenmişti ama her açılışta "Çekil"e çevriliyordu; artık Aşağı yapış varsayılan ve seçilebilir.
  - "Güncellemeleri otomatik denetle", Pomodoro süreleri, hava durumu yenileme sıklığı, dock orta tık eylemi ve çalışan göstergesi (nokta/çizgi), pil tasarrufunda animasyon azaltma, çentikte tam ekranda gizleme, boşta gösterim, açılma davranışı ve tekerlek eylemi ayarları davranışa bağlandı.
  - "Windows görev çubuğunu gizle" anahtarı kapalıyken dock görev çubuğuna dokunmuyor.
- **Çökmeler:** sağ alt menü ilk tıklamada kapanıyordu (`FailFast`); dock ve çentik kenar zamanlayıcılarındaki başka iş parçacığı erişimi çökmesi giderildi; `crash.log` artık gerçekten yazılıyor ve gözlenmeyen görev hataları süreci düşürmüyor.
- **Görev çubuğu güvenliği:** dock görev çubuğunu iki kez gizleyince "otomatik gizle" kalıntısı kalıyordu; Explorer yeniden başlayınca tepsi simgesi kayboluyor ve görev çubuğu yeniden görünüyordu; "Yer ayır" modunda AppBar kaydı yenilenmiyordu; ilk açılış sihirbazı X ile kapatılınca dock açılıp görev çubuğu gizleniyordu; güncelleme ve kaldırma kancalarında görev çubuğu hata toleranslı biçimde geri getiriliyor.
- UWP pencerelerinde "Sonlandır" `ApplicationFrameHost`'u değil gerçek uygulamayı sonlandırıyor.
- Tam ekran algısı odak başka ekrandayken de her monitörün kendi en üst penceresine bakıyor.
- Ayarlar sıfırlanınca kurulum sihirbazı tekrar açılmıyor; çalışan özellikler yeni varsayılanla yeniden kuruluyor.
- Sabitli uygulama kısayolları çözülürken sızan COM nesnesi serbest bırakılıyor.
- Topluluk katkıları (teşekkürler **xdaxer**):
  - Kontrol Merkezi'ndeki Wi-Fi ve Bluetooth anahtarları artık radyoyu gerçekten açıp kapatıyor; radyo yoksa, kapalıysa ya da Windows izin vermiyorsa döşeme bunu gösteriyor ve Windows ayarlarına yönlendiriyor (#12).
  - Pili olmayan bilgisayarlarda çentikteki pil göstergesi gizleniyor (#8).
  - Dock pencere önizlemesi üst düzey pencereye kaydediliyor; önizleme güncellemesi başarısız olursa sonraki düzende yeniden deneniyor (#10).
  - Açılışta kapalı çentiğin zemini çiziliyor (#13).
  - Açık çentiğin üstünde Müzik, Kontrol, Durum, Takvim ve Raf sekmeleri; kapalı çentikte saatin yanında Wi-Fi ve Bluetooth durum simgeleri (tıklayınca Kontrol sekmesi açılır). Simgeler yalnız Kontrol paneli açıkken ve boşta görünüm "Saat, pil ve bağlantılar" iken çıkar (#14).

### Eklenenler (Added)
- **Genel kısayollar:** çentik, raf, dock, Koy menüsü ve oynat/duraklat için `Ctrl+Alt+N/R/D/K/Space`; tuş yakalama kutusuyla değiştirilir, Windows'un ayırdığı ya da başka uygulamanın tuttuğu kombinasyonlar satırda bildirilir.
- **Ekranlar sayfası:** monitör haritası, ekran başına çentik ve dock, yeni bağlanan ekran için seçenek, "Tanımla" düğmesiyle ekran numarası. Ayarlar kararlı monitör kimliğine bağlıdır; ekran çıkarılıp takılınca geri gelir.
- **Koyu / Açık tema** (ve "Sistem"), yarı saydam malzeme seçeneği, köşe yuvarlaklığı, animasyon hızı; Windows "animasyonları azalt" ve pil tasarrufuna uyum. Emojiler yerine tutarlı çizgi ikonlar, erişilebilirlik adları ve klavye odağı.
- **Koy'u kaldır:** Hakkında sayfasında, onay kartıyla ("Ayarlarımı sakla" varsayılan işaretli). Windows'un "Yüklü uygulamalar" sayfasından kaldırınca da görev çubuğu geri gelir, Windows ile başlatma kaydı silinir ve ayarlarınız korunur. Kurulu olmayan sürümde düğme kapalıdır.
- Hakkında sayfasında gerçek sürüm ve son güncelleme denetimi durumu.
- **Dock sistem tepsisi** (topluluk katkısı, teşekkürler **xdaxer**, #11): Windows görev çubuğu gizliyken Discord, OneDrive gibi arka plan uygulamalarının simgelerine dock'taki düğmeden açılan pencereyle ulaşılır; sol ve sağ tık uygulamaya iletilir. Koy yalnız görev çubuğu gerçekten gizliyken tepsiyi devralır ve her kaydı Windows'a da iletir; Koy kapanınca, duraklayınca ya da çökünce tepsinin eksiksiz geri gelmesi hedeflenir. Dock sayfasından "Sistem tepsisini dock'ta göster" ile kapatılabilir (varsayılan açık). Elle denenmedi.
- Geliştirici aracı: `tools/Koy.UiSnapshots` (arayüzü ekrana çıkarmadan PNG'ye çizer).

### Değişenler (Changed)
- Dock ve çentik tek bir pencere izleyici ve tek bir medya servisini paylaşıyor; pencere olaylarında dock yenilemesi birleştiriliyor (daha az iş).
- Koy penceresi, sihirbaz ve sağ alt menü ortak tema ve ölçü sözlüklerinden besleniyor; sabit renk ve emoji kalmadı.
- Derleme tekrarlanabilir: yerel yollar PDB'ye gömülmüyor.
- Sürüm ve CI: release-please ile otomatik sürüm PR'ı, GitHub Actions adımları commit SHA'sına sabit, `vpk` sürümü Velopack paket sürümüne bağlı.

### Kaldırılanlar (Removed)
- Çentik ve dock sağ tık menülerindeki "Çıkış". Çıkış yalnız Koy penceresindeki "Koy'dan çık" düğmesi ve sağ alt menüden yapılır.
- Hiçbir davranışa bağlı olmayan ayarlar: ses görselleştirici, "müzik dalgasını durdur", "Windows'un kendi göstergesini gizle", çentik boyutu, dock'ta pencere gruplama ve "son kullanılanlar".
- Eski Ayarlar penceresi ve kullanılmayan kod, marka konseptleri ve sunum dosyaları.

### Güvenlik (Security)
- Yayımlanan ikili dosyalara geliştirici makinesinin yerel yolları artık gömülmüyor.
- GitHub Actions adımları commit SHA'sına sabitlendi (tedarik zinciri sertleştirmesi).

### Bilinen eksikler
Dock tepsisi (#11) gerçek donanımda elle denenmedi ve bellek etkisi ölçülmedi; takvimde gün/hafta görünümü, serbest zamanlayıcı ve kronometre; hava durumunda şehir seçimi; kontrol merkezi döşemelerini sürükleyerek sıralama; gerçek çok monitörlü ve karışık DPI donanımda doğrulama; bellek ölçümü (son ölçüm 82,7 MB, hedef 60 MB). Ayrıntı: [`docs/ROADMAP.md`](docs/ROADMAP.md).

## [0.1.0] - 2026-11-04

> **Not (sonradan eklendi):** Aşağıdaki listede bu sürümde bile eksik ya da bağlı olmayan şeyler vardı: ekran seçimi arayüzü olmadığı için çoklu ekran kullanıcıya açık değildi, OSD HUD çentiğe bağlı değildi, kısayollar ve ayarların çoğu davranışa bağlı değildi, "Aşağı yapış" seçilemiyordu, "1 saat duraklat" duraklatmıyordu, takvimde kronometre ve serbest zamanlayıcı hiç yoktu (hâlâ yok). Düzeltmeler için [Unreleased](#unreleased) bölümüne bakın.

**Koy**'un ilk halka açık sürümü! Windows 11 için sıfır tarayıcı (WebView2/Electron içermeyen), tek süreçte çalışan, yay fiziği animasyonlu **Notch (Çentik)** ve Seelen UI modelinde **Dock**.

### Eklenenler (Added)
- **Yay Animasyonlu Çentik (Notch):**
  - Ekranın üst ortasında 236×34 px boşta durum (saat ve pil göstergesi; müzik çalarken albüm kapağı ve %0 CPU tüketen 4 çubuklu dalga ikonu).
  - İçbükey (*concave*) üst kulaklara sahip özel `NotchShape` vektör geometrisi ve `Spring` yay fiziğiyle 640 px genişliğe açılan sekme yapısı.
  - **Müzik Paneli:** `GlobalSystemMediaTransportControlsSessionManager` üzerinden Spotify, tarayıcılar ve medya oynatıcılar için kapak resmi, şarkı/sanatçı bilgisi, zaman çizelgesi (seek) ve çoklu oturum geçişi.
  - **Takvim & Pomodoro Paneli:** Pazartesi başlangıçlı ay görünümü, yerel zamanlayıcı, kronometre ve çalışma/kısa mola/uzun mola durum makineli Pomodoro sayacı.
  - **Raf (Shelf) Paneli:** Dosya veya metinleri çentiğe sürükleyip bırakma (dosyayı çentiğin üzerine sürükleyince Raf sekmesi otomatik açılır) ve dışarı sürükleme.
  - **Kontrol Merkezi & Durum Panelleri:** CoreAudio ses seviyesi, WMI ve DDC/CI donanım parlaklığı, Wi-Fi/Bluetooth radyo anahtarları, Rahatsız Etme durumu, pil yüzdesi ve Open-Meteo hava durumu (tembel/lazy başlatmalı).
  - **OSD HUD Göstergeleri:** Ses veya ekran parlaklığı değiştiğinde çentikte 1.5 saniye beliren 260×40 px yerleşik gösterge (ses için beyaz `#F4F4F5`, parlaklık için sarı `#FACC15`).
- **Seelen Modeli Dock:**
  - İki ayrı yerleşim biçimi: **Yüzen Kapsül** (60 px yükseklik, 18 px köşe yuvarlaklığı) ve **Tam Genişlik Cam (Full-Width Glass)** (44 px yükseklik, solda canlı medya hapı, ortada uygulamalar, sağda Koy menüsü).
  - **Pencere Yaklaşma Davranışları (`DockProximityMode`):** *Çekil / Akıllı Gizlenme (Dodge - Intellihide)*, *Yer Ayır (ReserveSpace - AppBar)* ve *Hep Gizli (AlwaysHidden)*.
  - **Canlı DWM Pencere Önizlemesi:** Dock simgelerinin üzerinde 400 ms durulduğunda `DwmRegisterThumbnail` ile gerçek zamanlı pencere önizlemesi.
  - **Z-Order Kararlılığı & Etkileşim:** Alt+Tab geçişlerinde sabitlenmemiş açık pencerelerin dock sırasını koruma, sol tıkla odaklama/küçültme, orta tıkla yeni pencere açma veya kapatma, özel koyu cam sağ tık menüsü.
  - **Görev Çubuğu Güvenliği:** Dock açıkken birincil (`Shell_TrayWnd`) ve ikincil (`Shell_SecondaryTrayWnd`) görev çubuklarını gizleme; kapanışta, çökmede, kaldırmada veya acil durum düğmesiyle eksiksiz geri yükleme (`TaskbarService.Restore()`).
- **Çoklu Ekran (Multi-Monitor) Mimarisi:**
  - `DisplayLayoutResolver` ve `MonitorService` ile her monitörde kendi DPI ölçeğinde bağımsız Çentik ve Dock pencereleri.
  - **Ekran Bazlı Tam Ekran İzolasyonu:** Yan ekranda tam ekran oyun veya video açıldığında yalnız o ekrandaki Koy gizlenir; ana ekrandaki Çentik ve Dock çalışmaya devam eder (`Win+Shift+S` ekran alıntısı aracı filtreli).
  - `WM_DISPLAYCHANGE` ile ekran takılıp çıkarıldığında pencereleri dinamik oluşturma ve yeniden konumlandırma.
- **Koy Penceresi, Sağ Alt Sistem Menüsü ve İlk Kurulum Sihirbazı:**
  - 880 px genişliğinde, 8 sayfalı (**Genel, Çentik, Dock, Ekranlar, Görünüm, Kısayollar, Performans, Hakkında**) modern ayarlar penceresi (`KoyWindow`).
  - Sağ altta 320 px hızlı popover menü (`SagAltMenuWindow`) ve CsWin32 `Shell_NotifyIcon` tabanlı sistem tepsisi simgesi (`TrayIconService`).
  - İlk açılışta 3 adımlı kurulum sihirbazı (`SetupWizardWindow`).
  - Tam Türkçe (`tr-TR`) ve İngilizce (`en-US`) anlık dil desteği (`Loc.Instance`).
  - **Marka Kimliği:** Konsept C "Koy Rozeti" (Windows 11 Fluent Squircle + Oyulmuş Çentik + K Monogramı) vektör logosu ve çok katmanlı `.ico` varlık kiti.
  - **Dağıtım & CI/CD:** Velopack kurulum paketi (`Koy-win-Setup.exe`), taşınabilir paket (`Koy-win-Portable.zip`), `SHA256SUMS.txt` doğrulaması ve GitHub Actions otomatik derleme/yayın iş akışları.

[Unreleased]: https://github.com/brhnshn/koy/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/brhnshn/koy/releases/tag/v0.1.0
