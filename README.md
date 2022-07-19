# Binary-Search-Tree-Projesi
www.patika.dev


Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Aşamalar

1- root=7
2- 5 rakamı root'dan küçük olduğu için sol tarafına yazılır.
          
                7
              /
             5
3-  1 rakamı root'dan ve 5'den küçük olduğu için 5'İn soluna yazılır.

                7
              /
             5
           /
          1
          
 4- 8 rakamı root'dan büyük olduğu için sağ tarafa yazılır.
 
                 7
              /     \
             5        8
           /
          1
          
 5- 3 rakamı root'dan ve 5 rakamından küçük, 1 rakamından büyük olduğu için 1'in sağına yazılır.
 
                 7
              /     \
             5        8
           /
          1
            \
              3

6- 6 rakamı root'dan küçük, 5 rakamından büyük olduğu için 5'in sağ tarafına yazılır.

                 7
              /     \
             5        8
           /    \
          1       6
            \
              3

7- 0 rakamı root'dan,5 ve 1 rakamından küçük olduğu için 1'in sol tarafına yazılır.
          
                 7
              /     \
             5        8
           /    \
          1       6
        /   \
      0       3          
          
          
8- 9 rakamı root'dan ve 8 rakamından büyük olduğu için 8'in sağ tarafına yazılır.          
          
                 7
              /     \
             5        8
           /    \       \
          1       6       9
        /   \
      0       3             
          
          
9- 4 rakamı root'dan ve 5 rakamından küçük, 1 rakamından büyük,3 rakamından büyük olduğu için 3'ün sağ tarafına yazılır.             
          
                 7
              /     \
             5        8
           /    \       \
          1       6       9
        /   \
      0       3 
                \
                  4
          
 10 - 2 rakamı root'dan ve 5 rakamından küçük, 1 rakamından büyük,3 rakamından küçük olduğu için 3'ün sol tarafına yazılır.       
          
          
                 7
              /     \
             5        8
           /    \       \
          1       6       9
        /   \
      0       3 
            /   \
           2      4         
          
          
          
          
          
          
          
          
          
          
          
          
          
