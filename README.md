## **Icon Kütüphanesi Nasıl Düzenlenir?**
Bunun için 3 yol var. 
1. Icomoon üzerindeki hesaptan giriş yapıp, yeni bir icon seçip, yeni fontu indirebilirsiniz. 
2. Github üzerinden projeyi indirip, icomoon'a tekrar import edebilirsiniz. Burada Github projesindeki projesinin de güncel olması önemlidir. [Bunu unutmayalım](#uyari-1)


3. Icomoon sitesi bir gün aramızdan ayrılırsa, font dosyası düzenlemeyi sağlayan yardımcı bir uygulama ile font dosyasını güncellemek mümkün fakat bu oldukça zahmetli olacaktır. 

## **Icon Kütüphanesi  Website UI Projesine Nasıl Entegre Edilir?**
Icomoon'un bize sağlamış olduğu demo klasöründeki *fonts\dugun-icons.woff* font dosyasını Website UI projemizdeki *assets\fonts* yoluna, style.css dosyası içindeki css kodlarını ise *assets\scss\icons\_dugun-icons.scss* içeriğiyle değiştirin. [Değişim  yaparken şunu unutmayın](#uyari-3)

## **Icon Sitesi**

http://icons.dugun.work/

# UYARILAR

## UYARI 1:
Bu yüzden icon kütüphanesi güncellenmesi sonrası **icons** projesini de güncellemeyin unutmayın.
Yaptığınız yeni ikon seçimi veya yeni ikon eklemekten bağımsız olarak ikon seçimleri yapıldıktan sonra `Dugun.com.json` ve `selection.json` güncellemeyi unutmayınız.
    
## UYARI 2:
 Projedeki isimlendirme kurallarına riayet edelim. Light, regular, bold, custom, brands isminde 4 farklı icon grubumuz var. Yeni eklenecek icon isimlerini buna uygun düzenleyelim. Yeni bir icon grubu ekleyecek iseniz de aynı kurallara uyalım.
 
## UYARI 3
 *assets\scss\icons\_dugun-icons.scss* bu dosya salt icomoon'un bize verdiği css dosyamız değil. Ufak tefek değişiklikler var. Bu yüzden yeni css dosyası ile değiştirirken dikkatli olun. Sadece icon classlarını değiştirin. Lint etmeyi unutmayın.
