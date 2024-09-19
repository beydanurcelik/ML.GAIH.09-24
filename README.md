# ML.GAIH.09-24
#Global AI Hub Machine Learning Final Projesi

#a.	https://www.kaggle.com/code/beydanurcelik/ml-gaih-09-24

#Veri seti, Amerika Birleşik Devletleri'nde meydana gelen trafik kazalarını içeren bir koleksiyondur. İçinde kaza tarihleri, lokasyon bilgileri (enlem, boylam), hava durumu, yol koşulları, kaza şiddeti ve araç sayısı gibi çeşitli değişkenler bulunmaktadır. Toplamda 2.5 milyondan fazla kayıt içeren bu veri seti, kazaların nedenlerini, dağılımını ve etkilerini analiz etmek için oldukça zengindir. Bu sayede, trafik güvenliği ile ilgili önemli içgörüler elde edilebilir.

#Bu projeye başlarken önce gerekli kütüphaneleri yükledim; numpy, pandas, matplotlib ve seaborn ile başladım. Sonra, veri setimi dosyadan yükleyip ilk 5 satırını inceledim, böylece verinin yapısını kavradım. Eksik değerler olup olmadığını kontrol ettim ve hangi sütunların sorunlu olduğunu belirledim. Eksik veri oranı yüksek olan sütunları temizleyerek verilerimi düzenli hale getirdim. Ardından, kazaların şiddetini ve coğrafi dağılımını görselleştirmek için grafikler oluşturdum; bu, verilerimin daha anlamlı olmasını sağladı. Modelim için hangi bilgilerin giriş ve hangilerinin çıkış olacağını belirledikten sonra, özellikleri standartlaştırarak verilerimi aynı ölçekte olacak hale getirdim. Son olarak, verilerimi bir makine öğrenmesi modeli ile eğitip test ettim ve sonuçları değerlendirdim.

#Proje Çıktıları
Bu projede, "US Accidents" veri setini kullanarak hem gözetimli hem de gözetimsiz öğrenme algoritmalarını uyguladım. Amacım, kaza verilerini analiz etmek ve bu verilerden anlamlı içgörüler elde etmek oldu.

#Gözetimli Öğrenme: Bu tür algoritmalardan biri olan [örneğin "Random Forest"], yüksek doğruluk oranlarıyla sonuçlandı. Kaza sayısını tahmin etmede ve belirli koşullar altında kaza riskini değerlendirmede etkili oldu.
#Gözetimsiz Öğrenme: [örneğin "K-means"] algoritması ise verileri gruplandırmada iyi sonuçlar verse de bazı durumlarda karmaşık verilerle karşılaştım ve hat aldığım oldu. Özellikle, belirli kazaların sebeplerini net bir şekilde sınıflandırmadım.

#Seçtiğim veri seti, gözetimli öğrenme algoritmaları için daha uygun görünmekte. Bunun nedeni, veri setinin etiketlenmiş veriler içermesi ve belirli kaza özelliklerinin (örneğin, hava durumu, yol koşulları) sonuçları etkilemesi. Bu özellikler, makine öğrenimi modellerinin eğitilmesine ve doğru tahminler yapabilmesini sağlar.
#Ek olark, gözetimsiz öğrenme algoritmaları, etiketlenmemiş veri setlerinde daha etkili olmasına rağmen, veri setindeki karmaşık ilişkileri açığa çıkarmakta zorlandı ve sıkça hata verdi. Bu nedenle, veri seti gözetimli öğrenme uygulamaları için daha olanallı.

#Sonuç olarak, bu projede hem gözetimli hem de gözetimsiz öğrenme algoritmalarını kullanarak trafik kazaları üzerinde derinlemesine bir analiz gerçekleştirdim. Gelecekte, daha fazla veri ve farklı algoritmalarla çalışarak, trafik güvenliğine katkı sağlayacak daha sağlam modeller geliştirebilir.
