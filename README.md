# Binary Search Three

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

- Root olarak 7'yi alırız

              7  

- 5 7'den küçüktür bu yüzden 7'nin soluna yerleştiririz
              
              7
          /  
        5

- 1 7 ve 5'ten küçüktür dolayısıyla her ikisinin soluna yerleştiririz

              7
           /
        5
      /
    1

- 8 7'den büyüktür 7'nin sağına yerleştiririz
          
              7
           /     \
        5          8
      /
    1

- 3 7'den küçük fakat 1'den büyüktür. 7'nin soluna ve 1'in sağına yerleşir.
         
              7
           /     \
        5          8
      /
    1 
     \
      3

- 6 7'den küçük fakat 5'ten büyüktür. 7'nin soluna 5'in sağına yerleşir
                  
              7
           /     \
        5          8
      /    \          
    1        6
       \
          3
            

- 0 7 ve 1'den küçüktür dolayısıyla bu sayıların soluna yerleşir
                  
              7
           /     \
        5          8
      /    \         
    1        6
  /     \
0         3

- 9 7'den ve 8'den büyüktür ddolayısıyla bu sayıların sağına yerleşir
                  
              7
           /     \
        5          8
      /    \         \
    1        6         9
  /     \
0         3

- 4 7'den küçük fakat 3'ten büyüktür. Dolayısıyla 7'nin soluna 3'ün sağına yerleşir
            
              7
           /     \
        5          8
      /    \         \
    1        6         9
  /     \
0         3
            \
              4

- 2 7'den ve 3'ten küçüktür dolayısıyla her ikisinin sağına yerleşir
                           
              7
           /     \
        5          8
      /    \         \
    1        6         9
  /     \
0         3
        /   \
      2       4

