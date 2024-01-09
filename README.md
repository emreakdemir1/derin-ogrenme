#  Akciğer ve Kolon Hastalıklarının Görüntü Tabanlı Sınıflandırılması

:information_source: **Dersin Kodu:** [YAZ20411](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Adı:** [DERİN ÖĞRENME](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Öğretim Elemanı:** Öğr. Gör. Dr. Fatih BAL  [Github](https://github.com/balfatih)   |    [Web Sayfası](https://balfatih.github.io/)
   
---

## Grup Bilgileri

| Öğrenci No | Adı Soyadı           | Bölüm          		   | Proje Grup No | Grup Üyelerinin Github Profilleri                 |
|------------|----------------------|--------------------------|---------------|---------------------------------------------------|
| 1200505029 | Emre Akdemir			| Yazılım Mühendisliği     | PROJE_23      | [Github](https://github.com/emreakdemir1)     |
| 1200505040  | Fatih Taşkın  | Yazılım Mühendisliği     | PROJE_23      |     |
| 1170505904  | Furkan Tutkaç   | Yazılım Mühendisliği     | PROJE_23       |      |
| 1200505047  | Halil İbrahim Polat| Yazılım Mühendisliği   | PROJE_23       |      |                                          |
---

## Proje Açıklaması

 Amaç:
Bu proje, derin öğrenme yöntemlerini kullanarak akciğer ve kolon hastalıklarının görüntülerini sınıflandırmayı hedeflemektedir. Özellikle, akciğerdeki zatürre vakalarını viral veya bakteriyel kaynaklı olarak ayırmak üzerine odaklanmaktadır. Bu sınıflandırma, tıbbi görüntüleme alanında doğru teşhis ve tedavi için önemli bir adım olabilir.

Kapsam:
Proje, 15000 adet akciğer ve kolon hastalıklarına ait görüntüden oluşan bir veri seti üzerinde çalışmaktadır. Veri seti, zatürre hastalığının viral ve bakteriyel kaynaklı görüntülerini içermektedir. Derin öğrenme modelleriyle bu görüntülerin sınıflandırılması, doğruluk oranlarını artırmak ve doğru teşhisler yapabilmek için yapay zeka tekniklerini kullanmayı amaçlamaktadır.

Kullanılan Teknolojiler:
Proje, derin öğrenme için yaygın olarak kullanılan derin sinir ağları kütüphaneleri olan TensorFlow,Keras veya PyTorch gibi araçları içerebilir. Veri ön işleme adımları için OpenCV gibi görüntü işleme kütüphaneleri kullanılabilir. Model eğitimi için GPU hızlandırıcılardan faydalanılabilir. Model performansının değerlendirilmesi için doğruluk, hassasiyet, özgüllük ve F1 skoru gibi ölçümler kullanılabilir.

---

## Proje Dosya Yapısı

- **/derinöğrenmeproje**
  - **/modeller**
    - `cnn1`
    - `cnn2`
    - 'yapaysinirağları1'
    - 'yapaysinirağları2'
    - 'transferlearning1'
    - 'transferlearning2'
  - **/veriseti**
    - `lung_image_sets`
- **/public**
- `README.md`
- `LICENSE`  


---

## Kurulum

Projeyi Çalıştırma:
Projeyi çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

Gerekli kütüphanelerin yüklenmesi: Projede kullanılacak kütüphanelerin (TensorFlow, Keras, OpenCV vb.) yüklenmesi gereklidir.
Veri setinin indirilmesi ve hazırlanması: 15000 görüntülük veri seti indirilmeli, gerekiyorsa ön işleme adımları (boyutlandırma, normalleştirme vb.) yapılmalıdır.
Derin öğrenme modelinin seçilmesi ve eğitimi: CNN, transfer learning gibi modeller seçilebilir ve eğitim için görüntüler bu modele beslenmelidir.
Modelin değerlendirilmesi: Eğitilen modelin doğruluğunu, hassasiyetini ve diğer performans ölçütlerini değerlendirmek için test veri seti kullanılmalıdır.
Sonuçların görselleştirilmesi: Elde edilen sonuçlar ve sınıflandırma performansı grafikler veya metrikler aracılığıyla görselleştirilmelidir.


---

## Kullanım

Gereksinimlerin Yüklenmesi:

Python'un kurulu olması gereklidir.
Gerekli kütüphaneleri yüklemek için terminale veya komut istemcisine aşağıdaki komutları yazabilirsiniz:
pip install tensorflow opencv-python
Veri Setinin Hazırlanması:

Veri setini indirin veya erişilebilir bir kaynaktan temin edin.
Görüntü verilerini yükleyin ve gerekirse boyutlandırma, normalleştirme gibi ön işleme adımlarını yapın.
Derin Öğrenme Modelinin Eğitimi:

Derin öğrenme modelini seçin veya oluşturun (örneğin, Convolutional Neural Network - CNN).
TensorFlow veya PyTorch gibi kütüphaneleri kullanarak bir model oluşturun ve eğitin. Eğitim için veri setini modelinize besleyin.
Modelin Değerlendirilmesi:

Eğitilen modelin performansını değerlendirmek için ayrılmış bir test veri setini kullanın.
Doğruluk, hassasiyet, özgüllük, F1 skoru gibi metriklerle modelin performansını ölçün.
Sonuçların Kullanılması:

Eğitilmiş modeli gerçek veri veya yeni görüntülerle kullanarak sınıflandırma yapın.
Modelin tahminlerini görselleştirin veya sonuçları raporlayın.
Projeyi Çalıştırma:

Python ortamınızda projenin ana dosyalarını çalıştırın. Örneğin, model eğitimini içeren bir Python betiği olabilir.
Jupyter Notebook veya Python betiklerini (Python dosyaları .py uzantılı dosyalar) kullanarak adımları takip edebilirsiniz.

---

## Katkılar
https://machinelearningmastery.com/transfer-learning-for-deep-learning/
https://www.analyticsvidhya.com/blog/2021/08/beginners-guide-to-convolutional-neural-network-with-implementation-in-python/
https://github.com/balfatih
https://medium.com/@tuncerergin/keras-ile-derin-ogrenme-modeli-olusturma-4b4ffdc35323


---

## İletişim

e-posta adresim : emrecep46@gmail.com
instagram : emre.akdemir1
