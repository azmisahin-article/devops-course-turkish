# Git

Bir ağacın büyüme süreci, sürüm kontrolü kavramına benzer bir şekilde düşünülebilir.

![Bir ağacın büyüme süreci](https://static.vecteezy.com/system/resources/previews/000/097/111/original/plant-growth-cycle-free-vector.png)

1. **Başlangıç Durumu (İlk Commit):** Bir ağaç **tohum** olarak başlar. Bu başlangıç durumu, bir projenin **başlangıç noktasına** benzer. İlk commit olarak düşünebiliriz.
2. **Gelişim ve Değişiklikler (Commitler):** Ağaç, **zamanla büyür ve değişir**. Yeni dallar, yapraklar ve gövde bölümleri oluşur. Bu büyüme ve değişim süreci, **projede yapılan değişiklikleri** temsil edebilir. Her yeni **büyüme aşaması**, bir **commit olarak kaydedilen değişiklikler** gibi düşünülebilir.
3. **Paralel Dallanmalar (Branchler):** Ağacın dallanması, **farklı yönlere doğru büyümes**i gibi düşünülebilir. Bir ağaç, farklı dallara sahip olabilir ve bu dallar farklı **gelişme yollarını** temsil eder. Bu, projelerdeki **dallanma** ve farklı özelliklerin geliştirilmesi anlamına gelir.
4. **Birleştirme (Merge):** Farklı dalların birleştirilmesi, ağaçlardaki dalların bir araya getirilmesine benzer. Bu, projede farklı özelliklerin veya dalların birleştirilmesi aşamasını temsil eder.
5. **Hatalar ve Düzeltmeler (Bug Fixes):** Ağaçlar hastalık veya zarar görebilir. Bu durum, projelerde hataların veya eksikliklerin düzeltilmesi anlamına gelir. Bu düzeltmeler, bir projede yapılan hataların giderilmesine benzer.
6. **Bitiş (Son Commit):** Bir ağaç, büyüme sürecinin sonunda belirli bir noktada durur. Bu nokta, projenin tamamlanmış veya bir dönüm noktasına gelmiş olduğu durumu temsil edebilir.

Ağaç büyümesi, sürüm kontrolü kavramlarına paralellik gösteren doğal bir örnektir. Her büyüme aşaması, projede yapılan değişiklikleri, dallanmaları, düzeltmeleri ve birleştirmeleri temsil edebilir. Bu tür doğal örnekler, karmaşık teknik konseptleri daha somut ve anlaşılır hale getirebilir.

*Git, **dağıtık bir sürüm kontrol sistemi** olarak kullanılır. Bu, her katılımcının yerel olarak bir kopya oluşturabileceği ve bu kopyaların bir merkezi sunucuda yönetilmeye gerek kalmadan senkronize edilebileceği anlamına gelir.*

---

**Git Kurulum**

[Git - Downloads](https://git-scm.com/downloads)

**Uzak** **Git**

Git komutlarını denemek ve kullanmak için kendi bilgisayarınızda bir **geliştirme ortamı** oluşturabilir yada **github codespace** gibi bir platformda test edebilirsiniz.

*GitHub Codespaces, projelerinizi çevrimiçi bir geliştirme ortamında çalıştırmanızı ve düzenlemenizi sağlayan bir hizmetdir. Bu hizmet sayesinde, kodunuzu herhangi bir tarayıcı üzerinden erişebileceğiniz bir ortamda düzenleyebilir ve projelerinizi hızlıca başlatabilirsiniz. Bu hizmeti 2 çekirdekli bir altyapı ile aylık 60 saat kullanarak test edebilirsiniz.*

**Codespaces**

[Codespaces](https://github.com/codespaces)

**Git Yapılandırma**

Git'in yapılandırması, Git'in nasıl çalışacağını ve hangi kullanıcı bilgilerini kullanacağını belirtmenizi sağlar. Git yapılandırması, global, kullanıcı ve proje düzeyinde yapılabilir.

**`git config`** komutu temelde **üç** farklı düzeyde yapılandırma ayarlarını yönetmenizi sağlar:

1. **Yerel (Local) Düzey:** Bir projenin çalışma dizininde bulunan **`.git/config`** dosyasında saklanır. Bu ayarlar, yalnızca **belirli projede** geçerlidir.
2. **Kullanıcı (Global) Düzey:** Kullanıcının ev dizinindeki **`.gitconfig`** dosyasında saklanır. Bu ayarlar, kullanıcının **tüm projeleri** için geçerlidir.
3. **Sistem (System) Düzey:** Sistem genelindeki Git yapılandırmasıdır. Tüm kullanıcılar ve projeler için geçerli olur. **Genellikle sistem yöneticileri tarafından yapılandırılır.**

**Git Temelleri**

**Yeni bir Git Deposu Oluşturma**

```bash
git init
```

**Değişiklikleri İzlemeye Başlama:**

```bash
git add .
```

**Belirli dosyaları** stage etmek için:

```bash
git add dosya1 dosya2
```

**Commit Oluşturma:**

```bash
git commit -m "Değişiklik açıklaması"
```

*NOT : Yazılım geliştirme süreçlerinde daha anlamlı ve düzenli bir şekilde git taahhüt (commit) mesajlarının yazılmasını sağlayan bir yaklaşımlar benimsemelisiniz. Bu yaklaşımlar, projelerin daha iyi yönetilmesine, değişikliklerin daha kolay takip edilmesine ve otomatik sürüm yönetim araçlarıyla uyumlu olmasına yardımcı olur.*

[anlamlı taahhüt](https://www.conventionalcommits.org/)

**Uzak Sunucu Listesini Gösterme**

```bash
git remote
```

**Uzak Sunucu Detaylarını Gösterme**

```bash
git remote -v
```

**Uzak Depo Bağlantısı:**

```bash
git remote add origin https://github.com/kullanici_adi/proje_adı.git
```

**Dal Yönetimi**

```bash
git branch <yeni_dal_adı>
```

**Dallar arasında geçiş yapmak**

```bash
git checkout <dal_adı>
```

**Uzak Depoya Yükleme**

```bash
git push origin <dal_adı>
```

**Değişiklikleri Çekme ve Birleştirme**

```bash
git pull origin <dal_adı>
```

**Durum Kontrolü:**

```bash
git status
```

**Yerel dalı uzak dal ile eşleştiren bir izleme**

```bash
git push --set-upstream origin feature-new
```

**Dalları Birleştirme / Entegre Etme**

```bash
git merge <kaynak_dalı>
```

**Hedef Dalı Seçme**

```bash
git checkout <hedef_dal>
```

**Birleştirmeyi Başlatma**

```bash
git merge <kaynak_dalı>
```

**Birleştirmeyi Onaylama**

```bash
git commit -m "<kaynak_dalından_değişiklikleri_birleştir>"
```

**Değişiklikleri Gönderme (gerekiyorsa)**:

```bash
git push origin <hedef_dal>
```

Git'in daha gelişmiş özellikleri ve komutları hakkında daha fazla bilgi edinmek için Git belgelerini incelemeniz faydalı olacaktır.

[Git - Reference](https://git-scm.com/docs)

---

**Ek Bilgiler**

Geliştirme ortamınızı hızlandırmak için ek araçlar kullanabilirsiniz.

[Gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

---

**Ek Uyarılar**

**Git çakışmaları** (conflicts), aynı dosyanın farklı dallarda veya farklı yerel kopyalarda farklı değişikliklerle düzenlendiği durumlarda ortaya çıkar. Bu tür çakışmaları çözmek için Git, manuel müdahale gerektiren durumları tespit eder. Genellikle çakışmalar, farklı kullanıcılar veya farklı dallarda çalışan geliştiricilerin aynı dosyayı düzenlediği durumlarda ortaya çıkar.

Çakışmaları çözmek için aşağıdaki adımları izleyebilirsiniz:

1. **Değişiklikleri Getir (Pull):** Önce uzak depodaki (örneğin GitHub'daki) en son değişiklikleri almak için çalışma dizininizdeki dalınızı güncelleyin. Bu, mevcut dalınızı güncellemek ve potansiyel çakışmaları en aza indirmek için önemlidir.
    
    ```bash
    git pull origin <dal_adı>
    ```
    
2. **Çakışmaları Tespit Et:** Bu adımı genellikle bir dal birleştirildiğinde veya değişikliklerinizle çakışma oluştuğunda yaparsınız. Çakışmalar, Git tarafından otomatik olarak tespit edilir ve ilgili dosyalarda işaretlenir. Bu dosyalara baktığınızda, çakışmaları görmelisiniz. Çakışmalar, genellikle aşağıdaki gibi işaretlenmiş satırlarla belirtilir:
    
    ```bash
    <<<<<<< HEAD
    // Burada sizin değişiklikleriniz
    =======
    // Burada uzak depodan gelen değişiklikler
    >>>>>>> <diğer_dal/ad>
    ```
    
3. **Çakışmaları Düzenle:** Çakışmaları çözmek için düzenlemeler yapmanız gerekecek. İhtiyacınıza bağlı olarak, hangi değişiklikleri almak istediğinizi belirlemelisiniz. Manuel olarak bu çakışmayı düzeltebilir veya değişiklikleri birleştirebilirsiniz.
4. **Dosyayı Kaydet ve İşaretle:** Çakışmaları çözdükten sonra, düzenlediğiniz dosyayı kaydedip işaretleyin.
5. **Commit Yapın:** Çakışmayı çözdüğünüzde ve değişiklikleri birleştirdiğinizde, düzeltilmiş dosyalarınızı bir commit ile kaydedin.
6. **Push Yapın:** Eğer çakışmayı çözdüğünüz dalı uzak sunucuya (örneğin GitHub'a) taşıyacaksanız, commit'leri uzak sunucuya göndermek için push komutunu kullanın.
7. **Dalı Birleştirin (Opsiyonel):** Eğer çakışmayı çözdüğünüz dalı başka bir dal ile birleştirmek isterseniz, bu adımı gerçekleştirin. Dal birleştirme işlemi çakışmaları daha da çözebilir veya yeni çakışmaları tetikleyebilir. Bu nedenle dikkatli olun.

Özetle, çakışmalar, aynı dosyanın farklı yerlerde farklı şekillerde değiştirildiğinde ortaya çıkar. Bu durumda, çakışmaları çözmek ve dosyayı düzgün bir şekilde birleştirmek için manuel müdahale gerekebilir. En iyi uygulama, düzenlemeleri dikkatlice kontrol etmek, gereksiz kodları temizlemek ve tüm değişiklikleri anlamlı bir şekilde birleştirmek olacaktır.
