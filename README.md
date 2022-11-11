# face-recognition-own-video
Bu repoyu inceledikten sonra kendi çektiğiniz bir videodaki insanları AI yardımı ile tanımlayabilecek hale geleceksiniz.
<br/>
Kodu düzenlerken ve datayı yaratırken dikkat edilmesi gerekenler:
* 1-Çektiğiniz video çok hızlı yada bulanık olmasın tahmin etmek istediğiniz yüzler açık bir şekilde belli olsun.
* 2-Çektiğiniz videodaki insanların kişi başına 1 fotoğrafa ihtiyacınız var bu fotoğrafında bulanık olmaması önemlidir ayrıca fotoğrafın ismininde kişinin ismi olması gekiyor ekranda yazılıcak olan yazı image adını referans almaktadır.
* 3-Datayı ailenizden sağlayabilirsiniz eğer tek iseniz dizi kesitlerinden data sağlanabilir tabi kesitteki insaların fotoğraflarınıda bulmanız gerekecektir. Bunun dışında yapmanız gereken bişey yok en basic hali ile bir computer vision projesi. İyi eğelenceler.
* (modeli ve ihtiyacınız olan weightleri indirme linkleri weightler = "https://www.kaggle.com/datasets/acharyarupak391/vggfaceweights" haarcascade modeli = "https://drive.google.com/uc?id=1_X-V1Lp6qMAl_-9opsseieprD3Lhdq8U" haar cascade'i indirdikten sonra zip'den çıkartıp direkt olarak proje doyanıza koyabilirsiniz weightleri ise indirdikten sonra .h5 uzantılı dosyayı ditek olarak proje dosyasının içinde koyabilirsiniz.)
