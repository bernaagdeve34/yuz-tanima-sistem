
# Yüz Tanıma Projesi

## Proje Amacı
Bu proje, yüz tanıma teknolojisini kullanarak görsellerdeki yüzleri tespit etmek ve sınıflandırmak için geliştirilmiştir. Amaç, gerçek zamanlı ve yüksek doğruluk oranına sahip bir yüz tanıma sistemi oluşturmaktır. Bu süreçte derin öğrenme teknikleri ve görüntü işleme yöntemleri kullanılmıştır.

## Kullanılan Veri Setleri ve Araçlar
- Veri Setleri: Çeşitli yüz ifadeleri ve pozlar içeren açık kaynaklı yüz tanıma veri setleri kullanıldı.
- OpenCV: Görüntü işleme ve yüz algılama işlemleri için kullanıldı.
- TensorFlow/Keras: Derin öğrenme modeli oluşturma ve eğitimi için kullanıldı.
- NumPy, Pandas: Veri ön işleme ve analiz aşamalarında kullanıldı.
- Matplotlib, Seaborn: Eğitim süreci görselleştirmeleri için kullanıldı.

## Temel Bulgular
- Model Başarımı: Eğitim süreci sonucunda model, test veri setinde %95 doğruluk oranına ulaştı.
- Gerçek Zamanlı Tanıma: Web kamerası üzerinden canlı yüz tanıma özelliği başarıyla entegre edildi.
- Performans Testleri: Farklı ışık koşulları ve açılarda test edilerek modelin kararlılığı doğrulandı.

## Nasıl Çalıştırılır
1. Gerekli Kütüphaneleri Yükleyin:  
   ```bash
   pip install -r requirements.txt
   ```
2. Projeyi Başlatın:  
   ```bash
   python main.py
   ```
3. Canlı Tanıma: Web kamerası ile gerçek zamanlı yüz tanımayı deneyebilirsiniz.

## Katkıda Bulunanlar
- Berna Ağdeve - Proje Sahibi ve Baş Geliştirici

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.
