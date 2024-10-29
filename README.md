# YFCC392K-Face-Attributes-Dataset
Weakly Labeled Face Attribute Dataset collected from YFCC100M dataset.

## :zap:	:zap:	Repo moved to [converging-machine](https://github.com/converging-machine/YFCC392K-Face-Attributes-Dataset) :zap:	:zap:	

**Abstract:** The scales of the data accessible through internet search engines can reach hundreds of millions, or even billions. The existence of such large weak-labeled databases has gained importance in the training of face recognition algorithms. Starting with the publicly available YFCC100M, we propose a weakly-labeled subset for multi-label face recognition for self-supervised methods.  A 392K image subset of YFCC100M of 128x128 images  was obtained by querying for the 40 facial attributes.  We made this dataset publicly available for other face recognition studies, by sharing the IDs, the links and the bounding boxes. To reduce outliers with respect to CelebA, we apply the Elliptic Envelope algorithm, in the the latent feature space learned over CelebA, obtaining 353K face images. MixMatch algorithm is applied to this last set, to obtain pseudo labels. Pretraining with these pseudo-labels and final fine-tuning with CelebA brings an improvement of 0.4% points in the Area Under the ROC Curve (AUC) score over the system trained only with CelebA.

**Özet:** İnternet arama motorları üzerinden erişilebilen verinin ölçeği yüz milyonları, hatta milyarları bulabilmektedir. Bu denli büyük zayıf-etiketli verinin varlığı, yarı-gözetimli yöntemlerin ve özellikle web-gözetimli yöntemlerin kullanımını öne çıkarmıştır. Bu çalışmada, yarı-gözetimli yöntemlerde kullanılmak üzere, çoklu-etiketli yüz tanıma problemi için zayıf-etiketli veri seti toplanmıştır. Bu amaçla, genele açık ve değişmeyen YFCC100M veri setinin içinden, yüz öznitelikleri ile etiketli CelebA setinin 40 yüz özelliğine göre arama yapılarak 128x128 pixel boyutlarında 392 bin imge elde edilmiştir. Başka yüz tanıma çalışmalarında kullanılabileceği göz önünde bulundurularak, bu imgelerin ID'leri, bağlantıları ve kullanılan yüz görüntülerinin sınırlayıcı kutusu  paylaşılmıştır. 
CelebA veri setine göre ayrıksı olan imgeler, CelebA üzerinde eğitilmiş bir ağın öğrendiği saklı gösterimler üzerine Eliptik Zarf yöntemi kullanılarak elendiğinde, 353 bin  adet yüz imgesine ulaşılmıştır. Bu süzülmüş veri setine MixMatch algoritması uygulanıp, elde edilen sözde-etiketlerle ön-eğitim yapıldığında, başlangıçtaki ağın ROC eğrisi değerinde ortalama %0.4 artış sağlanmıştır.

**Cite this:**
M. C. Yavuz, S. A. Ali Ahmed, M. E. Kısaağa, H. Ocak and B. Yanıkğlu, "YFCC-CelebA Face Attributes Datasets," 2021 29th Signal Processing and Communications Applications Conference (SIU), 2021, pp. 1-4, doi: 10.1109/SIU53274.2021.9477959.

https://ieeexplore.ieee.org/abstract/document/9477959

