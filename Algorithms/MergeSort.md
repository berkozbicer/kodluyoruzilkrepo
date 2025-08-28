# Merge Sort Projesi

## Proje 2

### Verilen Dizi
```
[16, 21, 11, 8, 12, 22]
```

---

## 1) Merge Sort Aşamaları

**Adım 1: Diziyi ikiye böl**  
```
[16, 21, 11]   |   [8, 12, 22]
```

**Adım 2: Alt dizileri tekrar böl**  
```
[16] [21, 11]   |   [8] [12, 22]
```

**Adım 3: Tekrar böl**  
```
[16] [21] [11]   |   [8] [12] [22]
```

**Adım 4: Küçük dizileri sırala ve birleştir**  
- [21] ve [11] → `[11, 21]`  
- [12] ve [22] → `[12, 22]`  

Sonuç:  
```
[16] [11, 21]   |   [8] [12, 22]
```

**Adım 5: Tekrar birleştir**  
- [16] ve [11, 21] → `[11, 16, 21]`  
- [8] ve [12, 22] → `[8, 12, 22]`  

Sonuç:  
```
[11, 16, 21]   |   [8, 12, 22]
```

**Adım 6: Son birleştirme**  
- [11, 16, 21] ve [8, 12, 22] → `[8, 11, 12, 16, 21, 22]`  

**Sıralı dizi:**  
```
[8, 11, 12, 16, 21, 22]
```

---

## 2) Big-O Gösterimi

Merge Sort her zaman diziyi ikiye böler ve sonra birleştirir.

- Bölme işlemi: O(log n)  
- Birleştirme işlemi: O(n)  
- Toplam karmaşıklık:  
**O(n log n)**