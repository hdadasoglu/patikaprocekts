# Binary Tree
- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

- Root 5 olarak seçilmiştir.


                              5
                             / \
                           3     7
                          /\    / \ 
                         1  4  6   8
                        /\          \
                       0  2          9

- 2 Sayısını Yapımızda arayalım

            2<5 'tir sola gidiyoruz
            2<3 'tür sola gidiyoruz
            2>1 'dir sağa gidiyoruz
            ve 2'yi bulduk