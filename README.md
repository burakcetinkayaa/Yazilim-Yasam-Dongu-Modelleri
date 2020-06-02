# Yazilim-Yasam-Dongu-Modelleri
Tüm canlılar ve hayatın içindeki her şey gibi yazılımın da yaşam döngüsü ve bir modeli vardır. Örneğin, hayvanlar alemi en basit şekilde belirtmek gerekirse; doğar, yaşar, büyür ve de ölür.
Yazılım da aynı bu şekilde bir yaşam döngü modeline (“software development life cycle”, “SDLC”) sahiptir. Planlama, analiz, tasarım , uygulama, test etme ve birleştirme ve de son olarak yazılım tamamlandıktan sonraki kısım için gerekli olan bakım ve sürdürülebilirdik olmak üzere altı aşamadan oluşmaktadır.

Gelin bu aşamalara beraber bakalım; 
• Planlama: Yazılım yaşam döngü modelinin ilk aşaması olan planlamada öncelik olarak gereksinimler belirlenir. Müşteri ile görüşülerek istekleri ve beklentileri tam olarak görüşülüp buna göre üretim aşamasındaki gereksinimlerin maliyeti, kaç kişiye ihtiyaç duyulacağı vb. gibi konular konuşulur ve böylece projenin planı belirlenmiş olur. 
 
• Analiz: Bu aşamanın amacı belirlenmiş olan ihtiyaçları ve sistemin işlevlerini kesin olarak belirlemek ve belli bir biçimde dokümante etmektir. Temel amacı bir yazılımcı gözüyle mevcut yapıdaki işlerin ortaya çıkarılması ve her şeyin doğru algılandığından emin olmaktır. Son olarak ise bu aşama UML diyagramlarının çizilmeye başlandığı ilk aşamadır. 
 
•Tasarım: Analiz sonrası belirlenmiş olan gereksinimler tamamlandıktan sonra, planlama ve analizin yardımıyla tasarım aşamasına geçilmiş olunur. Yazılımda bulunacak özelliklerin nasıl olacağı ve bunların nasıl gerçekleştirileceği belirlenir. Bu aşamada kodlama yapılmaz. Bu aşama mimari tasarım ve detaylı tasarım olmak üzere iki aşamadan oluşmaktadır; 
°Mimari tasarım: Bu aşamada sistemin nasıl bir yapıda olacağına karar verilir. Örneğin: Bir bina yapımında kaç katlı olacağının, kaç daireye sahip olacağının belirlenmesi. 
°Ayrıntılı tasarım: Bu aşamada ise veri tabanı tasarlanır, algoritmalar ve programda kullanılacak olan dil belirlenir. Bunlar ve benzeri gibi detaylar ayrıntılı bir şekilde belirlenmelidir. 
 
•Uygulama: Planlanmış, analiz edilip tasarımı tamamlanmış olan programımız için kod yazmaya başladığımız aşamadır. Bu aşama kodlama, test etme ve kurulum olmak üzere üç bölümden oluşur. 
Kodlama sırası ve sonrası için en önemli etkenlerden biri test etmedir. Erken test edilmesi ile birlikte sonucuna bağlı olarak para, zaman ve de prestij kayıpları engellenmek istenir. 
 
•Bakım ve sürdürülebilirlik: Yazılan programın tesliminden sonra başlayan bu aşamada önemli olan şey bakımı ve sürdürülebilir olmasıdır. Bakımın temel amacı var olan veya ileride karşılaşılabilecek hataları tespit edip onları düzeltmektir. İkinci ve de üçüncü bir amacı ise eksik olan kısımları tamamlamak ve de ürüne yeni özellikler eklemektir. 
 
Yazılım yaşam döngüsünün daima aktif olabilmesi ve de en verimli sonucu vermesi için yazılım süreç modelleri(software process models) kullanılır. 
 

Yazılım Süreç Modelleri (Software Process Models) 
 
1. Kodla ve Düzelt(Code and Fix): 

Bu model basitçe; ürün hazır olana kadarki süreçte kodlama yapılarak sağlanır.
Avantajları: Planlamaya ihtiyaç duyulmaması, Çok küçük proje veya prototiplerde kullanılabilir olması, herkese açık bir model olması, uzmana ihtiyaç duyulmaması, aşamaları çabuk geçilebilir olması.

Dezavantajları: Planlama olmadığından dolayı ne zaman biteceği belli değildir, hataların belirlenmesi zordur, düzeltmek yüksek maliyete sebebiyet verebilir, kodların esnek olmayışından dolayı     değiştirilmesi zordur.
Şelale (Waterfall) Modeli
Bu model yazılım gereksinimi, tasarım, gerçekleştirme, test, işlem ve bakım safhalarından oluşmaktadır. Her safha bir önceki safha ile bağlantılı olarak başlar. Bir sonraki safhanın kullanabileceği şekilde değiştirerek devam eder.
Avantajları: Kullanımı ve anlaması kolay olan bu modelin yönetimi de kolaydır. Farklı safhalardan oluştuğundan dolayı proje planı en başta net şekilde bellidir. Çok küçük ve gereksinimleri iyi anlaşılmış olan projelerde iyi çalışır.
Dezavantajları: Nesne yönelimli, devam eden ve de uzun projeler için uygun değildir. Projedeki değişimlere elverişsizdir. Değişime açık olmayan bir model olduğundan müşteri memnuniyetini sağlamak çok zordur. Ürün en son safhada tamamlandığından dolayı müşterinin isteği eksik olarak anlaşılmış veya anlaşılmamış ise projenin iptaline sebep olur.
V Modeli
V modeli analiz, üst-alt seviye tasarım, kodlama, birim-entegrasyon-sistem testlerinden oluşur. V modeline şelale modelinin geliştirilmiş hali de denilebilir. Doğrusal ilerlemek yerine kodlama aşamasından sonra yapılan testlerden dolayı yukarı doğru bir eğim alır ve de V şeklini aldığından dolayı bu adı alır. 

Avantajları: Doğrulama ve onaylama planları erken aşamalarda vurgulanır, sadece son üründe değil tüm teslim edilebilir ürünlerde uygulanır. Yönetim tarafından takibi kolaydır.
Dezavantajları: Aynı anda gerçekleştirilecek olaylara imkan tanımaz. Fazlar arası tekrarlama kullanmaz. Risk çözümleme aktiviteleri içermez. Geliştirme devam ettikçe iş ve ürün gereksinimleri de değişkenlik gösterebilir.
Evrimsel Geliştirme (Evolutionary Development)

İlk tam ölçekli model olan bu model çok birimli organizasyonlar için önerilmektedir. Her aşamada üretilen ürünler tam işlevselliği içermektedir. Modelin başarısı ilk evrimin başarısına bağlıdır.
Evrimsel geliştirmede iki çeşit vardır;
Keşifçi Geliştirme (Exploratory Development): Bu kısmın amacı müşteri gereksinimlerini incelemek amacıyla müşteriyle çalışıp son sistemi teslim etmektir. 
Atılacak Prototipleme (Throw-Away Prototyping): Bu kısmın amacı ise sistem gereksinimlerini anlamaktır. 
Avantajları: Kullanıcıların gereksinimlerini daha iyi anlaşılır hale getirir. Devamlı olarak değerlendirme geliştirme risklerini azaltır. Böylece hatalar azalır. 
Dezavantajları: Süreci tam olarak göremeyiz, ürün yine son safhada görülür anlamına gelebilir. Bakımı zordur. Yazılım gereksinimini yenilemek gerekebilir. 

Prototipleme (Prototyping): Bu modelin amacı isminden de anlaşılacağı gibi prototip oluşturup geliştirmektir. Gereksinimlerin doğru anlaşılması bu süreç için oldukça önemlidir. Hızlı plan, hızlı tasarım ve de hızlı kodlama ön plandadır. 
Avantajları: Karmaşayı ve yanlış anlaşılmayı engeller. Yeni gereksinimlere açıktır ve de risk kontrolü vardır. 
Dezavantajları: Belgeleme olmadan hızlı ve kirli prototipler oluşturur. Hedefler eğer net değilse önemli güvenlik açıkları oluşur. Düzeltme adımı atlanırsa performans düşüklüğüne sebebiyet verebilir. 
Helezonik(Spiral) Model: Bu modelin üzerinde durduğu en temel konular risk analizi ve de prototip üretmedir. Her döngüde o bölümün analizi yapılır. Her döngü sonunda yeniden planlamak yapılarak hedefler yeniden hesaplanır. Bu model, önceden geliştirilmiş bileşenleri kullandığından dolayı projeler için uygundur. En büyük getirisi risk analizinin detaylı ele alınmasıdır. Bundan sebep zaman ve maliyet hesabı kolay hesaplanır. Özellikle güvenlik yazılımlarının oluşumunda bu model kullanılmaktadır. 
Avantajları: Kullanıcı sistemi daha erken görebilir. Parçalara bölüp önce risk taşıyanı çözer. Pek çok yazılı modelini içinde barındırır. Hayaları erken giderme şansına sahiptir.
Dezavantajları: Küçük ve düşük riskli projeler için fazla pahalı bir sistemdir.Kompleks (hemen kavranamayan) bir yapıya sahiptir. Fazla dokümantasyondan oluşur. 

Formal Sistem Geliştirme (Formal System Development): Bu model yazılım tasarım ve gerçekleştirmesiyle ilgili matematiksel bir tekniktir. Temelinde karmaşık sistemleri geliştirme ve program geliştirmeye destek yatar. Kullanıcı karşısına çıkan belirtim hatalarını en aza indirger. 
Formal belirtim, tasarım ve geçerleme yöntemi ile doğruluğun geliştirilmesini vurgular. Yazılım artımlara geliştirilir. Amacı  pahalı hata ayıklama işlemlerini önlemek için kodu başta doğru yazmak ve test aşamasından doğruluğunu sağlamaktır.
Avantajları: Yazılımdaki belirsizlik, eksiklik ve de uyumsuzlukları belirler. Hatasız yazılım geliştirmeye imkan sağlar. Her iterasyondan (*dizi elemanlarının teker teker yazılması yerine çeşitli döngüler kullanarak yazılmasıdır) sonra aşamalı olarak artan efektik çözümler sunar. Karmaşık değildir.
Dezavantajları: Çok zaman alan ve de pahalı bir modeldir. Kullanım esnasında personelle iletişim mekanizması zor işler. Diğer modellerin bu modelin uygulamasıyla ilgili temel bilgilere sahip olması  için eğitilmeye ihtiyacı vardır. 

Yeniden Kullanıma Yönelik Geliştirme (Re-Use Based Development): Önceden hazırlanmış veya dışarıdan alınmış yazılımların kullanılmasıyla geliştirme yapılmasıdır. Bu tür uygulamalar yapabilmek için altyapı kurulmuş olmaktadır.
Avantajları: Kaynak kontrolü ve maliyet denetimi yapılabilir. Basit ve anlaşılırdır. Önceden oluşturulmuş olan sınıflar kullanılabilir. 
Dezavantajları: Gereksinimleri anlamak güçtür. Pahalıdır. Uzmanlar tarafından yapılması gerekir. Başarım garantisi yoktur.

Artırımlı Geliştirme (Incremental Development): Müşteri ürünlerinde değişikliğe ihtiyaç duyarsa bu model bu değişikliğe uyum sağlar. Belli bir takvime bağlı kalarak yazılımı kesim kesim geliştirip teslim etmeyi hedef seçer. Her kesim kendinden öncekinin üstüne ek işlevlerin eklenmesiyle yenilenir. Yazılım geliştirmenin kısıtlı sayıda çalışanla yapılmasını sağlıyor oluşu bu modeli üstünlük sahibi eder. Bu model yinelemelidir. Yeniden kullanılabilir bir ürün tüm döngülerin sonunda ortaya çıkar. 
Avantajları: Gereksinimler müşterilerle birlikte belirlenir, önemine göre teslim edilecek artımlar belirlenir. Projenin başarısız olma riskini azaltır.En önemli sistem özellikleri daha fazla test edilme imkanı bulmuş olur. Böl ve Yönet (Divide and Conquer) yaklaşımıdır.
Dezavantajları: Artırımları tanımlamak için tüm sistemi tanımlatmak gereklidir. Gereksinimleri doğru artımlara atamak bazen zor olabilir. Deneyimli personele ihtiyaç vardır. Artımların kendi içlerinde tekrarlamalara izin vermez.
Birleşik Süreç (Unified Process): Nesneye dayalı yazılım geliştirmek amacıyla var olan yöntemlerin en iyi özelliklerini bir araya getirerek oluşturulmuştur. Yinelemeli, arttırmalı, evrimsel ve de risk güdümlüdür. 
Bu modeldeki yazılım geliştirme aşamaları başlangıç, ayrıntılandırma, tamamlama ve de yayım olmak üzere 4’e ayrılır.
Başlangıç: Vizyon kararı, fizibilite çalışması, tamam ya da devam kararı.
Ayrıntılandırma: Daha realist bir çözümleme, çekirdek yapının ve de yüksek risk içeren kısımların tekrarlamalı olarak oluşturulması.
Tamamlama: Daha az riskli ve daha az öncelikli kısımların yinelemeli olarak gerçekleşmesi.
Yayım: Beta (*yazılımın ilk sürümündeki sistem testlerinden ve eksiklik testlerinden geçirilmeyi belirtir.) testleri, piyasaya sürme çalışmaları.
Avantajları: Değişken isteklere uygun olması, erken geri besleme (feed-back) yapıyor oluşu, büyük sistemlerde çözüm kolaylığı sağlaması, Her iterasyonda deneyim kazanılıyor olması, Risklerin erken giderilişi, Ürünün erken elde edilmesi.
Dezavantajları: Risk yönetimi düşüktür, Dokümantasyon yükü ağır olduğundan maliyetli olabilir, karmaşıktır. 

Çevik Modeller (Agile Programming): İteratif(*devamlı tekrarlayan) değiştirme temelli bir grup yazılım geliştirme yöntembilimine (metadoloji) dayanır. Gereksinimler ve çözümler farklı grupların ortak çalışmasıyla olgunlaşır.  Çevik modeller genellikle sıkı denetim ve adaptasyona sahip bir proje yönetim sürecini benimser. İyi bir takım çalışması, örgütlenme ve de tabii ki iyi bir yazılımın hızlı bir şekilde ulaştırılması hedeflendiği bir metottur. Çelik metotlar yazılım geliştirme yaklaşımı değil, geliştirme süreçleri topluluğudur.   
Çevik Yazılım (Agile Development) değer sistemini ve de somut yazılım metotlarını içerir . Bu yazılım çeşidine, yazılım sektöründe yeni bir filozof akımı veya yeni bir yazılım meta modeli de denebilir. Bu yeni felsefik düşüncenin somut örnekleri arasında Extreme Programming, Scrum ve de Lean Development vardır.
Extrem programlama (Extreme Programming) yazılım kalitesini ve değişen müşteri gereksinimlerine yanıt vermeyi amaçlayan bir yazılım geliştirme metodolojisidir.
Scrum, yazılım Mühendisliği'nde bir uygulama geliştirme yöntemidir. Bu geliştirme yönteminin temel özelliği gözlemci, geliştirmeci ve tekrara dayalı olmasıdır. Birçok modern yazılım projesinin oldukça karmaşık olduğu ve en baştan tümünü planlamanın zor olacağı şeklindeki bir varsayımdan hareket eder.
Yalın Yazılım Geliştirme  (Lean Development), yalın üretim ilke ve uygulamalarının yazılım geliştirme alanına dönüştürülmesidir.
Avantajları: Öğrenim gerektirmez, adaptasyon süreci hızlıdır. Takım elemanları işi zevkle yapar, verim artışı yaşanır. Sık sık feed-back alındığından dolayı ürün istenilene çok yakın şekilde teslim edilir.
Somut örneklerinden de kısaca bahsettiğimize göre Çevik Yazılıma ve de prensiplerine bakalım istiyorum;
Süreç ve araçlar, kişiler arası etkileşim iyidir, kapsamlı dokümantasyon vardır, sık ve aralıklı olarak teslimat yapılarak müşteri memnuniyeti sağlanır, yazılım kısa sürede teslim edilir, ekip arasında iyi bi anlaşma sağlanır, motivasyon yüksektir.
Avantajları: İnsanın doğal eğilimine yakın olduğundan adapte olması kolay olur. Takım elemanları arasındaki motivasyon yüksektir, verim fazladır. Sık üretilen çıktılar sayesinde müşteri memnuniyeti fazladır.. Plan aşamasında ayrıntılı plan yerine iterasyonun planı yapılır. Değişime açıktır. 
Dezavantajları: Sürekli değişen ihtiyaçlardan dolayı aşırı çalışmaya neden olur. Proje başarısına bağlı bir kariyer geleceği olduğundan dolayı takım üzerinde yoğun bir baskı hissi vardır.
Scrum Günümüzde Neden Popüler?
Aslında bunu çevik yazılımdan da anlamış olabileceğiniz gibi Scrum projelerinde müşteri memnuniyeti ve proje başarı oranı çok fazla. Takımın kendi içindeki motivasyonu Scrum’u bu denli popüler hale getiren baş etmenlerden. Tabii bunlar biraz daha dışarıdan bakılınca görülebilecek sonuçlar fakat yazılımsal olarak bakacak olursak eğer; kapsamlı dokümantasyondan çok çalışan yazılıma önem verilir. Sözleşmelerden çok müşteri ile birlikte çalışmayı hedefler. Yazılım geliştirmeye iteratif yaklaşır. Bunlar ve bunlara benzer sebeplerden dolayı Scrum günümüzde fazlasıyla popülerdir ve öyle de kalacak gibi gözüküyor. Büyük projelerde, başarı istenen projelerde rakamsal olarak bakarsak eğer 1890-1990 arasındaki memnuniyetsizliklerle birlikte ortaya çıkan çevik yazılım ve scrum bu dönemde başarı oranını yaklaşık olarak %80’e çıkararak büyük bir başarı elde etmiştir. Bundan sebep günümüzde tercih edilmektedir.
