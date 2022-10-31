# ProductManagement

Çalışma 2 farklı mikroservisten oluşmaktadır.
Swagger entegre edilmiştir. 

![image](https://user-images.githubusercontent.com/107306557/199033520-96530ff7-b8cf-4864-a8d9-0236813033bb.png)
1. PRODUCT MICROSERVICE.
Prdoduct mikroserviste 2 farklı endpoint bulunmaktadır.
SAVE: ürünü kaydeder ve diğer mikroservisle iletişim kurup oraya stok bilgisi açar.
Veri girişi sırasında productCode unique olmalıdır.
GETALLPRODUCT:Tüm kayıtlı ürünleri getiren method

2. STOCK MICROSERVICE.
Prdoduct mikroserviste 3 farklı endpoint bulunmaktadır.
UPDATESTOCK:Urun id si kullanarak stogu degistiren method
GETALL:Stoktaki tüm ürünlerin adını ve stok miktarını getiren method
INDBYPRODUCTNAME:Girilen Stringi ürün adlarında arayıp , bu stringi içeren ürünleri getiren method


