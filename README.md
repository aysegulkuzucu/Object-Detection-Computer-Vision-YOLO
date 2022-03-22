# Object-Detection-Computer-Vision-YOLO

Bu projede anlık olarak bir "object detection" işlemi nasıl gerçekleştirebiliriz, bunun uygulamasını göstermeye çalıştım.

Biz görüntülerden anlamlı bilgiler çıkarmak için bilgisayarla görü yöntemlerini kullanırız. Eğer videolar üzerinde tespit ve analiz sonrasında takip edilecek olan bir nesne varsa anlamlı bilgiler çıkarmak daha zordur. Bu gibi durumlarda derin öğrenme algoritmalarını kullanarak görüntü işleme problemlerini de kolayca çözebiliriz.

Nesne tespiti de, dijital görüntülerde ve videolarda belirli bir sınıftaki anlamsal nesnelerin örneklerini algılamakla ilgilenen, bilgisayarla görme ve görüntü işleme ile ilgili bir bilgisayar teknolojisidir. Biz çeşitli yöntemler ya da algoritmalar kullanarak bir görüntüdeki nesneleri sınırlayıcı kutu dediğimiz bir kutu ile çerçeve içine alarak nesne algılama işlemini gerçekleştiririz.

Özellikle son yıllarda nesne tespiti konusunda popüler olan algoritmalardan biri olan ve YOLO olarak kısalttığımız You Only  Look Once, tek bir sinir ağı ile problemi uçtan uça optimize ederek doğrudan algılama performansına göre nesne tespiti yapar. Nesne tespitinde hız çok önemlidir ve YOLO’yu diğer algoritmalardan ayıran en önemli özelliği de gerçek zamanlı nesne tespiti yapabilmesidir.  YOLO modelinin çeşitli versiyonları bulunmaktadır. 

Yaptığım çalışmada çalışmada scale yolov4 modelini kullandım. Bu işlem için de Google colabrator aracını kullandım. Çünkü Google colabraty bize ücretsiz gpu sağlayan bir araç. 

Bu şekilde anlık olarak web kameramız üzerinden object detection işlemi gerçekleştirdim. Bunu hazır eğitilmiş bir modelin ağırlıkları üzerinden gerçekleştirdim. Aslında biz bunu kendi ettiğimiz bir modelin ağırlıklarını kullanarak da tabii ki yapabilirdik. 


![image](https://user-images.githubusercontent.com/61588968/159534936-0f1769fe-9ba7-46bb-92b8-b85d232c1499.png)
