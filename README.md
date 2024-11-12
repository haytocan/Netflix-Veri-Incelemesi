# Netflix Veri Incelemesi

![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/6/69/Netflix_logo.svg)

Bu proje, Netflix verilerinin detayli bir sekilde analizini icerir. Farkli ulkelerdeki Netflix icerik kutuphanelerinin genislikleri ve paket fiyatlari incelenmis, analiz edilen veriler cesitli gorsellestirmelerle desteklenmistir.

## Proje Ozeti

- 65 farkli ulkenin Netflix verileri incelenmistir.
- Analiz edilen veri setinde **hicbir eksik deger (null) bulunmamaktadir**.
- Veriler, ulkelerin toplam kutuphane genisligi, TV sovu ve film sayisi ile temel, standart ve premium paketlerin aylik maliyetlerini icermektedir.

## Verinin Genel Yapisi

**Veri Setinin Sutunlari (Toplam 7 sutun):**
| Sutun Adi                      | Veri Sayisi (Non-Null) | Veri Tipi |
|---------------------------------|------------------------|-----------|
| Ulke                            | 65                     | object    |
| Toplam Kutuphane Genisligi      | 65                     | int64     |
| TV Gosteri Sayisi               | 65                     | int64     |
| Film Sayisi                     | 65                     | int64     |
| Aylik Maliyet - Temel ($)       | 65                     | float64   |
| Aylik Maliyet - Standart ($)    | 65                     | float64   |
| Aylik Maliyet - Premium ($)     | 65                     | float64   |

**Veri tipi dagilimi:** `float64(3)`, `int64(3)`, `object(1)`  
**Bellek kullanimi:** 3.7+ KB

## One Cikan Bulgular

- **Kayip Degerler:** Analiz edilen veri setinde kayip deger tespit edilmemistir.
- **Kutuphane Genisligi:** En genis kutuphane sahip ulke **Cekya**'dir.
- **TV Gosteri Sayisi:** En fazla TV gosterisne sahip ulke **Cekya**'dir.
- **Film Sayisi:** En fazla film icerigine sahip ulke **Malezya**'dir.

## Projenin Amaci ve Yontemi

Bu projede, ulkeler arasi Netflix fiyatlandirmalarinin ve icerik cesitliliginin karsilastirilmasi hedeflenmistir. Kesifsel veri analizi (EDA) yontemleri kullanilarak veri incelenmis ve sonuclar gorsellestirilmistir. Calismanin amaci, Netflix'in ulkeler arasi icerik ve fiyat politikasina dair icgoruler sunmaktir.

Kaggle Linki : https://www.kaggle.com/code/hayatcanaydin/farkli-ulkelerdeki-netflix-fiyatlari-analizi