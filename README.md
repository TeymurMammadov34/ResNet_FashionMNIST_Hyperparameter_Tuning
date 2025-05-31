# Fashion MNIST - ResNet Model with Hyperparameter Tuning 🧠👕

Bu proje, Fashion MNIST veri kümesi üzerinde basit bir ResNet mimarisi ile derin öğrenme sınıflandırma modelini eğitmekte ve Keras Tuner ile hiperparametre optimizasyonu yapmaktadır.

## 🔧 Kullanılan Teknolojiler
- TensorFlow & Keras
- Keras Tuner (RandomSearch)
- Fashion MNIST Dataset
- Residual Blocks (ResNet mimarisi)

## 📌 Adımlar
1. Fashion MNIST verisi yüklendi ve normalize edildi.
2. Kendi Residual Block fonksiyonumuz tanımlandı.
3. `HyperModel` sınıfı ile model oluşturuldu.
4. Hiperparametreler `RandomSearch` ile optimize edildi.
5. En iyi model test verisi ile değerlendirildi.

## 🚀 Çalıştırmak için
```bash
pip install tensorflow keras keras-tuner
```
# 📊 Sonuç
En iyi model test verisi üzerinde `accuracy` ve `loss` metrikleri ile değerlendirildi.
