Angular ile online alışveriş sitesi deneme çalışmam.
İki çeşit ürün ekleme butonu var. Biri klasik form üzerinden diğeri ise Reactive form kullanarak ürün ekliyor.
Klasik form üzerinden ürün ekleme kısmına girebilmek için sisteme giriş yapmanız gerekiyor. Local stroge dan aldığım kullanıcı adı : selahattin , şifre:12345 değerleri ile giriş yapılabiliyor. Giriş yapıldığında sağ üst kısımda log in butonu log out olarak değişmektedir. 
Alertify servisi kullanarak sepete ekle dediğimiz ürünün ismi ile sepete eklendi alerti çıkmaktadır.
İki adet kategori bulunmaktadır. Kategori butonlarına basarak o kategoriye ait ürünleri listeleyebilirsiniz.
Arama kutusu ile aranan ürünün bulabilirsiniz.
Ürün ekleme kısımlarında kutucuklara bilgileri yazıp sildiğinizde bir uyarı ile doldurulmasının zorunlu olduğunu belirtliyor. Ürün ekle butonu tüm bilgiler doldurulduğunda aktif oluyor.

İlk başta ürünleri görmek için  json server yüklemeniz gerekiyor. (npm install -g json-server)
İkinci adımda json-server --watch shop.json (aynı konumda olmalısınız) komutu ile görüntüleniyor.

