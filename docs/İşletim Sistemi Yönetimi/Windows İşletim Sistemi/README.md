# Windows İşletim Sistemi

![Windows İşletim Sistemi](https://victorockkenya.com/wp-content/uploads/2019/06/Windows-Operating-Systems-795x405.jpg)

**İşletim Sistemi Performans Verileri**

![Windows Task Manager](https://i.imgur.com/OW1hv7n.png)

Windows Task Manager, Microsoft Windows işletim sistemlerinde bulunan **bir sistem yönetim aracıdır**. Bu araç, kullanıcıların bilgisayarlarının **performansını** izlemelerine, çalışan uygulamaları ve işlemleri **yönetmelerine**, sistem kaynaklarını **izlemelerine** ve hatta sistem sorunlarını **teşhis** etmelerine yardımcı olur.

Çalıştırmak için : **Taskmgr** komutunu kullanabilirsiniz.

---

**Visual Studio Code Başlangıç Rehberi:** 
Visual Studio Code, hızlı bir şekilde **kodlamaya** başlamanıza yardımcı olan **ücretsiz** bir kodlama düzenleyicisidir. Editörleri değiştirmeden **herhangi bir programlama dilinde** kodlamak için kullanın. Visual Studio Code, Python, Java, C++, JavaScript ve daha fazlası dahil olmak üzere birçok dili destekler.

[Visual Studio Code](https://code.visualstudio.com/Download)

- Temeller

![Temeller](https://code.visualstudio.com/assets/docs/getstarted/userinterface/hero.png)

- Canlı Ekip İşbirliği

![Vs Code - Live Team Collaboration](https://i.imgur.com/hWyudbm.png)
- Kaynak Kontrol
    
    [Git - Downloads](https://git-scm.com/download)
    

![Kaynak Kontrol](https://code.visualstudio.com/assets/docs/sourcecontrol/intro/github-clone.png)

- Terminal

![Terminal](https://code.visualstudio.com/assets/docs/terminal/basics/select-profile-dropdown.png)

- Programlama Dilleri

![Programlama Dilleri](https://code.visualstudio.com/assets/docs/languages/overview/language-identifiers.png)

- Node.js

![Node.js](https://code.visualstudio.com/assets/docs/nodejs/nodejs/hello-world-debugging.png)

- TypeScript

![TypeScript](https://code.visualstudio.com/assets/docs/typescript/tutorial/compiled-hello-world.png)

- Python

![Python](https://code.visualstudio.com/assets/docs/python/tutorial/debug-step-02.png)

- Java

![Java](https://code.visualstudio.com/assets/docs/java/java-tutorial/getting-started.png)

[java-tutorial](https://code.visualstudio.com/docs/java/java-tutorial/run-debug.mp4)

[JavaHelloWorld](https://code.visualstudio.com/docs/java/java-tutorial/JavaHelloWorld.Standalone.mp4)

- C#

![C#](https://code.visualstudio.com/assets/docs/csharp/get-started/open-new-project.gif)

Daha detaylı bilgi için orjinal kaynakları inceleyebilirsiniz.

[Visual Studio Code Documantation](https://code.visualstudio.com/docs)

---

**Windows PowerShell Komutları**

PowerShell, başlangıçta Microsoft tarafından geliştirilmiş bir komut satırı arayüzü ve komut dosyası dili olarak başlamıştır ve genellikle Windows işletim sistemiyle ilişkilendirilir. Ancak, PowerShell'in bazı versiyonları ve türevleri Windows dışında da kullanılabilmektedir.

**Kurulum**

[Installing PowerShell on Windows - PowerShell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.3)

[Installing PowerShell on Ubuntu - PowerShell](https://learn.microsoft.com/en-us/powershell/scripting/install/install-ubuntu?view=powershell-7.3)

[Installing PowerShell on macOS - PowerShell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-macos?view=powershell-7.3)

PowerShell, Windows işletim sistemlerinde kullanılan bir komut satırı arayüzü ve betikleme dilidir. PowerShell'i kullanmaya başlamak için aşağıdaki adımları takip edebilirsiniz:

1. **PowerShell'in Temel Kavramları:**
PowerShell'i anlamak için temel kavramları öğrenmek önemlidir. Cmdlet'ler (komutlar), değişkenler, fonksiyonlar, modüller gibi terimleri anlamak işinizi kolaylaştıracaktır.
2. **PowerShell İçin Ortamı Hazırlama:**
PowerShell, Windows işletim sistemlerinde genellikle varsayılan olarak kuruludur. **Başlat** menüsünden veya arama çubuğundan "**PowerShell**" yazarak PowerShell uygulamasını bulup açabilirsiniz.

![PowerShell](https://i.imgur.com/KpFIdVF.png)

**Temeller**

```powershell
# Yardım konularını
 Get-Help
```

```powershell
# Tüm çalışan işlemleri listele
Get-Process
```

```powershell
# Tüm çalışan servisleri listele
Get-Service
```

```powershell
# Sadece belirli bir servisi listele
Get-Service spooler
```

```powershell
# Belirtilen dizindeki dosyaları ve klasörleri listele
Get-ChildItem C:\
```

```powershell
# Belirli bir dosya türüne sahip dosyaları listele
Get-ChildItem C:\works -Filter *.txt
```

```powershell
# Yeni bir dosya oluştur
New-Item -Path "C:\works\YeniDosya.txt" -ItemType File
```

```powershell
# Yeni bir klasör oluştur
New-Item -Path "C:\works\YeniKlasör" -ItemType Directory
```

Eğer "PermissionDenied" hatası alıyorsanız : **Yönetici Olarak Çalıştırın:** PowerShell'i yönetici olarak çalıştırmayı deneyin. Bunun için PowerShell uygulamasına sağ tıklayın ve "Yönetici Olarak Çalıştır" seçeneğini seçin.

```powershell
# Dosyayı başka bir yere kopyala
Copy-Item "C:\works\YeniDosya.txt" -Destination "C:\works\YeniKlasör\EskiDosya.txt"
```

```powershell
# Dosyayı başka bir yere kopyala
Copy-Item "C:\works\YeniDosya.txt" -Destination "C:\works\YeniKlasör\EskiDosya.txt"
```

```powershell
# Dosyayı sil
Remove-Item "C:\works\SilinecekDosya.txt"
```

```powershell
# Klasörü ve içeriğini sil (Recursive olarak)
Remove-Item "C:\works\SilinecekKlasör" -Recurse
```

```powershell
# Dosyayı Başka Bir Yere Taşıma
Move-Item -Path "C:\works\Dosya.txt" -Destination "D:\backup\Dosya.txt"
```

```powershell
# Klasörü Yeniden Adlandırma - Taşıma
Move-Item -Path "C:\works" -Destination "C:\newWorks"
```

```powershell
# Çoklu Dosya Taşıma
Move-Item -Path "C:\works\Dosya1.txt", "C:\works\Dosya2.txt" -Destination "D:\Yedekler"
```

```powershell
# Desen Kullanarak Dosyaları Taşıma
Move-Item -Path "C:\works\*.txt" -Destination "D:\backup"
```

```powershell
# Dosyayı sil
Remove-Item "C:\works\SilinecekDosya.txt"
```

```powershell
# Klasörü ve içeriğini sil (Recursive olarak)
Remove-Item "C:\works\SilinecekKlasör" -Recurse
```

```powershell
# Mevcut çalışma dizinini görüntüle
Get-Location
```

```powershell
# Mevcut çalışma dizinini değiştirir
Set-Location c:\
```

```powershell
# Komut istemini temizle
Clear-Host
```

```powershell
# Belirtilen URL'den sayfa içeriğini çek
$webContent = Invoke-WebRequest -Uri "https://www.example.com"
# İçeriği görüntüle
$webContent.Content
```

Örneğin bu içeriği bir html sayfasına aktarabiliriz.

```powershell
# içeriği bir sayfaya aktar
$webContent.Content > google.html
# içeriği tarayıcı üzerinde görüntüle
explorer google.html
```

```powershell
# Not Defteri uygulamasını başlat
Start-Process notepad
```

```powershell
# Belirtilen adrese ping gönder
Test-Connection google.com
```

**Veri Türleri**

PowerShell, çeşitli veri türlerini destekleyen nesne odaklı bir komut satırı aracıdır. İşte PowerShell'da bulunan temel veri türleri

```powershell
# **PowerShell ile Metin İşlemleri**
$isim = "Dünya"
Write-Host "Merhaba, $isim!"
```

Açıklama: Metin veri türü, karakter dizilerini temsil eder. Çift veya tek tırnak içinde yazılır. Değişken veya ifadelerle içerik dinamik olarak oluşturulabilir.

```powershell
# **Sayılar**
$sayi1 = 10
$sayi2 = 5
$toplam = $sayi1 + $sayi2
Write-Host "Toplam: $toplam"
```

Açıklama: Sayılar, tamsayı (integer) veya ondalık sayı (float) olarak temsil edilir. Matematiksel işlemlerde kullanılır.

```powershell
# **Diziler**
$meyveler = @("Elma", "Armut", "Çilek")
Write-Host "İlk meyve: $($meyveler[0])"
```

Diziler, birden fazla değeri içeren koleksiyonlardır. İndeks numarasıyla elemanlara erişilir.

```powershell
# **Boolean**
$dogru = $true
$yanlis = $false
Write-Host "Doğru mu? $dogru"
```

Boolean, mantıksal değerleri temsil eder. Genellikle koşullu ifadelerde ve mantıksal kararlar almak için kullanılır.

```powershell
# **Tarih ve Saat**
$suAn = Get-Date
Write-Host "Şu anki saat: $suAn"
```

Tarih ve saat değerlerini temsil eder. Zaman hesaplamaları ve zaman dilimleriyle çalışmada kullanılır.

```powershell
# **Değişkenler**
$yas = 25
Write-Host "Yaş: $yas"
```

Değişkenler, geçici olarak veri saklamak için kullanılır. Farklı veri türlerini saklamak için kullanılabilirler.

```powershell
# **Nesneler**
$kisi = [PSCustomObject]@{
Ad = "Duygu"
Soyad = "Aktokmak"
Yas = 25
}
Write-Host "$($kisi.Ad) $($kisi.Soyad), yaş: $($kisi.Yas)"
```

Nesneler, birden çok özelliği (property) ve hatta metodları temsil eden veri yapılarıdır. Özelliklerde veri saklanabilir ve özel işlemler yapılabilir.

```powershell
# **Null**
$bosDeger = $null
if ($bosDeger -eq $null) {
     Write-Host "Değer boş."
}
```

Null, bir değişkenin veya ifadenin bir değere sahip olmadığını belirtir.

---

**Örnek:**

Diyelim ki bir dizindeki metin dosyalarını listeleyip, içeriklerinde belirli bir kelimeyi aramak istiyorsunuz. İşte bu işlemde pipelining'i kullanabilirsiniz:

```powershell
# **Örnek : PowerShell ile Dosya İçeriğini Filtreleme ve Sayma**
Get-ChildItem -Path C:\works -Filter *.txt | ForEach-Object {
    $dosyaYolu = $_.FullName
    $dosyaIcerik = Get-Content $dosyaYolu
    $kelimeSayisi = ($dosyaIcerik -split '\s+' | Measure-Object).Count
    Write-Host "Dosya: $dosyaYolu, Toplam Kelime Sayısı: $kelimeSayisi"
}
```

Yukarıdaki örnekte, `Get-ChildItem` ile belirli bir dizindeki metin dosyalarını listeledik. Daha sonra bu dosyaları `ForEach-Object` ile tek tek ele alarak içeriklerini aldık. İçerikleri boşluklara göre böldük ve `Measure-Object` ile kelime sayısını hesapladık. Sonuçları çıktı olarak yazdırdık.

**Pipelining**, |  komutların birbirine bağlanarak işlemler zinciri oluşturmasını sağlar ve kodunuzun daha temiz ve anlaşılır olmasına yardımcı olur. Bu sayede daha karmaşık veri işleme ve analiz işlemleri yapabilirsiniz.

---

**Fonksiyonlar**

PowerShell'da fonksiyonlar, belirli bir işlemi gerçekleştiren ve tekrar kullanılabilir bir kod bloğudur. Bir fonksiyon oluşturmak için `function` anahtar kelimesini kullanabilirsiniz. İşte basit bir fonksiyon 

örneği:

```powershell
function MerhabaDunya {
    Write-Host "Merhaba, Dünya!"
}

MerhabaDunya  # Fonksiyonu çağırma
```

Yukarıdaki örnekte "MerhabaDunya" adında bir fonksiyon oluşturduk ve bu fonksiyon "Merhaba, Dünya!" mesajını ekrana yazdırdı. Fonksiyonları parametrelerle de çağırabilirsiniz:

```powershell
function Selam($isim) {
    Write-Host "Merhaba, $isim!"
}

Selam "Dünya"  # "Merhaba, Dünya!" çıktısı alınır
```

**Betikler (Script Dosyaları):**

PowerShell'da betikler, `.ps1` uzantılı dosyalar olarak oluşturulan ve içinde PowerShell komutlarının bulunduğu dosyalardır. Betikler, tekrar eden işlemleri otomatikleştirmek veya karmaşık görevleri yürütmek için kullanılır. 

PowerShell ISE editörünün kullanarak yada farklı editörler yardımı ile oluşturabilirsiniz.

![PowerShell ISE](https://i.imgur.com/txHwhg2.png)

Örneğin:

```powershell
# Merhaba.ps1
$isim = Read-Host "Adınızı girin"
Write-Host "Merhaba, $isim!"
```

Bu betik, kullanıcıdan isim alarak "Merhaba, [isim]!" mesajını yazdıracaktır.

Betikleri çalıştırmak için PowerShell penceresine betiğin tam yolunu veya sadece betik adını yazabilirsiniz:

```powershell
.\Merhaba.ps1  # Betiği çalıştırır
```

**Not:** PowerShell varsayılan olarak betikleri çalıştırmayı engelleyen bir güvenlik politikası ile gelir. Bu politika, betikleri yürütmeyi engellememek için aşağıdaki komutu yönetici olarak çalıştırmayı deneyebilirsiniz:

```powershell
Set-ExecutionPolicy RemoteSigned
```

Bu komut, yerel betiklerin (yani sizin veya güvendiğiniz kaynaklardan gelen betiklerin) yürütülmesine izin verirken, uzaktan gelen betiklerin dijital olarak imzalanmış olmasını gerektirir.

---

Microsoft'un resmi PowerShell belgeleri (https://docs.microsoft.com/en-us/powershell/) size kapsamlı bir rehberlik sunar. Başlangıç, gelişmiş ve uzman düzeyde bilgiler içerir.

---

**Windows PowerShell Komutları Ağ Yapılandırması:** 

Windows PowerShell, gelişmiş komut satırı aracı olarak Windows işletim sistemlerinde kullanılır. PowerShell komutlarını ile Ağ Yapılandırmasını anlamalarına ve kullanmalarına yardımcı olmayı amaçlamaktadır.

PowerShell, Windows işletim sistemlerinde kullanılan bir komut satırı arayüzü ve betikleme dilidir. PowerShell'i kullanmaya başlamak için aşağıdaki adımları takip edebilirsiniz:

1. **PowerShell'in Temel Kavramları:**
PowerShell'i anlamak için temel kavramları öğrenmek önemlidir. Cmdlet'ler (komutlar), değişkenler, fonksiyonlar, modüller gibi terimleri anlamak işinizi kolaylaştıracaktır.
2. **PowerShell İçin Ortamı Hazırlama:**
PowerShell, Windows işletim sistemlerinde genellikle varsayılan olarak kuruludur. **Başlat** menüsünden veya arama çubuğundan "**PowerShell**" yazarak PowerShell uygulamasını bulup açabilirsiniz.
    
![PowerShell](https://i.imgur.com/KpFIdVF.png)

**Test-NetConnection:**

```powershell
# Bu komut, [google.com](http://google.com/) adresine 80 numaralı port üzerinden bağlantı denemesi yapar. Bu örnek, HTTP bağlantısını test eder.
Test-NetConnection google.com -Port 80
```

**Resolve-DnsName:**

```powershell
# Bu komut, [www.google.com](http://www.google.com/) alan adını çözerek ilgili IP adresini görüntüler.
Resolve-DnsName www.google.com
```

**Get-NetAdapter:**

```powershell
# Bu komut, bilgisayarınızdaki ağ adaptörlerini listeler. Adaptörlerin adları, durumları ve hızları gibi bilgileri içerir.
Get-NetAdapter
```

**Get-NetIPAddress:**

```powershell
# Bu komut, bilgisayarınızdaki ağ IP adreslerini listeler. IP adresleri, alt ağ maskeleri ve adaptör adları gibi bilgileri içerir.
Get-NetIPAddress
```

**Get-NetRoute:**

```powershell
# Bu komut, bilgisayarınızdaki ağ rotalarını listeler. Hedef IP adresleri, ağ maskeleri, ağ kapıları ve arayüz adları gibi bilgileri içerir.
Get-NetRoute
```

**Set-NetIPAddress:**

```powershell
# Bu komut, `Ethernet` adlı adaptörün IP adresini `192.168.1.10` olarak ayarlar.

# Bu komutta `-PrefixLength` parametresini eklemeyi unutmayın. Bu parametre, IP adresinin alt ağı uzunluğunu belirtir. Örneğin, 24 bit IPv4 alt ağının tipik uzunluğudur.
Set-NetIPAddress -IPAddress "192.168.1.10" -InterfaceAlias "Ethernet" -PrefixLength 16

# # *Eğer "Access is denied" hatası alıyorsanız : **Yönetici Olarak Çalıştırın:** PowerShell'i yönetici olarak çalıştırmayı deneyin. Bunun için PowerShell uygulamasına sağ tıklayın ve "Yönetici Olarak Çalıştır" seçeneğini seçin.*
```

**New-NetFirewallRule:**

```powershell
# Bu komut, yeni bir güvenlik duvarı (firewall) kuralı oluşturur. Örnekte, gelen HTTP trafiğini izin veren bir kural oluşturulur.

# *Eğer "Access is denied" hatası alıyorsanız : **Yönetici Olarak Çalıştırın:** PowerShell'i yönetici olarak çalıştırmayı deneyin. Bunun için PowerShell uygulamasına sağ tıklayın ve "Yönetici Olarak Çalıştır" seçeneğini seçin.*
New-NetFirewallRule -DisplayName "HTTP Allow" -Direction Inbound -Action Allow -Protocol TCP -LocalPort 80
```

**Test-WSMan:**

```powershell
# Bu komut, belirtilen bilgisayara WSMan ile bağlantı kurup kuramayacağını test eder. WS-Management yeteneklerini kontrol eder.
Test-WSMan <computername>

# **WSMan (Windows Remote Management)**, Microsoft tarafından geliştirilmiş bir protokoldür ve uzaktan yönetim ve otomasyon görevlerini gerçekleştirmek için kullanılır. WSMan, temel olarak uzaktan iletişim ve komut iletimi sağlamak amacıyla tasarlanmıştır. Bu protokol, PowerShell ve diğer uzaktan yönetim araçlarının temelinde yer alır.
```

İşlem başarılı olduğunda aşağıdaki gibi bir çıktı alırsınız.

```powershell
wsmid           : http://schemas.dmtf.org/wbem/wsman/identity/1/wsmanidentity.xsd
ProtocolVersion : http://schemas.dmtf.org/wbem/wsman/1/wsman.xsd
ProductVendor   : Microsoft Corporation
ProductVersion  : OS: 0.0.0 SP: 0.0 Stack: 3.0
```

Eğer başarılı değil ise, WinRM hizmetini analiz etmek ve yapılandırmak için hedefte şu komutu çalıştırın: "winrm quickconfig".

```powershell
# "winrm quickconfig" komutu, Windows Remote Management (WinRM) hizmetini hızlı bir şekilde yapılandırmak ve etkinleştirmek için kullanılan bir PowerShell komutudur.
# WinRM, uzaktan yönetim işlemlerini gerçekleştirmek için kullanılan bir protokoldür ve PowerShell ile uzaktan yönetim işlemlerini gerçekleştirmek için kullanılır.
winrm quickconfig
```

**Get-DnsClientServerAddress:**

```powershell
# Bu komut, DNS sunucu adreslerini görüntüler. DNS sunucularının hangi adreslere ayarlı olduğunu gösterir.
Get-DnsClientServerAddress
```

**Set-DnsClientServerAddress:**

```powershell
# Bu komut, Ethernet adlı adaptörün DNS adresini 8.8.8.8 ve 8.8.4.4 olarak ayarlar.
Set-DnsClientServerAddress -InterfaceAlias "Ethernet" -ServerAddresses ("8.8.8.8", "8.8.4.4")
```

**Test-NetConnection -TraceRoute:**

```powershell
# Bu komut, [google.com](http://google.com/) adrese giden rotayı izler. Hangi ağ kapılarından geçildiğini ve ne kadar süreyle ulaşıldığını gösterir.
Test-NetConnection google.com -TraceRoute
```

**Get-NetFirewallProfile:**

```powershell
# Bu komut, güvenlik duvarı profillerini (domain, private, public) listeler. Hangi profillerin etkin olduğunu ve hangi türde trafiği izin verildiğini görüntüler.
Get-NetFirewallProfile
```

**Senaryo: Yeni Bir Sunucunun Ağ Yapılandırması**

---

**Ağ Adaptörünü Listeleyin:**

```powershell
# Mevcut ağ adaptörlerini listelemek için Get-NetAdapter komutunu kullanın. Hangi adaptörü yapılandıracağınıza karar verin.
Get-NetAdapter
```

**IP Adresi ve Alt Ağ Maskesi Ekleyin:**

```powershell
# Seçtiğiniz ağ adaptörüne IP adresi ve alt ağ maskesi atayın.
New-NetIPAddress -InterfaceAlias "Ethernet" -IPAddress "192.168.1.100" -PrefixLength 24
```

**Varsayılan Ağ Geçidi Ekleyin:**

```powershell
# Ağ adaptörüne varsayılan ağ geçidi ekleyin.
New-NetRoute -InterfaceAlias "Ethernet" -DestinationPrefix "0.0.0.0/0" -NextHop "192.168.1.1"
```

**DNS Sunucularını Ayarlayın:**

```powershell
# DNS Sunucularını yapılandır
Set-DnsClientServerAddress -InterfaceAlias "Ethernet" -ServerAddresses ("8.8.8.8", "8.8.4.4")
```

**Ağ Adaptörünü Etkinleştirin:**

```powershell
# Ağ adaptörünü etkinleştir
Enable-NetAdapter -Name "Ethernet"
```

**Yapılandırmayı Doğrulayın:**

```powershell
# Yapılandırmayı kontrol etmek için Get-NetIPAddress, Get-NetRoute, ve Get-DnsClientServerAddress komutlarını kullanın.
Get-NetIPAddress -InterfaceAlias "Ethernet"
Get-NetRoute -InterfaceAlias "Ethernet"
Get-DnsClientServerAddress -InterfaceAlias "Ethernet"
```

Bu senaryo, yeni bir sunucunun temel ağ yapılandırmasını PowerShell kullanarak nasıl gerçekleştirebileceğinizi göstermektedir.

---

Microsoft'un resmi PowerShell belgeleri (https://docs.microsoft.com/en-us/powershell/) size kapsamlı bir rehberlik sunar. Başlangıç, gelişmiş ve uzman düzeyde bilgiler içerir.

---

**Hyper-V Sanallaştırma**

Hyper-V, Microsoft tarafından geliştirilen bir **sanallaştırma** platformudur. Bu platform, **fiziksel sunucuları sanal sunuculara** dönüştürmek ve **birden çok işletim sistemi örneğini** **aynı fiziksel sunucu üzerinde** çalıştırmak için kullanılır.

Hyper-V'nin resmi olarak desteklediği işletim sistemleri **sadece Windows** işletim sistemleriyle sınırlıdır. Hyper-V, yalnızca Windows Server ve belirli Windows sürümleri üzerinde çalışabilir. Bu nedenle **macOS**, **Unix** veya **Linux** üzerinde Hyper-V'yi resmi olarak çalıştıramazsınız.

Ancak, macOS, Unix ve Linux gibi işletim sistemleri üzerinde de sanallaştırma yapmak için farklı araçlar ve platformlar mevcuttur. Örneğin:

- **macOS:** [VirtualBox](https://www.virtualbox.org/), Parallels Desktop veya VMware Fusion gibi uygulamalar, macOS üzerinde sanal makineler oluşturmanıza ve farklı işletim sistemlerini çalıştırmanıza yardımcı olabilir.
- **Unix/Linux:** [VirtualBox](https://www.virtualbox.org/), VMware Workstation/Player gibi araçlar, Unix veya Linux işletim sistemleri üzerinde sanal makineler oluşturmanızı sağlar. Ayrıca, KVM (Kernel-based Virtual Machine) gibi çözümler, özellikle Linux üzerinde sanallaştırma için kullanılır.

---

**Hyper-V'yi etkinleştirme**

Yönetici olarak bir PowerShell konsolu açın.

Aşağıdaki komutu çalıştırın:

```powershell
# Bu PowerShell komutu, Microsoft Hyper-V sanallaştırma özelliğini etkinleştirmek için kullanılır. Hyper-V, Windows işletim sistemleri üzerinde sanal makineler oluşturmanıza ve yönetmenize olanak tanır. Bu komutla Hyper-V özelliğini etkinleştirmiş olursunuz. İşte bu komutun detayları:

# Enable-WindowsOptionalFeature: Bu cmdlet, Windows işletim sisteminde isteğe bağlı özellikleri etkinleştirmek veya devre dışı bırakmak için kullanılır.

# -Online: Bu parametre, değişikliklerin şu anki işletim sistemi yüklü olan çevrimiçi ortamda uygulanmasını sağlar.

# -FeatureName Microsoft-Hyper-V: Bu parametre, etkinleştirmek istediğiniz özelliğin adını belirtir. "Microsoft-Hyper-V" adı, Hyper-V sanallaştırma özelliğini temsil eder.

# -All: Bu parametre, belirtilen özelliğin tüm bileşenlerini etkinleştirmek için kullanılır. Hyper-V için gereken tüm bileşenler etkinleştirilir.
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All
```

*PowerShell'i Yönetici olarak çalıştırdığınızdan emin olun.*

**Yükleme tamamlandığında yeniden başlatın**.

---

**Hyper-V ile Sanal Makine Oluşturma**

Başlat menüsünden Hyper-V Hızlı Oluştur'u açın.

![Hyper-V Hızlı Oluştur](https://learn.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/media/quick-create-start-menu.png)

**Bir işletim sistemi seçin** veya yerel bir yükleme kaynağı kullanarak kendi işletim sisteminizi seçin.

![Bir işletim sistemi seçin](https://learn.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/media/vmgallery.png)

*Sanal makineyi oluşturmak için kendi görüntünüzü kullanmak istiyorsanız, **Yerel Yükleme Kaynağı'nı** seçin. Yada bu adımı atlayın.*

**Yükleme Kaynağını Değiştir** seçin.

![Yükleme Kaynağını Değiştir](https://learn.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/media/change-source.png)

Yeni bir sanal makineye dönüştürmek istediğiniz .iso veya .vhdx dosyasını seçin.

---

Masaüstü bilgisayarlar ve dizüstü bilgisayarlar için **Ubuntu**'nun en son LTS sürümü : 

[Download Ubuntu Desktop | Download | Ubuntu](https://ubuntu.com/download/desktop)

Masaüstü bilgisayarlar ve dizüstü bilgisayarlar için **Windows**’un en son sürümü: 

[Download Windows 11](https://www.microsoft.com/en-in/software-download/windows11)

---

*Windows üzerinde Windows ve Ubuntu gibi işletim sistemlerini otomatik olarak indirme ve kurulumlarını başlatabilirsiniz.*

**Görüntü bir Linux görüntüsüyse, Güvenli Önyükleme seçeneğinin işaretini kaldırın.**

![Güvenli Önyükleme](https://learn.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/media/toggle-secure-boot.png)

"Sanal Makine Oluştur"u seçin.

Gerekli indirmeler yapılacaktır.

![Hyper-V - Virtual Machine Download Image](https://i.imgur.com/hgiYFKL.png)

***Tebrikler, yeni bir sanal makineniz var.** Artık işletim sistemini kullanmaya hazırsınız.*

![Hyper-V Manager - Virtual Machine Created](https://i.imgur.com/TvZWXj5.png)

"Connect" butonu ile sanal makinanıza bağlanabilirsiniz.
 

Sanal makineniz şöyle görünmelidir:

![Ubuntu - System Configuration](https://i.imgur.com/JA3s0ah.png)

Windows işletim sistemi içerisinde Ubuntu dağıtımı yapılandırmaya hazırsınız.

Devam edin ve ilk yapılandırma tanımlarını girin.

**Klavye ayarlarınızı tanımlayın**.

![Ubuntu - Keyboard Settings](https://i.imgur.com/ocQFPfK.png)

**Bölgenizi seçin**

![Ubuntu - Select your location](https://i.imgur.com/mv1gtoD.png)

**Sistem tanımlarınızı yapın.**

![Ubuntu - Define your hostname](https://i.imgur.com/gD06kHU.png)

**Güncellemeleri alın.**

![Ubuntu - Update](https://i.imgur.com/Dwv8H0M.png)

**Oturum Açın**

![Ubuntu - Login with xrdp](https://i.imgur.com/k3KryKX.png)

**Makinanız şu an çalışmaktadır.**

**Basit oturuma geçmek için**

![Ubuntu - Select Basic Session](https://i.imgur.com/q0p4FvB.png)

**Ubuntu Desktop a ulaşmış olacaksınız.**

![Ubuntu - Connect your online accounts](https://i.imgur.com/YTAWhtz.png)

Bu adımları geçebilir yada tanımlayabilirsiniz.

![Ubuntu - Authentication Reuired](https://i.imgur.com/w79oema.png)

**Güncellemeleri almak yada bir uygulama kurmak için belirlediğiniz parolayı girin.**

![Ubuntu - Desktop Welcome](https://i.imgur.com/p0hMA5u.png)

**Linux dünyasına hoşgeldiniz.**

---

Ubuntu'da terminali açmak için aşağıdaki adımları takip edebilirsiniz:

1. **Klavye Kısayolu:`Ctrl`** + **`Alt`** + **`T`** tuşlarına birlikte basın. Bu, terminali açmak için varsayılan klavye kısayoludur.
2. **Uygulama Menüsü İle:**
    - Genellikle sol alt köşede bulunan "Uygulamaları Göster" düğmesine tıklayın.
    - Arama çubuğuna "Terminal" veya "Terminal Emülatörü" yazın.
    - Görünen Terminal uygulama simgesine tıklayın.
3. **Çalıştır Komutu İle:`Alt`** + **`F2`** tuşlarına birlikte basarak "Bir Komut Çalıştır" iletişim kutusunu açın. "gnome-terminal" yazın ve Enter tuşuna basın.

Terminal açıldığında, komutları yazarak sistemle etkileşime girebilirsiniz. 

 Linux komut satırında aşağıdaki temel başlangıç komutları deneyebilirsiniz:

- **`ls`**: Mevcut konumda bulunan dosya ve dizinleri listeler.
- **`cd`**: Dizin değiştirir.
- **`pwd`**: Mevcut çalışma dizinini görüntüler.
- **`mkdir`**: Yeni bir dizin oluşturur.
- **`touch`**: Yeni boş bir dosya oluşturur.
- **`cp`**: Dosya veya dizinleri kopyalar.
- **`mv`**: Dosya veya dizinleri taşır (adını değiştirir).
- **`rm`**: Dosya veya dizinleri siler (bu komutu kullanırken dikkatli olun).
- **`nano`** veya **`vim`**: Metin düzenleyiciler, terminal üzerinden dosya oluşturmak ve düzenlemek için.
- **`apt`** veya **`apt-get`**: Yazılım kurulumu, güncellemesi ve kaldırması için kullanılan paket yönetimi komutları.
    
![Ubuntu - Terminal](https://i.imgur.com/L4EDXB6.png)


Resmi belgeler size kapsamlı bir rehberlik sunar. Başlangıç, gelişmiş ve uzman düzeyde bilgiler içerir.

[Install the Hyper-V role on Windows Server | Microsoft Learn](https://learn.microsoft.com/en-us/windows-server/virtualization/hyper-v/get-started/install-the-hyper-v-role-on-windows-server)

[Hyper-V on Windows 10 | Microsoft Learn](https://learn.microsoft.com/en-us/virtualization/hyper-v-on-windows/)

---

**IIS - Windows Tabanlı Web Hizmetleri**

Internet Information Services (IIS), Microsoft tarafından geliştirilen ve Windows tabanlı sunucularda **web hizmetleri sağlayan bir web sunucusu rolüdür**. IIS, web sitelerini **barındırmak**, **yönetmek** ve **yayınlamak** için kullanılır. Genellikle Windows Server işletim sistemleriyle birlikte gelir, ancak bazı Windows sürümlerinde de opsiyonel olarak kurulabilir.

**IIS kurulumu**

PowerShell kullanarak Windows üzerinde Internet Information Services (IIS) kurulumu oldukça kolaydır. IIS, Windows'ta web sunucusu olarak kullanılır. İşte PowerShell ile IIS kurulumu için adımlar:

1. **PowerShell'i Yönetici Olarak Başlatın:**
Başlat menüsünden "PowerShell"i aratarak sağ tıklayın ve "Yönetici Olarak Çalıştır" seçeneğini seçin.
2. **IIS Kurulum Komutu:**
PowerShell penceresine aşağıdaki komutu yazın ve Enter tuşuna basın. 
    
    ```powershell
    # Bu komut, Windows Server üzerinde IIS'in temel bileşenlerini ve yönetim araçlarını kurar.
    Install-WindowsFeature -name Web-Server -IncludeManagementTools
    ```
    
    ```powershell
    # Bu komut, Windows üzerinde IIS'in temel bileşenlerini ve yönetim araçlarını kurar.
    Enable-WindowsOptionalFeature -Online -FeatureName IIS-WebServer -All
    ```
    
3. **Kurulumun Tamamlanması:**
Komut çalıştırıldıktan sonra IIS bileşenleri indirilir ve kurulum tamamlanır. Kurulum tamamlandığında, IIS ile ilgili hizmetler ve özellikler sistemde etkinleştirilmiş olur.
    
    ```
    # Tarayıcınızdan http://localhost/ adresine bağlanmayı deneyin
    # Varsayılan olarak 80 numaralı port yayın başlar.
    # Varsayılan web sitesi C:\inetpub\wwwroot klasöründe yer alır.
    ```

   ![Windows - IIS](https://i.imgur.com/4cZEkrS.png)
   
5. **IIS'i Yönetmek:**
IIS'i yönetmek için PowerShell veya GUI tabanlı araçları kullanabilirsiniz. IIS Manager aracı genellikle GUI ile yönetmek için kullanılırken, PowerShell komutları ile de pek çok işlem yapabilirsiniz. Örneğin:
    - 
        
        ```powershell
        # IIS üzerinde yeni Web sitesi oluşturmak
        New-WebSite -Name "MyWebsite1" -Port 81 -PhysicalPath "C:\inetpub\MyWebsite1"
        # C:\inetpub\MyWebsite1 klasörü eğer yok ise oluşturulmalıdır.
        
        ```
        
    - 
        
        ```powershell
        
        # IIS üzerinde Sanal dizin eklemek:
        New-WebVirtualDirectory -Site "MyWebsite1" -Name "example" -PhysicalPath "C:\inetpub\MyWebsite1\Virtual"
        
        ```
        
    - 
        
        ```powershell
        # Web uygulaması eklemek
        New-WebApplication -Name "MyApp" -Site "MyWebsite1" -PhysicalPath "C:\inetpub\MyWebsite1\MyApp"
        
        ```
        
    
    Bu örneklerde, "MyWebsite1", "Virtual" ve "MyApp" gibi isimleri ve dizin yollarını kendi gereksinimlerinize göre değiştirmelisiniz.
    
    Örnek klasörlerinizin içine index.html gibi dosyalar yerleştirerek sonuçları gözlemleyin.
    
    IIS (Internet Information Services) altında bulunan tüm siteleri durdurmak veya silmek için IIS Manager veya PowerShell gibi araçları kullanabilirsiniz. İşte her iki yöntemle de tüm siteleri durdurma ve silme adımları:
    
    ### **IIS Manager Kullanarak Siteleri Durdurma veya Silme:**
    
    1. Başlat menüsünde "IIS" veya "Internet Information Services (IIS) Manager" yazarak IIS Manager'ı açın.
    2. Sol taraftaki gezinme panelinde "Sites" (Siteler) düğmesine tıklayarak tüm siteleri gösterin.
    3. Tüm siteleri seçmek için Ctrl tuşuna basılı tutup tüm siteleri tıklayın veya durdurmak veya silmek istediğiniz siteleri tek tek seçin.
    4. Yukarıdaki menü çubuğunda "Durdur" seçeneğine tıklayarak seçtiğiniz siteleri durdurabilirsiniz. Aynı şekilde "Sil" seçeneği ile de silebilirsiniz.
        
   ![Windows - IIS Manager](https://i.imgur.com/h7rs8aJ.png)
        
    
    ### **PowerShell Kullanarak Siteleri**
    
    ```powershell
    # Tüm siteleri listeleme
    Get-Website
    ```
    
    ```powershell
    # Belirli bir sitenin detaylarını görmek isterseniz
    Get-Website -Name "SiteName"
    ```
    
    **Durdurma veya Silme:**
    
    PowerShell komutlarıyla da IIS altındaki tüm siteleri durdurabilir veya silebilirsiniz.
    
    ```powershell
    # **Tüm Siteleri Durdurmak**
    Get-Website | Stop-Website
    ```
    
    Bu komut, tüm siteleri durduracaktır.
    
    ```powershell
    # **Tüm Siteleri Silmek**
    Get-Website | Remove-Website
    ```
    
    Bu komut, tüm siteleri siler. Ancak önce kullanıcıya onay verilmesi istenecektir.
    
    **Dikkatli olun: Tüm siteleri silmek geri alınamaz bir işlemdir, bu nedenle silmeden önce verilerinizi yedeklemek ve işlemin sonuçlarını anlamak önemlidir.**
    
    Her iki yöntemle de, IIS Manager kullanarak veya PowerShell komutlarıyla, siteleri durdurabilir veya silme işlemlerini gerçekleştirebilirsiniz.
    
    ### **PowerShell Kullanarak Siteleri Başlatma**
    
    **1. Belirli Bir Siteyi Başlatmak:**
    
    Belirli bir sitenin adını veya ID'sini biliyorsanız, aşağıdaki komutu kullanabilirsiniz:
    
    ```powershell
    # **Belirli Bir Siteyi Başlatmak**
    Start-Website -Name "SiteName"
    ```
    
    **2. Tüm Siteleri Başlatmak:**
    
    Eğer tüm siteleri başlatmak istiyorsanız, aşağıdaki komutu kullanabilirsiniz:
    
    ```powershell
    # T**üm Siteleri Başlatmak**
    Get-Website | Start-Website
    ```
    
    Bu komut, durdurulmuş tüm siteleri başlatacaktır.
    
    Yukarıdaki komutları kullanırken, sitelerinizi dikkatli bir şekilde kontrol edin ve gerektiğinde yedeklemeleri almayı unutmayın. Ayrıca, siteleri başlatma işlemi üzerinde gerçekleştiriyorsanız, canlı ortamlarda bunu yapmadan önce kullanıcıların ve iş süreçlerinin etkilenip etkilenmeyeceğini dikkate almalısınız.
    
    **PowerShell Kullanarak IIS'i Yeniden Başlatmak:**
    
    1. Aşağıdaki PowerShell komutunu kullanarak IIS hizmetini yeniden başlatabilirsiniz:
    
    ```powershell
    # **IIS'i Yeniden Başlatmak**
    Restart-Service -Name "W3SVC"
    ```
    
    Bu komut, "W3SVC" adlı IIS hizmetini (World Wide Web Hizmetleri) yeniden başlatacaktır.
