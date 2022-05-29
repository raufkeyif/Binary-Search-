# Binary-Search-
Binary Search Project
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root’umuz 7
7’den sonraki rakamı, 7 ile karşılarştıracağız.
5, 7’den büyük mü? küçük mü?
= Küçük

                                    **7**
                                   '
                                  '
                               **5**  
Gördüğünüz gibi 7’nin sol altına yerleştirdik. Bunun sebebi, Binary Search’te karşılaştırdığınız sayıdan küçükse sola büyükse sağına yazılır.
Karşılaştırma işlemine devam edelim…

                                    **7**
                                  '        '
                                '            '
                             '                  '
                             **5**              **8**                                     
                              '    ''               '                        
                             '       '                '
                          **1**       **6**            **9**
                         '       '  
                       '          ' 
                    ** 0**           **3**
                                   '      '
                                 '          '
                            **2**           **4** 
