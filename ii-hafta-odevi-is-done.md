# II. Hafta Ödevleri

# *Yeni bir Gitthub repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir?*
## GPL (Genel Kamu Lisansı)
- En çok kullanılan özgür yazılım lisansı diyebiliriz. 
- GPL teşvik edici gelişime açık bir lisansdır. 
- Hem geliştirici hem de kullanıcı açısından büyük olanaklar sağlar. 
- GPL’in en çok dikkat ettiği konu üretilen yazılımın kaynak kodları ile beraber dağıtılmasıdır.
- GPL lisansını kullanan bir yazılımı alıp kendi projenize eklerseniz siz de kaynak kodunuzu GPL ile lisanslamalısınız ve açık kaynak olarak dağıtmalısınız. 
- GPL, yazılımın ücretlendirme konusunda fikir beyan etmez, yazılımlar ücretsiz olmak zorunda değildir. Bu ibare lisansta bulunmasına rağmen GPL lisanslı yazılımların çoğu ücretsizdir.
- GPL in dezavantajı diyebileceğimiz bir yanı ise GPL ile lisanslanmış yazılımın başkaları tarafından değiştirilerek geliştirilmesi sonucunda elde ettiği gelire hiç bir konuda maddi talepte bulunamazsınız. 
  - Yaptığınız yazılımın ya da kütüphaneden gelir elde etmek gibi bir durumunuz varsa başka lisanslarla lisanslamanız gerekir.
- GPL lisansı kullanarak geliştirilen yazılımlar; Mozilla, Mozilla ThunderBird, GIMP, Audacity, Scribus, eMule, Vuze, Shareaza, Notepad++, VLC, Processing.

## LGPL (Kısıtlı Genel Kamu Lisansı)
- Kısıtlı Genel Kamu Lisansı (LGPL) genel ağırlıklıkta kütüphane olarak geliştirilen yazılımlarda kullanılır. 
- GPL in aksine LGPL’de geliştirdiğiniz bir kütüphaneyi özel mülk yazılımın içerisinde kapalı kaynak olarak kullanabilirsiniz. Ancak LGPL ile geliştirilmiş kütüphanenin içerisinde herhangi bir değişiklik yapmış veya yama geliştirmiş iseniz bu kısmı açmak zorundasınız.
- Büyük yazılım firmaları LGPL ile ilgili kütüphaneleri kendi projelerine eklerken script dosyaları yazarak kendi projelerine bağlarlar. Böylelikle LGPL de bir değişikliği kolaylıkla açık olarak yayınlama imkanına sahip olurlar.
- LGPL lisansı altında geliştirilen yazılımlar; Mozilla, Mozilla ThunderBird, GIMP, LibreOffice,Processing, OpenGL

## BSD Lisansı
- BSD lisansı adını Berkeley Software Distribution dan alır. 
- Özgür yazılım lisans ailesindendir. 
- Yazılım üzerine neredeyse hiç bir sınırlama koymaz. 
- İstenilen şekilde değiştirebilirsiniz, kodu kapatabilirsiniz ve üzerinden para kazanabilirsiniz. 
- İsteyen herkes istediği gibi kullanabilmektedir.
- BSD lisansı altında geliştirilen projeler; PostgreSQL, OpenCV

## MPL (Mozilla Kamu Lisansı)
- MPL açık kaynak lisans ailesi içerisindedir. 
- Genel olarak BSD lisansının olanaklarıyla Genel Kamu Lisansını bir araya getirmeye çalışan bir lisansdır.
- MPL lisansı altında geliştirilen yazılımlar; Mozilla, Mozilla ThunderBird, LibreOffice

## MIT Lisansı
- MIT lisansı üzerinde geliştirilmiş olan yazılımın bir kopyasını dağıtma, kullanma, kopyalama, değiştirme, alt lisanslama gibi imkanların hepsini sağlar. 
- Ticari ve hususi olarak kullanma imkanını sağlar. 
- Zorunlu yapmanız gereken MIT lisans ibaresini kodunuza eklemeniz gerekmektedir ve telif bulundurmanız gerekmektedir. 
- Yazarları sorumlu tutamazsınız.

## Apache Lisansı
- Apache lisansı yazılan programın kodlarının tüm kopyaları, değiştirilmiş ve ya değiştirilmemiş, lisansın bir kopyası eşliğinde dağıtabilir ya da kullanabilir. 
- Üzerinde yapılan değişiklikler değiştirilmiş olarak işaretlenmelidir. Ticari kullanım olarak kullanım imkanı sağlar.


# Merge - Squash - Rebase arasındaki farklar nelerdir?
- Merge , Bir dalı birleştirmek, orijinal dallanma yapısını sağlam tutarken bir dalı başka bir dala çekmeyi içerir
- Rebase, bir branchin orijinal temel taahhüdünü değiştirir. 
- Git squash komutu, farklı bir rebase kullanımı olarak değerlendirmek daha doğru olacaktır.Geçmişte atılan commit’leri yeniden düzenlemek, isimlendirmek veya birleştirmek için kullanıyoruz.
- Git merge ile yaptığımız birleştirmede yeni bir commit yaratacak ve yeni branch'deki **tüm history tarafını kaybetmeden birleştirme işlemi** gerçekleşmiş olcaktır. 
- Git squash komutu aslında farklı bir rebase kullanımı olarak değerlendirmek daha doğru olacaktır. Geçmişte atılan **commit'leri yeniden düzenlemek, isimlendirmek veya birleştirmek** için kullanıyoruz. 
- Git rebase ile birleştirdiğimizde ise branchteki **commit'lerimizi tek tek alıp istediğmiz branch üzerine ekleyecektir**. Böylelikle **tek bir history** oluşturacak ve istenmeyen history ortadan kalkacaktır.
- Rebase vs Merge >> aslında benzer işi yaptıklarını ve fark olarak ise git rebase kullanımında history’nin temizlendiğini ve git merge kullandığımızda ise tüm geçmişin korunduğunu görüyoruz.

 
 # *Agile-Scrum-Kanban kavramları*

- **Agile (çevik) yöntem**
  - Yazılım geliştirmede kullanılan proje yönetimine özel bir yaklaşımdır. Bu yöntem ekiplerin yazılım geliştirme süreçlerinin öngörülemezliğine cevap vermesine yardımcı olur. Genellikle sprint olarak bilinen artımlı, yinelemeli iş dizilerini kullanır ve yapılacak işlerin önem sırasına göre yapılması gerektiğini öne sürer. Bu metodolojiye göre projenin en iyi şekilde ortaya konulması için kaynaklar ve ekip özenli bir hazırlık süreci geçirmelidir. 
  - Agile metodunun temel esasları şöyle sıralanabilir:
     - Deneysellik
     - Önceliklendirme
     - Kendi kendini örgütleme
     - Zaman çerçevesi
     - İş birliği
  - Agile yöntemi, bu esaslardan birini atlayarak yönetilen bir projenin başarısız olacağını ileri sürmektedir. Agile yöntemine göre bu esaslar titizlikle uygulandığında; projede risk faktörü azalacak, olası hatalar ortaya çıkacak, hatalar erkenden tespit edilecek ve ürün pazara daha çabuk ulaşacaktır.
  - Agile Manifesto — 4 Temel Değer:
     - İş süreçleri ve araçlardan ziyade bireyler ve bireyler arasındaki etkileşim değerlidir.
     - Kapsamlı bir dokümantasyon sürecinden ziyade, çalışan bir yazılım ortaya koymak daha önemlidir.
     - Müşteri ile işbirliği yapmak, sözleşme görüşmelerinden daha önemlidir.
     - Değişime cevap vermek, mevcut planı izlemekten daha önemlidir.

- **Scrum**
  - “İnsanların mümkün olan en yüksek değere sahip ürünleri üretken ve yaratıcı bir şekilde geliştirirken, karmaşık ve adaptasyona açık sorunları ele alabildikleri bir çerçeve” 
Agile proje yönetim metodolojilerinden biridir. Kompleks yazılım süreçlerinin yönetilmesi için kullanılır. Bunu yaparken bütünü parçalayan; tekrara dayalı bir yöntem izler. Düzenli geri bildirim ve planlamalarla hedefe ulaşmayı sağlar. Bu anlamda ihtiyaca yönelik ve esnek bir yapısı vardır. Müşteri ihtiyacına göre şekillendiği için müşterinin geri bildirimine göre yapılanmayı sağlar. İletişim ve takım çalışması çok önemlidir. 
  - 3 temel prensip üzerine kurulmuştur;
     - Şeffaflık; Projenin ilerleyişi, sorunlar,gelişmeler herkes tarafından görülebilir olmalıdır.
     - Denetleme; Projenin ilerleyişi düzenli olarak kontrol edilir.
     - Uyarlama; Proje, yapılabilecek değişikliklere uyum sağlayabilmelidir.

- **Kanban**
  - Yalın Üretim tekniklerinden biri olup üretimi yönetmek için kullanılan görsel bir metottur. Çekme sistemi ile hangi ürünün ne zaman ve ne miktarda üretildiğini kontrol eder. Kanban sistemini anlayabilmek için öncelikle tam zamanında üretim(Japonların araba üretirken Kullandığı JIT sistemi) kavramını özümsemek gerekir.Kanban üretim sürecinde yer alan aşamaları görsel olarak işaretlemek için kartların kullanılmasıdır. Kanban aynı zamanda, birçok endüstri dalında dağıtım ekibini çevreleyen kargaşayı organize etmenin ve iş akışını ortaya çıkarmanın ve işlem problemlerini çözmenin bir yoludur. Bitmemiş işlerin ne kadar sürede işlem gördüğünü belirleyerek, işlem süresinin azaltılmasını sağlar. Atıkları azaltmak ve üretimi en üst düzeye çıkarmak için süreçlerin standart hale gelmesini sağlar.


# Github Flow'un alternatifleri nelerdir? Artılarını ve eksilerini karşılaştırınız.

**Github Flow** hafif bir workflow'dur. Github tarafından 2011 yılında oluşturulmuştur. 

- Avantajları:
Sürekli entegrasyon avantajı
Git Flow'a alternatif
Tek bir versiyonu yönetmek için ideal 
- Dezavantajları:
Proje çabucak kompleks hale gelebilir
Çok sayıda versiyon yönetimi için önerilmez 

**Git Flow** en popüler ve en bilinen workflow'dur. Vincent Driessen tarafından 2010 yılında oluşturulmuştur. 2 ana branch üzerine kurulmuştur.(master ve develop) 

- Avantajları:
    - Projenin yaşam döngüsünde branchlerin daha temiz bir durumda olmasını sağlar.
    - Branch isimlendirmeleri proje yönetimini kolaylaştırır.
    - Git eklentileri desteği vardır.
    - Çok sayıda versiyon yönetimi yapılabilir. 
- Dezavantajları
    - Git geçmişi çok düzgün okunamaz.
    - 2 branche bölünmeden dolayı sürekli üretimi ve entegrasyonu daha zorlu hale gelir
    - Tek versiyon için önerilmez. 

**GitLab Flow** GitLab tarafından 2014 yılında geliştirilmiştir. Github Flow'dan farklı olarak farklı branchleri vardır. 

- Avantajları:
    - Git geçmişi daha okunaklı ve temizdir.
    - Tek versiyon için avantajlıdır. 
- Dezavantajları:
    - Github Flow'dan daha kompleksdir.
    - Çok fazla versiyonlamada Git Flow kadar karmaşık bir yapıya bürünebilir. 

**One Flow** 2015 yılında Git Flow'a alternatif olarak Adam Ruka tarafından üretilmiştir. Git Flow ile arasındaki fark One Flow'da develop branch'inin olmamasıdır. 
- Avantajları:
    - Takımın kararlarına göre değişkenlik gösterebilir.
    - Tek versiyon için uygundur.
    - Git geçmişi daha temizdir. 
- Dezavantajları:
    - Sürekli teslim projeler için uygun değildir.
    - Feature branch'i sürekli entegrasyonu daha zor hale getirir.
    - Çok fazla versiyonlama kısmında iyi değildir.

# *Gang of Four(GOF)*
- Gang of Four topluluğu tarafından yayınlanan tasarım desenleri, Nesne Yönelimli Programlamada karşılaşılmış tasarım sorunlarına üretilmiş optimum çözümler olarak tanımlanabilir. Tasarım desenleri bizlere daha yönetilebilir ve okunabilir kod yazmak konusunda avantajlar sağlar. Bunun yanında performans ve geliştirilebilirlik konusunda da katkıları vardır. 
- Tasarım desenleri genel olarak 3 başlık altında toplanır. 
     - Creational Patterns - Kurucu Desenler: Nesnelerin oluşturulması ile ilgili patternlerdir. 
          - Factory Method
          - Singelton
          - Abstract Factory
          - Builder
     - Structural Patterns – Yapısal Desenler: Nesnelerin birbiri ile olan ilişkisini konu alır.
          - Adapter
          - Decorator
          - Facade
          - Proxy
     - Behavioral Patterns – Davranışsal Desenler: Sınıfların bir görevi yerine getirirken nasıl davranacağı ile ilgili desenlerdir.
          - Iterator
          - Observer
          - Memento
          - Mediator


# *Interface ve Abstract sınıflar arasındaki farklar nelerdir?*

**Abstraction (Soyutlama)**
- Abstraction, OOP (Object Oriented Programming-Nesne Tabanlı Programlama) içerisindeki önemli kavramlardan birisidir. 
- C#’taki soyutlama; diğer Object Oriented dillerde olduğu gibi iç detayları gizleyerek sadece işlevleri göstermeye denir. 
- Abstract sınıfları genel olarak inheritance (kalıtım) uygularken kullanırız. new anahtar sözcüğü ile nesneleri oluşturulamaz. İçerisinde değişken ve metod bulundurabilir.
- Abstract sınıflardan türetilen sınıfların abstract metodları implement etmesi zorunludur. Diğer metodları override etmeden de kullanabilir. 
- Constructors (yapıcı metodlar) ve destructors (yıkıcı metodlar) bulundurabilirler. 
- Static tanımlanamazlar. (Tanımlanmaya çalışılırsa compiler “an abstract class cannot be sealed or static” hatası verir) 
- Bir sınıf yalnızca bir abstract sınıfı inheritance yoluyla implement edebilir. 
- Çoklu kalıtım (multiple inheritance) desteklenmez. 
- Abstract olmayan metodları da bulundurabilir. 
- Kendisinden inherit alacak sınıflar ile arasında **“is-a”** ilişkisi vardır.

**Interface**
- Bir sınıfın ne yapması gerektiğini belirtir, nasıl yapması gerektiğini değil. 
- new keywordü ile nesneleri oluşturulamaz. 
- Default olarak tüm Interface üyeleri abstract ve public olarak tanımlanır. Sizin özellikle belirtmeniz gerekmez. 
- Bir sınıf birden fazla interface’i inherit edebilir, çoklu kalıtım (multiple-inheritance) desteklenir. 
- İçerisinde yalnızca metodların imzaları yer alır, içi dolu metod bulunduramazlar. 
- Kendisinden inherit alacak sınıflar ile arasında **“can-do”** ilişkisi vardır.

