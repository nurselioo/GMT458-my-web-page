# GMT 458 - Web GIS Assignment 1: Personal Web Page

## Proje Hakkında
Bu proje, Geomatik Mühendisliği GMT 458 Web GIS dersi kapsamında hazırlanmış kişisel web sayfasıdır. HTML, CSS, Leaflet ve OpenLayers teknolojilerini içermektedir.

### İçerik
- **index.html:** Biyografi ve genel tanıtım (CSS animasyonu içerir).
- **books.html:** Okunan kitaplar tablosu ve kapak resimleri.
- **maps.html:** Gezmek istenen yerlerin yer aldığı Leaflet ve OpenLayers harita uygulamaları.

### Karşılaşılan Sorunlar ve Çözümleri
1. **Issue 1 (Marker Zoom Threshold):** Çok sayıda marker'ın uzak zoom seviyelerinde üst üste binmesini önlemek için Leaflet üzerinde `zoomend` dinleyicisi ile `getZoom() >= 6` kontrolü yapılmış ve zoom eşiği uygulanmıştır. OpenLayers tarafında ise katmana `minZoom` parametresi tanımlanmıştır.
2. **Issue 2 (Earth Repeating Itself):** Uzaklaşınca haritanın yatayda kendini tekrarlamasını engellemek için:
   - Leaflet `tileLayer` seçeneğine `noWrap: true` ve harita sınırlarına `maxBounds` eklenmiştir.
   - OpenLayers `ol.source.OSM` yapılandırmasına `wrapX: false` eklenmiştir.

### AI (Yapay Zeka) Kullanım Bildirimi
- **Öğrenilen / Destek Alınan Konular:** Leaflet ve OpenLayers'ta harita tekrarını engelleyen `noWrap` ve `wrapX` parametrelerinin doğru tanımlanma hiyerarşisi ile Leaflet katman kontrolünde zoom eşiği mantığı.
- **Tahmini AI Kullanım Süresi:** Yaklaşık 25 - 30 dakika.