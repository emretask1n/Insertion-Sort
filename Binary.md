# Binary Search Tree Projesi

### 1- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları

 - [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 
 
                               7 
                            /     \
                        5           8
                      /   \            \ 
                     1      6             9
                  /   \
                 0      3
                       /  \
                     2      4


 ## Eklemek istediğimiz eleman  olarak 1'i seçelim ;
  --> Tree'ye eleman eklemek istedİğimiz zaman root'dan başlıyoruz. Root elemanımız 7 'dir. Gelen eleman Root sayısı olan 7'den büyük ise sağ, küçük ise sola ekliyoruz. 1 sayısını yapıya ekleyelim.  Root'dan küçük  olduğu için sol tarafta bulunan elemana ekliyoruz. Sol tarafta 5 elemanı mevcut. 1 elemanı 5 elemanından küçük olduğundan sol tarafa eklenecektir.                
