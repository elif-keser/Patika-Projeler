## Proje 2

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

---

## Merge Sort Analizi

### Başlangıç Dizisi:
- `[16, 21, 11, 8, 12, 22]`

### Aşamalar:

**1. Divide:**
- `[16, 21, 11, 8, 12, 22]`  
  1. `[16, 21, 11]`
  2. `[8, 12, 22]`


- `[16, 21, 11]`
  1. `[16]`
  2. `[21]`
  3. `[11]`

     
- `[8, 12, 22]`
  1. `[8]`
  2. `[12]`
  3. `[22]`

**2. Merge ve Sıralama:**
- `[16] + [21]` → `[16, 21]`
- `[16, 21] + [11]` → `[11, 16, 21]`
- `[8] + [12]` → `[8, 12]`
- `[8, 12] + [22]` → `[8, 12, 22]`

**3. Birleştirme:**
- `[11, 16, 21] + [8, 12, 22]` → `[8, 11, 12, 16, 21, 22]`

###  Sonuç:
- `[8, 11, 12, 16, 21, 22]`

###  Big-O Gösterimi:
- Best,Average,Worst Case: O(n log n)
