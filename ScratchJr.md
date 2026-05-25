# ScratchJr ile Uygulama

## "Sözdizimi" (Bloklar)

ScratchJr'da kod yazmak, blokları soldan sağa dizmek demektir. İşte en önemli bloklar ve metin karşılıkları:

| Kategori | Blok (Metin Karşılığı) | Ne İşe Yarar? |
| :--- | :--- | :--- |
| **Sarı (Tetikleyici)** | `[Bayrak]` | Yeşil bayrağa tıklandığında başlar. |
| | `[Dokun]` | Karaktere dokunulduğunda başlar. |
| **Mavi (Hareket)** | `[Sağ]`, `[Sol]`, `[Zıpla]` | Karakteri hareket ettirir. |
| **Mor (Görünüm)** | `[Konuş]` | Karakterin konuşma baloncuğu çıkarmasını sağlar. |
| **Turuncu (Kontrol)** | `[Bekle]` | Belirli bir süre bekler. |
| **Kırmızı (Son)** | `[Bitir]` | Rutini sonlandırır. |

## Örnek Rutin: Konuşan Hesap Makinesi

Hesaplama animasyonu için sıralı adımlar:

### Senaryo: 2 + 3 = 5
**Karakter:** Kedi
**Kod Dizisi (Rutini):**
`[Dokun]` ➔ `[Konuş: "2 artı 3 kaç eder?"]` ➔ `[Bekle: 20]` ➔ `[Konuş: "Beş eder!"]` ➔ `[Zıpla]` ➔ `[Bitir]`

### Uygulama:
1. Tablet veya bilgisayarda **ScratchJr** uygulaması açılır.
2. Yeni bir proje oluşturulur.
3. Alttaki programlama alanına yukarıdaki bloklar sırasıyla sürükleyip birbirine takılır.
4. Kediye dokununca cevabı söyleyecek.