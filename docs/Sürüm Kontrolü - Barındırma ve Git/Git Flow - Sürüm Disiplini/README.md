# Git Flow - Sürüm Disiplini

Git Flow, yazılım geliştirme sürecinde **sürüm yönetimi ve işbirliği** için kullanılan bir **yöntemdir**. Çeşitli dal ve birleştirme adımlarıyla geliştirme, test ve sürüm dağıtım süreçleri kontrol edilir.

![Doğada mevsimlerin döngüsü](https://www.circlesusa.org/wp-content/uploads/2019/12/TLP-seasons-1024x971.jpg)

Doğada mevsimlerin döngüsü, farklı aşamaların belirli bir **sırayla** gerçekleşmesini sağlar. Git Flow da benzer bir yaklaşımı temsil eder. Farklı aşamalardan (örneğin, "develop" ve "release" dalları) geçerken, proje sürümleri belirli bir disiplin ve düzen içinde yönetilir.

**Başarılı bir Git dallanma modeli**

GitFlow'un temel amacı, sürüm yönetimini ve kod tabanının **düzenini kolaylaştırmaktır.** Bu model, proje içinde birden fazla türde dal (branch) ile çalışmayı ve bu dalların **nasıl birleştirileceğini** ve yönetileceğini tanımlayan bir **dallanma modeli sağlar**.

[A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)

1. **Master**: **Stabil** ve her zaman çalışan üretim kodunun yer aldığı **ana dal**. Doğrudan kullanıcılar tarafından kullanılmaktadır.
2. **Develop**: Geliştirme süreci için ana dal. Tüm yeni özelliklerin ve **düzeltmelerin birleştirildiği** yerdir.
3. **Feature**: Yeni **özelliklerin** veya geliştirmelerin geliştirildiği **geçici** dallardır. Geliştiriciler yeni bir özellik eklemek istediğinde, bu özellik için bir özellik dalı oluşturur ve geliştirme tamamlandığında **develop** dalına birleştirir.
4. **Release**: Yeni bir **sürüm** hazırlığı için kullanılan dallardır. Geliştirme aşaması tamamlandığında, **develop dalındaki** kod **release dalına kopyalanır** ve testler yapılır. Testler başarılı olduğunda, bu dal **master ve develop dallarına birleştirilir** ve **sürüm etiketi** oluşturulur.
5. **Hotfix**: Üretimdeki bir hatayı düzeltmek için **acil** bir şekilde çözüm sağlamak amacıyla kullanılan dallardır. Bu dallar, hatayı düzeltmek için **master dalından türetilir** ve düzeltme yapıldıktan **sonra hem master hem de develop dallarına birleştirilir**.

---

*Not : "master" teriminin ırkçılık bağlamı, bu terimin tarihindeki kullanımından kaynaklanmaktadır. Terimin kökeni, esas olarak kölelik dönemine dayanmaktadır. Terim, İngilizce'de "usta" veya "efendi" anlamına gelirken, Amerika Birleşik Devletleri'nde ve diğer bazı bölgelerde "köle sahibi" veya "efendi" olarak da kullanılmıştır. [ Black Lives Matter - 2020 ]* 

![Black Lives Matter - 2020](https://th.bing.com/th/id/OIP.fO38d2-9DxmXLUk3oTQQcQHaE-?pid=ImgDet&rs=1)

---

**Git Sürüm Kontrol - Git Flow Yapılandırma**

GitFlow, temelde **Git kullanarak çalıştığından**, GitFlow'u kullanmak için **özel bir kurulum yapmanıza gerek yoktur**. Bunun yerine, GitFlow'un **işleyişini anlamak** ve Git komutlarını doğru şekilde kullanmak önemlidir.

[Installation](https://github.com/nvie/gitflow/wiki/Installation)

GitFlow'u daha kolay yönetmek için bazı **üçüncü taraf araçlar** da mevcuttur. Bu araçlar, GitFlow komutlarını otomatikleştirmeye ve süreçleri basitleştirmeye yardımcı olabilir. Bu araçlar arasında GitFlow-avh (GitFlow için gelişmiş versiyon) ve git-flow-completion (bash tab tamamlama desteği) gibi popüler seçenekler bulunmaktadır.

https://github.com/petervanderdoes/gitflow-avh

**GitFlow Kullanımı**
GitFlow orjinal belgesini incelemeniz önerilir.

https://github.com/nvie/gitflow

---
