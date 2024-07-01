# YOLOv8 ALGORİTMASIYLA PAP SMEAR GÖRÜNTÜLERİNDE SINIFLANDIRMA İŞLEMİ
Bu çalışmada, kadınlarda sıklıkla görülen rahim ağzı kanserinin erken teşhisi 
amacıyla pap smear testi sonuçlarındaki görüntülerin yolov8 algoritması kullanılarak 
sınıflandırılmasına odaklanılmaktadır. Sipakmed veri seti üzerinde gerçekleştirilen 
bu çalışma, yapay zeka tabanlı görüntü işleme yöntemlerinin klinik uygulamalardaki 
potansiyelini ortaya koymaktadır. Sipakmed veri setinde toplam 4049 izole hücre 
görüntüsü bulunur. Hücre görüntüleri normal, anormal ve iyi huylu hücreleri içeren 
beş kategoriye ayrılır. Bu sınıfların isimleri sırasıyla dyskeratotic, koilocytotic, 
metaplastic, parabasal ve superficial-intermediate’ dir. Yapay zekanın eğitimi daha 
iyi olması açısından ve verisetinde klasördeki verilerin homojen olarak dağılması 
amacıyla bu görüntülere veri arttırımı tekniği uygulanarak görüntüler çoğaltılmıştır. 
Veri arttırımı işleminden sonra yapay zeka, yolov8l-cls modeliyle eğitilmiştir. Eğitim 
sonucunda oluşan yapay zekayı içeren best.pt dosyası test görüntülerinde 
kullanılarak modelin performansı ölçülmüştür. Eğitilen yapay zeka modeli genel 
olarak her bir sınıfa ait test görüntülerinde ortalama %95 - %98 aralığında bir 
doğruluk oranına ulaşmıştır. Bu çalışmanın klinikte karar destek sistemi olarak 
kullanılabilmesi için, elde edilen YOLOv8 tabanlı yapay zeka modelinin entegre 
edildiği bir GUI ( kullanıcı arayüzü ) tasarlanmıştır.
![val_batch0_labels](https://github.com/kbbora/papsmear_classification_YOLOV8/assets/170621354/5cff8f8d-1acb-4f63-aacd-92c6ed28d9e7)
