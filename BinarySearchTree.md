# Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

*****************

Root = 7

5 sayısı 5<7 olduğu için root'un sol tarafında bulunur.

1 sayısı 1<7 && 1<5 için 5'in sol tarafında bulunur.

8 sayısı 8>7 olduğu için root'un sağ tarafında bulunur.

3 sayısı 3<7 && 3<6 && 3>1 olduğu için 1'in sağ tarafında bulunur.

6 sayısı 6<7 ve 6>5 olduğu için root'un sol, 5'in sağ tarafında bulunur.

*************************

                              5
                             / \
                           3     7
                          /\    / \ 
                         1  4  6   8
                        /\          \
                       0  2          9
                       
   ***************

[Patika](www.patika.dev)

[Binary Search Projesi](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje)
