BURSA RIDE 3D - GUNCELLENMIS KAYNAK PROJESI

Icerik:
- index.html: Three.js tabanli oyun
- yehomaOBJ.obj / yehomaOBJ.mtl: motosiklet modeli
- .github/workflows/build.yml: Android APK derleme workflow'u

Bu guncellemede:
- Suruse Basla icin HTML onclick yedegi ve click event'i eklendi.
- 3D trafik araclari ve trafik hareketi eklendi.
- Menu: kamera modu, motor rengi secimi, grafik seviyesi, gorev/odul, kaydetme.
- Onceki hava modlari, yagmur/kar parcaciklari, gece-gunduz, 3D binalar ve dokunmatik kontroller korundu.
- Ucuncu sahis kamera secenegi eklendi.

Onemli sinirlamalar:
Bu halen gelistirme prototipidir. Bursa'nin birebir gercek yol verisi, gercek GPS navigasyonu,
tam motor galerisi/satin alma ekonomisi, tam surucu/kask 3D karakteri, gelismis fizik/kaza
simulasyonu, ayna yansimalari ve detayli ses sistemi bu pakette tamamlanmis degildir.
Menu ogeleri prototip seviyesindedir; gorev odulu bir kez verilir. Gercek Bursa haritasi icin
lisans/harita verisi ve yol agi entegrasyonu gerekir.

APK derleme:
.github/workflows/build.yml dosyasi GitHub Actions kullanir. Projeyi GitHub'a yukleyip
Actions > Bursa Ride 3D APK > Run workflow ile derleyebilirsiniz. Cikan artifact:
Bursa-Ride-3D-APK.

Kontroller:
- Sol/sag: yon; Gaz: hizlanma; Fren: yavaslama.
- Vites + / -: manuel vites.
- Hava: gunduz, aksam, neon gece, yagmur, kar.
- Menu: kamera, renk, grafik, gorev, kayit.
