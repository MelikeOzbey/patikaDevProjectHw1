# patikaDevProjectHw1
async ve await kullanımı

www.patika.dev

getData fonksiyonu **"async"** olarak tanımlı ve default olarak dışa aktarılmıştır. 
Fonksiyonun içindeki asenkron fonksiyonlar **"await"** ile tanımlanmıştır.
-  Fonksiyon **Number** tipinde tek parametre alır. Bu parametre **user id**'yi belirtir.
-  Fonksiyonun görevi aşağıdaki endpoint'e giderek parametrede verilen user id ile ilgili kullanıcının verilerini çekmek olmalı. 
İstekleri **"axios"** kütüphanesini kullanarak yapılmıştır. İsteği yaparken aşağıdaki endpointin sonundaki rakamı parametrede gelen user id'ile değiştirilmektedir.

[https://jsonplaceholder.typicode.com/users/1]

 Yine aynı fonksiyonun içerisinde ve yine aynı user id için bir de "posts" isteği yapılmıştır.İsteği yaparken aşağıdaki endpoint'in sonundaki rakamı
 parametrede gelen user id'ile değiştirmeniz gerekiyor.

	[https://jsonplaceholder.typicode.com/posts?userId=1]
  
  index.js de getData fonksiyonu çağırılarak bu iki veri de console yazdırılmaktadır.
