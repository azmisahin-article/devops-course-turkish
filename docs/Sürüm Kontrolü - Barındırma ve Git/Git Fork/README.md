# Git Fork

Git Fork, bir projenin kopyasını alarak kendi bağımsız dalınızda çalışmanıza olanak tanır. Bu şekilde orijinal projenin değişmeden kalmasını sağlayabilirsiniz.

![organizma evrimi](https://static.acne.org/ipb_uploads/monthly_2018_08/03-antibiotic-resistance-in-bacteria.jpg.dec038eea707f4f86d56d2b68b22d3af.jpg)

Doğada, farklı türler benzer bir atasal organizmadan **evrimleşebilir**. Günümüzde en gözlenebilir evrimsel süreçlerden biri, antibiyotik direncinin **evrimidir**. Antibiyotik direnci, bakterilerin antibiyotiklere karşı duyarlılığını kaybederek bu ilaçlara karşı direnç kazanmalarıdır.

Bu, Git Fork'un bir benzeridir. Projenin "ana" sürümü korunurken, farklı ekipler veya geliştiriciler kendi projelerini **geliştirebilir** ve **uyarlayabilir**. Yani, antibiyotiğe dirençli bakteriler mutasyonlarını diğer bakterilere **aktarabilirler.**

**Proje Forklama**

Bir projeyi çoğaltarak ve kendi hesabınıza bağımsız bir kopya oluşturarak "forklama" işlemi gerçekleştirilir. 

[Fork a repo - GitHub Docs](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

GitHub'da bir *depoyu çatallamak* için bir örnek sağlamak amacıyla tasarlanmış bir repo.

[Depoyu çatallamak](https://github.com/octocat/Spoon-Knife)

Bir ***çatal*** oluşturmak, başka birinin projesinin **kişisel bir kopyasını üretmek**tir. Çatallar, orijinal depo ile kişisel kopyanız arasında bir tür **köprü görevi** görür. Orijinal projeye kadar değişikliklerinizi sunarak diğer kişilerin projelerini **daha iyi hale getirmeye** yardımcı olmak için ***Çekme İstekleri*** gönderebilirsiniz

**Kopya Alma (Clone)**

**`git clone`**, bir Git deposunu kopyalamak için kullanılan bir komuttur. Bu komut, uzak bir Git deposunun tamamını **yerel bir bilgisayara kopyalamak için** kullanılır. Kopyalanan depo, tüm geçmiş sürümleri, dalları ve dosyaları içerir, böylece bu yerel kopya üzerinde çalışabilirsiniz.

[Git clone rehberi](https://github.com/git-guides/git-clone)

**Pull Request (Pull Talebi):**
Yaptığınız değişiklikleri ana projeye **entegre etmek** isterseniz, Git barındırma platformunda bulunan "Pull Request" veya benzer bir seçeneği kullanarak bir talep oluşturun. Bu talep, yaptığınız değişiklikleri **ana projeye** eklemek istediğinizi ifade eder.

[About pull request reviews - GitHub Docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/about-pull-request-reviews)

**Talep İnceleme ve Onay:**
Ana projenin sahipleri veya geliştiricileri talebinizi **inceleyeceklerdir**. Talebiniz **onaylanabilir**, **düzenlenebilir** veya **reddedilebilir**. Kabul edilirse, yaptığınız değişiklikler ana projeye dahil edilir.

[Reviewing proposed changes in a pull request - GitHub Docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request)

**Teşekkür ve Katkılar:**
Onaylanan talepteki değişikliklerin projeye katkı sağladığını ve geliştirme sürecine etkide bulunduğunu göstermek için geliştiricilere teşekkür edilir.

---

**Ek Uyarılar**

**Create a Merge Commit (Birleştirme İşlemi Oluştur):**
Bu yöntemde, farklı dallardaki değişiklikler birleştirilirken birleştirme işlemi sırasında yeni bir "merge commit" oluşturulur. Bu commit, dalların birleştirilmesi ile ortaya çıkan değişiklikleri gösterir. Tüm commit geçmişi ve dal geçmişi korunur, böylece her bir dalın ne zaman ve nerede birleştirildiği net bir şekilde görülebilir.

Bu yöntemde, mevcut dalı hedef dala birleştirmek için şu komutları kullanabilirsiniz:

```bash
git checkout <hedef_dal>
git merge <mevcut_dal>
```

Bu komutlar, mevcut dalınızı hedef dala birleştirirken yeni bir merge commit oluşturacaktır.

**Squash and Merge (Birleştirme ve Sıkıştırma):**
Bu yaklaşımda, bir dalın değişiklikleri diğer dala **tek bir büyük değişiklik** olarak birleştirilir. Yani, tüm commit'ler *tek bir büyük commit haline getirilir* ve bu büyük commit ana dala eklenir. Bu yöntem, çok sayıda küçük commit yerine daha temiz ve anlamlı bir commit geçmişi elde etmek istendiğinde kullanışlıdır.

Eğer squash and merge yöntemini kullanmak istiyorsanız, hedef dalda squash işlemini yapmadan önce mevcut dalı rebase etmeniz gerekebilir:

```bash
git checkout <hedef_dal>
git pull origin <hedef_dal>
git rebase -i <mevcut_dal>
```

Yukarıdaki komutlarla, mevcut dalını hedef dala rebase edebilir ve ardından **`pick`** yerine **`squash`** komutunu kullanarak commit'leri sıkıştırabilirsiniz.

- Yukarıdaki komutu çalıştırdığınızda, bir metin düzenleyici açılacaktır ve bu düzenleyicide mevcut dalınızdaki commit listesi gösterilecektir.
- Düzenleyiciye girdikten sonra, her commitin başında **`pick`** yazan satırları göreceksiniz. İlk (en eski) commit'in başındaki **`pick`** ifadesini **`pick`** yerine **`squash`** olarak değiştirin. Diğer tüm commitlerin başındaki **`pick`** ifadelerini **`squash`** olarak bırakın veya değiştirin. Bu, tüm commit'leri ilk commitin altında sıkıştırmanızı sağlar.
- Düzenleme işleminden sonra kaydedin ve düzenleyiciyi kapatın. Daha sonra, birleştirme mesajınızı düzenleyebileceğiniz bir başka düzenleyici açılacaktır. Burada, tüm commit mesajlarını tek bir mesajda birleştirebilirsiniz. Birleştirme mesajını düzenledikten sonra kaydedin ve düzenleyiciyi kapatın.
- Squash işlemini tamamlamak için rebase işlemini bitirin:
    
    ```bash
    git rebase --continue
    ```
    
- Eğer rebase sırasında çakışmalar oluşursa, bu çakışmaları çözerek rebase işlemini tamamlayın. Çakışmaları çözümledikten sonra aynı komutla rebase işlemini devam ettirebilirsiniz.
- Son adımda, güncellenmiş commit geçmişini hedef dala gönderin:
    
    ```bash
    git push origin <hedef_dal>
    ```
    

Bu adımları takip ederek squash işlemi gerçekleştirebilirsiniz. Bu işlem, birden fazla commiti tek bir büyük ve anlamlı commit haline getirmek için kullanılır.

**Rebase and Merge (Rebase ve Birleştirme):**
Bu yöntemde, önce **hedef daldaki en son değişiklikler alınır** ve ardından dalın değişiklikleri bu en son duruma rebase edilir. Yani, dalın değişiklikleri **hedef dalın en son durumuna** uygulanır. Sonuç olarak, dalın commit geçmişi daha düzgün ve lineer bir şekilde görünür. Ancak, bu yöntem çakışmaları çözmek ve commit geçmişini yeniden düzenlemek gerektiğinde daha karmaşık olabilir.

Rebase and merge yöntemini kullanmak için şu komutları kullanabilirsiniz:

```bash
git checkout <hedef_dal>
git pull origin <hedef_dal>
git rebase <mevcut_dal>
```

Yukarıdaki komutlar, mevcut dalını hedef dalın en son durumuna rebase eder.
