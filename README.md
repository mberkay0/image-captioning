# Turkish Image Captioning (Türkçe Görüntü Altyazılama)

EEE409 Introduction to Machine Learning Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://githubtocolab.com/mberkay0/image-captioning/blob/main/image_captioning.ipynb)

<div align="center">
  <img src="https://dcmp.org/images/learning_center/5-1.jpg" width="55%"/>
</div>


Görüntüler üzerinde altyazı oluşturma, görüntüde bulunan
nesnelerin ve bunların çevreyle olan ilişkilerinin doğal bir
dil ile anlamlı açıklamalarının otomatik olarak üretilmesini
amaçlar. Son zamanlarda artan ilgiyle birlikte önemli bir
alan olmuştur. Bilgisayarlı görü ve doğal dil işleme
alanlarını birleştirmektedir. Makine çevirisi alanındaki
gelişmelerden sonra bu alanda başarılı sonuçlar veren
kodlayıcı-kod çözücü tekniği, özellikle İngilizce için
otomatik görüntü altyazısı oluşturma konusunda kullanılan
yöntemlerden biridir. Bu çalışmada ise, Türkçe dili için
otomatik görüntü altyazısı oluşturan iki farklı kod çözücü
model sunulmaktadır. Bu çalışma, verilen görüntülerin
özniteliklerini çıkaran, evrişimsel sinir ağına sahip bir
kodlayıcıyı, altyazı oluşturan, tekrarlayan sinir ağı ve
transformer mimarisine sahip iki farklı kod çözücü ile
birleştirerek, Türkçe MS-COCO veri kümesi üzerinde iki
farklı kodlayıcı-kod çözücü modelini test etmektedir.
Modellerin performansları oldukça sınırlı ve gürültülü bir
veride görece iyi sonuçlar vermektedir.


# Sonuçlar

Modellerden çıkan çeşitli altyazı örnekleri aşağıda verilmiştir.

<div align="center">
  <img src="/images/result1.png"/><br>Fig.1: CNN + RNN için sonuçlar</br>
</div>

<div align="center">
  <img src="/images/result2.png"/><br>Fig.2: CNN + Transformer için sonuçlar</br> 
</div>

Aşağıda sayısal sonuçlar verilmiştir. Tüm metrikler için Transformer [1] kullanan model RNN [2] kullanan modeli geçmiştir. 

<div align="center">
  <img src="/images/result3.png"/><br>Fig.3: Yöntemlerin otomatik değerlendirme sonuçlarına göre standart sapma ve ortalama değerleri.</br> 
</div>



# References

[1] [Karpathy, A., & Fei-Fei, L. (2015). Deep visual-semantic alignments for generating image descriptions. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 3128-3137).](https://arxiv.org/pdf/1412.2306.pdf)

[2] [Messina, N., Falchi, F., Esuli, A., & Amato, G. (2021, January). Transformer reasoning network for image-text matching and retrieval. In 2020 25th International Conference on Pattern Recognition (ICPR) (pp. 5222-5229). IEEE.](https://arxiv.org/pdf/2004.09144.pdf)


