# Insertion Sort Projesi

## Proje 1

### Verilen Dizi
```
[22, 27, 16, 2, 18, 6]
```

---

## 1) Insertion Sort Aşamaları

**Başlangıç:**  
`[22, 27, 16, 2, 18, 6]`

- **Adım 1:** 27, 22’nin yanında zaten doğru yerde.  
`[22, 27, 16, 2, 18, 6]`  

- **Adım 2:** 16, 27’den küçük → sola kaydırılır.  
`[22, 16, 27, 2, 18, 6]`  
16, 22’den de küçük → sola kaydırılır.  
`[16, 22, 27, 2, 18, 6]`  

- **Adım 3:** 2, 27’den küçük → sola.  
`[16, 22, 2, 27, 18, 6]`  
2, 22’den küçük → sola.  
`[16, 2, 22, 27, 18, 6]`  
2, 16’dan küçük → sola.  
`[2, 16, 22, 27, 18, 6]`  

- **Adım 4:** 18, 27’den küçük → sola.  
`[2, 16, 22, 18, 27, 6]`  
18, 22’den küçük → sola.  
`[2, 16, 18, 22, 27, 6]`  

- **Adım 5:** 6, 27’den küçük → sola.  
`[2, 16, 18, 22, 6, 27]`  
6, 22’den küçük → sola.  
`[2, 16, 18, 6, 22, 27]`  
6, 18’den küçük → sola.  
`[2, 16, 6, 18, 22, 27]`  
6, 16’dan küçük → sola.  
`[2, 6, 16, 18, 22, 27]`  

**Sıralı dizi:**  
```
[2, 6, 16, 18, 22, 27]
```

---

## 2) Big-O Gösterimi

- Ortalama ve en kötü durumda: **O(n²)**
- En iyi durumda (zaten sıralıysa): **O(n)**

---

## 3) Time Complexity’de 18’in Durumu

18, sıralandıktan sonra ortalarda yer aldığı için:  
**Average Case** kapsamına girer.

---

## 4) Selection Sort İlk 4 Adım

Verilen dizi:  
```
[7, 3, 5, 8, 2, 9, 4, 15, 6]
```

- **Adım 1:** En küçük 2, baştaki 7 ile yer değiştirir.  
`[2, 3, 5, 8, 7, 9, 4, 15, 6]`  

- **Adım 2:** En küçük 3, zaten doğru yerde.  
`[2, 3, 5, 8, 7, 9, 4, 15, 6]`  

- **Adım 3:** En küçük 4, 5 ile yer değiştirir.  
`[2, 3, 4, 8, 7, 9, 5, 15, 6]`  

- **Adım 4:** En küçük 5, 8 ile yer değiştirir.  
`[2, 3, 4, 5, 7, 9, 8, 15, 6]`  

**İlk 4 adım sonrası dizi:**  
```
[2, 3, 4, 5, 7, 9, 8, 15, 6]
```
