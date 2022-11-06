# Proje_3-Binary-Search-Tree-Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Adım 1: Binary search tree algoritmasında bir root belirlenir. 
Root:7
Root düğümünden küçük olan değeri sol alt ağacına,büyük olan değeri sağ alt ağacına eklenir.

2.adım: 5,7'den küçük olduğu için sol alt ağa yerleştirilir.

                  7
                 /   
                5    
             
3.adım: 1,7'den küçük olduğu için sol alt agaca eklenir.5'den küçük olduğu için 5'in sol alt ağacına eklenir.

                    7
                  /   
                 5   
               / 
              1 

        
 4.adım: 8,7'den büyük olduğu için sağ alt ağaca eklenir.
 
                  7
                /  \ 
               5     8
              /      
             1 
             
5.adım: 3,7'den küçüktür fakat 1'den büyüktür o yüzden 1'in sağ alt ağacına eklenir.

                  7
                /  \ 
               5     8
              /      
             1 
              \
               3
               
6.adım: 6,7'den küçüktür fakat 5'den büyüktür o yüzden 5'in sağ alt ağacına eklenir.

                  7
                /   \ 
               5     8
              /  \    
             1    6
              \
               3
              


7.adım: 0,7'den ve 1'den küçüktür 1'nın sol alt agacına eklenir.

                  7
                /   \ 
               5     8
              /  \    
             1    6
           /  \
          0    3

           
      
 
 8.adım: 9,7'den ve 8'den büyüktür 8'in sağ alt agacına eklenir.
 
           
                 7
               /   \ 
              5     8
            /  \      \
           1    6       9
         /  \
        0    3
        
9.adım : 4,7'den küçüktür sol alt ağacına, 3'den büyüktür 3'ün sağ alt ağacına eklenir.

                 7
               /   \ 
              5     8
            /  \      \
           1    6       9
         /  \
        0    3
               \
                 4
  10.adım: 2,7'den küçüktür sol alt ağacına, 3'den küçüktür 3'ün sol alt ağacına eklenir.
  
                 7
               /   \ 
              5     8
            /  \      \
           1    6       9
         /  \
        0    3
               \
                 4
                 
