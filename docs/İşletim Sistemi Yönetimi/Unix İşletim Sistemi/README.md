Orijinal Unix işletim sistemi temel alınarak geliştirilen ve özellikle sunucu sistemlerinde kullanılan bir işletim sistemi ailesidir. Birçok ticari ve açık kaynaklı Unix benzeri işletim sistemi bulunur.

![JupTWln_qjpPZ0.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a22b9796-64eb-48d0-ac8a-9afc266bc5ff/JupTWln_qjpPZ0.jpg)

**macOS:** Apple'ın Mac bilgisayarları için geliştirdiği işletim sistemidir. BSD tabanlı bir Unix çekirdeği kullanır ve Apple'ın özel donanım ve yazılım entegrasyonu ile tanınır.

!https://cdn.osxdaily.com/wp-content/uploads/2020/10/8-best-macos-big-sur-features-1.jpg

**Linux:** Özgür ve açık kaynaklı bir işletim sistemidir. Birçok farklı dağıtımı (Ubuntu, Fedora, Debian gibi) vardır ve çok çeşitli amaçlar için kullanılır. Sunucu sistemlerinden mobil cihazlara kadar geniş bir yelpazede kullanılır.

![R.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c7571b42-89bc-4aea-8806-78a881558c34/R.png)

**Linux**, Unix benzeri bir çekirdeğe dayanır. **Farklı dağıtımları** (Ubuntu, Fedora, Debian, CentOS gibi) vardır ve genellikle **özgür ve açık kaynaklıdır**. Linux, **hem masaüstü** **hem de sunucu** sistemleri için geniş bir kullanım alanına sahiptir.

Linux çekirdeğini incelemek yada kendi dağıtımlarınızı oluşturmak istiyorsanız, kernel arşivine bakabilirsiniz.

[The Linux Kernel Archives](https://www.kernel.org/)

- **Ubuntu**, *Debian dağıtımına dayalı* popüler bir Linux dağıtımıdır. Kullanıcı dostu olacak şekilde tasarlanmıştır ve Linux'u daha geniş bir kitleye erişilebilir hale getirmeyi amaçlar. Ubuntu, çeşitli **önceden yüklenmiş** yazılımlar ve **uygulamalar** içerir; genellikle **GNOME** adlı bir grafiksel masaüstü ortamı, üretkenlik araçları, web tarayıcıları ve daha fazlası. Ayrıca güvenliğe ve düzenli güncellemelere büyük önem verir. Ubuntu, **uzun süreli destek (LTS)** sürümleri ve düzenli sürümler sunar, farklı kullanıcı ihtiyaçlarını karşılar.

Linux, özgür yazılım felsefesini benimseyerek **herkesin kullanabileceği**, **inceleyebileceği**, **değiştirebileceği** ve **dağıtabileceği** bir işletim sistemi sunar. Bu sayede kullanıcılar daha fazla kontrol sahibi olabilirler ve yazılım geliştirmeye katkıda bulunabilirler.

---

**Nano**

Nano, basit ve kullanıcı dostu bir metin düzenleyicidir ve komut satırında çalışır. Linux sistemlerde **genellikle varsayılan metin düzenleyici** olarak gelir ve ayrıca ayrı bir şekilde yüklenebilir. Nano'nun kullanımı oldukça basittir. 

Başlatmak için bir terminal ekranı başlatın.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/59f1dca2-9ef4-4a22-b22c-467fba273840/Untitled.png)

 

Bu, Nano'yu başlatır ve boş bir sayfa açar.

```powershell
nano
```

**Nano metin düzenleyicisini kullanmak için komutla**r:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/f9da92e3-1871-4fd8-b080-ea4ad3ef9b96/Untitled.png)

1. Yardım Görüntülüme
    1. `**CTRL + G**` tuş kombinasyonu yardımı ile yardım içeriklerine oluşabilir ve nano ile ilgili tüm kısayol tuşlarını görüntüleyebilirsiniz.
    2. `**CTRL + X**` tuşlarına basın. Bu, editöre geri dönecektir.
2. Metni Düzenleme:
    1. Metni düzenlemek için klavyenizdeki karakterleri doğrudan girebilirsiniz.
3. Temel Hareket:
    1. Yukarı ve aşağı ok tuşlarıyla metni yukarı veya aşağı hareket ettirebilirsiniz.
    2. Sağ ve sol ok tuşlarıyla metni yatay olarak gezinebilirsiniz.
4. Kaydetme ve Çıkma
    1. Metinde yaptığınız değişiklikleri kaydetmek için **`Ctrl + O`** (büyük harf "O") tuşlarına basın ve ardından Enter tuşuna basın. **Bu, dosyanızı kaydedecektir**.
    2. Nano'dan çıkmak için **`Ctrl + X`** tuşlarına basın. Eğer dosyanızda değişiklikler yapılmışsa, Nano size çıkmadan önce dosyayı kaydetmek isteyip istemediğinizi soracaktır.
5. Dosya Açma ve Kaydetme
    1. Nano'yu belirli bir dosyayı düzenlemek için açmak için terminalde **`nano dosya_adı`** şeklinde komut kullanın. Örneğin, **`nano belge.txt`** ile "belge.txt" adlı bir dosyayı düzenleyebilirsiniz.
    2. Dosyayı farklı bir adla kaydetmek için **`Ctrl + O`** kullanın ve ardından yeni dosya adını girin.
    3. Dosyayı farklı bir adla kaydetmeden çıkmak için **`Ctrl + X`** tuşlarına basın.
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/899794ff-21d8-43c9-afd3-2deab6ebd75f/Untitled.png)
    

Bu temel komutlar, Nano'yu kullanmaya başlamak için yeterlidir. Klavye kısayolları, Nano'nun gücünü ve verimliliğini artıran önemli bir özelliktir. Kullanımı kolay olduğu için özellikle yeni başlayanlar için ideal bir metin düzenleyicidir.

---

**Linux Terminal Komutları**

Linux, güçlü bir **komut satırı** (terminal) arayüzü sunar. Terminal, metin tabanlı bir kullanıcı arayüzüdür ve birçok görevi komutlarla gerçekleştirmenizi sağlar. Temel komutlar arasında dosya yönetimi, paket yönetimi, sistem yapılandırması ve daha fazlası bulunur.

---

Linux terminal komutlarını denemek için aşağıdaki adımları izleyebilirsiniz:

**Terminal Açma**: İlk olarak, kullanıcı arabiriminin komut satırı bölümünü açmanız gerekiyor. Genellikle "Terminal" veya "Komut İstemi" gibi bir uygulama adı altında bulunur. Linux dağıtımınıza bağlı olarak, uygulama menüsünden veya arama çubuğundan erişebilirsiniz.

**Terminus**: 
****Bu platform, temel Linux terminal komutlarını interaktif bir şekilde öğrenmenize ve denemenize olanak tanır.

[Terminus](https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html)

**Docker Lab**:

Bu platform ücretsiz bir Alpine **Linux** Sanal Makinesine sahip olma deneyimi sunar. Kayıt işlemini gerçekleştirerek belirli bir oturum süresi boyunca bu platform üzerinde çalışmalar yapabilir ve başkaları ile de paylaşabilirsiniz.

[Play with Docker](https://labs.play-with-docker.com/)

---

**Temel Linux Terminal Bilgisi**

**Linux temel terminal komutları**, Linux tabanlı işletim sistemlerinde sık kullanılan komutlardır.

**`echo`**: Verilen metni terminale yazar.

```
echo "Merhaba dünya"
```

**`ls`**: Bir komutun kılavuz sayfasını görüntüler. Örnek olarak burada “**`ls`**” komutu için yardım bilgileri görüntülenecektir. “`h`” tuşu ile yardım konularına ulaşabilir yada “`q`” tuşu ile geri dönebilirsiniz.

```
man **ls**
```

---

**Dosya ve Dizin İşlemleri**

**`ls`**: Mevcut dizindeki dosyaları ve dizinleri listeler.

```bash
ls
```

**`cd`**: Dizinleri değiştirmek için kullanılır.

```bash
cd /home/kullanici/dosyalar
```

**`pwd`**: Şu anki çalışma dizinini gösterir.

```bash
pwd
```

`**touch**`: "`touch`" komutu, yeni bir dosya oluşturmak veya mevcut bir dosyanın değiştirilme tarihini güncellemek için kullanılır. Terminali açın ve aşağıdaki komutu kullanarak yeni bir dosya oluşturabilirsiniz:

```bash
touch yeni_dosya.txt
```

Bu komut, "yeni_dosya.txt" adında boş bir dosya oluşturur.

**`mkdir`**: Yeni bir dizin oluşturur.

```bash
mkdir yeni_dizin
```

**`cp`**: Dosya veya dizinleri kopyalar.

```bash
cp dosya.txt yeni_dosya.txt veya cp -r dizin yeni_dizin
```

**`mv`**: Dosya veya dizinleri taşır veya adlarını değiştirir.

```bash
mv dosya.txt /diger_dizin veya mv eski_ad yeni_ad
```

**`rm`**: Dosya veya dizinleri siler.

```bash
rm dosya.txt veya rm -r dizin
```

**`rmdir`**: Boş bir dizini siler.

```bash
rmdir dizin
```

**Dosya İşleme ve Metin Düzenleme**

Metin düzenleme için metin editörleri.

"nano" kullanarak:

```bash
nano yeni_dosya.txt
```

Bu komut, "nano" metin düzenleyiciyi başlatır ve "yeni_dosya.txt" adlı yeni bir dosya açar. Düzenlemeyi tamamladıktan sonra "Ctrl + O" tuş kombinasyonu ile kaydedebilir ve "Ctrl + X" ile çıkabilirsiniz.

"vim" kullanarak:

```bash
vim yeni_dosya.txt
```

Bu komut, "vim" metin düzenleyiciyi başlatır ve "yeni_dosya.txt" adlı yeni bir dosya açar. Düzenlemeyi tamamladıktan sonra "Esc" tuşuna basın, ardından ":wq" yazıp "Enter" tuşuna basarak kaydedebilir ve çıkabilirsiniz.

**`cat`**: Bir dosyanın içeriğini terminale yazar.

```bash
cat dosya.txt
```

**`grep`**: Bir metin dosyasında belirli bir metni arar.

```bash
grep "arama_metni" dosya.txt
```

**`less`**: Dosyanın içeriğini sayfa sayfa görüntüler.

```bash
less dosya.txt
```

“`q`” tuşu yardımı ile çıkış yapabilirsiniz.

**`head`**: Dosyanın başlangıcındaki belirli sayıda satırı görüntüler.

```bash
head -n 10 dosya.txt
```

**`tail`**: Dosyanın sonundaki belirli sayıda satırı görüntüler.

```
tail -n 5 dosya.txt
```

---

**Dosya İzinleri**

**Kullanıcılar için izinleri değiştirme:** "`chmod`" (kullanıcılar için izinleri değiştirme) Linux ve Unix tabanlı işletim sistemlerinde kullanılan bir komuttur. Bu komut, dosya veya dizinlerin **izinlerini değiştirmenizi** sağlar. İzinler, bir dosyanın veya dizinin **kimin tarafından** okunabilir, yazılabilir veya çalıştırılabilir olduğunu belirler. Bu komut, **temel olarak üç grup**tan oluşan izinleri değiştirmenize yardımcı olur: kullanıcı (user), grup (group) ve diğer (others).

1. **Kullanıcı (User) İzinleri:** Dosya veya dizini oluşturan veya sahibi olan kullanıcıya ait izinlerdir. Kullanıcı, dosya veya dizini değiştirme veya silme iznine sahip olabilir.
2. **Grup (Group) İzinleri:** Dosya veya dizini oluşturan kullanıcının ait olduğu grup üyelerinin izinlerini temsil eder. Diğer grup üyeleri, bu izinlere sahip olabilir.
3. **Diğer (Others) İzinleri:** Dosya veya dizine erişim izni verilen diğer tüm kullanıcıları temsil eder. Yani dosyanın sahibi veya grup üyesi olmayan kullanıcılar için geçerlidir.

"**izinler**" alanı, dosya veya dizinin izinlerini temsil eden bir dizedir. Genellikle **rakamlarla** ifade edilir ve 3 haneli bir sayıdır (örneğin, 755 veya 644 gibi). Her hane, **sırasıyla** kullanıcı, grup ve diğer kullanıcıların izinlerini belirtir.

```
chmod 755 dosya.txt
```

Bu komut, "dosya.txt" adlı dosyanın **kullanıcıya (sahip)** **okuma, yazma ve çalıştırma izinlerini** (7), grup üyelerine **okuma ve çalıştırma** izinlerini (5) ve diğer kullanıcılara **sadece okuma iznini** (5) verir.

Bir dizinin izinlerini değiştirmek için:

```bash
chmod 644 works/

```

Bu komut, "dizin" adlı dizinin kullanıcıya **okuma ve yazma izinlerini** (6), grup üyelerine sadece **okuma** iznini (4) ve diğer kullanıcılara **sadece okuma** iznini (4) verir.

Rakamsal temsilini daha iyi anlamanıza yardımcı olacak bir liste aşağıda verilmiştir:

- 0: İzin yok (---
- 1: Yürütme izni (execute --x)
- 2: Yazma izni (-w-)
- 3: Yazma ve yürütme izni (-wx)
- 4: Okuma izni (r--)
- 5: Okuma ve yürütme izni (r-x)
- 6: Okuma ve yazma izni (rw-)
- 7: Tüm izinler (rwx)

---

**Paket Yönetimi** 

**`apt-get`**, Debian tabanlı Linux dağıtımlarında (örneğin, Ubuntu) paket yönetimi işlemleri için kullanılan bir komuttur. Bu komut, paketlerin yüklü olup olmadığını kontrol etmek, yeni paketleri yüklemek, mevcut paketleri güncellemek, paketleri kaldırmak ve diğer paket yönetimi görevlerini gerçekleştirmek için kullanılır.

İşte **`apt-get`** komutunu kullanarak sıkça kullanılan bazı işlemler:

**Paket Güncelleme:** Mevcut paket veritabanını güncellemek ve sistemdeki tüm paketleri güncellemek için:

```bash
sudo apt-get update
sudo apt-get upgrade
```

İlk komut, paket veritabanını günceller ve ikincisi güncellenebilir paketleri yükler.

**`*apt-get update`** komutu paket veritabanını güncellerken, **`apt-get upgrade`** komutu yüklü paketleri günceller. Bu iki komutu bir arada kullanarak, sisteminizin güncel ve güvenli olmasını sağlayabilirsiniz. İlk olarak **`apt-get update`** ile paket veritabanını güncelleyin ve ardından **`apt-get upgrade`** ile mevcut paketleri güncelleyin.*

**Paket Araştırma:** Bir paketi aramak ve bilgi almak için:

```bash
sudo apt-cache search aranacak_kelime
sudo apt-cache show paket_adı
```

İlk komut, "aranacak_kelime" ile eşleşen paketleri listeler ve ikincisi belirli bir paket hakkında ayrıntılı bilgi sağlar.

Örneğin:

```bash
sudo apt-cache search http
```

```bash
sudo apt-cache show curl
```

**Yeni Paket Yükleme:** Yeni bir paketi yüklemek için:

```bash
sudo apt-get install paket_adı
```

"paket_adı" kısmını yüklemek istediğiniz paketin adıyla değiştirin.

**Paket Kaldırma:** Bir paketi kaldırmak için:

```bash
sudo apt-get remove paket_adı
```

"paket_adı" kısmını kaldırmak istediğiniz paketin adıyla değiştirin.

**Paket Temizleme:** Önbellekte (cache) tutulan paketleri temizlemek için:

```bash
sudo apt-get clean
```

Bu komut, önbellekteki tüm paketleri siler.

**`*sudo apt-get clean`** komutunun kullanılmasının bazı nedenleri : **Disk Alanını Geri Kazanma, Güvenlik, Yedekleme, Düzenlilik***

**Paket Bağımlılıklarını Çözme:** Eksik paket bağımlılıklarını otomatik olarak çözmek için:

```bash
sudo apt-get -f install
```

Bu komut eksik bağımlılıkları yükler veya düzeltir.

**`*apt-get`** komutu, Linux sistemlerinde yazılım yönetimi ve güncelleme işlemlerini hızlı ve etkili bir şekilde gerçekleştirmenize olanak tanır. Sistem yönetimi için önemli bir araçtır ve çoğu Debian tabanlı dağıtımın bir parçasıdır.*

---

**Kullanıcı Yönetimi**

Mevcut kullanıcı **bilgilerini** ve kullanıcının ait olduğu grupları **görüntülemek** için **`id`** komutunu kullanabilirsiniz. Bu komut, kullanıcının **kimlik bilgilerini ve grup üyeliklerini** ayrıntılı bir şekilde gösterir. Terminali açın ve aşağıdaki komutu kullanarak bu bilgilere erişebilirsiniz:

```bash
id
```

Bu komut, kullanıcının adını (uid), grup adını (gid) ve kullanıcının ait olduğu ek grupları (groups) gösterir. Örnek bir çıktı aşağıdaki gibi görünebilir:

```bash
uid=1000(kullanici_adi) gid=1000(kullanici_adi) groups=1000(kullanici_adi),4(adm),27(sudo),30(dip),46(plugdev),113(lpadmin),128(sambashare)

```

Bu çıktıda:

- **`uid`** kullanıcının **kimlik numarası**nı (User ID) temsil eder.
- **`gid`** kullanıcının **varsayılan grup** kimlik numarasını (Primary Group ID) temsil eder.
- **`groups`** ise kullanıcının ait olduğu **tüm grupları** listeler.

Özellikle **`groups`** bölümü, kullanıcının ait olduğu diğer grupları gösterir. Bu, kullanıcının **birden fazla gruba üye olduğu durumlarda** faydalıdır.

**Yeni bir kullanıcı oluşturma**

Yeni bir kullanıcı oluşturmak için aşağıdaki komutu kullanabilirsiniz. Burada "yeni_kullanici"yi oluşturmak istediğiniz kullanıcı adıyla değiştirin:

```bash
sudo adduser yeni_kullanici
```

Komutu çalıştırdığınızda, size yeni kullanıcı için bir şifre belirlemeniz ve bazı **ek kullanıcı bilgileri**ni girmeniz istenecektir.

1. **Kullanıcı Adı (Username):** Eklemek istediğiniz kullanıcının adını girmeniz istenir. Bu kullanıcı adı, kullanıcının kimliğini belirler.
2. **Şifre (Password):** Kullanıcının hesabına erişmek için kullanacağı şifreyi girmeniz gerekir. Şifre güvenli ve karmaşık olmalıdır.
3. **Tam Ad (Full Name):** Kullanıcının gerçek adını veya tam adını girmeniz istenir. Bu bilgi kullanıcının profiline eklenir.
4. **Oda Numarası (Room Number):** Kullanıcının iş yerindeki fiziksel oda numarasını girmeniz istenir. Bu alan genellikle gereksizdir ve boş bırakılabilir.
5. **Telefon (Phone):** Kullanıcının iş telefon numarasını girmeniz istenir. Bu da genellikle gereksizdir ve boş bırakılabilir.
6. **Diğer Bilgiler (Other Information):** İşlemi tamamlamak için kullanabileceğiniz başka bilgiler veya notlar eklemek için bir metin alanı sağlanır. Bu da genellikle boş bırakılır.
7. **Kullanıcının Grupları (User groups):** Kullanıcının ait olacağı grupları seçmeniz istenebilir. Örneğin, "sudo" grubuna ekleyerek kullanıcıya yönetici yetkileri verebilirsiniz.
8. **Verilen Bilgilerin Doğrulanması (Is the information correct?):** Tanımlanan bilgilerin doğru olup olmadığını onaylamanız istenebilir.

**Kullanıcıya Oturumu Açın:** Kullanıcı oluşturulduğunda, yeni kullanıcı adını ve şifresini kullanarak oturumu açabilir. Bu yeni kullanıcı, kendi ev dizini ve kullanıcı bağlamı ile bir oturum açacaktır.

```bash
sudo su - yeni_kullanıcı_adı
```

**Kullanıcı İlgili Gruplara Ekleyin :** Yeni kullanıcıyı, ihtiyaçlarınıza göre ilgili gruplara ekleyebilirsiniz. Örneğin, "**sudo**" grubuna ekleyerek bu kullanıcının **yönetici** (sudo) yetkilerine sahip olmasını sağlayabilirsiniz:

```bash
sudo usermod -aG sudo yeni_kullanici
```

Bu komut, "yeni_kullanici" adlı kullanıcıyı "sudo" grubuna ekler.

**Yeni gruplar oluşturmak**

Yeni bir grup oluşturmak için "`groupadd`" komutunu kullanabilirsiniz. Aşağıdaki komutu kullanarak yeni bir grup oluşturabilirsiniz:

```bash
sudo groupadd yeni_grup
```

Yukarıdaki komutu kullanırken "yeni_grup" kısmını oluşturmak istediğiniz grup adıyla değiştirin. Bu komut, yeni bir grup oluşturur ve varsayılan olarak grup adı "yeni_grup" olarak atanır.

*Grup oluşturma işlemi tamamlandığında herhangi bir çıktı almayabilirsiniz, ancak grup başarıyla oluşturulmuş olacaktır.*

**Grup Bilgilerini Kontrol Etme:** Grubun başarıyla oluşturulup oluşturulmadığını doğrulamak için aşağıdaki komutu kullanabilirsiniz:

```bash
cat /etc/group | grep yeni_grup
```

Bu komut, grupların bulunduğu "/etc/group" dosyasını **kontrol eder** ve oluşturduğunuz yeni grubun **adını arar**. Eğer grup başarıyla oluşturulduysa, grup adını ve grup kimlik numarasını görmelisiniz.

**Kullanıcı Hesaplarını ve Grupları Görüntüleme:** İlk olarak, sistemdeki mevcut kullanıcı hesaplarını ve grupları görüntülemek için aşağıdaki komutları kullanabilirsiniz:

- Kullanıcı hesaplarını listelemek için:
    
    ```bash
    cat /etc/passwd
    ```
    
    ```bash
    grep "kullanıcı_adı" /etc/passwd
    ```
    
- Grupları listelemek için:
    
    ```bash
    cat /etc/group
    ```
    
    ```bash
    grep "kullanıcı" /etc/group
    ```
    

*NOT: "`usermod`" ve "`groupmod`" komutları, tipik olarak Linux veya Unix tabanlı bir işletim sistemi terminalinde kullanılabilir ve kullanıcılar ve gruplar hakkında bilgi verir. Bu komutları kullanmak için genellikle `root` veya `sudo` yetkisine sahip bir kullanıcı olarak **oturum açmanız** gerekebilir, çünkü bu komutlar sistem düzeyinde değişiklik yapabilirler.*

**Ek Sistem Bilgileri**

"`visudo`" komutu, Linux sistemlerinde sudoers dosyasını düzenlemek için güvenli bir metin düzenleyiciyi açar. Sudoers dosyası, **kimin hangi komutları sudo (superuser do) yetkileri ile çalıştırabileceğini** belirleyen önemli bir sistem dosyasıdır. Bu dosyayı düzenlerken dikkatli olmalısınız, çünkü yanlış bir düzenleme sisteminizi kullanılamaz hale getirebilir.

**`visudo`** komutunu kullanarak sudoers dosyasını düzenlemek için aşağıdaki adımları izleyebilirsiniz:

1. Terminali açın: Bir terminal penceresi açın. Bu işlemi "Ctrl + Alt + T" tuş kombinasyonu veya uygulama menüsünden yapabilirsiniz.
2. **`visudo`** komutunu çalıştırın: Aşağıdaki komutu kullanarak sudoers dosyasını düzenlemek için **`visudo`** komutunu çalıştırın. Bu komutu çalıştırdığınızda, sudoers dosyası varsayılan bir metin düzenleyici olan "nano" veya "vim" ile açılacaktır. Hangi düzenleyiciyi kullanacağınız sistem yapılandırmasına bağlıdır.
    
    ```bash
    sudo visudo
    ```
    
    Eğer sistem "nano" düzenleyiciyi kullanıyorsa, düzenlemeyi yapmak için talimatları takip edebilirsiniz. "vim" düzenleyici kullanılıyorsa, "i" tuşuna basarak düzenleme moduna geçip düzenlemelerinizi yapabilir ve ardından "Esc" tuşuna basarak düzenleme modundan çıkabilirsiniz.
    
3. Sudoers dosyasını düzenleyin: Sudoers dosyası, kullanıcıların ve grupların sudo yetkilerini belirlemek için **özel bir sözdizimine** sahiptir. Düzenlemelerinizi yaparken, doğru sözdizimine ve kurallarına dikkat etmelisiniz.
4. Değişiklikleri kaydedin ve düzenleyiciyi kapatın: Düzenlemeleri tamamladıktan sonra, **`visudo`** düzenleyicisini kaydedip kapatmak için genellikle aşağıdaki adımları izlersiniz:
    - "nano" kullanıyorsanız:
        - **`Ctrl + O`** tuş kombinasyonuyla kaydet
        - Enter tuşuna basarak onayla
        - **`Ctrl + X`** tuş kombinasyonuyla düzenleyiciyi kapat
    - "vim" kullanıyorsanız:
        - **`Esc`** tuşuna basarak düzenleme modundan çıkın.
        - **`:wq`** yazın ve Enter tuşuna basarak kaydedin ve çıkın.
5. Düzenleme işlemi tamamlandığında, sudoers dosyası güncellenmiş olacaktır. Artık sudo komutlarını kullanırken yeni yetkilendirmelerinizi veya düzenlemelerinizi kullanabilirsiniz.

**Kullanıcıyı Sudo Yetkileri ile Ekleme**

Linux sistemlerinde bir kullanıcıya sudo yetkileri eklemek, o kullanıcının root (yönetici) benzeri yetkilerle komutları çalıştırmasına olanak tanır. Sudo yetkileri, sistem yönetimi ve güvenlik açısından önemlidir. İşte bir kullanıcıya sudo yetkileri eklemek için adım adım nasıl yapılacağına dair bir rehber:

1. **Root Yetkileri ile Giriş Yapın:** Sudo yetkilerini düzenlemek için, sisteme root (yönetici) yetkileriyle giriş yapmanız gerekebilir. Bunun için terminali açın ve aşağıdaki komutu kullanarak root kullanıcısına geçiş yapın:
    
    ```bash
    sudo su -
    ```
    
    Bu komut, root kullanıcısına geçiş yapmanızı sağlar. Root şifresini girmeniz istenebilir.
    
2. **Sudoers Dosyasını Düzenleyin:** Kullanıcılara sudo yetkileri vermek için "sudoers" dosyasını düzenlemeniz gerekir. **`visudo`** komutu ile bu dosyayı güvenli bir şekilde düzenleyebilirsiniz:
    
    ```bash
    visudo
    ```
    
    Bu komut, "sudoers" dosyasını açar ve düzenlemeyi yapmanıza olanak tanır.
    
3. **Kullanıcıya Sudo Yetkileri Ekleyin:** "sudoers" dosyasını düzenledikten sonra, kullanıcıya sudo yetkilerini eklemek için aşağıdaki satırı ekleyin:
    
    ```bash
    kullanici_adi ALL=(ALL:ALL) ALL
    ```
    
    Yukarıdaki satırda:
    
    - **`kullanici_adi`**: Sudo yetkileri eklemek istediğiniz kullanıcının adını yazın.
    - **`ALL=(ALL:ALL)`**: Bu bölüm, kullanıcının **hangi bilgisayarlar üzerinde** ve **hangi kullanıcılar adına** sudo yetkilerini kullanabileceğini belirtir. Genellikle bu şekilde bırakılır.
    - **`ALL`**: Bu kısım, kullanıcının hangi komutları çalıştırabileceğini belirtir. "ALL" yazarak kullanıcının tüm komutları çalıştırmasına izin verirsiniz.
    
    Örnek olarak, kullanıcı adı "azmi" olan bir kullanıcıya sudo yetkileri eklemek istiyorsanız:
    
    ```bash
    azmi ALL=(ALL:ALL) ALL
    ```
    
4. **Düzenlemeyi Kaydedin ve Çıkın:** Düzenleme işlemini tamamladıktan sonra, düzenleyiciyi kaydetmek ve kapatmak için metin düzenleyici komutları kullanın (genellikle **`Ctrl + O`** ve **`Ctrl + X`**).
5. **Kullanıcıyı Sistemden Çıkış Yapın:** Root kullanıcısından çıkış yapmak için aşağıdaki komutu kullanın:
    
    ```bash
    exit
    ```
    
6. **Yeniden Giriş Yapın:** Kullanıcıya yeni sudo yetkileri eklediyseniz, bu değişiklikleri kullanabilmek için kullanıcı adınızla tekrar oturum açın. Artık sudo komutları kullanabilirsiniz.

---

**Sistem Bilgisi ve İzleme**

**`ps`**, Unix ve Unix benzeri işletim sistemlerinde (Linux dahil) **çalışan işlemleri görüntülemek** için kullanılan bir komuttur. "`ps`" komutu, sistemdeki çalışan işlemler hakkında bilgi almanızı sağlar. Bu komut, bir terminal penceresinde kullanılarak çalışan işlem listesini görüntülemenize olanak tanır.

"`ps`" komutunun temel kullanımı şu şekildedir:

```bash
ps [seçenekler]
```

Birçok farklı seçenek kullanarak "`ps`" komutunu özelleştirebilirsiniz. İşte yaygın olarak kullanılan bazı seçenekler:

- **e:** Tüm işlemleri gösterir.
- **f:** Tam ayrıntılarla işlemleri gösterir.
- **l:** Uzun formatlı çıktı sağlar.
- **a:** Tüm kullanıcıların işlemlerini gösterir.
- **u:** Belirli bir kullanıcının işlemlerini gösterir.
- **x:** Kontrol terminaline bağlı olmayan işlemleri de gösterir.

Örnekler:

1. Tüm işlemleri görmek için:
    
    ```bash
    ps -e
    
    ```
    
2. Belirli bir kullanıcının işlemlerini görmek için:
    
    ```
    ps -u kullanici_adi
    ```
    
3. Uzun formatlı çıktı almak için:
    
    ```bash
    ps -l
    ```
    

Bu komutlar, **işlem izleme, hata ayıklama ve sistem performansını anlama** gibi birçok senaryoda faydalıdır. Özellikle sistemdeki işlemlerin durumu, kaynak kullanımı ve hata ayıklama amaçları için kullanışlıdır. "ps" komutunun daha fazla seçeneği ve kullanımı için "man ps" komutunu kullanarak komut belgelerine erişebilirsiniz.

"`kill`" komutu, Unix ve Unix benzeri işletim sistemlerinde çalışan işlemleri **sonlandırmak** veya **sinyal göndermek** için kullanılan bir komuttur. Genellikle, bir işlemi sonlandırmak veya belirli bir sinyal göndermek için kullanılır.

"`kill`" komutunun temel kullanımı şu şekildedir:

```bash
kill [seçenekler] işlem_IDleri
```

- "seçenekler" komutun davranışını özelleştirmenize olanak tanır.
- "işlem_IDleri", sonlandırmak veya sinyal göndermek istediğiniz işlemlerin kimlik numaralarını temsil eder.

Yaygın olarak kullanılan "kill" komutu seçeneklerinden bazıları şunlardır:

- **TERM veya -15:** Bu, işlemi normal şekilde sonlandırır. İşlem, sonlandırma sinyali aldığında düzenli bir şekilde kapatılır.
- **KILL veya -9:** Bu, işlemi zorla sonlandırır. İşlem derhal sonlandırılır ve işlemi kapatma fırsatı verilmez.
- **HUP veya -1:** Bu, işlemi SIGHUP sinyali ile sonlandırır. Birçok daemon işlemi yeniden başlatmak veya yeniden yapılandırmak için bu sinyali kullanır.
- **STOP veya -19:** Bu, işlemi duraklatır. İşlem çalışmıyor gibi görünür ve daha sonra "CONT" sinyali ile devam edebilir.
- **CONT veya -18:** Bu, duraklatılmış bir işlemi devam ettirir.

Örnekler:

Bir işlemi ID'si kullanılarak sonlandırmak için:

```bash
kill -TERM 12345
```

Bir işlemi PID'si (Process ID) kullanarak zorla sonlandırmak için:

```bash
kill -KILL 6789

```

Bir işlemi adı veya işlem grubu adıyla sonlandırmak için:

```
pkill -TERM uygulama_adı
```

Lütfen "kill" komutunu kullanırken dikkatli olun, çünkü işlemi zorla sonlandırmak bazı veri kaybına veya istenmeyen sonuçlara neden olabilir. Genellikle, işlemi normal bir şekilde sonlandırmak için önce "`TERM`" sinyali göndermek daha iyidir.

**Sistem günlükler**ini kontrol etmek ve özel bir hata mesajı veya uyarı bulmak için aşağıdaki komutları kullanabilirsiniz:

```bash
sudo journalctl -xe
```

*Bu komut sistem günlüklerini listeleyecektir.*

**Hizmeti Başlatma:**

```bash
sudo systemctl start XXX
```

**Hizmeti Yeniden Başlatma:**

```bash
sudo systemctl restart XXX
```

**Hizmeti Aktifleştirme:**

```bash
sudo systemctl enable XXX
```

**Hizmetin Durumunu Kontrol Etme**

```bash
sudo systemctl status XXX
```

…

---

**Dosya Sıkıştırma ve Arşivleme**

"`tar`" (tape archive) komutu, Linux ve Unix tabanlı işletim sistemlerinde dosya ve dizinlerin **sıkıştırılması**, **arşivlenmesi** ve **açılması** için kullanılan bir komuttur. "`tar`" komutu sıklıkla yedekleme, dosya paylaşımı ve dosya arşivleme işlemlerinde kullanılır.

Temel "tar" komutları ve kullanımları şunlardır:

1. **Arşiv Oluşturma (tarball oluşturma):**
    
    ```
    tar -cvf arsiv_adı.tar dosya1 dosya2 dizin1
    ```
    
    - **`c`**: Arşiv oluştur.
    - **`v`**: İşlemi ayrıntılı olarak göster (isteğe bağlı).
    - **`f`**: Arşiv adını belirt.
2. **Arşivi Sıkıştırma (gzip ile):**
    
    ```
    tar -czvf arsiv_adı.tar.gz dosya1 dosya2 dizin1
    ```
    
    - **`z`**: gzip sıkıştırması uygula.
    - Diğer bayraklar aynıdır.
3. **Arşivi Sıkıştırma (bzip2 ile):**
    
    ```
    tar -cjvf arsiv_adı.tar.bz2 dosya1 dosya2 dizin1
    ```
    
    - **`j`**: bzip2 sıkıştırması uygula.
    - Diğer bayraklar aynıdır.
4. **Arşivi Açma (tarball açma):**
    
    ```
    tar -xvf arsiv_adı.tar
    ```
    
    - **`x`**: Arşivi aç.
    - Diğer bayraklar aynıdır.
5. **Arşivi Sıkıştırıp Açma (gzip ile):**
    
    ```
    tar -xzvf arsiv_adı.tar.gz
    ```
    
    - **`z`**: gzip sıkıştırmasını aç.
    - Diğer bayraklar aynıdır.
6. **Arşivi Sıkıştırıp Açma (bzip2 ile):**
    
    ```
    tar -xjvf arsiv_adı.tar.bz2
    ```
    
    - **`j`**: bzip2 sıkıştırmasını aç.
    - Diğer bayraklar aynıdır.
7. **Arşiv İçeriğini Listeleme:**
    
    ```
    tar -tvf arsiv_adı.tar
    ```
    
    - **`t`**: Arşiv içeriğini listele.
    - Diğer bayraklar aynıdır.
8. **Belirli Bir Dizin İçeriğini Arşive Ekleme:**
    
    ```
    tar -rvf arsiv_adı.tar yeni_dizin/
    ```
    
    - **`r`**: Arşive ekleme işlemi.
    - Diğer bayraklar aynıdır.

*Bu temel "tar" komutları, dosya ve dizinlerin arşivlenmesi, sıkıştırılması ve açılmasında kullanılır. İhtiyacınıza göre bu komutları kullanarak farklı işlemler gerçekleştirebilirsiniz.*

---

**Ağ Komutları**

**ping:** Bir sunucuya veya cihaza erişilebilirliği kontrol etme.

```bash
ping google.com
```

**ip:** Ağ bağlantılarını yapılandırma ve ağ bilgilerini görüntüleme.

```bash
ip address
```

**ssh:** Uzak sunuculara güvenli bir şekilde bağlanma.

```bash
ssh google.com
```

*Daha detaylı ağ komutları için* **Linux Terminal Komutları - Ağ Yapılandırması** *konsunu inceleyiniz.*

---

**Linux Ağ Yapılandırması**

Linux'ta temel ağ yapılandırmasını gerçekleştirmek için ağ bağlantılarını yapılandırmak, IP adresleri ayarlamak, ağ arayüzlerini kontrol etmek ve DNS yapılandırmalarını yapmak gibi adımlar bulunur. 

---

**Temel Ağ Kavramlarını Anlama**

Ağ, IP adresleri, alt ağlar, DNS (Domain Name System) gibi temel ağ kavramlarını anlamak önemlidir.

**Ağ** : Bilgisayarlar ve diğer cihazlar arasındaki iletişimi sağlayan bağlantılı bir sistemdir. Ağlar, veri paylaşımı, iletişim, kaynak paylaşımı ve diğer birçok işlev için kullanılır.

**IP Adresi** : IP  adresleri, bilgisayarların veya diğer ağ cihazlarının **birbirleriyle iletişim kurmak için** kullandığı **benzersiz tanımlayıcı numaralar**dır. IPv4 (32 bitlik) ve IPv6 (128 bitlik) olmak üzere iki ana türü vardır.

**Alt Ağ**: Büyük bir IP adresi aralığını **daha küçük, yönetilebilir alt gruplara bölmek için** kullanılır. Bu, ağ trafiği yönlendirmeyi ve ağ yönetimini kolaylaştırır.

**DNS (Domain Name System)**: DNS, insanlar için anlaşılabilir **alan adlarını** (örneğin, **[www.example.com](http://www.example.com/)**) **IP adreslerine çeviren bir hizmet**tir. İnternet üzerindeki cihazlar, DNS aracılığıyla birbirlerini bulurlar.

**MAC Adresi (Media Access Control Address)**: Her ağ kartına veya ağ arabirimine **özgü** olan bu **adresler**, cihazların yerel ağda birbirlerini **tanımalarına** yardımcı olur. Genellikle **donanımsal** bir adres olarak kabul edilir.

**Router (Yönlendirici)**: Ağ trafiğini **farklı ağlar veya alt ağlar arasında yönlendiren cihazlar**dır. İnternet erişim noktanızdaki yönlendirici, ev veya iş ağınızı internetle bağlar.

**Switch (Anahtarlayıcı)**: Switchler, ağdaki cihazlar arasındaki **veri iletimini kolaylaştırmak için** kullanılır. MAC adreslerine dayalı olarak **veri paketlerini doğrudan hedef cihaza** ileten cihazlardır.

**Firewall (Güvenlik Duvarı)**: Güvenlik duvarları, **ağa gelen ve ağdan çıkan trafiği kontrol etmek**, izin vermek veya engellemek için kullanılır. Ağ güvenliği için önemlidirler.

**Port**: Portlar, ağ trafiğini belirli bir uygulamaya veya hizmete yönlendiren numaralardır. Örneğin, HTTP trafiği için 80 numaralı port kullanılır.

**Gateway (Ağ Geçidi)**: Ağdaki cihazların **dış dünya ile iletişim kurmasını sağlayan bir geçit**tir. Genellikle yönlendirici olarak görev yapar.

---

**Ağ Arabirimlerini Yönetme**

Linux'ta ağ arabirimlerini kontrol etmek için **`ifconfig`** veya **`ip`** komutları kullanılır.

**Ağ Arabirimlerini Listeleme**

```bash
ip addr show
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/3acb2765-fcb5-4067-99ce-0ca72dd3b925/Untitled.png)

**Ağ Arabirimi Durumunu Kontrol Etme**

```bash
ip addr show eth0
```

Genelde “UP” gib bir çıktı ile karşılaşırsınız.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/5e78b35b-03d3-414e-a465-6777505ae28b/Untitled.png)

---

**Ağ Arabirimi Durumunu Etkinleştirme/Devre Dışı Bırakma**

Ethernet bağlantılarını etkinleştirme, devre dışı bırakma, IP adresi atama ve ağ durumunu kontrol etme gibi işlemler.

Ağ arabirimini etkinleştirmek veya devre dışı bırakmak için **`ifup`** ve **`ifdown`** komutlarını kullanabilirsiniz:

```bash
sudo ifup eth0   # Arabirimi etkinleştirme
sudo ifdown eth0 # Arabirimi devre dışı bırakma
```

“*command not found”* hatası alıyorsanız, *Ubuntu 20.04 ve sonraki sürümlerinde **`ifconfig`** komutu yerine **`ip`** komutunu kullanmanız önerilir. **`ifconfig`** komutu yerine **`ip`** komutunu kullanarak ağ arayüzlerini yönetebilirsiniz.*

yada gerekli kurulumları kontrol edebilirsiniz.

```bash
sudo apt list --installed | grep ifup
```

```bash
sudo apt-get install ifupdown
```

Herhangi bir kurulum gözlemlemiyorsanız. ifupdown ı kurabilirsiniz.

*Ancak, gerektiğinde **`net-tools`** paketini yükleyerek **`ifconfig`** komutunu kullanabilirsiniz. Bu paketi yüklemek için aşağıdaki komutları kullanabilirsiniz:*

```bash
sudo apt update
sudo apt install net-tools
```

*Ancak, uzun vadede, Linux topluluğu daha modern ve güçlü bir ağ yönetim aracı olarak **`ip`** komutunu tercih etmektedir. Dolayısıyla, **`ip`** komutunu kullanmayı öğrenmek ve alışkanlık haline getirmek daha iyi bir seçenek olabilir.*

**Ağ Arayüzlerini Listeleme:**

```bash
ip link show
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/76347c53-2736-486f-aa91-82229a6ec636/Untitled.png)

**Ağ Arayüzünü Etkinleştirme:**

```bash
sudo ip link set eth0 up
```

*Komutunu uyguladığınızda herhangi bir çıktı almadıysanız, bu genellikle komutun başarıyla tamamlandığı anlamına gelir. Linux komutları genellikle bir çıktı üretmezlerse işlemin başarıyla gerçekleştiği kabul edilir.*

Bu komut, **`eth0`** adlı ağ arayüzünü etkinleştirir. Eğer bir hata veya problem olsaydı, komut hata mesajı üretirdi.

Eğer **`ip link show eth0`** komutunu kullanarak **`eth0`** ağ arayüzünün durumunu kontrol ederseniz, ağ arayüzünün etkinleştirildiğini görebilirsiniz. Örnek kullanım:

```bash
ip link show eth0
```

Bu komutun çıktısında, ağ arayüzünün durumu (**`UP`** veya **`DOWN`**) ve diğer bilgiler görüntülenecektir.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/6513577b-9345-4a1d-9075-b45a8df0c949/Untitled.png)

**Ağ Arayüzünü Devre Dışı Bırakma:**

```bash
sudo ip link set eth0 down
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/8cf43364-e33e-4026-b862-34f00f21894b/Untitled.png)

**IP Adresi ve Subnet Mask Eklemek:**

```bash
sudo ip address add 192.168.1.100/24 dev eth0
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/2fbdc0cd-51e2-468b-b933-2a1a80bdc03e/Untitled.png)

**IP Adresini Kaldırmak:**

```bash
sudo ip address del 192.168.1.100/24 dev eth0
```

**Ağ Arayüzünün Durumunu Gösterme:**

```bash
ip link show eth0
```

Terminal komut arabirimlerinde yapılan işlemlerinin, ubuntu arayüzündeki görünümü

![ubuntu-network-ethernet.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/790b2e2c-2ba2-454a-a59e-0c1c3655800b/ubuntu-network-ethernet.png)

**Ağ Yapılandırma Değişikliklerini Uygulama**

Ağ yapılandırma değişikliklerini uygulamak için ağı yeniden başlatın:

```bash
sudo systemctl restart networking
```

*“Not: docker lab gibi platformlarda test editorsanız, `systemctl` komutu bulunmayabilir.”*

Ubuntu 20.04 ve sonrası sürümlerinde, ağ hizmet yönetimi genellikle NetworkManager veya systemd-networkd gibi araçlar aracılığıyla yapılır. Bu nedenle **`networking`** servisini yeniden başlatmak yerine, ilgili hizmet aracını kullanmanız gerekebilir.

Eğer NetworkManager kullanıyorsanız:

```bash
sudo systemctl restart NetworkManager
```

*Genelde bu komut bir çıktı üretmeyecektir.*

Yönlendirme tablosunu görüntüleme:

```bash
ip route show
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/547ceda2-56c4-4c51-9a83-381dc613a860/Untitled.png)

*Linux tabanlı sistemlerde geçerli olan yönlendirme tablosunu görüntüler. Bu komut, sistemdeki ağ trafiğinin nasıl yönlendirildiğini ve nereye gittiğini gösterir.*

Çıktı, aşağıdaki gibi bir formatta görünebilir:

```scss
default via 192.168.1.1 dev eth0
192.168.1.0/24 dev eth0 proto kernel scope link src 192.168.1.100
```

Bu çıktı, iki farklı yönlendirme kuralını temsil ediyor:

1. İlk satır, "**default**" olarak etiketlenen bir varsayılan ağ geçidi ****belirtir. Bu, bilgisayarın tüm çıktı trafiğini yönlendireceği noktayı gösterir. "**via**" kelimesi ağ geçidi IP adresini, "**dev**" ise kullanılan ağ arayüzünü belirtir.
2. İkinci satır, 192.168.1.0/24 ağını doğrudan erişim yoluyla belirtir. "dev" ağ arayüzünü, "**proto**" ise kullanılan protokolü belirtir. "**scope link**" ağın doğrudan bağlantı üzerinden erişilebilir olduğunu ifade eder.

**Ağ Arabirimlerini Yönetme - `nmcli` Komutu (Network Manager)**

Tüm ağ arabirimlerini görüntüleme:

```bash
nmcli device show
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/75596c45-2092-4c48-b841-9fbdb9763cf0/Untitled.png)

*NetworkManager aracılığıyla yönetilen ağ cihazlarının ayrıntılarını görüntüler. Bu komut, ağ arayüzlerini, IP adreslerini, durumlarını ve diğer ağ bağlantı bilgilerini gösterir.*

Çıktı, aşağıdaki gibi bir formatta görünebilir:

```yaml
GENERAL.DEVICE:                         eth0
GENERAL.TYPE:                           ethernet
GENERAL.HWADDR:                         XX:XX:XX:XX:XX:XX
GENERAL.MTU:                            1500
GENERAL.STATE:                          100 (connected)
```

Bu çıktı, ağ cihazının (örneğin **`eth0`**), tipini (**`ethernet`**), donanım adresini (**`HWADDR`**), maksimum iletim birimini (**`MTU`**) ve bağlantı durumunu (**`STATE`**) gösterir.

**`MTU`***, ağ arabiriminin **maksimum veri paket**i boyutunu ifade eder. MTU değeri, iletilen veri paketlerinin boyutunu belirler. 1500, standart Ethernet ağlar için tipik bir MTU değeridir ve bu da genellikle 1500 bayt büyüklüğündeki veri paketlerinin iletilmesine izin verir. MTU, ağ verimliliği ve performansı üzerinde etkili olabilir ve bazen ayarlanması gerekebilir.*

**`STATE`**, *ağ arabiriminin mevcut durumunu ifade eder. 100, "connected" yani "**bağlı**" anlamına gelir. Bu, ağ arabiriminin etkin olduğunu ve çalışır durumda olduğunu gösterir. Başka bir değer, örneğin "`disconnected`" (bağlantısı kesik) veya "`down`" (kapalı) gibi, ağ arabiriminin farklı durumlarını gösterir.*

**`nmcli device show`** komutu, NetworkManager tarafından yönetilen ağ cihazlarının durumunu ve ayrıntılarını görüntülemek için kullanılır. Bu, ağ yapılandırması ve sorun giderme yaparken oldukça faydalı olabilir.

**Arabirimi etkinleştirme:**

```bash
sudo nmcli device set eth0 managed yes
```

**Arabirimi devre dışı bırakma:**

```bash
sudo nmcli device set eth0 managed no
```

**Wi-Fi ağlarına bağlanma:**

```bash
nmcli device wifi connect **SSID** password **PASSWORD**
```

*Wifi leri bu şekilde yönetebilirsiniz.*

---

**Ağ Konfigürasyon Dosyalarını Anlama**

**IP Adresi Atama**

Ağ arabirimine statik IP adresi atamak için **`/etc/network/interfaces`** veya **`ip`** komutunu kullanabilirsiniz:

```bash
sudo nano /etc/network/interfaces

# Örnek /etc/network/interfaces dosya içeriği:
# auto eth0
# iface eth0 inet static
#     address 192.168.1.100
#     netmask 255.255.255.0
#     gateway 192.168.1.1
#     dns-nameservers 8.8.8.8 8.8.4.4
```

Ancak bu dosyayı daha düzenli ve modüler hale getirmek için, **`/etc/network/interfaces.d/`** dizininde ayrı ayrı yapılandırma dosyaları oluşturabilir ve bunları ana **`interfaces`** dosyasına içe aktarabilirsiniz. Örnek bir kullanım şu şekilde olabilir:

**`/etc/network/interfaces`** dosyası:

```
# Diğer genel yapılandırmalar burada

# /etc/network/interfaces.d/ dizinini içe aktar
source /etc/network/interfaces.d/*
```

**`/etc/network/interfaces.d/`** dizinindeki yapılandırma dosyaları:

- **`/etc/network/interfaces.d/eth0.cfg`**:
    
    ```
    auto eth0
    iface eth0 inet static
        address 192.168.1.2
        netmask 255.255.255.0
        gateway 192.168.1.1
    
    ```
    
- **`/etc/network/interfaces.d/eth1.cfg`**:
    
    ```
    auto eth1
    iface eth1 inet dhcp
    ```
    

*Bu yapı, ağ arabirimleri için farklı yapılandırmaları daha kolay yönetmenize ve düzenlemenize olanak tanır.*

# Değişiklikleri kaydedip ağı yeniden başlatın:

```bash
sudo systemctl restart networking
```

veya

```bash
sudo ip addr add 192.168.1.100/24 dev eth0
sudo ip route add default via 192.168.1.1
```

*Buradaki **`dev`** kısaltması "device" kelimesinin kısaltmasıdır ve ağ ayarlarını yapılandırırken kullanılan bir parametredir. Bu komutda, **`ip addr add`** komutu ile bir IP adresi ve subnet mask ekleniyor ve hangi ağ arayüzüne (**`eth0`** gibi) ekleneceği belirtiliyor.*

*Yani, **`sudo ip addr add 192.168.1.100/24 dev eth0`** komutu ağ arayüzü **`eth0`** üzerine 192.168.1.100 IP adresini /24 subnet mask ile eklemek için kullanılır. **`dev`** parametresi ile IP adresinin hangi ağ arayüzüne atandığı belirtilir.*

*Bu bağlamda "**24**" belirli bir IP adresinin CIDR (`Classless Inter-Domain Routing`) gösterimidir ve bir IPv4 ağındaki IP adreslerini belirtirken kullanılır. Bu gösterim, IP adresinin ağ bölümünün **kaç bit** olduğunu belirtir ve IP adreslerinin ağ sınıfını belirlemek yerine daha esnek bir yaklaşım sunar.*

*IPv4 adresleri 32 bit uzunluğundadır. Bir CIDR gösterimi, IP adresinin kaç bitinin ağ adresini (ağ kısmını) ve kaç bitinin host adresini (ana makineyi) temsil ettiğini belirtir.*

*"24" bir CIDR gösterimidir ve ağ bölümünün 24 bit olduğunu ifade eder. 32 - 24 = 8 bit (1 **oktet**), yani bu ağda **256 adet** (2^8) IP adresi kullanılabilir demektir.*

*Örneğin, 192.168.1.100/24 ifadesindeki "192.168.1.100" IP adresi ve "/24" CIDR gösterimi birlikte kullanıldığında, IP adresinin ilk 24 bitinin ağ kısmını temsil ettiği ve geriye kalan son 8 bitin ana makineyi temsil ettiği anlamına gelir. Yani, bu CIDR gösterimi 192.168.1.0 ağına ait olan ve 192.168.1.1 ile 192.168.1.254 arasındaki IP adresleri için geçerli olur.*

*Bu gösterim, IP adresleriyle ağ yapılandırması ve alt ağlar oluşturma gibi işlemlerde kullanılır.*

---

**Ağ Paketlerini İzleme ve Analiz Etme**

- Ağ trafiğini izlemek ve analiz etmek için **`tcpdump`**, **`Wireshark`**, veya **`iftop`** gibi araçları kullanmak.

**`tcpdump`**, Linux ve diğer Unix benzeri işletim sistemlerinde ağ trafiğini yakalamak ve analiz etmek için kullanılan güçlü bir komuttur. Genellikle ağ sorunlarını teşhis etmek, güvenlik denetimleri yapmak veya ağ trafiğini izlemek için kullanılır.

İşte **`tcpdump`** komutunu kullanarak temel ağ trafiği analizi yapmak için kullanabileceğiniz bazı örnekler:

1. **Tüm Ağ Trafiğini İzleme:**
    
    ```css
    sudo tcpdump -i eth0
    ```
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/c0d19e77-01ba-4039-b0ae-97295bbf05b5/Untitled.png)
    
    - **`i eth0`**: **`eth0`** ağ arabirimini izleme seçeneği. İzlemek istediğiniz ağ arabirimini seçebilirsiniz.
2. **Belirli Bir Porttaki Trafiği İzleme:**
    
    ```css
    sudo tcpdump -i eth0 port 80
    ```
    
    - **`i eth0`**: **`eth0`** ağ arabirimini izleme seçeneği.
    - **`port 80`**: 80. porttaki (HTTP) trafiği izleme seçeneği. İzlemek istediğiniz portu belirleyebilirsiniz.
3. **Belirli Bir IP Adresinden veya IP Aralığından Gelen Trafiği İzleme:**
    
    ```css
    sudo tcpdump -i eth0 src 192.168.1.100
    ```
    
    - **`i eth0`**: **`eth0`** ağ arabirimini izleme seçeneği.
    - **`src 192.168.1.100`**: 192.168.1.100 IP adresinden gelen trafiği izleme seçeneği.
4. **Belirli Bir Protokolü İzleme:**
    
    ```css
    sudo tcpdump -i eth0 icmp
    ```
    
    - **`i eth0`**: **`eth0`** ağ arabirimini izleme seçeneği.
    - **`icmp`**: ICMP protokolünü izleme seçeneği. Diğer protokoller için "tcp", "udp" gibi kullanabilirsiniz.
5. **Belirli Bir Hedef IP Adresine Giden Trafiği İzleme:**
    
    ```css
    sudo tcpdump -i eth0 dst 192.168.1.200
    ```
    
    - **`i eth0`**: **`eth0`** ağ arabirimini izleme seçeneği.
    - **`dst 192.168.1.200`**: 192.168.1.200 IP adresine giden trafiği izleme seçeneği.
6. **Paketleri Belirli Bir Sayıda veya Belirli Bir Süre Boyunca İzleme:**
    
    ```css
    sudo tcpdump -i eth0 -c 10
    sudo tcpdump -i eth0 -G 3600 -W 1
    ```
    
    - **`i eth0`**: **`eth0`** ağ arabirimini izleme seçeneği.
    - **`c 10`**: Sadece ilk 10 paketi izleme seçeneği.
    - **`G 3600 -W 1`**: Her saat başına yeni bir dosya oluşturarak trafiği izleme seçeneği.
7. **İzleme Sonuçlarını Dosyaya Kaydetme:**
    
    ```css
    sudo tcpdump -i eth0 -w trafik.pcap
    ```
    
    - **`i eth0`**: **`eth0`** ağ arabirimini izleme seçeneği.
    - **`w trafik.pcap`**: İzleme sonuçlarını "trafik.pcap" adlı bir dosyaya kaydetme seçeneği. Bu PCAP formatında bir dosyadır ve daha sonra analiz için kullanılabilir.
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/9c53bc48-1650-47fc-9441-56cd06bf1470/Untitled.png)
    

**`tcpdump`** ile daha fazla özelleştirilmiş izleme senaryoları ve filtrelemeler yapabilirsiniz. Ayrıca, paketleri daha detaylı bir şekilde analiz etmek için Wireshark gibi grafiksel araçlarla birlikte kullanabilirsiniz. Bu komutun kullanımı geniş bir konu olduğu için, ihtiyaçlarınıza ve ağ trafiğinizin yapısına göre filtreler oluşturabilirsiniz.

---

**Ağ İletişimini Yönetme**

- **`ping`**, **`traceroute`**, **`netstat`**, ve **`ss`** gibi komutları kullanarak ağ iletişimini kontrol etme ve hata ayıklamak.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/150c1b19-66ac-4a6e-b2b7-a8cda5313bf0/Untitled.png)

**Ağ Test Araçları**

Ağ sorunlarını teşhis etmek ve hata ayıklamak için bazı kullanışlı araçlar:

**Ping** testi:

```bash
ping google.com
```

Bu komutu çalıştırdığınızda, **`google.com`** alan adına ICMP (Internet Control Message Protocol) paketleri gönderip yanıtlarını alarak hedefe erişilebilirliği ve ping sürelerini görebilirsiniz. Çıktı, gönderilen **paket sayısı**, **alınan yanıt sayısı**, **ortalama ping süresi** gibi bilgileri içerecektir.

Kullanım örneği:

```python
PING google.com (172.217.3.206) 56(84) bytes of data.
64 bytes from google.com (172.217.3.206): icmp_seq=1 ttl=54 time=15.8 ms
64 bytes from google.com (172.217.3.206): icmp_seq=2 ttl=54 time=16.0 ms
64 bytes from google.com (172.217.3.206): icmp_seq=3 ttl=54 time=15.9 ms
...

```

- **`64 bytes from google.com (172.217.3.206)`**: Bu kısım, hedef olarak belirtilen "google.com" alan adına (veya IP adresine) gönderilen ICMP paketlerine verilen yanıtları gösterir. "64 bytes" ifadesi, gönderilen **paket boyutunu** belirtir. "google.com (172.217.3.206)" ifadesi ise hedefin alan adı ve **IP adresini** gösterir.
- **`icmp_seq=1`**: Bu ifade, gönderilen ICMP paketinin **sıra numarasını** belirtir.
- **`ttl=54`**: "TTL" (Time To Live), paketin ağdaki yönlendiriciler üzerinden geçerken **kaç ağ düğümüne kadar iletim yapabileceğini** belirtir. Her yönlendirici geçişinde TTL bir azalır. Bu durumda, 54 TTL değerini gösterir.
    - *"TTL" (Time To Live), ağ paketlerinin ağ üzerinde geçebileceği maksimum adım sayısını belirtir. Bu, paketlerin sonsuz bir döngüde dolaşmasını engellemek için kullanılır. Her bir ağ düğümü veya yönlendirici üzerinden geçerken, TTL değeri bir azalır. Eğer bir paketin TTL değeri sıfıra ulaşırsa, paket o ağ düğümü veya yönlendirici tarafından atılır ve bir ICMP "Time Exceeded" hata mesajı gönderilir.*
    - *Paketin hedefine ulaşmak için geçebileceği maksimum adım sayısı olarak düşünebilirsiniz. TTL değeri, paketin yolu boyunca her bir yönlendiriciden geçerken azalır. Bu sayede paketler sonsuz döngülerden kaçınır ve bir şekilde hedefe ulaşır veya TTL sıfır olduğunda **atılır**.*
- **`time=15.8 ms`**: Bu ifade, ICMP paketinin hedefe ulaşma ve geri dönme süresini (ping süresini) milisaniye cinsinden gösterir. Bu durumda, hedefe gidip dönme süresi 15.8 milisaniye ( 0.0158 saniye) olarak ölçüldü.

**`ping`** komutunun ayrıca farklı seçenekleri ve parametreleri de bulunmaktadır. Daha fazla bilgi almak için **`man ping`** komutunu kullanabilirsiniz.

**Traceroute**:

```bash
traceroute google.com
```

Bu komutu çalıştırdığınızda, hedef alan adına (örneğin "google.com") yapılan yol izleme işlemini göreceksiniz. Her satır, izlenen ağ düğümünü ve yanıt sürelerini gösterecektir. Bu sayede verilerin nasıl farklı düğümler üzerinden geçtiğini ve iletişim gecikmelerini gözlemleyebilirsiniz.

*"traceroute" komutunun Ubuntu gibi bazı Linux dağıtımlarında varsayılan olarak bulunmayabileceği durumlar olabilir. Bunun yerine genellikle "traceroute" komutunun yerine "traceroute6" veya "tracepath" komutları kullanılabilir.*

*Eğer "traceroute" komutu mevcut değilse, aşağıdaki komutlarla alternatiflerini kullanabilirsiniz:*

1. ***tracepath:** Ubuntu'da "tracepath" komutu genellikle mevcuttur ve aynı işlevi görür. Terminali açın ve aşağıdaki gibi kullanabilirsiniz:*
    
    ```
    tracepath google.com
    ```
    
2. ***traceroute6:** Eğer IPv6 adreslerini izlemek istiyorsanız, "traceroute6" komutunu kullanabilirsiniz:*
    
    ```
    traceroute6 ipv6.google.com
    ```
    

*Eğer bu alternatif komutlar da çalışmıyorsa, komut istemcinizde eksik olabilir. Bu durumda "traceroute" benzeri bir komutun yüklenmesi gerekebilir. Ubuntu'da eksik olan komutları yüklemek için aşağıdaki komutu kullanabilirsiniz:*

```arduino
sudo apt-get install traceroute
```

*Bu komut, "traceroute" komutunu sisteminize yüklemeye çalışacaktır. Kurulum işlemi tamamlandıktan sonra, "traceroute" komutunu kullanabilirsiniz.*

**Port tarama**:

```bash
nmap -p 80 google.com
```

Ağda belirtilen IP adresine veya alan adına sahip bir hedef üzerinde belirtilen portun (80 numaralı port, HTTP protokolünü temsil eder) açık olup olmadığını taramanızı sağlar. Eğer port açıksa, hedef sunucunun bu portu dinlediği anlamına gelir. Eğer kapalıysa veya yanıt vermiyorsa, bu portun kapalı olduğunu gösterir.

*Unutmayın ki, nmap komutunu kullanırken izinlere dikkat etmek önemlidir ve başkalarının izni olmadan ağ tarayıcıları kullanmamalısınız.*

"nmap" aracını yükleyin:

```bash
sudo apt-get install nmap
```

---

***Dosya Sistem Hiyerarşisi:** Bazı sistem dosyaları ve klasörleri yalnızca root kullanıcısı tarafından değiştirilebilir. Bu tür dosyaları düzenlemeye veya değiştirmeye çalışırken "Operation not permitted" hatası alabilirsiniz.*

**Uygulama veya Komut Kısıtlamaları:** Sistem yöneticisi tarafından belirli komutların veya uygulamaların kullanımı sınırlandırılmış olabilir.

---

**DNS Yapılandırmasını Anlama**

- DNS sunucularınızı ve DNS çözümlemeyi yapılandırma.
- **`/etc/resolv.conf`** dosyasını düzenlemek ve DNS sunucularını ayarlamak gibi işlemler.

**DNS Ayarlarını Yapılandırma**

DNS ayarlarını düzenlemek için **`/etc/resolv.conf`** dosyasını düzenleyebilirsiniz:

```bash
sudo nano /etc/resolv.conf

# Örnek /etc/resolv.conf dosya içeriği:
# nameserver 8.8.8.8
# nameserver 8.8.4.4

# Değişiklikleri kaydedin.
```

**Hostname Görüntüleme:**

Sisteminizin mevcut hostname'ini görüntülemek için aşağıdaki komutu kullanabilirsiniz:

```bash
hostname
```

**Hostname Ayarlama:**

Sisteminizin hostname'ini ayarlamak için aşağıdaki komutu kullanabilirsiniz. Ancak bu sadece geçici bir değişikliktir ve yeniden başlatıldığında eski hostname'e döner:

```bash
sudo hostname yeni-hostname
```

**Hostname Kalıcı Olarak Ayarlama (Ubuntu Örneği):**

Ubuntu gibi bazı dağıtımlarda, hostname'i kalıcı olarak ayarlamak için aşağıdaki adımları izleyebilirsiniz:

- Hostname'i değiştirmek için **`/etc/hostname`** dosyasını düzenleyin:
    
    ```bash
    sudo nano /etc/hostname
    ```
    
    Dosyanın içeriğini düzenleyin ve yeni hostname'i girin. Ardından dosyayı kaydedin ve çıkın.
    
- Daha sonra, **`/etc/hosts`** dosyasını düzenleyerek değişiklikleri uygulayın:
    
    ```bash
    sudo nano /etc/hosts
    ```
    
    Dosyada, **`127.0.0.1`** satırının sonuna yeni hostname'i ekleyin:
    
    ```
    127.0.0.1  yeni-hostname
    ```
    
    Değişiklikleri kaydedin ve çıkın.
    
- Son olarak, aşağıdaki komutu kullanarak bilgisayarınızı yeniden başlatın:
    
    ```bash
    sudo reboot
    ```
    

…

---

**Linux Ağ Güvenliği ve Güvenlik Duvarları**

Linux tabanlı sistemlerde ağ güvenliği, ağ trafiğini izleme, yönetme ve koruma işlemlerini içerir. Aşağıda Linux üzerinde ağ güvenliği ve güvenlik duvarlarıyla ilgili bazı önemli konuları ve uygulamaları bulabilirsiniz:

1. **Güvenlik Duvarları (Firewall):** Güvenlik duvarları, ağ trafiğini denetlemek ve istenmeyen erişimleri engellemek için kullanılır. Linux üzerinde güvenlik duvarı kurulumu ve yapılandırması için yaygın olarak kullanılan araçlar şunlardır:
    - **iptables:** Linux'un dahili güvenlik duvarı yöneticisi olan iptables, gelişmiş ağ kuralları ve filtrelemeler oluşturmanıza olanak tanır.
    - **ufw (Uncomplicated Firewall):** Ufw, iptables'in kullanımını basitleştiren bir arayüze sahip bir araçtır. Özellikle yeni başlayanlar için uygun bir seçenektir.
    - **firewalld:** CentOS ve Fedora gibi dağıtımlarda kullanılan bir güvenlik duvarı yöneticisidir. Dinamik kurallar oluşturmayı kolaylaştırır.
2. **Ağ Monitörleme ve Günlük Kayıtları:** Ağ trafiğini izlemek ve günlük kayıtlarını kontrol etmek, olası güvenlik tehditlerini tespit etmek için önemlidir. Araçlar arasında Wireshark, tcpdump, Snort, Suricata ve rsyslog gibi araçlar bulunur.
3. **Intrusion Detection Systems (IDS) ve Intrusion Prevention Systems (IPS):** IDS ve IPS, ağ trafiğini izler ve anormal aktiviteleri algılar. Snort ve Suricata gibi açık kaynaklı IDS/IPS araçları, Linux üzerinde çalışabilir ve güvenlik duvarlarıyla entegre edilebilir.
4. **VPN (Virtual Private Network):** VPN, güvenli bir şekilde uzaktan erişim sağlamak ve ağ trafiğini şifrelemek için kullanılır. OpenVPN ve IPsec gibi protokoller, Linux üzerinde VPN sunucuları ve istemcileri oluşturmanıza olanak tanır.
5. **Sistem Güncellemeleri ve Yaması:** Linux sunucularınızın ve ağ cihazlarınızın güncel olduğundan emin olun. Ayrıca, güvenlik açıklarına karşı hızlı bir şekilde yamaları uygulayın.
6. **SSH Güvenliği:** SSH sunucunuzu güvence altına alın. Güçlü şifreler, anahtar tabanlı kimlik doğrulama ve SSH konfigürasyon dosyalarının güvence altına alınması gibi önlemler alın.
7. **Network Access Control (NAC):** NAC, ağa erişimi denetler ve sadece yetkilendirilmiş cihazların ağa bağlanmasına izin verir. Bu, ağ güvenliği için ek bir katman sağlar.
8. **Güçlü Şifre Politikaları:** Parola karmaşıklığı ve şifre süresi gibi güçlü şifre politikaları oluşturun ve uygulayın.
9. **Ağ Segmentasyonu:** Ağınızı segmente edin, böylece farklı ağ bileşenleri arasında izole edilmiş bölgeler oluşturabilirsiniz. Bu, bir bölgedeki güvenlik sorunlarının diğer bölgelere yayılmasını engeller.
10. **Güvenlik Eğitimi:** Ağ kullanıcılarına ve yöneticilerine güvenlik eğitimi verin. Bilinçli kullanıcılar, sosyal mühendislik ve diğer tehditlere karşı daha iyi hazırlıklı olabilirler.

Ağ güvenliği sürekli bir çaba gerektirir ve güvenlik tehditleri sürekli olarak evrilmektedir. Bu nedenle güvenlik önlemlerinizi düzenli olarak gözden geçirin ve güncelleyin. Ayrıca, Linux topluluğu ve güvenlik konularına odaklanmış web siteleri gibi kaynaklardan güncel bilgileri takip etmek de önemlidir.

---

**Linux Ağ Servisleri ve Sunucular**

Linux, ağ servisleri ve sunucuları sağlamak için oldukça popüler bir işletim sistemidir.

**Web Sunucusu (Web Server):** Linux, popüler web sunucu yazılımlarını çalıştırmak için kullanılır. **Apache**, **Nginx** ve LiteSpeed gibi web sunucuları, web sitelerini ve web uygulamalarını sunmak için Linux platformunda sıkça kullanılır.

**E-posta Sunucusu (Mail Server):** Linux, e-posta iletişimi için e-posta sunucularını çalıştırmak için tercih edilen bir platformdur. Postfix, Sendmail ve Exim gibi e-posta sunucu yazılımları Linux üzerinde yaygın olarak kullanılır.

**DNS Sunucusu (DNS Server):** Linux, DNS sunucularını yönetmek için kullanılır. BIND (Berkeley Internet Name Domain) gibi DNS sunucu yazılımları, Linux üzerinde kullanılabilir ve alan adlarını IP adreslerine çevirme işlevini yerine getirir.

**Dosya Sunucusu (File Server):** Linux, dosya sunucularını yönetmek için kullanılır. Samba ve NFS (Network File System) gibi protokoller, Linux tabanlı dosya sunucularını diğer cihazlarla paylaşılan dosyalara erişim sağlamak için kullanır.

**Veritabanı Sunucusu (Database Server):** Linux, birçok veritabanı sunucusunu barındırmak için kullanılır. MySQL, PostgreSQL, MongoDB ve MariaDB gibi veritabanı yönetim sistemleri (DBMS) Linux üzerinde çalıştırılabilir.

**SSH Sunucusu (SSH Server):** Linux, güvenli uzak erişim için **SSH sunucu**larını çalıştırmak için kullanılır. Bu sunucular, uzaktan erişim ve dosya transferi işlemlerini güvenli bir şekilde sağlar.

**VPN Sunucusu (VPN Server):** Linux, sanal özel ağ (VPN) sunucularını çalıştırmak için kullanılır. OpenVPN ve IPsec gibi VPN protokollerini destekleyen sunucular, uzak erişim ve güvenli bağlantılar sağlar.

**DHCP Sunucusu (DHCP Server):** DHCP sunucuları, ağdaki cihazlara otomatik olarak IP adresleri ve ağ yapılandırması sağlamak için kullanılır. Linux, ISC DHCP sunucusu gibi yazılımlarla DHCP hizmeti sunabilir.

**Proxy Sunucusu (Proxy Server):** Linux, ağ trafiğini yönlendirmek ve filtrelemek için kullanılan **proxy sunucu**larını çalıştırmak için uygundur. Squid gibi proxy sunucu yazılımları, Linux üzerinde kullanılabilir.

**Firewall Sunucusu (Firewall Server):** Linux, güvenlik duvarları (firewall) oluşturmak ve ağ trafiğini denetlemek için kullanılabilir. **iptables** ve nftables gibi yazılımlar, Linux tabanlı güvenlik duvarları oluşturmak için kullanılır.

---

.

**Linux Ağ Sorunlarını Giderme**

Linux tabanlı bir sistemde ağ sorunlarını gidermek için aşağıdaki adımları izleyebilirsiniz:

1. **Ağ Bağlantısını Kontrol Edin:**
    - İlk olarak, fiziksel bağlantıları kontrol edin. Ethernet kablosu doğru bir şekilde takılı mı? Kablonun veya portun zarar görmüş olup olmadığını kontrol edin.
2. **IP Adresini Kontrol Edin:**
    - **`ifconfig`** veya **`ip addr`** komutları ile ağ arabirimlerinizin IP adresini kontrol edin. Eğer bir statik IP adresi kullanıyorsanız, ayarlarınızın doğru olduğundan emin olun. DHCP kullanıyorsanız, bağlantı sorunlarını çözmek için DHCP sunucusunu kontrol edin.
3. **Ağ Hizmetlerini Kontrol Edin:**
    - Ağ hizmetlerinin (örneğin, DNS, DHCP) çalışıp çalışmadığını kontrol edin. Hizmetlerin çalışıp çalışmadığını görmek için **`systemctl status`** veya **`service`** komutlarını kullanabilirsiniz.
4. **Ağ Arabirimini Yeniden Başlatın:**
    - Ağ sorunlarını çözmek için ağ arabirimini yeniden başlatmayı deneyin. **`ifdown`** ve **`ifup`** komutlarını kullanarak ağ arabirimini devre dışı bırakabilir ve tekrar etkinleştirebilirsiniz.
5. **Ağ Hizmetlerini Yeniden Başlatın:**
    - Ağ hizmetlerini yeniden başlatmayı düşünün. Örneğin, DNS sorunları yaşıyorsanız, DNS hizmetini yeniden başlatabilirsiniz.
6. **Ağ Ekipmanını Kontrol Edin:**
    - Ağ cihazlarınızı (router, switch, modem vb.) kontrol edin ve bu cihazların doğru şekilde çalıştığından emin olun. Gerekirse yeniden başlatın.
7. **Firewall Ayarlarını Kontrol Edin:**
    - Güvenlik duvarı (firewall) ayarlarınızın ağ trafiği üzerinde olumsuz etkisi olup olmadığını kontrol edin. Eğer bir güvenlik duvarı kullanıyorsanız, gerekli portların açık olduğundan emin olun.
8. **Ağ Paketlerini İzleme:**
    - **`tcpdump`** veya **`Wireshark`** gibi araçlar kullanarak ağ trafiğini izleyin. Bu, ağdaki iletişimi incelemenize ve sorunları tanımlamanıza yardımcı olabilir.
9. **Ağ Konfigürasyon Dosyalarını Kontrol Edin:**
    - Ağ konfigürasyon dosyalarını (örneğin, **`/etc/network/interfaces`**, **`/etc/resolv.conf`**) kontrol edin ve doğru ayarlandığından emin olun.
10. **Ağ Kartı Sürücülerini Kontrol Edin:**
    - Ağ kartınızın doğru sürücüsünün yüklü olduğundan ve güncel olduğundan emin olun. Eğer sorunlar devam ediyorsa, sürücülerin güncellemelerini araştırın ve gerekirse güncelleyin.
11. **Ağ Protokollerini Denetleme:**
    - İnternet veya diğer ağ hizmetlerine erişim sağlayamıyorsanız, DNS veya diğer ağ protokollerinin doğru yapılandırıldığından emin olun.
12. **Ağ Sorunlarını Günlük Dosyalarını İnceleme:**
    - Ağ sorunlarını çözmek için günlük dosyalarını (**`/var/log`**) inceleyin. Bu dosyalar, ağ sorunlarının nedenini belirlemenize yardımcı olabilir.
13. **Topluluk ve Dokümantasyonu Kullanın:**
    - Linux topluluğu ve belgelendirme kaynakları, özellikle özel bir sorunla karşılaşırsanız, sorununuzu çözmek için faydalı kaynaklar olabilir.

Ağ sorunlarını tespit etmek ve çözmek genellikle sabır gerektiren bir süreçtir. Her bir adımı dikkatlice izleyerek sorununuzu teşhis etmek ve gidermek için çaba sarf edin.

---

**Ağ Sertifikasyonları**

Ağ sertifikasyonları, ağ alanında bilgi ve becerilerinizi belgelemek ve geliştirmek için alabileceğiniz resmi tanınmış sertifikalardır. Bu sertifikalar, ağ yöneticileri, güvenlik uzmanları, ağ mühendisleri ve diğer ağ profesyonelleri için önemlidir ve genellikle işverenler tarafından değerli bulunurlar. Aşağıda, bazı popüler ağ sertifikasyonlarını bulabilirsiniz:

1. **CompTIA Network+**: CompTIA Network+ sertifikası, temel ağ konularını ve becerilerini ölçen bir sertifikadır. Ağ yönetimi, ağ güvenliği ve ağ hata ayıklama gibi konuları kapsar. Bu sertifika, ağ kariyerine yeni başlayanlar için iyi bir başlangıçtır.
2. **Cisco CCNA (Cisco Certified Network Associate)**: CCNA sertifikası, Cisco ürünlerini kullanarak ağları yönetme ve tasarlama yeteneğinizi ölçer. Ağ yöneticileri ve mühendisleri için önemli bir sertifikadır.
3. **Cisco CCNP (Cisco Certified Network Professional)**: CCNP sertifikası, daha derinlemesine ağ konularını ve becerilerini ölçer. Cisco cihazları üzerinde gelişmiş yapılandırma, güvenlik ve hata ayıklama becerilerini içerir.
4. **CompTIA Security+**: CompTIA Security+, ağ güvenliği konularını kapsayan bir sertifikadır. Ağ güvenliği uzmanları için önemli bir başlangıç sertifikasıdır.
5. **Certified Information Systems Security Professional (CISSP)**: CISSP sertifikası, ağ güvenliği, bilgi güvenliği ve risk yönetimi gibi konularda derinlemesine bilgi ve deneyime sahip olanlar için uygundur. CISSP, ISC² tarafından verilir ve uluslararası bir itibara sahiptir.
6. **Certified Ethical Hacker (CEH)**: CEH sertifikası, bilgisayar sistemlerini etik olarak hacklemeyi öğrenenler için uygundur. Bu sertifikasyon, ağ güvenliği uzmanlarına, ağlarını potansiyel saldırılara karşı nasıl savunacaklarını anlama konusunda yetenek kazandırır.
7. **Certified Information Security Manager (CISM)**: CISM, bilgi güvenliği yönetimi ve ağ güvenliği alanında deneyime sahip profesyonellere yöneliktir. Bilgi güvenliği yönetimi ve risk yönetimi konularını kapsar.
8. **Certified Wireless Network Professional (CWNP)**: CWNP sertifikasyonları, kablosuz ağlarla ilgili konuları ele alır. CWNA (Certified Wireless Network Administrator) ve diğer CWNP sertifikaları, kablosuz ağ konularında uzmanlaşmayı hedefleyenler için uygundur.
9. **Juniper Networks Certification Program (JNCIA, JNCIS, JNCIP, vb.)**: Juniper Networks tarafından sunulan sertifikasyon programları, Juniper cihazlarıyla çalışan ağ profesyonellerine yöneliktir. JNCIA (Juniper Networks Certified Internet Associate) başlangıç seviyesindeyken, daha yüksek seviyeli sertifikalar JNCIS, JNCIP ve JNCIE olarak gelir.

Bu sertifikasyonlar, ağ alanında farklı uzmanlık seviyelerine ve ilgi alanlarına yöneliktir. Ağ kariyerinizde hangi alanı hedeflediğinizi ve ne tür bir deneyime sahip olduğunuzu göz önünde bulundurarak en uygun olanı seçmelisiniz. Ayrıca, sertifikasyon sınavlarına hazırlık kursları ve materyalleri sunan birçok kaynak ve eğitim kuruluşu vardır.

---

**Pratik Uygulama**

**Senaryo: Linux Komut Satırında Internet Hızı Testi**

1. **Aşama:** Terminali Açın
    - Linux tabanlı bilgisayarınızda bir terminal açın. Terminali açmak için genellikle "Ctrl + Alt + T" tuşlarına basabilirsiniz.
2. **Aşama:** Speedtest CLI'yı Yükleyin
    - Terminalde aşağıdaki komutları sırasıyla girerek Speedtest CLI aracını yükleyin:
    
    ```bash
    sudo apt-get update
    sudo apt-get install speedtest-cli
    ```
    
    Bu komutlar, Speedtest aracını sisteminize yükler.
    
3. **Aşama:** Hız Testini Yapın
    - Terminalde aşağıdaki komutu girerek hız testini başlatın:
    
    ```bash
    speedtest
    ```
    
    Bu komut, hız testini başlatır ve indirme, yükleme ve gecikme sürelerini gösterir.
    
4. **Aşama:** Sonuçları İnceleyin
    - Hız testi tamamlandığında, sonuçları inceleyin. Bu sonuçlar arasında indirme hızı, yükleme hızı ve gecikme süresi yer alır. Örnek bir sonuç şu şekilde görünebilir:
    
    ```makefile
    Download: 81.08 Mbit/s
    Upload: 20.45 Mbit/s
    Ping: 43.582 ms
    ```
    
    Bu sonuçlara bakarak internet hızınızı görebilirsiniz.
    
5. Aşama: Sonuçları Yorumlayın
    1. **Download (İndirme):** Bu değer, internet hızınızın indirme yani bilgisayarınıza veri alırken ne kadar hızlı olduğunu gösterir. Örneğin, "81.08 Mbit/s" değeri, internet bağlantınızın indirme hızının yaklaşık olarak 81.08 megabit/saniye olduğunu belirtir. 81.08 megabit/saniye (Mbit/s), her saniye boyunca 81.08 milyon bit veri aktarım hızını ifade eder. ( 1 megabit (Mbit), 1 milyon bit'e eşittir ). Ancak, bazı internet servis sağlayıcıları hızları megabyte/saniye (MB/s) cinsinden de ifade edebilir. 1 megabyte (MB), 8 megabite (Mbit) eşittir. Yani, 81.08 Mbit/s hızı yaklaşık olarak **10.135 MB/s** hızına denk gelir.
    2. **Upload (Yükleme):** Bu değer, internet hızınızın yükleme yani bilgisayarınızdan veri gönderirken ne kadar hızlı olduğunu gösterir. Örneğin, "20.45 Mbit/s" değeri, internet bağlantınızın yükleme hızının yaklaşık olarak 20.45 megabit/saniye olduğunu belirtir. 20.45 megabit/saniye (Mbit/s) hızını megabyte/saniye (MB/s) hızına dönüştürmek için, 1 megabit'in 8 megabyte'a eşit olduğunu hatırlamamız gerekiyor. Bu nedenle, 20.45 Mbit/s hızı yaklaşık olarak aşağıdaki gibi hesaplanabilir: 20.45 Mbit/s ÷ 8 = **2.55625 MB/s**
    3. **Ping (Gecikme):** Bu değer, internet bağlantınızın hedef sunucuya olan yanıt süresini ölçer. Daha düşük bir ping değeri, daha hızlı bir bağlantıyı gösterir. Örneğin, "43.582 ms" değeri, bağlantınızın yaklaşık olarak 43.582 milisaniye (ms) gecikme süresine sahip olduğunu gösterir.
6. **Aşama:** Terminali Kapatın
    - Hız testini inceledikten sonra terminali kapatabilirsiniz.

---

Resmi belgeler size kapsamlı bir rehberlik sunar.

[The Linux Documentation Project (tldp.org)](https://tldp.org/)

[Official Ubuntu Documentation](https://help.ubuntu.com/)

https://linuxjourney.com/

---

**Linux Ağ Güvenliği**

Linux güvenlik duvarı, bilgisayarınızın ağ trafiğini denetlemek ve izlemek amacıyla kullanılan bir koruma mekanizmasıdır. Genellikle "firewall" olarak adlandırılır. Linux tabanlı işletim sistemlerinde, farklı araçlar ve yöntemler kullanılarak güvenlik duvarı oluşturulabilir. İşte Linux güvenlik duvarıyla ilgili bazı temel konular:

1. **Iptables:** Iptables, Linux tabanlı sistemlerde en yaygın kullanılan güvenlik duvarı yönetim aracıdır. Bu araç sayesinde **gelen ve giden ağ trafiğini filtreleyebilir**, **izin verebilir** veya **reddedebilirsiniz**. Iptables kuralları, paketlerin belirli koşullara göre nasıl işleneceğini belirtir.
2. **UFW (Uncomplicated Firewall):** UFW, iptables'ın daha basit ve kullanıcı dostu bir arayüzüdür. UFW, komut satırında kolayca kullanılabilir ve hızlıca güvenlik duvarı kurmanıza yardımcı olur.
3. **Firewalld:** Firewalld, özellikle CentOS ve Fedora gibi dağıtımlarda kullanılan bir güvenlik duvarı yönetim aracıdır. Firewalld, dinamik olarak kuralları yönetmenizi sağlar ve servis tabanlı bir yaklaşım sunar.
4. **Güvenlik Politikaları:** Güvenlik duvarı kurallarını belirlerken, hangi portların açık olacağına ve hangi IP adreslerinin erişim izni alacağına karar vermelisiniz. Gereksiz portların kapatılması, sadece gerekli servislerin açılması ve güvenli IP adreslerine erişim izni verilmesi iyi güvenlik uygulamalarındandır.
5. **Loglama:** Güvenlik duvarınızın etkinliğini izlemek için loglama işlevselliği sağlamak önemlidir. Bu sayede hangi trafiğin engellendiği veya izin verildiği gibi bilgileri takip edebilirsiniz.
6. **VPN ve DMZ:** Sanal özel ağlar (VPN) ve demilitarize bölgeler (DMZ) gibi konseptler, güvenlik duvarını daha güçlü hale getirebilir. VPN, güvenli uzaktan erişim sağlayabilirken, DMZ izole edilmiş bir ağ alanıdır ve dış dünyayla iç ağınız arasında bir tampon bölge sağlar.
7. **Güvenlik Güncellemeleri:** Linux dağıtımınızın ve güvenlik duvarı yazılımının güncel olması önemlidir. Güvenlik açıkları ve zayıflıkların düzeltilmesi için düzenli güncellemeleri takip etmelisiniz.

Bu sadece birkaç temel kavramdır. Linux güvenlik duvarını kurarken ve yönetirken, güvenlik gereksinimlerinizi dikkate almalı ve en iyi uygulamalara uygun olarak yapılandırmalısınız.

---

**Linux Güvenlik Duvarı Kurulum**

Linux tabanlı sistemlerde güvenlik duvarı kurulumu, genellikle "iptables", "UFW (Uncomplicated Firewall)" veya "Firewalld" gibi araçlar kullanılarak gerçekleştirilir. 

---

**Firewall Yapılandırması - UFW (Uncomplicated Firewall)** 
UFW, daha basit bir arayüze sahip bir güvenlik duvarı aracıdır.

1. Terminali açın.
2. UFW'yi etkinleştirin:
    
    ```bash
    sudo ufw enable
    ```
    
3. İzinleri eklemek veya kaldırmak için aşağıdaki gibi komutları kullanabilirsiniz:
    
    ```bash
    sudo ufw allow 80/tcp   # HTTP trafiğine izin verme
    sudo ufw deny 22/tcp    # SSH trafiğini engelleme
    ```
    

**`ufw`** ile mevcut kuralları görüntülemek için aşağıdaki komutu kullanabilirsiniz:

```bash
sudo ufw status
```

Bu komut, güvenlik duvarınızda hangi kuralların etkin olduğunu ve hangi portların açık veya kapalı olduğunu görüntüler. 

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/4c841046-bb99-4588-9664-73f716267c6e/Untitled.png)

Çıktı, açık portların listesi ve izin verilen veya reddedilen kuralların durumunu içerecektir.

Eğer daha ayrıntılı bir çıktı isterseniz, aşağıdaki komutları da kullanabilirsiniz:

- **`sudo ufw status verbose`**: Kuralları daha ayrıntılı bir şekilde görüntüler.
- **`sudo ufw status numbered`**: Kuralları numaralandırarak görüntüler.

Bu komutlar, **`ufw`** ile yapılandırdığınız güvenlik duvarının mevcut durumu hakkında bilgi edinmenizi sağlar.

---

**Firewall Yapılandırması - Iptables** 

Iptables, Linux işletim sistemlerinde kullanılan bir güvenlik duvarı (firewall) yönetim aracıdır. İptables, gelen ve giden ağ trafiğini kontrol etmek, yönlendirmek ve filtrelemek için kullanılır. İşte iptables kullanarak bir güvenlik duvarı yapılandırmanızı adım adım nasıl yapabileceğinizi açıklayan temel adımlar:

**1. Iptables'i Kontrol Etme:**

Öncelikle iptables hizmetinin sistemde yüklü ve çalışır durumda olup olmadığını kontrol etmelisiniz. Aşağıdaki komut ile iptables hizmetinin durumunu görebilirsiniz:

```bash
sudo systemctl status iptables
```

Eğer iptables çalışmıyorsa veya yüklü değilse, bunu kurmanız gerekebilir:

```bash
sudo apt-get install iptables  # Debian/Ubuntu
sudo yum install iptables      # CentOS/RHEL
```

**2. Temel Kural Ayarları:**

Güvenlik duvarınızın temel kural ayarlarını yapmak için **`iptables`** komutunu kullanabilirsiniz. Örnek olarak, gelen trafiği engelleyen bir varsayılan politika oluşturabilirsiniz:

```bash
sudo iptables -P INPUT DROP
```

Bu komut, gelen trafiği engellemek için varsayılan politikayı "DROP" olarak ayarlar. Buna ek olarak, gelen trafiği izin vermek istediğiniz belirli portları açmalısınız. Örneğin, SSH (22. port) erişimine izin vermek için:

```bash
sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT
```

**3. Bağlantı İzleme (Stateful Firewall):**

Stateful bir güvenlik duvarı, bağlantıları izler ve sadece mevcut ve doğrulanmış bağlantılara izin verir. Bu, özellikle gelen ve çıkan trafiği yönetmek için önemlidir.

Örnek olarak, bağlantı izlemeyi etkinleştirmek için aşağıdaki komutu kullanabilirsiniz:

```bash
sudo iptables -A INPUT -m state --state ESTABLISHED,RELATED -j ACCEPT
```

**4. Diğer Kural Ekleme ve Düzenleme:**

İhtiyaca göre başka kuralar ekleyebilirsiniz. Örneğin, web sunucusu (HTTP ve HTTPS) trafiğini izin vermek için:

```bash
sudo iptables -A INPUT -p tcp --dport 80 -j ACCEPT   # HTTP
sudo iptables -A INPUT -p tcp --dport 443 -j ACCEPT  # HTTPS
```

**5. Kuralları Kaydetme:**

Kuralları oluşturduktan sonra, bunları kalıcı hale getirmeniz gerekir, böylece yeniden başlattığınızda kaybolmazlar. Bu, farklı Linux dağıtımlarında farklı komutlar gerektirebilir. Örneğin, Debian/Ubuntu'da **`iptables-persistent`** paketini kullanabilirsiniz:

```bash
sudo apt-get install iptables-persistent
sudo service iptables-persistent start
```

**6. Güvenlik Duvarını Etkinleştirme:**

Son olarak, güvenlik duvarınızı etkinleştirmeniz gerekiyor:

```bash
sudo iptables -L  # Kuralları kontrol etmek için
sudo service iptables restart  # Güvenlik duvarını yeniden başlatmak için
```

Bu adımlar, iptables kullanarak temel bir güvenlik duvarı yapılandırmanıza yardımcı olacaktır.

---

**Firewall Yapılandırması - Iptables** 

Iptables, Linux işletim sistemlerinde kullanılan bir güvenlik duvarı (firewall) yönetim aracıdır. İptables, gelen ve giden ağ trafiğini kontrol etmek, yönlendirmek ve filtrelemek için kullanılır. İşte iptables kullanarak bir güvenlik duvarı yapılandırmanızı adım adım nasıl yapabileceğinizi açıklayan temel adımlar:

**1. Iptables'i Kontrol Etme:**

Öncelikle iptables hizmetinin sistemde yüklü ve çalışır durumda olup olmadığını kontrol etmelisiniz. Aşağıdaki komut ile iptables hizmetinin durumunu görebilirsiniz:

```bash
sudo systemctl status iptables
```

Eğer iptables çalışmıyorsa veya yüklü değilse, bunu kurmanız gerekebilir:

```bash
sudo apt-get install iptables  # Debian/Ubuntu
sudo yum install iptables      # CentOS/RHEL
```

**2. Temel Kural Ayarları:**

Güvenlik duvarınızın temel kural ayarlarını yapmak için **`iptables`** komutunu kullanabilirsiniz. Örnek olarak, gelen trafiği engelleyen bir varsayılan politika oluşturabilirsiniz:

```bash
sudo iptables -P INPUT DROP
```

Bu komut, gelen trafiği engellemek için varsayılan politikayı "DROP" olarak ayarlar. Buna ek olarak, gelen trafiği izin vermek istediğiniz belirli portları açmalısınız. Örneğin, SSH (22. port) erişimine izin vermek için:

```bash
sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT
```

**3. Bağlantı İzleme (Stateful Firewall):**

Stateful bir güvenlik duvarı, bağlantıları izler ve sadece mevcut ve doğrulanmış bağlantılara izin verir. Bu, özellikle gelen ve çıkan trafiği yönetmek için önemlidir.

Örnek olarak, bağlantı izlemeyi etkinleştirmek için aşağıdaki komutu kullanabilirsiniz:

```bash
sudo iptables -A INPUT -m state --state ESTABLISHED,RELATED -j ACCEPT
```

**4. Diğer Kural Ekleme ve Düzenleme:**

İhtiyaca göre başka kuralar ekleyebilirsiniz. Örneğin, web sunucusu (HTTP ve HTTPS) trafiğini izin vermek için:

```bash
sudo iptables -A INPUT -p tcp --dport 80 -j ACCEPT   # HTTP
sudo iptables -A INPUT -p tcp --dport 443 -j ACCEPT  # HTTPS
```

**5. Kuralları Kaydetme:**

Kuralları oluşturduktan sonra, bunları kalıcı hale getirmeniz gerekir, böylece yeniden başlattığınızda kaybolmazlar. Bu, farklı Linux dağıtımlarında farklı komutlar gerektirebilir. Örneğin, Debian/Ubuntu'da **`iptables-persistent`** paketini kullanabilirsiniz:

```bash
sudo apt-get install iptables-persistent
sudo service iptables-persistent start
```

**6. Güvenlik Duvarını Etkinleştirme:**

Son olarak, güvenlik duvarınızı etkinleştirmeniz gerekiyor:

```bash
sudo iptables -L  # Kuralları kontrol etmek için
sudo service iptables restart  # Güvenlik duvarını yeniden başlatmak için
```

Bu adımlar, iptables kullanarak temel bir güvenlik duvarı yapılandırmanıza yardımcı olacaktır.

**Firewall Yapılandırması - Iptables** 

Iptables, Linux işletim sistemlerinde kullanılan bir güvenlik duvarı (firewall) yönetim aracıdır. İptables, gelen ve giden ağ trafiğini kontrol etmek, yönlendirmek ve filtrelemek için kullanılır. İşte iptables kullanarak bir güvenlik duvarı yapılandırmanızı adım adım nasıl yapabileceğinizi açıklayan temel adımlar:

**1. Iptables'i Kontrol Etme:**

Öncelikle iptables hizmetinin sistemde yüklü ve çalışır durumda olup olmadığını kontrol etmelisiniz. Aşağıdaki komut ile iptables hizmetinin durumunu görebilirsiniz:

```bash
sudo systemctl status iptables
```

Eğer iptables çalışmıyorsa veya yüklü değilse, bunu kurmanız gerekebilir:

```bash
sudo apt-get install iptables  # Debian/Ubuntu
sudo yum install iptables      # CentOS/RHEL
```

**2. Temel Kural Ayarları:**

Güvenlik duvarınızın temel kural ayarlarını yapmak için **`iptables`** komutunu kullanabilirsiniz. Örnek olarak, gelen trafiği engelleyen bir varsayılan politika oluşturabilirsiniz:

```bash
sudo iptables -P INPUT DROP
```

Bu komut, gelen trafiği engellemek için varsayılan politikayı "DROP" olarak ayarlar. Buna ek olarak, gelen trafiği izin vermek istediğiniz belirli portları açmalısınız. Örneğin, SSH (22. port) erişimine izin vermek için:

```bash
sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT
```

**3. Bağlantı İzleme (Stateful Firewall):**

Stateful bir güvenlik duvarı, bağlantıları izler ve sadece mevcut ve doğrulanmış bağlantılara izin verir. Bu, özellikle gelen ve çıkan trafiği yönetmek için önemlidir.

Örnek olarak, bağlantı izlemeyi etkinleştirmek için aşağıdaki komutu kullanabilirsiniz:

```bash
sudo iptables -A INPUT -m state --state ESTABLISHED,RELATED -j ACCEPT
```

**4. Diğer Kural Ekleme ve Düzenleme:**

İhtiyaca göre başka kuralar ekleyebilirsiniz. Örneğin, web sunucusu (HTTP ve HTTPS) trafiğini izin vermek için:

```bash
sudo iptables -A INPUT -p tcp --dport 80 -j ACCEPT   # HTTP
sudo iptables -A INPUT -p tcp --dport 443 -j ACCEPT  # HTTPS
```

**5. Kuralları Kaydetme:**

Kuralları oluşturduktan sonra, bunları kalıcı hale getirmeniz gerekir, böylece yeniden başlattığınızda kaybolmazlar. Bu, farklı Linux dağıtımlarında farklı komutlar gerektirebilir. Örneğin, Debian/Ubuntu'da **`iptables-persistent`** paketini kullanabilirsiniz:

```bash
sudo apt-get install iptables-persistent
sudo service iptables-persistent start
```

**6. Güvenlik Duvarını Etkinleştirme:**

Son olarak, güvenlik duvarınızı etkinleştirmeniz gerekiyor:

```bash
sudo iptables -L  # Kuralları kontrol etmek için
sudo service iptables restart  # Güvenlik duvarını yeniden başlatmak için
```

Bu adımlar, iptables kullanarak temel bir güvenlik duvarı yapılandırmanıza yardımcı olacaktır.

---

**Firewall Yapılandırması - Firewalld** 

Firewalld, özellikle CentOS ve Fedora gibi dağıtımlarda kullanılan bir güvenlik duvarı aracıdır.

1. Terminali açın.
2. Firewalld'yi yüklemek için aşağıdaki komutları kullanın:
    
    ```bash
    sudo yum install firewalld   # CentOS
    sudo dnf install firewalld   # Fedora
    ```
    
3. Firewalld'yi başlatın:
    
    ```sql
    sudo systemctl start firewalld
    ```
    
4. Servisleri eklemek veya kaldırmak için aşağıdaki gibi komutları kullanabilirsiniz:
    
    ```csharp
    sudo firewall-cmd --add-service=http --permanent   # HTTP servisine izin verme
    sudo firewall-cmd --remove-service=ssh --permanent  # SSH servisini kaldırma
    sudo firewall-cmd --reload   # Yapılandırmaları yeniden yükleme
    ```
    

---

Bu adımlarla, seçtiğiniz güvenlik duvarı aracını kullanarak Linux sistemine bir güvenlik duvarı kurabilirsiniz. İzinleri eklerken, sistem gereksinimlerinize ve güvenlik politikalarınıza uygun olarak yapmanız önemlidir.

---

**SSH Anahtarları ve OpenSSH**

SSH anahtarları, güvenli uzak erişim (SSH) protokolünün **kimlik doğrulama yöntemi** olarak kullanılan şifre yerine daha güvenli bir alternatiftir. SSH anahtarları, genellikle bir çift halinde gelir: özel anahtar (private key) ve genel anahtar (public key). Bu anahtarlar, ağa erişim sağlayan sistemler arasında kimlik doğrulama ve güvenli veri iletişimi için kullanılır.

!https://upload.wikimedia.org/wikipedia/commons/c/c9/Client-server-model.svg

Anahtarların çalışma prensibi şu şekildedir:

1. **Genel Anahtar (Public Key):** Bu anahtar, diğer taraflara **açık bir şekilde dağıtılabilir**. Sunucunun SSH yapılandırmasında bu anahtar kaydedilir. Genel anahtar, dijital imza ve şifrelemeyi yapmak için kullanılır.
2. **Özel Anahtar (Private Key):** Bu anahtar, sadece **sahibinin elinde bulunmalıdır.** Özel anahtar, genel anahtarla eşleşen bir anahtardır. Bu anahtar, kimlik doğrulama sürecinde sunucuya gönderilir.

SSH anahtarları, güvenlik sağlamanın yanı sıra, **otomatik giriş** ve **anahtar tabanlı oturum açma** gibi kolaylıklar sunar. Anahtarlar kullanıldığında, parolaları sürekli girmek yerine anahtarınızın sahip olduğu yetkiye bağlı olarak sistemlere erişebilirsiniz.

Anahtar yönetimi ve güvenliği çok önemlidir. Anahtarlarınızı güvenli bir şekilde saklamalı, başkalarıyla paylaşmamalı ve şifrelemeli bir ortamda korumalısınız. Ayrıca, anahtarınızın şifrelenmesi ve bir parola ile korunması da iyi bir uygulamadır.

!https://upload.wikimedia.org/wikipedia/commons/0/0f/Ssh_binary_packet_alt.svg

**SSH binary package**, genellikle SSH (Secure Shell) protokolünü uygulayan bir istemci yazılımının veya sunucu yazılımının derlenmiş ve paketlenmiş sürümünü ifade eder. SSH, güvenli bir şekilde **uzak erişim sağlamak ve dosya transferi yapmak** için kullanılan bir **kriptografik ağ protokolüdür.**

SSH istemci yazılımları, uzak sunuculara erişmek ve komutları çalıştırmak için kullanılırken, SSH sunucu yazılımları gelen bağlantıları kabul eder ve kimlik doğrulama ve şifreleme sağlar.

SSH yazılımı genellikle dağıtılmış (compiled) ve paketlenmiş halde gelir, böylece kullanıcılar bu yazılımları kolayca kurabilirler. Farklı işletim sistemleri için çeşitli SSH istemcileri ve sunucuları bulunmaktadır. Örneğin, popüler SSH istemcisi "**OpenSSH**", çoğu Linux dağıtımı ve diğer Unix benzeri işletim sistemlerinde bulunur.

Eğer belirli bir SSH istemcisi veya sunucu yazılımını kurmak istiyorsanız, kullandığınız işletim sistemine ve dağıtımına uygun olarak bu yazılımı indirebilir ve kurabilirsiniz. Paket yöneticileri (örneğin **`apt`**, **`yum`**, **`dnf`**, **`pacman`** gibi) kullanarak yazılımı kurabilirsiniz. Ayrıca, bu yazılımların resmi web siteleri genellikle indirme ve kurulum talimatları sunar.

---

**OpenSSH**

OpenSSH, Açık Güvenli Kabuk anlamına gelir ve ağ bağlantı araçlarının şifrelenmiş iletişim oturumları sağlamak için kullanılan bir **açık kaynaklı yazılım paketidir**. SSH (Güvenli Kabuk) protokolünü kullanarak bir bilgisayar ağı üzerinden şifrelenmiş iletişim oturumları sağlamak amacıyla geliştirilmiştir. İlk olarak özel SSH yazılımına ücretsiz bir alternatif olarak geliştirilmiştir ve uzak oturum açma oturumları ve diğer ağ hizmetlerini güvence altına almak için geniş bir şekilde kullanılır.

OpenSSH'nin temel özellikleri şunlardır:

1. **Güvenli Uzak Erişim:** OpenSSH, güvenli uzak erişimi sağlar. Kullanıcıların, geleneksel parola tabanlı yöntemlerden çok daha güvenli olan **kriptografik kimlik doğrulama** kullanarak uzaktaki bir sunucuya uzaktan oturum açmasına olanak tanır.
2. **Şifrelenmiş İletişim:** İstemci ve sunucu arasındaki tüm iletişim, giriş kimlik bilgileri, komutlar ve veri transferleri dahil olmak üzere **şifrelenir**. Böylece gizlilik sağlanır ve **dinlemeye karşı koruma** sağlanır.
3. **Port Yönlendirme:** OpenSSH, farklı türlerde port yönlendirmeyi destekler. Bu, yerel bir makine ile uzak bir sunucu arasında ağ trafiğini güvenli bir şekilde yönlendirmek için **güvenli tüneller oluşturmaya olanak tanır**. Bu, güvenlik duvarlarının arkasındaki kaynaklara erişmek veya uzak ağlardaki hizmetlere güvenli erişim sağlamak için kullanışlı olabilir.
4. **Güvenli Dosya Transferi:** OpenSSH, istemci ve sunucu arasında güvenli dosya transferini sağlayan **`sftp`** (Güvenli Dosya Transfer Protokolü) alt sistemini içerir. Bu, komut satırı arayüzü veya grafik araçları kullanarak **güvenli bir şekilde dosya transferi yapmayı sağlar.**
5. **Tünel Oluşturma:** OpenSSH, yerel ve uzak port yönlendirme, dinamik port yönlendirme (SOCKS vekil sunucusu oluşturma) gibi **çeşitli tünel seçeneklerini destekler.** Bu özellikler genellikle uzak ağlardaki hizmetlere ve kaynaklara güvenli erişim sağlamak için kullanılır.
6. **X11 Yönlendirme:** OpenSSH, şifrelenmiş bir bağlantı üzerinden grafiksel kullanıcı arayüzlerini (GUI'leri) iletebilir. Bu, kullanıcıların uzak bir sunucuda **GUI uygulamalarını çalıştırmasına** ve bunları yerel olarak görüntülemesine olanak tanır.
7. **Genel Anahtar Kimlik Doğrulama:** OpenSSH ile en yaygın kullanılan kimlik doğrulama yöntemlerinden biri genel anahtar kimlik doğrulamasıdır. Kullanıcılar **bir anahtar çifti oluştururlar** (genel anahtar ve özel anahtar), **genel anahtar uzak sunucuya yerleştirilirken özel anahtar yerel makinede tutulur**. Bu yöntem parolalara gerek kalmadan daha güçlü bir güvenlik sağlar.
8. **Ana Makine Tabanlı Kimlik Doğrulama:** OpenSSH ayrıca ana makine tabanlı kimlik doğrulamayı da destekler. Bu, belirli anahtarların ana makine tabanlı kimlik doğrulama kullanarak kimlik doğrulamasına izin verdiği anlamına gelir.

OpenSSH, **Linux**, **macOS** gibi **Unix** benzeri işletim sistemleri ve hatta üçüncü taraf bağlantı noktaları veya uygulamalar aracılığıyla **Windows** gibi çeşitli platformlarda **kullanılabilir**. Güvenli sistem yönetimi ve ağ işlemlerinin ayrılmaz bir parçası haline gelmiş olup, sistem yöneticileri, geliştiriciler ve güvenlik uzmanları tarafından uzak sistemleri ve hizmetleri yönetmek ve güvence altına almak için geniş bir şekilde kullanılmaktadır.

---

**Linux sunucusunda uzaktan komut çalıştırmak**

Linux sunucusunda uzaktan komut çalıştırmak için genellikle SSH (Secure Shell) protokolü kullanılır. SSH, güvenli bir şekilde uzaktan sunucuya erişim sağlayan bir protokoldür. İşte Linux sunucusunda uzaktan komut çalıştırmak için adımlar:

1. **SSH Sunucu Kontrolü:**
Uzaktan komut çalıştırmadan önce, uzak Linux sisteminizde SSH servisinin yüklü olduğundan emin olun. 
    
    ***SSH Servisini Kontrol Etme:**
    Hedef Linux sisteminde SSH servisinin yüklü olup olmadığını kontrol etmek için aşağıdaki komutu kullanabilirsiniz:*
    
    ```bash
    systemctl status ssh
    ```
    
    *Eğer SSH servisi yüklü ise, komut çıktısında durumu görünecektir. "active" veya "running" olarak belirtilmelidir.*
    
    ***SSH Servisini Kurma:**
    Eğer hedef sisteminizde SSH servisi yüklü değilse, aşağıdaki komutu kullanarak SSH servisini kurabilirsiniz (Debian/Ubuntu örneği):*
    
    ```bash
    sudo apt-get install openssh-server
    ```
    
    *Dağıtımınıza göre farklı komutlar veya yöntemler kullanmanız gerekebilir. SSH servisini kurduktan sonra, servisi başlatmak ve otomatik olarak başlamasını sağlamak için şu komutları kullanabilirsiniz:*
    
    ```bash
    sudo systemctl start ssh
    sudo systemctl enable ssh
    ```
    
    ***SSH Servisini Başlatma ve Durdurma:**
    Hedef sisteminizde SSH servisini başlatmak, durdurmak veya yeniden başlatmak için şu komutları kullanabilirsiniz:*
    
    ```bash
    sudo systemctl start ssh   # SSH servisini başlatma
    sudo systemctl stop ssh    # SSH servisini durdurma
    sudo systemctl restart ssh # SSH servisini yeniden başlatma
    ```
    
    *Ayrıca, güvenlik duvarı aktif ise, ssh portuna izin vermeniz gerekecektir.*
    
    ```bash
    sudo ufw allow ssh
    ```
    
    *Unutmayın ki SSH servisi güvenli bir şekilde yapılandırılmalıdır. Şifre tabanlı oturum açma yerine SSH anahtarları kullanmak, güvenliğinizi artıracaktır. Ayrıca, gereksiz açık portları ve erişim izinlerini sınırlamak da önemlidir*.
    
    Güvenlik duvarınızda SSH erişimini etkinleştirmek için kullanılır. SSH (Secure Shell), uzak sunuculara güvenli bir şekilde erişim sağlamak için kullanılan bir protokoldür.
    
    Bu komut, güvenlik duvarınızda gelen SSH bağlantılarına izin vermek için gerekli olan portu (genellikle **22** numaralı port) açar. Eğer sunucunuzda SSH bağlantısı sağlayacaksanız, bu komutu kullanarak SSH erişimini etkinleştirebilirsiniz.
    
    Komutu çalıştırdıktan sonra **`ufw`** güvenlik duvarı kuralı aşağıdaki gibi ekleyecektir:
    
    ```bash
    To                         Action      From
    --                         ------      ----
    OpenSSH                    ALLOW       Anywhere
    ```
    
    **OpenSSH : 22/tcp**
    
    Bu kural, herhangi bir kaynaktan gelen SSH trafiğine izin verir.
    
    *Hatırlatma: SSH erişimini açtığınızda güvenlik duvarınızın diğer ağ erişimlerini de gözden geçirmeli ve gereksiz açık portları kapatmalısınız. Ayrıca, güçlü şifreler veya SSH anahtarlarını kullanarak güvenliği artırmanız önemlidir*.
    
2. **Uzaktaki Sunucuya Bağlanma:**
Terminali açın ve aşağıdaki SSH istemcisi komutunu kullanarak uzaktaki sunucuya bağlanın:
    
    ```php
    ssh <KULLANICI_ADI>@<SUNUCU_IP_ADRESI>
    ```
    
    *SSH istemcisi genellikle Linux dağıtımlarının bir parçası olarak gelir, bu nedenle çoğu Linux sistemi SSH istemcisini varsayılan olarak içerir. Ancak, bu kesinlikle dağıtıma ve kurulum ayarlarına bağlıdır. Siz de şu komutu kullanarak SSH istemcinin yüklü olup olmadığını kontrol edebilirsiniz:*
    
    ```bash
    which ssh
    ```
    
    *Eğer çıktı olarak bir dosya yolu görürseniz, bu SSH istemcisinin yüklü olduğunu gösterir. Eğer bir çıktı alamazsanız, SSH istemcisinin yüklü olmadığı anlamına gelebilir.*
    
    *SSH istemcisi yüklü değilse, çoğu Linux dağıtımında SSH istemcisini yüklemek için aşağıdaki komutu kullanabilirsiniz (Debian/Ubuntu örneği):*
    
    ```bash
    sudo apt-get install openssh-client
    ```
    
    *Yukarıdaki komut, Debian veya Ubuntu tabanlı sistemlerde SSH istemcisini yükler.*
    
    **`<KULLANICI_ADI>`** yerine uzaktaki sunucuda sahip olduğunuz kullanıcı adını, **`<SUNUCU_IP_ADRESI>`** ise sunucunun IP adresini girin. Komutu çalıştırdığınızda, şifrenizi girmeniz istenecektir.
    
    **SSH istemcisinin sunucunun kimliğini doğrulamak isteyip istemediğini soran bir onay çıktısı getiriyor ise**,
    
    ```bash
    The authenticity of host 'vm (fe80::7d56:c132:4748:dc4b%27)' can't be established.
    ED25519 key fingerprint is SHA256:6BRU3Jw1R8rQJMCC8X1Kd0bj2xijs/vSxxE4QnDc51o.
    This key is not known by any other names
    Are you sure you want to continue connecting (yes/no/[fingerprint])
    ```
    
    Istemcisinin **ilk kez** belirtilen IP adresi veya host ismi ile bağlantı kurduğunda ortaya çıkan bir güvenlik uyarısıdır. Mesajda yer alan bilgiler, uzaktaki sunucunun kimliğini doğrulamak için kullanılır. Şimdi mesajın içeriğini adım adım açıklayalım:
    
    - "The authenticity of host 'vm (fe80::7d56:c132:4748:dc4b%27)' can't be established.":
    Bu kısım, belirtilen IP adresi veya host ismi ile sunucuya ilk kez bağlanıldığını ve sunucunun kimliğinin henüz doğrulanmadığını belirtir.
    - "ED25519 key fingerprint is **SHA256**:6BRU3Jw1R8rQJMCC8X1Kd0bj2xijs/vSxxE4QnDc51o.":
    Bu satır, sunucunun ED25519 anahtarının parmak izini ve SHA256 algoritması ile hesaplanmış bir özetini içerir. Bu anahtar parmak izi, sunucunun kimliğini teyit etmek için kullanılır.
    - "This key is not known by any other names":
    Bu kısım, sunucu anahtarının başka isimler altında bilinmediğini belirtir. Yani sunucunun kimliği, belirtilen anahtar parmak izi dışında farklı bir isimle bilinmiyor.
    - "Are you sure you want to continue connecting (yes/no/[fingerprint])?":
    Bu kısım, **SSH istemcisinin** sunucunun kimliğini doğrulamak isteyip istemediğini sorar. Eğer bu sunucuya güveniyorsanız ve parmak izini doğruladıysanız "yes" (evet) yanıtını vermelisiniz. Ayrıca, sunucunun anahtar parmak izini değişmediğinden emin olmak için önceki bağlantılardaki anahtar parmak izini ile **karşılaştır**abilirsiniz.
    
    **Değişmiş bir ana bilgisayar anahtarı uyarısıyla karşılaşıyorsanız.**
    
    ```bash
    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    @    WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!     @
    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    ..
    .
    SHA256:HMl7P8aDpSPj.......
    ```
    
    Bu uyarı, uzaktaki sunucunun kimliği veya şifreleme anahtarının son bağlandığınız zamandan bu yana değiştiğini belirtiyor. Bu, sunucunun yeniden kurulması, taşınması veya tehlikeye düşmesi gibi çeşitli nedenlerle meydana gelebilir. Uyarı, güvenlik riski olabileceğinizi fark etmeniz için görüntülenir.
    
    Uyarıdaki anahtar parmak izi (SHA256:HMl7P8aDpSPj....) , SSH anahtarı için benzersiz bir tanımlayıcıdır. Bu, doğru sunucuya bağlandığınızı ve kötü niyetli üçüncü bir taraf tarafından *araya girilmediğinizi* doğrulamanıza yardımcı olur.
    
    - **Sistem Yöneticisiyle İletişime Geçin:** Kuruluşunuz içindeki bir sunucuya veya güvendiğiniz bir hizmete bağlanıyorsanız, sistem yöneticinizle iletişime geçerek anahtarın gerçekten değişip değişmediğini onaylayabilirsiniz.
    - **Bilinen Anahtarlar Dosyasını Güncelleyin:** Anahtar değişiminin geçerli olduğundan eminseniz (örneğin, size bildirildiyse), .ssh/**`known_hosts`** dosyanızdaki sorunlu anahtar girdisini kaldırabilir ve ardından yeniden bağlanabilirsiniz. Bu anahtarın tamamını veya sadece ilgili satırı silebilirsiniz.
    - **Anahtarı Doğrulayın:** Yeni anahtarın parmak izini, sunucu yöneticisi veya belgelendirme gibi güvendiğiniz bir kaynakla doğrulayabilirsiniz. Bağlanmaya çalıştığınız sunucunun **istenen sunucu** olduğundan emin olun.
    - **Riski Değerlendirin:** Anahtar değişiminin geçerliliği konusunda emin değilseniz ve doğrulayamıyorsanız, bağlantıya devam etmemek daha güvenli olacaktır. “Ortadaki adam” saldırıları ciddi bir güvenlik riskidir, bu nedenle uzaktaki sunucunun doğruluğundan emin olmak **son derece önemlidir**.
    
3. **Komut Çalıştırma:**
Bağlantı kurulduktan sonra (şunun gibi bir ekran ile karşılaşırsınız), 
    
    ```bash
    kullaniciadi@sunucuip:~$
    ```
    
    komutları doğrudan uzaktaki sunucuda çalıştırabilirsiniz. 
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/c186b2fa-7f1d-44a4-8b22-6aad04bc1ca4/Untitled.png)
    
4. **Bağlantıyı Sonlandırma:**
İşiniz bittiğinde bağlantıyı sonlandırmak için terminalde **`exit`** komutunu kullanabilirsiniz.

Eğer uzaktaki komutları **otomatik olarak çalıştırmak istiyorsanız**, SSH'deki "**komut geçişi**" özelliğini kullanabilirsiniz. Bu, SSH komutu ile direkt olarak uzaktaki komutu birleştirerek çalıştırmanızı sağlar. Örneğin:

```bash
ssh kullaniciadi@sunucuip "ls -l /path/to/directory"
```

Bu komut uzak sunucu üzerinde çalıştırılır ve geri dönülür.

Unutmayın ki SSH ile uzaktan erişim güvenlik önemli olduğundan, **güçlü şifreler veya SSH anahtarları kullanmanızı öneririm**. Ayrıca, uzaktan sunucuya erişim izinlerini sadece gerektiği kadar açık tutmaya dikkat edin.

---

**SSH anahtarları kullanarak uzaktan erişim**

SSH anahtarları kullanarak uzaktan erişim sağlamak, daha güvenli ve kolay bir yöntemdir. 

1. **Anahtar Çifti Oluşturma:**
İlk adım, bir SSH anahtar çifti oluşturmaktır. Bu çift, bir *genel anahtar* ve *bir özel anahtardan* oluşur. *Genel anahtar* **sunucuya** yerleştirilirken, *özel anahtar* **lokal** cihazınızda saklanmalıdır.
    
    Anahtar çiftini oluşturmak için aşağıdaki komutu **lokal** cihazınızda kullanabilirsiniz:
    
    ```bash
    ssh-keygen -t ed25519 -C "your_email@example.com"
    ```
    
    Bu komut, **ED25519** tipinde bir anahtar çifti oluşturur. **`-C`** parametresi ile e-posta adresinizi belirtebilirsiniz.
    
    **passphrase** : SSH anahtarınızı oluştururken özel anahtara (private key) eklemek isteyip istemediğinizi sorduğu bir adımdır. Özel anahtarınıza bir parola (passphrase) eklemek, ekstra bir güvenlik katmanı sağlar.
    
    Parolanızı girdiğinizde, özel anahtarınızın kullanımı için her seferinde bu parolayı girmeniz gerekecektir. Bu, özel anahtarın sızdırılması durumunda bile yetkisiz erişimi zorlaştırır. Eğer parola eklemek istemiyorsanız, boş bırakabilirsiniz, bu da "**no passphrase**" (parolasız) anlamına gelir.
    
    Özel anahtar (private key) dosyanız genellikle **`~/.ssh/id_ed25519`** şeklinde oluşturulur.
    
    Anahtar oluşturulduğunda aşağodaki gibi bir çıktı alırsınız.
    
    ```bash
    The key fingerprint is:
    SHA256:Vw6ovnAzkPd4LsviF3/208Rckjwa/T1sxw+EUtTcqn0 your_email@example.com
    The key's randomart image is:
    +--[ED25519 256]--+
    |           ..o . |
    |         .  . o .|
    |        . ...+ o |
    |     . .  .+o O .|
    |    o o S ...O.*.|
    |     +.o .  o *+E|
    |    . *oo    o.o+|
    |    .+o*. o . . .|
    |   ..o+o.o ...   |
    +----[SHA256]-----+
    ```
    
2. **Genel Anahtarı Sunucuya Eklemek:**
Oluşturulan genel anahtarı, uzak sunucuya eklemeniz gerekmektedir. Bu, sunucunun sizinle güvenli bir şekilde iletişim kurabilmesini sağlar.
    
    
    Genel anahtarınızın içeriğini kopyalamak için aşağıdaki komutu kullanabilirsiniz:
    
    ```bash
    # Anahtarı görüntüleyin
    # windows için : cd .ssh && type id_ed25519.pub
    cat ~/.ssh/id_ed25519.pub
    ssh-ed25519 AAAAC3NzaC1lZDI1NT...your_email@example.com
    
    # uzak sunucuya bağlanın
    ssh kullaniciadi@sunucuip
    
    # Sonra bu anahtarı uzak sunucunun **~/.ssh/authorized_keys** dosyasına ekleyin
    echo "kopyalanan_genel_anahtar" >> ~/.ssh/authorized_keys
    
    #  çıkış yapın
    exit
    ```
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/22e802b3-ada8-4de7-b6b7-b6ea3255ee0a/Untitled.png)
    
    ```bash
    # uzak sunucuya bağlantısını test edin.
    ssh kullaniciadi@sunucuip
    
    # SSH Anahtarınıza bir parola belirledi iseniz, bu parola ile giriş yapın
    ```
    
3. **Uzaktan Bağlanma:**
Anahtarlar doğru şekilde ayarlandığında, uzak sunucuya bağlanmak için aşağıdaki komutu kullanabilirsiniz:
    
    ```bash
    ssh username@remote_host
    ```
    
    Burada **`username`**, uzak sunucudaki kullanıcı adınızı; **`remote_host`**, uzak sunucunuzun IP adresini veya alan adını temsil eder.
    
    Eğer özel anahtarınıza bir parola eklediyseniz, bağlanırken bu parolayı girmeniz istenecektir.
    

*Bu adımları takip ederek SSH anahtarlarıyla uzaktan erişim sağlayabilirsiniz. Anahtar tabanlı kimlik doğrulama, güçlü bir güvenlik katmanı sağlar ve şifre tabanlı kimlik doğrulamaya göre daha zor çözülebilir. Anahtarları güvende tutmanız, güvenliğinizi sağlamak açısından kritiktir.*

---

**Apache HTTP Sunucu**

Apache Software Foundation (ASF) tarafından geliştirilen Apache projeleri genellikle açık kaynaklı yazılım ve veri işleme alanında kullanılan çok sayıda projeyi içerir.

**Temel Bilgiler:**
Apache projeleri hakkında temel bilgilere sahip olmak önemlidir. ASF'nin web sitesi (**https://www.apache.org/**) projeler hakkında temel bilgileri içerir. Ayrıca, Apache Yazılım Vakfı'nın misyonunu ve açık kaynak yazılımın önemini anlamak da faydalı olabilir.

**Linux İşletim Sistemi Kullanımı:**
Apache projelerinin çoğu Linux tabanlı sistemlerde kullanılır. Linux işletim sistemi ve temel komutları hakkında bilgi sahibi olmak, Apache projeleriyle çalışırken size yardımcı olacaktır.

**Apache HTTP Sunucusu:**
Apache HTTP Sunucusu (httpd) dünyanın en popüler web sunucularından biridir. Web sunucularını kurmayı ve yapılandırmayı öğrenmek için Apache HTTP Sunucusu hakkında belgeleri inceleyebilirsiniz. (**https://httpd.apache.org/docs/**)

**Apache Maven:**
Apache Maven, proje yönetimi ve otomasyonu için kullanılan bir araçtır. Özellikle Java tabanlı projeler için yaygın olarak kullanılır. Maven hakkında bilgi edinmek, Apache projeleriyle çalışırken bağımlılık yönetimi ve yapım süreçlerini daha iyi anlamanıza yardımcı olacaktır.

**Hadoop ve Big Data Projeleri:**
Eğer büyük veri işleme ve analizi ile ilgileniyorsanız, Apache Hadoop gibi büyük veri projelerini incelemeye başlayabilirsiniz. Hadoop, Apache'nin büyük veri işleme ekosisteminin temelini oluşturur. Apache Spark, Apache Hive ve Apache HBase gibi diğer büyük veri projelerini de öğrenmek isteyebilirsiniz.

**Apache Kafka:**
Apache Kafka, dağıtık akış işleme ve olay günlüğü hizmeti sağlayan bir projedir. Veri akışlarıyla çalışmayı öğrenmek istiyorsanız Apache Kafka'yı inceleyebilirsiniz.

**Apache Cassandra veya Apache CouchDB:**
Apache Cassandra ve Apache CouchDB gibi NoSQL veritabanlarına ilgi duyuyorsanız, bu projeleri inceleyebilirsiniz. Bunlar, dağıtık ve ölçeklenebilir veritabanlarıdır.

**Diğer Apache Projeleri:**
ASF, birçok farklı alanda projeler geliştirmektedir. İlgilendiğiniz alana bağlı olarak, Apache projeleri arasından seçim yapabilirsiniz. Örneğin, veri analitiği, yapay zeka, güvenlik, metin madenciliği veya veri işleme gibi birçok farklı konuda Apache projeleri bulunmaktadır.

---

**Apache HTTP Sunucusu**, genellikle sadece "Apache" olarak adlandırılan, açık kaynaklı ve ücretsiz bir **web sunucusu** yazılımıdır. İnternet üzerinde web sitelerini yayınlamak, web sayfalarını sunmak, dinamik içerik üretmek ve istemcilere (tarayıcılara) sunmak için kullanılır. Apache, oldukça popüler ve geniş bir kullanıcı tabanına sahip bir web sunucusu çözümüdür.

**Apache HTTP Sunucu - Kurulumu**

Apache HTTP Server'ı kurmak için, işletim sisteminize uygun komutları kullanmanız gerekebilir. Örneğin, `Ubuntu` tabanlı bir sistemde:

```bash
sudo apt update
sudo apt install apache2
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/4082cbc9-21a1-405c-b3e1-9ad926b0a5fd/Untitled.png)

---

**Apache HTTP Sunucu - Yapılandırma**

Apache kurulumunu tamamladıktan sonra, web sitelerini yönetmek için aşağıdaki temel adımları takip edebilirsiniz:

- Web sitenizin dosyalarını genellikle **`/var/www/html`** dizininde barındırırsınız. Bu dizine web sayfalarınızı yükleyebilirsiniz.
- Apache'nin ana konfigürasyon dosyası genellikle **`/etc/apache2/apache2.conf`**olarak bulunur. Burada **genel ayarlar** ve **sanal ana bilgisayarlar** (Virtual Hosts) gibi **yapılandırmaları** yapabilirsiniz.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/0ce88a46-8d57-4df4-bc4c-41186fd131ec/Untitled.png)

---

**Apache HTTP Sunucu - Sanal Sunucular**

Apache, birden fazla web sitesini aynı sunucuda barındırmak için "Virtual Hosts" adı verilen bir mekanizma sağlar. Her bir sanal ana bilgisayar, kendi alan adı veya IP adresi üzerinden erişilebilen bağımsız bir web sitesi gibi davranır.

Örneğin Ubuntu tabanlı bir sistemde varsayılan siteler **`/etc/apache2/sites-available/000-default.conf`** dosyasında yer alır.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/dac01acf-3bd7-4a63-89dd-3b1d4f1c2572/Untitled.png)

Sunucunun dinlediği portlar ise `**/etc/apache2/ports.conf`** dosyasında yer alır.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/5fdf0fa0-ee9c-477f-bf2f-4f2b85f95ad1/Untitled.png)

Sanal ana bilgisayar eklemek için örnek bir adım:

- Sanal ana bilgisayar yapılandırma dosyasını düzenleyin. 
**`/etc/apache2/sites-available/000-default.conf`**
    
    ```bash
    <VirtualHost *:80>
            DocumentRoot /var/www/html/site-001
    </VirtualHost>
    
    <VirtualHost *:81>
            DocumentRoot /var/www/html/site-002
    </VirtualHost>
    ```
    
- Port bilgilerini güncelleyin  `**/etc/apache2/ports.conf**`
    
    ```bash
    Listen 80
    Listen 81
    
    <IfModule ssl_module>
    Listen 443
    </IfModule>
    
    <IfModule mod_gnutls.c>
    Listen 443
    </IfModule>
    ```
    
- İçeriği düzenleyerek sunucu adını, IP adresini, dizin yolunu ve diğer ayarları belirtin.
    
    *Sanal anahtarın belirtildiği **port** ile Apache **konfigürasyonu** arasında **uyumsuzluk** olmamasını sağlayın. Örnekteki **`<VirtualHost *:81>`** ile Apache konfigürasyonunuzun 81. portu dinlediğinden emin olun. Apache ayarlarını kontrol etmek için aşağıdaki komutu kullanabilirsiniz:*
    
- Gerekli dizinleri oluşturun.
    
    ```bash
    sudo mkdir /var/www/html/site-001
    sudo mkdir /var/www/html/site-002
    ```
    
    *Dosya yolunu doğru ayarladığınızdan emin olun. Sanal anahtarınızın **`DocumentRoot`** öğesinin **`/var/www/html/site-001`** gibi bir dizin yer almalıdır.* 
    
- Sitenizi yerleştirin
    
    ```bash
    sudo nano /var/www/html/site-001/index.html
    sudo nano /var/www/html/site-001/index.html
    ```
    
    *Bu dizinin var olduğundan ve içinde "index.html" dosyasının bulunduğundan emin olun.*
    
- İzinleri gözden geçirin.
    
    ```bash
    sudo chown -R www-data:www-data /var/www/html/site-001
    sudo chown -R www-data:www-data /var/www/html/site-002
    
    sudo chmod -R 755 /var/www/html/site-001
    sudo chmod -R 755 /var/www/html/site-002
    ```
    
    D*osyaların doğru izinlere sahip olduğundan emin olmak için aşağıdaki komutları kullanabilirsiniz:*
    
    Not: **`*chown`**, "change owner"ın kısaltmasıdır ve Linux/Unix işletim sistemlerinde dosya veya dizinlerin sahipliğini değiştirmek için kullanılır.*
    
    ```bash
    chown [seçenekler] [kullanıcı:grup] [dosya_veya_dizin]
    ```
    
- Sanal ana bilgisayarı etkinleştirmek için:

```bash
sudo systemctl reload apache2
```

İşlem günlüklerini incelemek için aşağıdaki parametreleri kullanabilirsiniz.

```bash
*sudo grep -R "Listen" /etc/apache2/*
```

Aşağıdaki gibi bir çıktı görüntülüyor olmalısınız.

```bash
/etc/apache2/ports.conf:Listen 80
/etc/apache2/ports.conf:Listen 81
/etc/apache2/ports.conf:Listen 443
/etc/apache2/ports.conf:Listen 443
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/54226be1-00c4-42dd-871c-f672c0426f2a/Untitled.png)

**Servisi Yönetme**

- Apache servisini başlatmak için: **`sudo systemctl start apache2`**
- Apache servisini durdurmak için: **`sudo systemctl stop apache2`**
- Apache servisini yeniden başlatmak için: **`sudo systemctl restart apache2`**
- Apache servisinin durumunu kontrol etmek için: **`sudo systemctl status apache2`**

---

**Apache HTTP Sunucu - Modüller**

Apache HTTP Sunucusu, modüler bir yapıya sahiptir ve işlevselliği modüller aracılığıyla sağlar. Bu modüller, sunucunun özelliklerini genişletmek ve özelleştirmek için kullanılır. 

**mod_ssl**: Bu modül, sunucunuzun SSL/TLS (Güvenli Yuva Katmanı/Transport Layer Security) şifrelemesi ve HTTPS desteği ekler. SSL sertifikası kullanarak güvenli iletişim sağlamak için kullanılır.

**mod_rewrite**: Bu modül, URL yeniden yazımı ve yönlendirme için kullanılır. Dinamik URL'leri daha anlaşılır ve SEO dostu hale getirebilir ve trafik yönlendirmesi yapabilirsiniz.

**mod_proxy**: Bu modül, sunucunuzun proxy sunucusu olarak çalışmasını sağlar. Bu, yük dengelemesi yapmak veya sunucunuzun arkasındaki uygulamalara erişim sağlamak için kullanılır.

**mod_auth**: Bu modül, kullanıcı kimlik doğrulama ve yetkilendirme için kullanılır. Kullanıcı adı ve şifre ile korunan bölgelere erişim kontrolü sağlar.

**mod_headers**: Bu modül, HTTP başlıklarını işlemek için kullanılır. Özellikle özel başlıklar eklemek veya mevcut başlıkları düzenlemek için kullanılır.

**mod_expires**: Bu modül, önbellekleme (caching) için kullanılır. İçerik önbelleklemesi, web sitenizin hızını artırabilir ve sunucu yükünü azaltabilir.

**mod_deflate/mod_gzip**: Bu modüller, sunucu tarafı sıkıştırma sağlar. Bu, web sayfalarının daha hızlı yüklenmesine ve daha az bant genişliği kullanılmasına yardımcı olabilir.

**mod_security**: Bu modül, web uygulama güvenliği için bir güvenlik duvarı ekler. Web saldırılarına karşı koruma sağlayabilir ve güvenliği artırabilir.

**mod_cgi/mod_cgid**: Bu modüller, CGI (Common Gateway Interface) betiklerini çalıştırmak için kullanılır. Dinamik içerik oluşturmak için kullanılır.

**mod_alias**: Bu modül, URL yönlendirmesi ve yeniden adlandırma için kullanılır. Özellikle 301 ve 302 yönlendirmeleri oluşturmak için kullanışlıdır.

**mod_userdir**: Bu modül, her kullanıcı için kişisel web dizinleri oluşturmanıza izin verir. Kullanıcıların ~username şeklinde erişebileceği kişisel web sayfalarını barındırmak için kullanılır.

**mod_autoindex**: Bu modül, bir dizinin otomatik dizin listesini oluşturur. Bu, bir dizindeki dosyaların ve alt dizinlerin listesini sunar.

---

**Apache HTTP Sunucu - Güvenlik**

Apache HTTP Sunucusu'nun güvenliğini sağlamak, web sitenizin ve sunucunuzun korunması için kritik bir öneme sahiptir. 

**Güncellemeleri Takip Edin:**
Apache HTTP Sunucusu'nun güncellemelerini ve yamalarını düzenli olarak takip edin ve sunucunuzu en son sürüme güncelleyin. Güncellemeler genellikle güvenlik düzeltmelerini içerir.

**Dosya İzinleri Kontrol Edin:**
Sunucunuzdaki dosya ve dizinlerin izinlerini sıkı bir şekilde kontrol edin. Web kök dizini dahil olmak üzere gereksiz dosya ve dizin erişimini sınırlayın. İzinleri sadece gereken minimum düzeyde verin.

**mod_security Kullanın:`mod_security`** modülünü kullanarak, web uygulama güvenliğinizi artırın. Bu modül, saldırılara karşı koruma sağlar ve kötü amaçlı istekleri engeller.

**SSL/TLS Kullanın:**
HTTPS kullanarak iletişimi şifreleyin. Bu, kullanıcıların verilerini korumak için önemlidir. **`mod_ssl`** veya benzeri bir SSL/TLS modülünü etkinleştirin ve güvenilir bir SSL sertifikası kullanın.

**DoS Saldırılarına Karşı Koruma Sağlayın:**
Sunucunuzu DDoS (Hizmet Reddi Saldırısı) ve benzeri saldırılara karşı korumak için gelişmiş ağ güvenliği önlemleri alın. İhtiyaç durumunda bir DDos saldırı önleyici hizmet kullanmayı düşünün.

**Güçlü Şifreler Kullanın:**
Sunucu yönetici hesapları ve kullanıcı hesapları için güçlü şifreler kullanın. Şifreler düzenli olarak değiştirilmelidir.

**ErrorReporting Kapatın:**
Hata mesajlarını mümkün olduğunca sınırlayın. Hata mesajlarında sunucu bilgilerini ifşa etmemeye dikkat edin. Hata mesajlarından fazla bilgi vermemeye özen gösterin.

**Kötü Amaçlı Yazılım Tara:**
Sunucunuzun kötü amaçlı yazılım içerip içermediğini düzenli olarak tarayın. Antivirüs ve kötü amaçlı yazılım tarayıcıları kullanarak sunucunuzu güvende tutun.

**Günlükleme ve İzleme:**
Sunucu günlüklerini düzenli olarak kontrol edin ve izlemeyi sağlayın. Anormal aktiviteleri tespit etmek ve saldırıları engellemek için günlük verilerini analiz edin.

**Dosya Yükleme Sınırlamaları:**
Eğer kullanıcıların dosya yüklemelerine izin veriyorsanız, yüklenen dosyaların türlerini ve boyutlarını sınırlayın. Güvenilmeyen dosya yüklemelerine karşı koruma sağlayın.

**Güvenlik Duvarı (Firewall) Kullanın:**
Sunucunuzun önünde bir güvenlik duvarı kullanarak gelen ve giden trafiği kontrol edin. İzin verilen trafiği sıkı bir şekilde denetleyin.

**SSH Erişimini Sınırlayın:**
SSH erişimini sınırlayarak sunucunuzun güvenliğini artırın. Yalnızca güvendiğiniz IP adreslerinden SSH erişimine izin verin ve parola tabanlı oturum açmayı devre dışı bırakın.

**Güvenlik İncelemeleri ve Denetimler:**
Periyodik olarak güvenlik incelemeleri yapın ve güvenlik denetimlerini uygulayın. Bu, potansiyel güvenlik açıklarını tespit etmenize ve kapatmanıza yardımcı olur.

**Yedeklemeleri Düzenli Olarak Alın:**
Sunucunuzun verilerini düzenli olarak yedekleyin ve bu yedekleri güvenli bir şekilde saklayın. Veri kaybını önlemek için yedeklemelerinizi test edin.

---

**Apache HTTP Sunucu - Performans Ayarları**

Apache HTTP Sunucusu'nun performansını optimize etmek, web sitenizin hızını artırmak ve daha fazla kullanıcıya hizmet verebilir hale gelmek için önemlidir. Performansı artırmak için aşağıdaki bazı önemli ayarları göz önünde bulundurabilirsiniz:

**MPM (Çoklu İş Parçacığı Modülü) Ayarları:**
Apache, farklı MPM'lerle çalışabilir. Prefork, Worker ve Event gibi MPM'ler, sunucunuzun işlem modelini belirler. Genellikle Worker veya Event MPM'ler, çoklu iş parçacığı kullanarak daha iyi performans sağlar. MPM ayarlarını Apache yapılandırma dosyasında (**`httpd.conf`**) belirleyebilirsiniz.

**KeepAlive Ayarı:**
KeepAlive, tek bir TCP bağlantısının birden fazla HTTP isteği için kullanılmasını sağlar. Bu, tarayıcıların sunucu ile daha az bağlantı kurmasını sağlar ve sayfaların daha hızlı yüklenmesine yardımcı olur. Ancak, aşırı uzun KeepAlive zaman aşımı süreleri sunucunuzun kaynaklarını tüketebilir. Bu ayarı dikkatli bir şekilde yapılandırın.

**MaxClients ve ServerLimit Ayarları:**
MaxClients, sunucunuzun aynı anda hizmet veren maksimum eşzamanlı bağlantı sayısını belirler. ServerLimit ise bu bağlantı sayısını sınırlar. Bu ayarlar, sunucunuzun kaynaklarını verimli bir şekilde kullanmasını sağlar. Sunucunuzun donmasını önlemek için bu değerleri belirlerken fiziksel kaynaklarınızı göz önünde bulundurun.

**Önbellek Kullanımı:**
Önbellek mekanizmaları kullanarak sık kullanılan içeriği önbelleğe alabilirsiniz. Apache modülleri veya önbellek araçları (örneğin, Varnish veya Memcached) kullanarak bu işlemi gerçekleştirebilirsiniz. Önbellekleme, sunucunuzun yanıt sürelerini hızlandırabilir.

**Gzip Sıkıştırması:**
Sunucunuzdan gönderilen içeriği sıkıştırmak için Gzip veya Deflate sıkıştırma yöntemlerini kullanabilirsiniz. Bu, sayfa boyutunu küçültecek ve yükleme sürelerini azaltacaktır.

**Veritabanı Optimizasyonu:**
Eğer web uygulamanız bir veritabanı kullanıyorsa, veritabanı sorgularını optimize etmek ve gereksiz veritabanı erişimlerini azaltmak performansı artırabilir.

**CDN (İçerik Dağıtım Ağı) Kullanımı:**
CDN hizmetleri, statik içeriği sunucunuzdan uzaklaştırarak hızlı dağıtımını sağlar. Bu, özellikle büyük medya dosyaları ve görseller için faydalıdır.

**ServerSignature ve ServerTokens Ayarları:**
ServerSignature ve ServerTokens ayarları, sunucunuzun kimliğini gizlemek için kullanılabilir. Bu, potansiyel saldırganların sunucu hakkında daha az bilgi sahibi olmalarını sağlar.

**Log Dosyalarını İnceleme:**
Apache'nin günlük dosyalarını düzenli olarak kontrol edin ve gereksiz kayıtları devre dışı bırakın. Bu, sunucunuzun kaynaklarını boşa harcamayacaktır.

**SSL Hızlandırma:**
Eğer SSL/TLS kullanıyorsanız, modern şifreleme protokollerini ve cihazları destekleyen donanım veya yazılım tabanlı SSL hızlandırma teknolojilerini kullanarak SSL hızını artırabilirsiniz.

---

**Apache HTTP Sunucu - Hata Ayıklama ve Günlükleme**

Apache HTTP Sunucusu'nda hata ayıklama ve günlükleme (logging) önemli bir rol oynar. Bu, sunucunun sağlığını izlemenize, sorunları tespit etmenize ve çözmenize yardımcı olur. İşte Apache HTTP Sunucusu'nda hata ayıklama ve günlükleme yapmak için izlenebilecek adımlar:

1. **Hata Günlüğünü Etkinleştirme:**
Apache'nin hata günlüğünü etkinleştirmek için **`httpd.conf`** veya ilgili yapılandırma dosyanızda **`ErrorLog`** direktifini ayarlayın. Örneğin:
    
    ```arduino
    ErrorLog "/var/log/httpd/error_log"
    
    ```
    
2. **Erişim Günlüğünü Etkinleştirme:**
Erişim günlüğü, sunucuya gelen tüm isteklerin kaydını tutar. Erişim günlüğünü etkinleştirmek için **`httpd.conf`** veya ilgili yapılandırma dosyanızda **`CustomLog`** direktifini ayarlayın. Örneğin:
    
    ```arduino
    CustomLog "/var/log/httpd/access_log" common
    ```
    
3. **Günlük Seviyelerini Ayarlama:**
Apache, günlük kayıtlarını farklı seviyelerde kaydedebilir: error, warn, info, debug gibi. Hangi günlük seviyelerinin kaydedileceğini belirlemek için **`LogLevel`** direktifini kullanın. Örneğin:
    
    ```perl
    LogLevel warn
    ```
    
4. **Özel Günlükleme Biçimleri:**
Günlükleme biçimlerini özelleştirmek için **`LogFormat`** direktifini kullanabilirsiniz. Özelleştirilmiş günlükleme biçimleri, belirli bilgilerin kaydedilmesini sağlar. Örnek bir özel günlükleme biçimi:
    
    ```perl
    LogFormat "%h %l %u %t \"%r\" %>s %b \"%{Referer}i\" \"%{User-agent}i\"" combined
    CustomLog "/var/log/httpd/access_log" combined
    ```
    
5. **Hata Sayfalarını Özelleştirme:**
Apache'nin varsayılan hata sayfalarını özelleştirebilirsiniz. Bu, özellikle kullanıcı deneyimini iyileştirmek ve hataları daha anlaşılır hale getirmek için önemlidir.
6. **Hataları İnceleme:**
Hataları incelemek için hata günlüğünü düzenli olarak kontrol edin. Hata kodları, hata açıklamaları ve nedenleri gibi bilgiler bu günlükte bulunur. Hataları tespit edin ve bunları çözümlemek için adımlar atın.
7. **Erişim Günlüğünü İnceleme:**
Erişim günlüğü, gelen her isteği kaydeder. Bu günlüğü inceleyerek hangi kaynakların ne kadar kullanıldığını ve hangi isteklerin başarısız olduğunu izleyebilirsiniz.
8. **Güvenlik ve Performans İzleme:**
Günlükler, sunucunuzun güvenliğini ve performansını izlemek için de kullanılabilir. Özellikle güvenlik olaylarına ve aşırı yükleme durumlarına dikkat edin.
9. **Günlük Dosyalarını Yedekleme ve Temizleme:**
Günlük dosyalarını belirli bir süre sonra yedekleyin ve gereksiz eski günlükleri temizleyin. Bu, disk alanını korur ve günlük dosyalarının yönetimini kolaylaştırır.

**`httpd`**: Bu dizin, genellikle Red Hat, CentOS ve Fedora gibi Red Hat tabanlı Linux dağıtımlarında kullanılan Apache HTTP Sunucusu'nun log dosyalarını içerir. Debain tabalı linux dağıtımlarında kullanılan Apache HTTP Sunucusu tanımları şu şekilde olabilir.

Apache, erişim ve hata logları tutar. Loglar genellikle **`/var/log/apache2`** dizininde bulunur. Bu log dosyalarını izleyerek, sunucunuzun performansını ve erişim istatistiklerini izleyebilirsiniz.

*Hatalar ve sorunlar hata ve erişim günlüklerinde kaydedilir. İlgili **günlük dosyalarını kontrol etmek için** aşağıdaki komutları kullanabilirsiniz:*

```bash
sudo tail -f /var/log/apache2/error.log
sudo tail -f /var/log/apache2/access.log
```

---

**Apache HTTP Sunucu - Yük Dengelemesi**

Apache HTTP Sunucusu'nda yük dengelemesi, gelen istekleri farklı arka plan sunucularına dağıtarak web uygulamanızın daha yüksek performans ve kullanılabilirlik sunmasına yardımcı olur. Yük dengelemesi, yüksek trafikli web siteleri, yedekleme sunucuları ve daha fazlası için önemlidir. İşte Apache HTTP Sunucusu'nda yük dengelemesi nasıl yapılır:

**Yük Dengeleme Modülünü Etkinleştirme:**
Apache'nin yük dengeleme modülünü etkinleştirmeniz gerekecektir. Apache'nin mod_proxy_balancer modülü, yük dengelemesi için kullanışlıdır. Bu modülü etkinleştirmek için **`mod_proxy`** ve **`mod_proxy_balancer`** modüllerini etkinleştirmeniz gerekecektir.

```bash
LoadModule proxy_module modules/mod_proxy.so
LoadModule proxy_balancer_module modules/mod_proxy_balancer.so
```

**Yük Dengeleme Grubunu Tanımlama:**
Yük dengelemesi yapmak için, bir yük dengeleme grubu tanımlamanız gerekir. Bu grup, dengelemek istediğiniz arka plandaki sunucuları içerir. Örnek bir yük dengeleme grubu tanımı:

```jsx
<Proxy balancer://mycluster>
    BalancerMember http://backend1.example.com:80
    BalancerMember http://backend2.example.com:80
</Proxy>

```

Bu örnekte **`mycluster`** adlı bir yük dengeleme grubu oluşturuldu ve iki arka plan sunucu (**`backend1.example.com`** ve **`backend2.example.com`**) tanımlandı.

**VirtualHost Yapılandırması:**
Apache VirtualHost yapılandırması içinde yük dengelemesi yapılandırmasını ekleyin. Örnek bir VirtualHost yapılandırması:

```arduino
<VirtualHost *:80>
    ServerName mywebsite.com
    ProxyPass / balancer://mycluster/
    ProxyPassReverse / balancer://mycluster/
</VirtualHost>
```

Bu yapılandırma, **`mywebsite.com`** için gelen istekleri **`mycluster`** adlı yük dengeleme grubuna yönlendirir.

**Yük Dengeleme Ayarlarını Özelleştirme:**
Yük dengeleme grubu ve VirtualHost yapılandırmasını ihtiyacınıza göre özelleştirin. Örneğin, ağırlıklandırma, yedek sunucular, oturum taşıma ve daha fazlasını yapılandırabilirsiniz.

**Yük Dengelemesini Test Etme:**
Apache HTTP Sunucusu'ndaki yük dengelemesini test etmek ve doğru çalıştığından emin olmak için farklı istekler gönderin ve sunucu günlüklerini izleyin. Yük dengeleme düzgün çalışıyorsa, istekler arka plandaki sunucular arasında dengeli bir şekilde dağıtılmalıdır.

**Sunucu ve Uygulama İzlemesi:**
Yük dengelemesi sonrasında sunucu ve uygulama performansınızı izlemek ve gerektiğinde ölçeklendirmek önemlidir. Hangi sunucuların yük altında olduğunu izleyin ve gerektiğinde yeni sunucular ekleyin veya eski sunucuları kaldırın.

Yük dengelemesi, daha fazla trafik ve yüksek kullanılabilirlik gerektiren web siteleri ve uygulamaları için önemlidir. İyi yapılandırılmış bir yük dengelemesi, kullanıcıların daha hızlı yanıt almasını ve sunucunun daha yüksek kullanılabilirlik sağlamasını sağlar.

---

**Apache HTTP Sunucu - Topluluk ve Kaynaklar**

Apache HTTP Sunucusu hakkında daha fazla bilgi edinmek ve sorularınızı cevaplamak için Apache topluluğuna katılın.

Daha detaylı bilgi öğrenmek için [Getting Started - Apache HTTP Server Version 2.4](https://httpd.apache.org/docs/2.4/getting-started.html) orijinal dokümanları inceleyin.

---

**Apache - Tomcat Sunucusu**

---

Apache Tomcat, **Java tabanlı web uygulamalarını barındırmak** ve **yönetmek** için kullanılan popüler bir açık kaynaklı **uygulama sunucusudur**. 

---

**Temel Java Bilgisi**:
Apache Tomcat, Java tabanlı bir sunucu olduğu için temel Java bilgisine sahip olmanız önemlidir. Java'nın temel kavramlarını ve syntax'ını öğrenmek başlangıç için ideal olacaktır.

---

**Apache Tomcat'ın Kurulumu**:

Ubuntu üzerinde Tomcat kurulumu yapmak için aşağıdaki adımları takip edebilirsiniz. Bu örnekte, **Ubuntu 24 sürümünü kullanıyoruz**, ancak diğer Ubuntu sürümlerinde de benzer adımlar geçerlidir.

Öncelikle terminali açın. **Terminali açmak** için "Ctrl + Alt + T" tuşlarına aynı anda basabilirsiniz.

Tomcat'ı kurmadan önce sistem paketlerini güncellemek iyi bir uygulamadır. Aşağıdaki komutu kullanarak paketlerinizi güncelleyin:

```bash
sudo apt update
sudo apt upgrade
```

Tomcat'ın kurulabilmesi için `Java JDK`'ya ihtiyacınız vardır. Eğer sistemde Java JDK kurulu değilse, aşağıdaki komutla **OpenJDK'yi yükleyin**:

```bash
sudo apt install openjdk-11-jdk
```

**Tomcat**'ın resmi web sitesinden **en son sürümün indirme bağlantısını alın**. Aşağıdaki komutu kullanarak Tomcat'ı indirebilirsiniz. [(Sürüm numarasını güncelleyin):](https://downloads.apache.org/tomcat)

```bash
wget https://downloads.apache.org/tomcat/tomcat-10/v10.1.13/bin/apache-tomcat-10.1.13.tar.gz
```

Tomcat'ı bir **dizine çıkarın** (örneğin, **`/opt`** dizinine):

```bash
sudo tar -xzvf apache-tomcat-10.1.13.tar.gz -C /opt
```

Tomcat dizinini daha **kullanıcı dostu bir isme** simgeleyebilirsiniz. Örneğin:

```bash
sudo mv /opt/apache-tomcat-10.1.13 /opt/tomcat
```

Tomcat'ı başlatmak için aşağıdaki komutu kullanın:

```bash
sudo /opt/tomcat/bin/startup.sh
```

Şöyle bir çıktı görmelisiniz.

```bash
Using CATALINA_BASE:   /opt/tomcat
Using CATALINA_HOME:   /opt/tomcat
Using CATALINA_TMPDIR: /opt/tomcat/temp
Using JRE_HOME:        /usr
Using CLASSPATH:       /opt/tomcat/bin/bootstrap.jar:/opt/tomcat/bin/tomcat-juli.jar
Using CATALINA_OPTS:
Tomcat started.
```

Tarayıcınızı açın ve **`http://localhost:8080`** adresine giderek **Tomcat yönetici arayüzüne** erişebilirsiniz.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/f8b9459f-ecb2-4328-ad80-20cdbd319051/Untitled.png)

---

**Apache -Tomcat - Rol Tanımlama**

Tomcat yönetici arayüzüne giriş yaparken sorun yaşıyorsanız, muhtemelen kullanıcı adı ve şifreyi yanlış giriyorsunuz veya bu bilgileri **daha önce yapılandırmamış** olabilirsiniz.

Tomcat'ı durdurun:

```bash
sudo /opt/tomcat/bin/shutdown.sh
```

Tomcat'ın **`conf`** dizininde yer alan **`tomcat-users.xml`** dosyasını düzenleyin. Bir metin düzenleyici kullanarak bu dosyayı açın:

```bash
sudo nano /opt/tomcat/conf/tomcat-users.xml
```

Dosyanın sonuna aşağıdaki gibi bir kullanıcı ve rol ekleyin. Bu örnekte kullanıcı adı "`admin`" ve şifre "`password`" olarak ayarlanmıştır. Güvenlik nedeniyle **daha güçlü bir şifre** kullanmanızı öneririz.

```xml
<role rolename="manager-gui"/>
<user username="admin" password="password" roles="manager-gui"/>
```

Dosyayı kaydedip kapatın (nano kullanıyorsanız "Ctrl + X" tuşlarına basın, ardından "Y" ve "Enter" tuşlarına basarak kaydedin).

Tomcat'ı tekrar başlatın:

```bash
sudo /opt/tomcat/bin/startup.sh
```

Tarayıcınızı açın ve **`http://localhost:8080`** adresine gidin.

Yönetici arayüzüne erişmek için kullanıcı adı ve şifrenizi (yukarıdaki adımlarda belirlediğiniz) girin.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/38712923-4f67-4d8d-93e9-cef17da49862/4174308b-0737-4794-a3a2-dc1bd3575525/Untitled.png)

Bu adımları takip ederek Tomcat yönetici arayüzüne başarılı bir şekilde giriş yapmalısınız.

---

**Apache - Tomcat - Temel Kavramlar:**

**Web Sunucusu (Web Server)**:
Apache Tomcat, bir web sunucusu olarak görev yapabilir. Web sunucuları, HTTP istemcilerinin (genellikle tarayıcılar) isteklerini alır ve bu isteklere yanıtlar verir. Tomcat, bu temel işlevi yerine getirmenin yanı sıra Java tabanlı web uygulamalarını çalıştırma yeteneği sunar.

**Servlet**:
Servletler, Java dilinde yazılmış web uygulamalarının temel yapı taşlarıdır. HTTP istemcilerinin taleplerini işlemek ve dinamik web sayfalarını oluşturmak için kullanılır. Servletler, javax.servlet.Servlet arabirimi uygulanarak yazılır ve Tomcat tarafından yönetilir.

**JSP (JavaServer Pages)**:
JSP, sunucu tarafında dinamik web sayfaları oluşturmak için kullanılan bir Java teknolojisidir. JSP sayfaları, HTML içine Java kodu eklenerek oluşturulur ve sunucu tarafında işlenir.

**Web Uygulaması (Web Application)**:
Web uygulaması, bir web sunucusu altında çalışan bir dizi servlet, JSP, HTML, veritabanı bağlantısı ve diğer kaynakları içeren bir proje veya uygulamadır. Tomcat, bu web uygulamalarını çalıştırmak için kullanılır.

**WAR (Web Application Archive)**:
WAR dosyası, bir web uygulamasının paketlenmiş ve sıkıştırılmış halidir. Tomcat'a bir web uygulaması dağıtmak için genellikle WAR dosyası kullanılır. Tomcat, WAR dosyasını alır, çözümler ve çalıştırır.

**Yapılandırma Dosyaları**:
Tomcat sunucusunun davranışını ve yapılandırmasını kontrol etmek için kullanılan yapılandırma dosyaları bulunur. Önemli bir yapılandırma dosyası **`server.xml`** dir. Bu dosya, sunucu ayarlarını ve web uygulamalarını tanımlar.

**Context (Bağlam)**:
Bir web uygulamasının çalışma bağlamını tanımlayan bir yapıdır. Her web uygulaması, sunucu üzerinde benzersiz bir bağlama sahiptir. Bu, URL'lerin nasıl eşlendiğini ve nasıl işlendiğini belirler.

**Port (Bağlantı Noktası)**:
Tomcat sunucusunun belirli görevleri için kullanılan ağ bağlantı noktalarını tanımlar. Örneğin, HTTP istekleri için varsayılan olarak 8080 bağlantı noktası kullanılır.

**Tomcat Manager (Tomcat Yöneticisi)**:
Tomcat yönetim arayüzüdür. Buradan web uygulamalarını yönetebilir, dağıtabilir ve izleyebilirsiniz.

**Tomcat Dizini Yapısı**:
Tomcat'ın dosya dizin yapısı, sunucunun ve web uygulamalarının yerleştirilmesi için belirli klasörleri içerir. Örneğin, **`webapps`** klasörü, web uygulamalarının dağıtıldığı yerdir.

---

**Apache - Tomcat - Örnek Web Uygulaması Oluşturma:**

**Java ve Tomcat'ı Kurun**:
İlk olarak, bilgisayarınıza Java JVM ve Apache Tomcat'ı kurun. Önceki yanıtlarımda bahsettiğim gibi, bu adımları tamamladığınızdan emin olun.

**Çalışma Dizinini Hazırlama**:
Web uygulamanızı oluşturmak için bir çalışma dizini oluşturun. Örneğin, "MerhabaDunya" adında bir klasör oluşturabilirsiniz.

**Web Uygulama Yapısı**:
Bir web uygulamasının temel yapısını oluşturun. Tipik olarak, aşağıdaki klasörleri içeren bir yapı kullanılır:

- **`WEB-INF`** klasörü: Bu klasör, web uygulamanızın yapılandırma ve sınıf dosyalarını içerir.
    - **`WEB-INF/web.xml`**: Web uygulamanızın yapılandırmasını tanımlayan bir deployment descriptör dosyasıdır.
    - **`WEB-INF/classes`**: Java sınıflarınızın derlenmiş sürümlerini içerir (örneğin, servlet sınıfları).
- **`META-INF`** klasörü (isteğe bağlı): Bu klasör, web uygulamanızın meta bilgilerini içerir.

**"Merhaba Dünya" Servletini Oluşturma**:
**`WEB-INF/classes`** klasöründe "MerhabaDunyaServlet.java" adında bir Java Servlet sınıfı oluşturun. Bu servlet, tarayıcıdan gelen isteklere yanıt olarak "Merhaba, Dünya!" mesajını dönecek şekilde programlanmalıdır. Örnek bir servlet kodu şöyle olabilir:

```java
import java.io.*;
import javax.servlet.*;
import javax.servlet.http.*;

public class MerhabaDunyaServlet extends HttpServlet {
    public void doGet(HttpServletRequest request, HttpServletResponse response)
        throws ServletException, IOException {
        response.setContentType("text/html");
        PrintWriter out = response.getWriter();
        out.println("<html><head><title>Merhaba Dünya</title></head>");
        out.println("<body><h1>Merhaba, Dünya!</h1></body></html>");
    }
}
```

**Deployment Tanımı (web.xml)**:
**`WEB-INF`** klasöründeki **`web.xml`** dosyasında servletinizi ve URL eşleştirmelerini tanımlayın. Aşağıda bir örnek:

```xml
<web-app>
    <servlet>
        <servlet-name>MerhabaDunyaServlet</servlet-name>
        <servlet-class>MerhabaDunyaServlet</servlet-class>
    </servlet>
    <servlet-mapping>
        <servlet-name>MerhabaDunyaServlet</servlet-name>
        <url-pattern>/MerhabaDunya</url-pattern>
    </servlet-mapping>
</web-app>
```

**WAR Dosyasını Oluşturma**:
Web uygulamanızı Tomcat'a dağıtmak için WAR dosyasını oluşturun. "MerhabaDunya" klasörünü sıkıştırın ve **`.war`** uzantılı bir dosya yapın.

**WAR Dosyasını Dağıtma**:
WAR dosyasını Tomcat'ın **`webapps`** klasörüne kopyalayın. Tomcat otomatik olarak WAR dosyasını alır, çözümler ve çalıştırır.

**Tomcat Sunucusunu Başlatma**:
Tomcat sunucusunu başlatın. Önceki yanıtlarımda belirtildiği gibi, Tomcat'ı başlatmak için **`startup.bat`** veya **`startup.sh`** komutunu kullanabilirsiniz.

**Web Uygulamanızı Tarayıcıda Görmek**:
Tarayıcınızı açın ve **`http://localhost:8080/YourWebAppName`** adresini ziyaret edin. "YourWebAppName" kısmını oluşturduğunuz web uygulamasının adıyla değiştirin. Örneğin, "**http://localhost:8080/MerhabaDunya**" adresi "Merhaba, Dünya!" mesajını göstermelidir.

---

**Apache - Tomcat - Yapılandırma**:

**server.xml**:
**`server.xml`** dosyası, Tomcat sunucusunun temel yapılandırma dosyasıdır ve Tomcat'ın ana yapılandırma dosyası olarak kabul edilir. Bu dosyayı düzenlemek için aşağıdaki adımları izleyebilirsiniz:

- HTTP bağlantı noktasını değiştirmek veya HTTPS kullanmak için **`<Connector>`** öğelerini düzenleyin.
- Sanal ana bilgisayarlar (virtual hosts) eklemek için **`<Host>`** öğeleri ekleyin.
- AJP (Apache JServ Protocol) ile ilgili yapılandırmaları yapmak için **`<Connector>`** öğelerini düzenleyin.

**context.xml**:
**`context.xml`** dosyası, her bir web uygulamasının (Context) yapılandırmasını saklar. Bu dosyayı kullanarak veritabanı bağlantıları, kaynaklar ve bağlam özelleştirmeleri gibi özellikleri belirleyebilirsiniz.

**web.xml**:
**`web.xml`** dosyası, her bir web uygulamasının özel yapılandırmasını ve Servlet/JSP filtrelerini tanımlar. Bu dosya, web uygulamanızın kök dizininde bulunur ve uygulama düzeyindeki yapılandırmaları içerir.

**logging.properties**:
**`logging.properties`** dosyası, Tomcat sunucusunun günlükleme (logging) yapılandırmasını tanımlar. Bu dosya, log seviyelerini, log dosyasının konumunu ve diğer günlükleme ayarlarını belirlemenize olanak sağlar.

**catalina.properties**:
**`catalina.properties`** dosyası, Tomcat'ın temel özelliklerini ve davranışlarını ayarlamanızı sağlar. Örneğin, Tomcat'ın sıkıştırma veya gzip kullanma ayarlarını değiştirebilirsiniz.

**setenv.bat veya setenv.sh**:
**`setenv.bat`** (Windows) veya **`setenv.sh`** (Linux/Unix) dosyası, Tomcat başlatılırken ortam değişkenlerini veya JVM seçeneklerini ayarlamanızı sağlar. Bu dosyaları kullanarak Java bellek sınırları gibi özel ayarlar yapabilirsiniz.

**Tomcat Yönetici (Tomcat Manager)**:
Tomcat Manager uygulamasını etkinleştirmek için **`tomcat-users.xml`** dosyasını düzenleyin. Bu dosya, Tomcat yönetici paneline erişim izinlerini ve kullanıcıları tanımlar.

Tomcat'ı yapılandırırken dikkat etmeniz gereken bazı önemli noktalar şunlardır:

- Değişikliklerinizi yaparken dikkatli olun ve gereksiz yapılandırmalardan kaçının. Yapılandırma dosyalarını yedekleyin ve herhangi bir hata durumunda geri dönebileceğinizden emin olun.
- Güvenlik: Sunucunuzun güvenliğini önemseyin. Özellikle Tomcat Yönetici paneline erişim izinlerini dikkatli bir şekilde yönetin ve gereksiz erişimleri kapatın.
- Performans: Sunucunuzun performansını artırmak için uygun yapılandırmaları yapın. Özellikle HTTP bağlantılarını, veritabanı bağlantılarını ve bellek kullanımını izleyin.
- İzleme ve Günlükleme: Tomcat sunucusunun etkinliğini ve hatalarını izlemek için günlükleme ayarlarını doğru bir şekilde yapılandırın. Bu, sorunları hızlı bir şekilde tanımlamanıza yardımcı olacaktır.

---

**Apache - Tomcat - Servlet ve JSP Geliştirme:**

**Java Geliştirme Ortamı (IDE) Seçimi**:
Servlet ve JSP geliştirmek için bir Java IDE (Integrated Development Environment) seçin. Popüler IDE'ler arasında Eclipse, IntelliJ IDEA ve NetBeans bulunur. İhtiyaçlarınıza ve tercihlerinize uygun bir IDE seçin ve yükleyin.

**Tomcat Sunucusu Kurulumu**:
Eğer daha önce kurmadıysanız, Apache Tomcat sunucusunu kurun. Yukarıda verilen kurulum adımlarını takip edin ve Tomcat sunucusunu başlatın.

**Yeni Bir Web Projesi Oluşturma**:
IDE'nizde yeni bir Java web projesi oluşturun. Bu işlem, proje için bir çalışma alanı ve temel dosya yapısını ayarlar.

**Servlet Oluşturma**:
Servlet oluşturmak için aşağıdaki adımları izleyin:

- IDE'nizde yeni bir Java sınıfı oluşturun.
- Servlet sınıfınızı **`javax.servlet.Servlet`** arabirimini uygulayacak şekilde ayarlayın.
- **`doGet`** veya **`doPost`** gibi HTTP isteklerini işleyen metotlar ekleyin.
- İstediğiniz işlevselliği eklemek için Java kodunu yazın.

**Servlet'i URL ile Eşleştirme**:
Servlet'inizi bir URL ile eşleştirin. Bu, **`web.xml`** veya daha yeni sürümlerde Java tabanlı yapılandırma ile yapılabilir. Örneğin:

- **`web.xml`** kullanarak:
    
    ```xml
    <servlet>
        <servlet-name>MyServlet</servlet-name>
        <servlet-class>com.example.MyServlet</servlet-class>
    </servlet>
    <servlet-mapping>
        <servlet-name>MyServlet</servlet-name>
        <url-pattern>/myservlet</url-pattern>
    </servlet-mapping>
    ```
    
- Java tabanlı yapılandırma ile:
    
    ```java
    @WebServlet("/myservlet")
    public class MyServlet extends HttpServlet {
        // ...
    }
    ```
    

**JSP Oluşturma**:
JSP oluşturmak için aşağıdaki adımları izleyin:

- IDE'nizde yeni bir JSP dosyası oluşturun.
- JSP dosyasında HTML kodu ve Java kodu (scriptlet) kullanarak dinamik içerik oluşturun.
- Servletlerden gelen verileri veya iş mantığını kullanarak JSP sayfasını doldurun.

**Servlet ve JSP'yi Birleştirme**:
Servletler ve JSP sayfaları arasında iletişim kurmak için Java kodu kullanabilirsiniz. Servletlerden JSP'lere veri aktarımı yapmak veya JSP'den Servletlere yönlendirme yapmak gibi işlemleri gerçekleştirebilirsiniz.

**Web Uygulamanızı Dağıtma**:
Web uygulamanızı Tomcat sunucusuna dağıtmak için proje dosyalarını bir WAR (Web Application Archive) dosyasına paketleyin ve bu dosyayı Tomcat'ın **`webapps`** klasörüne kopyalayın. Tomcat, WAR dosyasını otomatik olarak çözümler ve çalıştırır.

**Tarayıcıda Test Etme**:
Web uygulamanızı tarayıcıda test edin. Tarayıcınızı açın ve belirlediğiniz URL'yi (örneğin, **`http://localhost:8080/mywebapp`**) ziyaret edin. Servlet ve JSP'niz çalışmalı ve sonuçları tarayıcıda göstermelidir.

**Hata Ayıklama ve İzleme**:
Hata ayıklama ve izleme için IDE'nizin veya Tomcat'ın sağladığı araçları kullanın. Hata mesajlarını inceleyerek ve logları kontrol ederek problemleri tanımlayın ve giderin.

---

**Apache - Tomcat - Veritabanı Entegrasyonu:**

**Veritabanı Seçimi**:
İlk adım olarak, kullanmak istediğiniz veritabanını seçmelisiniz. Veritabanı seçimi işletim sisteminiz, projenizin gereksinimleri ve bilgi sahibi olduğunuz veritabanı sistemleri gibi faktörlere bağlı olacaktır. Popüler veritabanları arasında MySQL, PostgreSQL, Oracle ve Microsoft SQL Server bulunmaktadır.

**Veritabanı Sürücüsü (JDBC Driver) İndirme ve Kurulum**:
Kullandığınız veritabanı için uygun JDBC sürücüsünü indirin ve Tomcat sunucusunun **`lib`** dizinine kopyalayın. JDBC sürücüsü, Java uygulamalarının veritabanlarıyla iletişim kurmasına olanak sağlar.

**Veritabanı Bağlantısı Ayarları**:
Veritabanına bağlantı ayarlarını yapılandırın. Bu ayarlar genellikle veritabanı sunucu adresi, bağlantı portu, veritabanı adı, kullanıcı adı ve şifre gibi bilgileri içerir. Bu ayarlar veritabanı türüne ve kullanılan JDBC sürücüsüne bağlı olarak değişebilir.

**DataSource (Veri Kaynağı) Tanımlama**:
Veritabanı bağlantıları için bir DataSource nesnesi tanımlamalısınız. Bu işlem **`context.xml`** dosyasında veya Java kodunda yapılabilir. Örneğin, **`context.xml`** dosyasında bir DataSource tanımlamak için:

```xml
<Resource name="jdbc/MyDB" auth="Container" type="javax.sql.DataSource"
    maxActive="100" maxIdle="30" maxWait="10000"
    username="yourusername" password="yourpassword"
    driverClassName="com.mysql.jdbc.Driver"
    url="jdbc:mysql://localhost:3306/mydb"/>
```

**Veritabanı İşlemlerini Gerçekleştirme**:
Veritabanı işlemlerini gerçekleştirmek için Servlet ve JSP'lerde JDBC veya ORM (Object-Relational Mapping) çerçevelerini kullanabilirsiniz. JDBC kullanıyorsanız, bağlantı almak ve sorguları çalıştırmak için JDBC API'sini kullanmalısınız.

Örnek bir JDBC bağlantısı ve sorgu çalıştırma kodu:

```java
Connection connection = null;
PreparedStatement preparedStatement = null;
ResultSet resultSet = null;

try {
    // DataSource'dan bağlantıyı al
    Context initContext = new InitialContext();
    DataSource ds = (DataSource) initContext.lookup("java:/comp/env/jdbc/MyDB");
    connection = ds.getConnection();

    // SQL sorgusu hazırla ve çalıştır
    String query = "SELECT * FROM mytable";
    preparedStatement = connection.prepareStatement(query);
    resultSet = preparedStatement.executeQuery();

    // Sonuçları işle
    while (resultSet.next()) {
        // Verileri al
        String data = resultSet.getString("columnName");
        // ...
    }
} catch (SQLException e) {
    e.printStackTrace();
} finally {
    // Bağlantıyı ve kaynakları kapat
    if (resultSet != null) resultSet.close();
    if (preparedStatement != null) preparedStatement.close();
    if (connection != null) connection.close();
}
```

**Güvenlik ve İzolasyon**:
Veritabanı bağlantıları ve işlemleri için güvenlik önlemleri almalısınız. Kullanıcı girişi denetimleri, SQL enjeksiyonlarına karşı koruma ve güncellemeleri izolasyon gibi güvenlik önlemlerine dikkat edin.

**Test Etme ve Hata Ayıklama**:
Veritabanı işlemlerini test edin ve hata ayıklama yapın. Veritabanı bağlantısı ile ilgili hataların hızlıca tanımlanıp giderilmesi önemlidir.

---

**Apache - Tomcat - Güvenlik**

**Tomcat Sürümünü Güncelleme**:
Tomcat'ın güncel sürümünü kullanmak önemlidir, çünkü yeni sürümler güvenlik düzeltmeleri içerir. Eski ve güncellenmeyen sürümler, güvenlik açıklarına karşı daha savunmasız olabilir.

**Yönetim Arayüzü Erişimini Kısıtlama**:
Tomcat yönetim arayüzüne (Tomcat Manager) erişimi kısıtlayın. **`tomcat-users.xml`** dosyasını kullanarak yönetici kullanıcıları ve rolleri tanımlayarak, bu arayüze sadece yetkilendirilmiş kişilerin erişimini sağlayın.

**Güvenlik Duvarı (Firewall) Kullanma**:
Sunucunuzu bir güvenlik duvarı ile koruyun ve gereksiz bağlantıları engelleyin. Sadece gerekli portlara erişim izni verin.

**HTTPS Kullanma**:
Özellikle kullanıcı kimlik bilgilerinin (şifreler, oturum kimlikleri) iletilmesi gereken alanlarda HTTPS kullanın. SSL/TLS sertifikaları ile sunucunuzu güvence altına alın.

**Dosya ve Dizin İzinlerini Kontrol Etme**:
Sunucu dosyaları ve dizinlerinin izinlerini sıkı bir şekilde kontrol edin. Verilerinizi ve yapılandırma dosyalarınızı sadece yetkilendirilmiş kullanıcıların erişebileceği bir dizinde tutun.

**DoS (Hizmet Reddi) Saldırılarına Karşı Koruma**:
Saldırılara karşı korumak için gereksiz hizmetleri devre dışı bırakın. Örneğin, sık kullanılmayan veya güvenlik açıklarına sahip olan Valve'leri kapatın.

**Giriş Denetimleri ve Kimlik Doğrulama**:
Web uygulamanızda kullanıcı girişi gerekiyorsa, giriş denetimlerini ve kimlik doğrulama mekanizmalarını kullanın. Bu, kullanıcıların güvenilir bir şekilde kimliklerini doğrulamalarını sağlar.

**SQL Enjeksiyonlarına Karşı Koruma**:
Kullanıcı girişi veya diğer kullanıcı tarafından sağlanan verileri güvenli bir şekilde işleyin ve SQL enjeksiyonlarına karşı önlemler alın. Prepared statement'lar veya ORM çerçeveleri gibi güvenli veritabanı sorgularını kullanın.

**Doğrulama Tokenları (CSRF Tokenları) Kullanma**:
Çapraz Site İstek Sahteciliği (Cross-Site Request Forgery, CSRF) saldırılarına karşı koruma sağlamak için doğrulama tokenları kullanın.

**Günlükleme (Logging)**:
Günlükleme ayarlarını etkinleştirin ve günlükleri düzenli olarak kontrol edin. Günlükler, güvenlik ihlallerini ve sorunları tanımlamanıza yardımcı olabilir.

**Güvenlik Taraması**:
Web uygulamanızı düzenli olarak güvenlik açıkları için tarayın ve güncellemeleri takip edin.

**Uygulama Katmanı Güvenliği**:
Web uygulamanızın iş mantığına özgü güvenlik önlemleri alın. Kullanıcı girişi, rol tabanlı erişim kontrolü ve oturum yönetimi gibi önlemleri uygulayın.

---

**Apache - Tomcat - İzleme ve Hata Ayıklama**

**Loglama (Logging)**:
Tomcat sunucusunun loglarını etkinleştirin ve izleyin. Tomcat, farklı log dosyalarına farklı türdeki olayları kaydeder. Bu logları kullanarak hataları ve uygulamanızın davranışını izleyebilirsiniz. Önemli log dosyaları şunlardır:

- **`catalina.out`**: Sunucu hata mesajları ve çıktıları için kullanılır.
- **`localhost_access_log.yyyy-mm-dd.txt`**: Erişim günlüğüdür ve HTTP istemcilerinin gelen isteklerini kaydeder.

**Web Uygulamanızdaki Günlükleme**:
Kendi web uygulamanızda günlükleme ekleyin. Log4j veya SLF4J gibi günlükleme çerçevelerini kullanarak uygulamanızın davranışını izleyebilir ve hataları yakalayabilirsiniz.

**Tomcat Yönetici Arayüzü (Tomcat Manager)**:
Tomcat yönetici arayüzü, çalışan uygulamaları, sunucu durumunu ve günlükleri izlemenize olanak sağlar. Tarayıcınızı kullanarak **`http://localhost:8080/manager`** adresine giderek bu arayüze erişebilirsiniz.

**Java Debug Wire Protocol (JDWP)**:
JDWP, Java uygulamalarını uzaktan hata ayıklamak için kullanılan bir protokoldür. Tomcat sunucusunu JDWP ile başlatarak Java hata ayıklayıcılarını kullanabilirsiniz. Özel hata ayıklama istemcileri (IDE entegrasyonu gibi) JDWP ile iletişim kurabilir.

**Tomcat İzleme ve İstatistikler**:
Tomcat, JMX (Java Management Extensions) aracılığıyla izleme ve istatistikler sunar. JConsole veya VisualVM gibi JMX tabanlı araçları kullanarak Tomcat sunucusunu izleyebilirsiniz. Ayrıca Tomcat'ın kendi istatistik sayfalarına erişebilirsiniz (**`http://localhost:8080/manager/status`**).

**Thread Dump Alma**:
Sunucunuzdaki olası donmaları veya yavaşlamaları izlemek için thread dump'larını alın. Bu, hangi iş parçacıklarının meşgul olduğunu ve neden olabileceğini anlamada yardımcı olabilir. **`kill -3 <Tomcat_PID>`** komutunu kullanarak thread dump alabilirsiniz.

**Hata Sayfalarını Özelleştirme**:
**`web.xml`** dosyasında hata sayfalarını özelleştirerek, kullanıcılara daha bilgilendirici hata mesajları gösterebilirsiniz.

**Geliştirme Ortamını Kullanma**:
Geliştirme ortamınızda (IDE) hata ayıklama araçlarını kullanarak kodunuzu inceleyin ve hataları bulun. Java hata ayıklama araçları, hata ayıklama sürecini kolaylaştırır.

---

**Apache - Tomcat - Performans İyileştirmesi**

**Tomcat Sürümünü Güncelleme**:
Tomcat'ın en son sürümünü kullanmak, performans ve güvenlik düzeltmelerini içerebilir. Yeni sürümler, sunucunun daha hızlı çalışmasını sağlayabilecek iyileştirmeler içerebilir.

**Bağlantı Yönetimi ve Veritabanı Optimizasyonu**:
Web uygulamanız veritabanına erişim gerektiriyorsa, veritabanı bağlantılarını etkin bir şekilde yönetmelisiniz. Veritabanı bağlantı havuzlarını (connection pool) kullanarak bağlantıları yeniden kullanın ve gereksiz bağlantılar oluşturmayın.

**Önbellekleme Kullanma**:
Önbellekleme, sıkça kullanılan verileri veya sayfaları ön belleğe alarak sunucunun yükünü azaltabilir. Apache Tomcat ile önbellekleme yapabilir veya dış bir önbellekleme sistemi (örneğin, Redis veya Memcached) kullanabilirsiniz.

**Statik Dosyaları Özel Bir Web Sunucusuna Taşıma**:
Statik içerikleri (örneğin, CSS ve JavaScript dosyalarını) özel bir web sunucusuna (örneğin, Apache HTTP Server) taşıyarak Tomcat sunucusunu yükten kurtarabilirsiniz. Bu, Tomcat sunucusunu işlemek için daha fazla kaynak ayırmanıza olanak sağlar.

**Apache Tomcat Sunucusunu Ölçeklendirme**:
Yüksek trafikli uygulamalar için Tomcat sunucusunu yatay olarak ölçeklendirerek performansı artırabilirsiniz. Load balancer kullanarak birden fazla Tomcat sunucusunu dağıtarak yükü dengeleyebilirsiniz.

**Veritabanı İndeksleme ve Optimizasyonu**:
Veritabanı sorgularınızı optimize edin ve sık kullanılan sorgular için veritabanı indeksleme kullanın. İyi tasarlanmış veritabanı şeması ve indeksler, veritabanı performansını artırabilir.

**Kod İyileştirmesi ve Önbellekleme**:
Web uygulamanızın kodunu optimize edin ve gereksiz veritabanı sorgularını önlemek için veri önbelleği kullanın. Özellikle veritabanından aynı verileri sık sık sorguluyorsanız bu önemlidir.

**Sıkıştırma (GZIP)**:
Tomcat sunucusunu yanıt verilen verileri sıkıştırmak için yapılandırın. Bu, veri transferini azaltarak yanıt sürelerini iyileştirebilir.

**Java Virtual Machine (JVM) Ayarlarını İyileştirme**:
JVM ayarlarını (heap boyutu, thread havuzu vb.) optimize ederek Java uygulamanızın performansını artırabilirsiniz.

**Profiling ve Hata Ayıklama Araçları Kullanma**:
Profiling araçları (örneğin, VisualVM veya YourKit) ve hata ayıklama araçları (örneğin, JConsole veya Eclipse MAT) kullanarak uygulamanızın performansını izleyin ve sorunları tanımlayın.

**Uygulama Katmanı Önbellekleme**:
Web uygulamanızın katmanlarını (örneğin, iş mantığı, sunum) önbellekleme kullanarak optimize edin. Bu, işlem sürelerini azaltabilir ve sunucu kaynaklarını verimli bir şekilde kullanmanıza olanak sağlar.

**Yük Testleri Yapma**:
Uygulamanızı yük testlerine tabi tutarak, performans sınırlarınızı belirleyin ve bu sınırları aşmadan önce kapasite artırma önlemleri alın.

---

**Apache - Tomcat - İleri Düzey Konular**

**Yük Dengeleme ve Yedekleme (Load Balancing and Failover)**:
Yüksek trafikli uygulamalar için Apache veya Nginx gibi bir yük dengeleyici kullanarak birden fazla Tomcat sunucusunu yönetebilirsiniz. Bu, yükü dengeleyerek performansı artırır ve yedekleme sunucuları ile yüksek kullanılabilirlik sağlar.

**Veritabanı Kümeleme (Database Clustering)**:
Uygulamanızın veritabanı katmanını kümeleme (clustering) ile yüksek erişilebilirlik ve veritabanı performansı sağlamak için ayarlayabilirsiniz.

**SSL/TLS Sertifikaları ve Güvenlik Duvarları**:
Güvenlik konularını daha da geliştirmek için SSL/TLS sertifikalarını etkinleştirin. Ayrıca, güvenlik duvarları ve Web Application Firewall (WAF) gibi güvenlik önlemlerini düşünün.

**Apache Tomcat Güvenlik Konfigürasyonu**:
Güvenlik konfigürasyonunu daha fazla özelleştirin ve güvenlik açıklarına karşı daha fazla önlem alın. Örneğin, çapraz site istek sahteciliğini (CSRF) önlemek için özel tokenlar kullanabilirsiniz.

**JNDI (Java Naming and Directory Interface) ve Veri Kaynakları (Data Sources)**:
JNDI ve veri kaynaklarını kullanarak, veritabanı bağlantıları ve diğer kaynakları daha etkin bir şekilde yönetebilirsiniz.

**Apache Tomcat ve Spring MVC Entegrasyonu**:
Apache Tomcat'i Spring MVC ile entegre ederek, daha karmaşık ve modüler web uygulamaları oluşturabilirsiniz. Spring güvenlik, veritabanı erişimi ve uygulama yapılandırması gibi özellikleri kolayca entegre edebilir.

**Performans İzleme ve Optimizasyon**:
Tomcat sunucusunun performansını izlemek ve optimize etmek için profesyonel izleme araçları kullanın. Ayrıca, Java Flight Recorder ve VisualVM gibi araçlarla JVM performansını analiz edin.

**Tomcat Özelleştirmesi ve Genişletmesi**:
Tomcat sunucusunu özelleştirmek ve yeni bileşenler eklemek için özel Tomcat Valve'leri, Tomcat Realm'ları veya özelleştirilmiş Servlet Filter'ları oluşturun.

**Containerization (Docker, Kubernetes)**:
Tomcat sunucusunu Docker konteynerlerine yerleştirerek uygulamanızın dağıtımını daha iyi yönetebilirsiniz. Kubernetes gibi orkestrasyon araçlarıyla konteyner tabanlı uygulamaları yönetin.

**Uygulama Günlükleme (Application Logging)**:
Uygulamanızın günlükleme gereksinimlerini daha iyi yönetmek için Log4j, SLF4J veya ELK Stack gibi günlükleme çerçevelerini kullanın.

---

**Apache - Tomcat - Topluluk ve Kaynaklar**

**Resmi Apache Tomcat Web Sitesi**:
**[Tomcat resmi web sitesi](http://tomcat.apache.org/)**, Tomcat hakkında en güncel bilgilere, belgelere ve sürümlere erişim sağlar.

**Tomcat Belge Sayfaları**:
Tomcat'ın **[belge sayfaları](http://tomcat.apache.org/documentation.html)**, Tomcat'ı kullanmanız için detaylı bilgiler içerir. Başlangıçtan ileri düzey konulara kadar birçok konuyu kapsar.

**Tomcat E-Posta Listeleri**:
**[Tomcat e-posta listeleri](http://tomcat.apache.org/lists.html)**, Tomcat topluluğu ile iletişim kurmanın önemli bir yoludur. Sorularınızı sormak ve diğer geliştiricilerden yardım almak için kullanabilirsiniz.

**Stack Overflow**:
**[Stack Overflow](https://stackoverflow.com/questions/tagged/tomcat)** üzerinde Tomcat ile ilgili birçok soru ve cevap bulabilirsiniz. Sorularınızı burada sormak veya diğer geliştiricilere yardım etmek için katılmak iyi bir fikirdir.

**Tomcat Reddit**:
**[Tomcat subreddit](https://www.reddit.com/r/tomcat/)**, Tomcat ile ilgili haberleri ve tartışmaları takip etmek için kullanabileceğiniz bir platformdur.

**Kitaplar**:
Apache Tomcat hakkında yazılmış birçok kitap bulunmaktadır. İlgili konuları daha derinlemesine öğrenmek için bu kaynakları kullanabilirsiniz. Örnek kitaplar arasında "Tomcat: The Definitive Guide" ve "Apache Tomcat 9 Guide Handbook" yer almaktadır.

**Topluluk Kaynakları**:
Apache Tomcat ile ilgili çeşitli bloglar, forumlar ve yazılı kaynaklar da mevcuttur. Bu kaynaklar, deneyim paylaşımı ve sorun giderme konularında yardımcı olabilir.

**Apache Software Foundation**:
**[Apache Software Foundation (ASF)](https://www.apache.org/)**, Apache Tomcat'ın bir parçası olarak yönetilen projelerin resmi organizasyonudur. ASF web sitesi, diğer Apache projeleri ve kaynakları hakkında bilgi sağlar.
