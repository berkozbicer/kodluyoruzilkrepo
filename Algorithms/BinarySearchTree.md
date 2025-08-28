# Binary Search Tree (BST) Projesi

## Proje 3

### Verilen Dizi
```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
```

---

## 1) Binary Search Tree Aşamaları

**Adım 1:** İlk eleman **7** → Root olur.  
```
       7
```

**Adım 2:** 5, 7’den küçük → soluna eklenir.  
```
       7
      /
     5
```

**Adım 3:** 1, 7’den küçük → sola; 5’ten küçük → onun soluna.  
```
       7
      /
     5
    /
   1
```

**Adım 4:** 8, 7’den büyük → sağına eklenir.  
```
       7
      /      5   8
    /
   1
```

**Adım 5:** 3, 7’den küçük → sola; 5’ten küçük → sola; 1’den büyük → sağına.  
```
       7
      /      5   8
    /
   1
         3
```

**Adım 6:** 6, 7’den küçük → sola; 5’ten büyük → sağına.  
```
       7
      /      5   8
    /    1   6
         3
```

**Adım 7:** 0, 7’den küçük → sola; 5’ten küçük → sola; 1’den küçük → onun soluna.  
```
       7
      /      5   8
    /    1   6
  /  0   3
```

**Adım 8:** 9, 7’den büyük → sağa; 8’den büyük → onun sağına.  
```
       7
      /      5   8
    / \        1   6     9
  /  0   3
```

**Adım 9:** 4, 7’den küçük → sola; 5’ten küçük → sola; 1’den büyük → sağına; 3’ten büyük → sağına.  
```
       7
      /      5   8
    / \        1   6     9
  /  0   3
             4
```

**Adım 10:** 2, 7’den küçük → sola; 5’ten küçük → sola; 1’den büyük → sağına; 3’ten küçük → soluna.  
```
       7
      /      5   8
    / \        1   6     9
  /  0   3
    /    2   4
```

---

## 2) Sonuç

**Binary Search Tree** tamamlandı.  

- Root: **7**  
- Root’un solunda: **5**, sağında: **8**  
- 5’in solunda: **1**, sağında: **6**  
- 1’in solunda: **0**, sağında: **3**  
- 3’ün solunda: **2**, sağında: **4**  
- 8’in sağında: **9**
