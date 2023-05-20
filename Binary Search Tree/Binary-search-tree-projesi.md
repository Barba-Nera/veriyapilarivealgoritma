# Binary Search Tree

## Soru 1

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

---

## Cevap

Başlangıçta bir eleman root olarak seçilecektir. Bu seçim için verilen dizinin soldan ilk elemanı olan "**7**" rakamı alınır. Sonraki gelen sayılar, **7** rakamına göre küçük ise sol tarafına büyük ise sağ tarafına yazılır.

**Oluşturulan Ağacın Aşamaları:**

1. Dizinin oluşturulması amacıyla 5 rakamının ağaçtaki yerleşimi

-                            7
                            /
                           5

2. "**1**" sayısı ağaç içerisindeki yerleşimi 7'den küçük ise sol taraftan devam eder. Sonrasında 5'ten küçük ise sol tarafına dahil edilir.

-                            7
                            /
                           5
                          /
                         1

3. Sıradaki sayı "**8**", 7'den büyük olduğu için sağ tarafına yazılarak ağaca eklenir.

-                            7
                            / \
                           5   8
                          /
                         1

4. "**3**" sayısı 7'den küçük olduğu için sol taraftan, 5'ten küçük olduğu için sol taraftan, 1'den büyük olduğu için "**5**" sayısının altına bir dal olarak yazılır.

-                            7
                            / \
                           5   8
                          / \
                         1   3

5. "**6**" sayısı 7'den küçük olduğu için sol taraftan, 5'ten büyük olduğu için sağ taraftan 3'ten büyük olduğu için "**3**" sayısının sağ tarafına yazılır.

-                            7
                            / \
                           5   8
                          / \
                         1   3
                              \
                               6

6. "**0**" sayısı 7'den küçük, 5'ten küçük, 1'den de küçük olduğu için "**1**" sayısının sol tarafına yazılır.

-                            7
                            / \
                           5   8
                          / \
                         1   3
                        /     \
                       0       6

7. "**9**" sayısı 7'den büyük ve 8'den de büyük olduğu için "**8**" sayısının sağ tarafına yazılır.

-                            7
                            / \
                           5   8
                          / \   \
                         1   3   9
                        /     \
                       0       6

8. "**4**" sayısı 7'den küçük, 5'ten küçük 1'den büyük olduğu için "**1**" sayısının sağ tarafına eklenir.

-                            7
                            / \
                           5   8
                          / \   \
                         1   3   9
                        / \   \
                       0   4   6

9. Son sayı olan "**2**", 7'den küçük, 5'ten küçük 1'den büyük ve 4'ten küçük olduğu için 4'ün sol altına yazılır.

-                            7
                            / \
                           5   8
                          / \   \
                         1   3   9
                        / \   \
                       0   4   6
                          /
                         2
