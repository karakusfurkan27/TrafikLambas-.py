Here's a `README` file for the Traffic Light Python project using Tkinter:

Trafik Lambası Uygulaması

Bu Python uygulaması, Tkinter kütüphanesi kullanarak basit bir trafik lambası simülasyonu yapmaktadır. Uygulama, kırmızı, sarı ve yeşil ışıkların belirli sürelerle dönmesini sağlar. Trafik lambası uygulaması, kullanıcıya temel Tkinter öğeleri ve döngüsel olay işleme hakkında fikir verir.

Özellikler
- Kırmızı, Sarı ve Yeşil Işıklar: Trafik lambasında 3 ana ışık bulunur: kırmızı, sarı ve yeşil.
- Zamanlayıcı: Her ışık, belirli bir süre boyunca yanar. Kırmızı ve yeşil ışıklar 9 saniye, sarı ışık ise 2 saniye yanar.
- Döngüsel Işık Değişimi: Uygulama, trafik ışığını sürekli olarak değiştirir. Işıklar sırasıyla kırmızı, yeşil ve sarı olarak değişir.

Kullanım
1. Python ve Tkinter Kurulumu:
   - Python'un yüklü olduğundan emin olun. Tkinter, Python ile birlikte gelir, bu yüzden ek bir kurulum yapmanıza gerek yoktur.
   
2. Kodu Çalıştırma:
   - Kodunuzu bir Python dosyasına yapıştırın (örneğin `trafik_lambasi.py`).
   - Terminal veya komut istemcisine `python trafik_lambasi.py` komutunu yazın ve uygulamayı başlatın.

Kod Açıklamaları
- `TrafficLight` Sınıfı: Trafik lambasını temsil eder. Tkinter `Canvas` widget'ı üzerinde ışıkları oluşturur ve her ışığı sırasıyla değiştirir.
- `change_light` Fonksiyonu: Bu fonksiyon, her ışık için belirli süreleri ayarlayarak ışıkların sırasıyla değişmesini sağlar. `root.after` fonksiyonu, zamanlayıcıyı ayarlamak için kullanılır.

Özelleştirme
- Işık Süreleri: `change_light` fonksiyonunda yer alan `delay` değişkeni, her ışığın yanma süresini ayarlamak için değiştirilebilir.
- Renkler: Işıkların renkleri `fill` parametresi ile değiştirilebilir. Örneğin, sarı ışığı farklı bir renge değiştirebilirsiniz.

Görünüm
- Uygulama açıldığında, küçük bir pencere içinde trafik lambasının simülasyonu görüntülenir.
- Işıklar sırasıyla kırmızı, yeşil ve sarı olarak değişir.
  
Umarım bu açıklamalar, trafik lambası uygulamanız hakkında iyi bir bilgi sağlar!
