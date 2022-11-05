# proje3
binary search
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazacağız

                   [Root]
                    [7]
                    / \
                   /   \
                 [5]   [8]
                 / \     \
                /   \     \
              [1]   [6]   [9]
              /  \     
             /    \
           [0]    [3]
                  / \
                 /   \
               [2]   [4]
Aşamalarımız
- Root:7 

- 5 Sayısı 7 sayısından küçük olduğundan dolayı için 7'nin soluna eklenir.

- 1 Sayısı 7 sayısından ve 5 sayısından küçük olduğu için 5'in soluna eklenir.

- 8 Sayısı 7 sayısından büyük olduğu için 7'nin sağına eklenir.

- 3 Sayısı 7 sayısından ve 5 sayısından küçük, 1 sayısından büyük olduğu için 1'in sağına eklenir.

- 6 Sayısı 7 sayısından küçük 5 sayısından büyük olduğu için 5'in sağına eklenir.

- 0 Sayısı 7  5 ve 1 sayısından küçük olduğu için 1'in soluna eklenir.

- 9 Sayısı 7 sayısından ve 8 sayısından büyük olduğu için 8'in sağına eklenir.

- 4 Sayısı 7 sayısından ve 5 sayısından küçük, 1 ve 3 sayısından büyük olduğu için 3'ün sağına eklenir.

- 2 Sayısı 7 sayısından ve 5 sayısından küçük, 1 sayısından büyük olduğu için 1 sayısının sağına, 3 sayısından küçük olduğu için 3'ün soluna eklenir.
