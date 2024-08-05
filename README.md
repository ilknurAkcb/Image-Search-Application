
# Görüntü İşleme ve Eşleştirme

Bu proje, OpenCV ve Python kullanarak görüntü işleme ve eşleştirme yöntemlerini uygulamak için bir örnektir. Kullanıcı, veritabanında bulunan görüntülerin SIFT (Scale-Invariant Feature Transform) özelliklerini çıkarabilir ve ardından yeni bir görüntüyü bu veritabanındaki görüntülerle karşılaştırabilir.

## 📋 Gereksinimler

Bu projeyi çalıştırmak için şu yazılım ve kütüphanelere ihtiyacınız vardır:

- Python 3.x
- OpenCV
- NumPy
- scikit-learn
- PIL (Python Imaging Library)


##💡 Açıklamalar
train.py: Veritabanındaki görüntülerin SIFT özelliklerini çıkarır ve K-means ile gruplar.
test.py: Yeni bir görüntüyü veritabanındaki görüntülerle karşılaştırır ve en benzer olanları listeler.

### Örnek Kullanım:


python train.py
python test.py test/yeni_goruntu.jpg




## ▶️ Nasıl Kullanılır

1. `database` klasörüne, veritabanında karşılaştırmak istediğiniz görüntüleri ekleyin.
2. `train.py` dosyasını çalıştırarak, veritabanındaki görüntülerin SIFT özelliklerini çıkarın ve K-means kümeleme algoritması kullanarak görüntüleri gruplayın.
3. `test.py` dosyasını çalıştırarak, yeni bir görüntüyü karşılaştırın ve en benzer görüntüleri bulun.


with open("README.md", "a") as readme_file:  # "a" mode to append
    readme_file.write(readme_content)

Yukarıdaki kütüphaneleri yüklemek için terminal veya komut istemcisinde şu komutu kullanabilirsiniz:

```bash
def install_packages():
    packages = ['opencv-python', 'numpy', 'scikit-learn']
    for package in packages:
        subprocess.check_call([sys.executable, "-m", "pip", "install", package])

# Paketleri yükle
install_packages()



