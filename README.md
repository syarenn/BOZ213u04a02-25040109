# Aylardaki Gün Sayısını Hesaplama

### Projenin Amacı Nedir?
Python'da fonksiyonlar kullanarak girilen yıl ve aya ait gün sayısını hesaplamak.

### Program Ne İşe Yarar?
Belirtilen ayın kaç gün sürdüğünü hesaplar. Şubat ayında artık yıl durumunu dikkate alır.

### Program Nasıl Çalışır?
1. `is_year_leap()` fonksiyonu yılın artık yıl olup olmadığını kontrol eder.
2. `days_in_month()` fonksiyonu yıl ve ay bilgilerini alır.
3. Ayın gün sayısı listeden belirlenir.
4. Artık yılda şubat ayının gün sayısı 29 olarak hesaplanır.
5. Geçersiz yıl veya ay girildiğinde `None` döndürülür.
6. Test sonuçları doğruysa ekrana `OK` yazdırılır.

### Kullanılan Python Yapıları Nelerdir?
- `def`, `return`
- `if`, `elif`, `else`
- `for` döngüsü
- Listeler ve indeksleme
- `and`, `or`
- `None`, `True`, `False`

### Programın Beklenen Çıktısı Nedir?
```text
1900 2 -> OK
2000 2 -> OK
2016 1 -> OK
1987 11 -> OK
```

### Program Nasıl Çalıştırılır?
Python IDLE üzerinden `.py` dosyası açılır ve F5 tuşuna basılır.

### Kaynakça
Python Software Foundation. (t.y.). *The Python tutorial*. https://docs.python.org/3/tutorial/
