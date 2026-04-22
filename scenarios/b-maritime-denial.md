# 🌊 Senaryo B: Asimetrik Deniz Engelleme (Sea Denial)
## ⟨ Operasyonel Simulasyon: UMF-SCEN-02 ⟩

### 1. Durum Analizi
**Tehdit**: Bir düşman görev grubu (Uçak gemisi, 2 destroyer, 1 lojistik gemi), stratejik bir boğaza (dar su yolu) giriş yapmaya hazırlanıyor.
**Amaç**: Düşman filosunun geçişini, büyük bir deniz savaşına girmeden, asimetrik ve insansız unsurlarla engellemek.

---

### 2. Teşkilat ve Konuşlandırma (DNHK & AUFK)
**Birimler**:
- **İDA Sürüleri (12 adet Kamikaze Bot)**: Pasif modda su altında/yüzeyde bekleyen otonom üniteler.
- **Kıyı Bataryaları (4 adet Gemi-savar Füze)**: Karadan deniz hedeflerine kilitli sabit ve mobil üniteler.
- **Drone Desteği (AUFK)**: Hedefleme verilerini sağlayan yüksek irtifa keşif drone'ları.

---

### 3. Operasyonel Akış (D-Series Logic)
1.  **D-1 Gözlem**: Drone'lar vasıtasıyla düşman filosunun tam GPS ve termal imzası çıkarılır.
2.  **D-2 Simülasyon**: Düşman hava savunma kapasitesi analiz edilir ve %88 başarı ihtimali olan "Sürü Saldırısı" COA'sı seçilir.
3.  **D-3 Senkronizasyon**:
    - **Faz I**: İDA sürüleri farklı yönlerden düşman destroyerlerini meşgul eder.
    - **Faz II**: Destroyerler İDA'larla uğraşırken, kıyı bataryaları (UMF-SEA-MISS) ana hedef olan uçak gemisine kilitlenir ve tekil vuruş gerçekleştirir.

---

### 4. Sonuç ve Caydırıcılık
Düşman amiral gemisinin %40 hasar alması ve lidersiz kalması sonucu görev grubu bölgeden çekilmek zorunda kalır.

| Kaynak | Tüketim | Sonuç |
| :--- | :--- | :--- |
| **UMF Kayıpları** | 4 İDA (Sürü) | %0 Personel Kayfı |
| **Düşman Kayıpları** | 1 Uçak Gemisi (Hasarlı), 1 Destroyer (İmha) | %100 Çekilme |

> [!TIP]
> **D-3 Stratejisi:** İDA sürüleri, sadece fiziksel saldırı değil, aynı zamanda düşman radarlarını yanıltan "Düşük Maliyetli Hedef" (Decoys) olarak kullanılmalıdır.

---
*Referans: UMF-SCEN-01-B*
*Sınıflandırma: Deniz Harp Akademisi Simulasyonu*
