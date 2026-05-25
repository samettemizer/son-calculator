# Scratch ile Hesap Makinesi Rehberi (8+ Yaş)

Bu rehber, Scratch kullanarak gerçek bir hesap makinesi yapmak için hazırlandı. ScratchJr'dan farklı olarak burada **Değişkenler** ve **Operatörler** kullanılarak sayılar toplanabilir, çıkarılabilir, çarpılabilir veya bölünebilir.

## Hazırlık: Değişkenlerin Oluşturulması

Kodlamaya başlamadan önce bilgisayarın sayıları aklında tutabilmesi için "Değişkenler" bölümünden şu kutular (değişkenler) oluşturulur:

1.  **Sayi 1**: İlk girdiğimiz sayı.
2.  **Sayi 2**: İkinci girdiğimiz sayı.
3.  **İşlem**: Yapacağımız matematiksel işlem (+, -, *, /).
4.  **Sonuç**: Hesaplamanın cevabı.

---

## 🏗️ Kod Blokları

Aşağıdaki bloklar sırasıyla dizilerek hesap makinesi çalıştırılabilir:

### 1. Soruları Sor ve Bilgileri Kaydet
*   `[Yeşil Bayrağa Tıklandığında]`
*   `[ "Birinci sayıyı girin" diye sor ve bekle ]`
*   `[Sayi 1] değişkenini [cevap] yap.`
*   `[ "İşlemi girin (+, -, *, /)" diye sor ve bekle ]`
*   `[İşlem] değişkenini [cevap] yap.`
*   `[ "İkinci sayıyı girin" diye sor ve bekle ]`
*   `[Sayi 2] değişkenini [cevap] yap.`

### 2. Hesaplamayı Yap (Mantık)
Burada "Kontrol" kategorisindeki `Eğer ... ise` bloklarını kullanacağız:

*   **Toplama:** `Eğer [İşlem] = [+] ise:`
    *   `[Sonuç] değişkenini ( (Sayi 1) + (Sayi 2) ) yap.`
*   **Çıkarma:** `Eğer [İşlem] = [-] ise:`
    *   `[Sonuç] değişkenini ( (Sayi 1) - (Sayi 2) ) yap.`
*   **Çarpma:** `Eğer [İşlem] = [*] ise:`
    *   `[Sonuç] değişkenini ( (Sayi 1) * (Sayi 2) ) yap.`
*   **Bölme:** `Eğer [İşlem] = [/] ise:`
    *   `[Sonuç] değişkenini ( (Sayi 1) / (Sayi 2) ) yap.`

### 3. Cevabı Söyle
*   `[(Sonuç) de ve 2 saniye bekle]`

### Bitti bu kadar!

---

## 💡 Ekstra: Daha iyi görünmesi için
*   **Karakter Seçimi:** Hesap makinen için konuşan bir robot veya bir profesör karakteri seçilebilir.
*   **Ses:** Sonuç açıklandığında bir "tada!" sesi ekleyerek uygulama daha eğlenceli hale getirilebilir.