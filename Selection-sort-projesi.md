# Insertion Sort

## Soru 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

---

### Cevap

<ol>
    <li>[22,27,16,2,18,6] Verilen dizi
    <li>[2,27,16,22,18,6] 
    <li>[2,6,16,22,18,27]
    <li>[2,6,16,18,22,27]
</ol>

---

## Soru 2

Big-O gösterimini yazınız.

### Cevap

<ol>
    <li>[22,27,16,2,18,6] (Verilen dizi) n
    <li>[2,27,16,22,18,6] n-1
    <li>[2,6,16,22,18,27] n-2
    <li>[2,6,16,18,22,27] +1
</ol>

`n + n(n-1) + (n-2) ...`<br>
`n . (n+1) / 2`<br>
`= O(n^2)`

---

## Soru 3

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

<ol>
    <li>Average case: Aradığımız sayının ordata olması
    <li>Worst case: Aradığımız sayının sonda olması
    <li>Best case: Aradığımız sayının dizinin en başında olması.
</ol>

### Cevap

[22,27,16,2,18,6] (Verilen dizi)<br>

<ul>
    <li>"18" sayısı sonuncu sayı olmadığına, ve orta bölüme daha yakın olduğu için "Average Case" kapsamına girer.
</ul>

---

## Soru 4

**[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

### Cevap

**[7,3,5,8,2,9,4,15,6]** dizinin ilk dört adımı

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]

---
