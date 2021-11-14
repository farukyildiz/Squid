# Squid Proxy

Merhaba arkadaşlar bu ders serimizde Squid'i tanımlamakla başlayıp ihtiyaçlarımız doğrultusunda konfigüre edip kullanmayı öğreneceğiz.

#### Pekala Squid nedir?

Squid basit bir açıklama ile; kullanıcıların istekleri ve ihtiyaçları doğrultusunda web trafiğini filtreleme yaparak yönetmeyi sağlayan bir Proxy Server'dır diyebiliriz. İlk olarak 1996 yılında GPL (yani Genel Kamu Lisansı) ile kullanıma sunulmuştur. Tabi kullanıma sunulduğu yıldan itibaren gelişimini sürdürmüştür. Şuan da ise en son kararlı sürümü 5.2 olarak Ekim 2021'de yayınlanmıştır. Tabi ki gelişimi devam etmektedir. Örneğin 6. sürümü 2020 yılının başlarından itibaren gelişimini devam ettirmektedir. 

#### Peki Squid yukarı da bahsettiğimiz filtreleme yi nasıl yapar?

Öncellikle Squid çeşitli erişim kontrollerine sahiptir ve bu kontroller ile gelen istekler işlenir ve ne yapılacağına karar verilir. Bu kontrollerin detaylarına ileri ki bölümlerde değineceğiz. 

Şimdi devam edersek; Squid HTTP, HTTPS ve FTP gibi protokolleri desteklemektedir. Bu bahsettiklerimizin yanı sıra birde Squid'in farklı yönleri de vardır. Bunlardan ilk olarak öne çıkan özelliği web sayfalarını ön belleğe alarak çalışmasıdır. Yani sık kullanılan içerikler ön belleğe alınır ve ön belleğe aldığı içerikleri tekrar kullanıma sunarak bant genişliğini etkin kullanmayı sağlamaktadır. Bunun yanında bu isteklere verilen yanıt sürelerini de düşürmektedir. 

