# JavaScript Soruları ve Cevapları

## JavaScript Nedir ve Tarihsel Gelişimi

JavaScript, web tarayıcılarında çalışan, hafif, yüksek seviyeli bir programlama dilidir. Tarihsel gelişimi şu şekildedir:

- **1995:** Netscape Communications Corporation tarafından LiveScript olarak piyasaya sürüldü.
- **1996:** Sun Microsystems ile işbirliği sonucu JavaScript adını aldı.
- **1997:** ECMAScript standardı yayımlandı, JavaScript bu standart üzerine kuruldu.

## Java ile JavaScript Arasındaki Fark

Java ve JavaScript birbirine benzer isimlere sahip olmalarına rağmen, farklı dillerdir. Ana farklar şunlardır:

- **Java:** Nesne tabanlı, güçlü tip kontrolü.
- **JavaScript:** Prototip tabanlı, zayıf tip kontrolü.

## JavaScript Veri Tipleri

JavaScript'te kullanılan temel veri tipleri şunlardır:

- **String:** Metin.
- **Number:** Sayı.
- **Boolean:** Mantıksal değer (true veya false).
- **Object:** Nesne.
- **Array:** Dizi.
- **Null:** Değer yok veya bilinmiyor.
- **Undefined:** Tanımsız.

## Null ile Undefined Arasındaki Fark

- **Null:** Bilinçli olarak bir değerin olmadığını ifade eder.
- **Undefined:** Değer atanmamış veya henüz tanımlanmamış bir değişkeni temsil eder.

## NaN Nedir

**NaN (Not a Number):** Sayı olmayan bir değeri temsil eder. Örneğin, matematiksel bir operasyon sonucu sayı olmayan bir değer üretildiğinde NaN kullanılır.

## Yorum Satırı Ekleme Yolları

JavaScript'te yorum eklemenin iki temel yolu vardır:

1. Tek satır yorum için `//`.
2. Çoklu satır yorum için `/* */`.

## Global Değişken

Global değişken, kodun herhangi bir yerinden erişilebilen bir değişkendir. Global değişkenler `window` objesinin bir özelliği olarak tanımlanır.

## "this" Anahtar Kelimesi

`this`, bir fonksiyonun çalıştığı bağlamı temsil eder. Bağlam, fonksiyonun nasıl çağrıldığına bağlıdır.

## "==" ile "===" Farkı

- `==`: Sadece değer karşılaştırır, tipleri dönüştürür.
- `===`: Hem değer hem de tip karşılaştırır.

Örnek:

'5' == 5   // true
'5' === 5  // false
## let, var, const Farkı

| Anahtar Kelime | Kapsam       | Yeniden Atanabilir | Block Scope |
| -------------- | ------------ | ------------------ | ----------- |
| let            | Block Scope   | Evet               | Evet        |
| var            | Function Scope| Evet               | Hayır       |
| const          | Block Scope   | Hayır              | Evet        |

## Arrow Fonksiyonları

Arrow fonksiyonlarının normal fonksiyonlardan farkları:
- Kısa syntax.
- `this` değeri otomatik olarak belirlenir.

Örnek:

const add = (a, b) => a + b;
