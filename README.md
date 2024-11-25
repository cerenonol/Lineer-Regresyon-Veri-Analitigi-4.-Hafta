# Ülkeler Arasında Mesai Saatleri ve Refah Düzeyi İlişkisi - Lineer Regresyon Analizi

Bu proje, ülkeler arasındaki **haftalık mesai saatleri** ile **refah düzeyi** arasındaki ilişkiyi incelemeyi amaçlamaktadır. Veriler kullanılarak, bu iki faktörün **kişi başına gelir** üzerindeki etkisi **lineer regresyon modeli** ile modellenmiştir. 

Proje, Python programlama dili ve popüler makine öğrenmesi kütüphaneleri olan **scikit-learn**, **pandas**, ve **seaborn** kullanılarak geliştirilmiştir. Aynı zamanda, verinin görselleştirilmesi ve modelin performansının değerlendirilmesi de gerçekleştirilmiştir.

## Proje Amacı

Projenin temel amacı, aşağıdaki iki faktörün kişi başına gelir üzerindeki etkisini anlamak ve tahminler yapmaktır:

- **Haftalık Ortalama Çalışma Saatleri**: Çalışanların haftada kaç saat çalıştığını belirten veriler.
- **Ülke Refah Düzeyi**: Her bir ülkenin refah düzeyini belirleyen veriler, genellikle ekonomik göstergelerle ölçülür.

Bu iki faktör kullanılarak **kişi başına gelir** tahmin edilmiştir. **Lineer regresyon modeli** sayesinde, bu faktörlerin gelir üzerindeki etkisi hesaplanmış ve modelin doğruluğu çeşitli metriklerle (MSE ve R²) değerlendirilmiştir.

## Kullanılan Teknolojiler

Projede kullanılan başlıca teknolojiler şunlardır:

- **Python**: Veri analizi ve makine öğrenmesi için ana programlama dili.
- **Pandas**: Veri manipülasyonu ve analizi.
- **NumPy**: Sayısal hesaplamalar ve verinin işlenmesi.
- **Matplotlib & Seaborn**: Veri görselleştirme.
- **scikit-learn**: Makine öğrenmesi algoritmalarını uygulamak için kullanıldı.
- **Jupyter Notebook / Google Colab**: Proje geliştirme ortamı.

## Proje Adımları

Proje aşağıdaki adımlardan oluşmaktadır:

1. **Veri Toplama ve İnceleme**: Haftalık mesai saatleri, refah düzeyi ve kişi başına gelir verileri toplandı ve incelendi.
2. **Veri Ön İşleme**: Verinin temizlenmesi, eksik değerlerin işlenmesi ve uygun formata dönüştürülmesi.
3. **Model Eğitimi**: Lineer regresyon modeli kurularak, haftalık mesai saatleri ve refah düzeyi verileri kullanılarak kişi başına gelir tahmin edilmiştir.
4. **Model Değerlendirme**: Modelin doğruluğu, **Ortalama Kare Hatası (MSE)** ve **R-Kare (R²) Değeri** gibi metriklerle değerlendirilmiştir.
5. **Görselleştirme**: Çeşitli grafiklerle, çalışma saatleri ve refah düzeyinin kişi başına gelir ile ilişkisi görselleştirilmiştir.

## Kurulum ve Çalıştırma

Projeyi yerel bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

### Gerekli Kütüphaneler

Projeyi çalıştırabilmek için aşağıdaki Python kütüphanelerine ihtiyacınız olacaktır. Bu kütüphaneleri yüklemek için terminal veya komut satırına şu komutu yazabilirsiniz:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
