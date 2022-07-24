
[Patika.dev](www.patika.dev)

# Binary Search Tree Projesi (Proje 3)

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
   Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

llk olarak 7 rakamından başlayorum , bunun Root  olduğunu düşünüyorum.. Ardınan ikinci rakama (5) geçiyorum. İkinci rakam, ilk rakam olan 7' ye bagli olacak yani Child Node olacak. 5 7' den küçük bir rakam. Bu sebepten onu sol alt tarafa aldim.
                                                 
                                                 7
                                              /
                                           5   
                                               

3.ncü rakamımız ise 1 Root Node ile karşılaştırdığımızda ondan kücük olduğunu görüyoruz. Bu yüzden onu 7nin sol alt node' u olacak  orda ama  5 var  burda yine bir karsilastirma yapiyoruz. 1  5‘ den kücük dolayisila  5 in bir alt sol node olacak .


                                 7
                                 /
                               5
                               /
                            1   
                            
                     
4. rakamimiz 8  ve 8 7’den büyük  dolayisiyla 7’nin saginda  yer alacak.
                                        7
                                        /\
                                      5    8
                                      /
                                    1
5. rakamimiz 3
3 Root dan kücük listenin solunda, 5 den kücük  5’in solunda , 1‘ den büyük  dolayisiyla 1’in saginda yer alacak.

                                                         7
                                                       /   \        
                                                     5       8
                                                   /   \
                                                 1  
                                                    \
                                                       3


6. rakamimiz 6 
Root dan kücük dolayisiyla agacin sol tarafinda , 5 den büyük  5 node nun sag  alt node na yerlesek
                                                   7
                                                  /  \              
                                               5        8
                                              /  \
                                            1      6
                                              \
                                               3
7. rakamimiz 0
Root olan 7 den kücük agacin solundan ilerliyoruz. 1 sayisinin sol alt node na yerlesiyor.

                                                    7
                                                  /  \              
                                               5        8
                                              /  \
                                            1      6
                                           /  \
                                         0      3

8. Rakamimiz 9
9 Root dan büyük agacimizin solunda yer alacak, burda 8 var 9  8 den büyük oldugundan 8’in sag alt node yerlesiyor
                                            
                                                    7
                                                  /  \              
                                               5        8
                                              /  \        \
                                            1      6       9
                                           /  \
                                         0      3


9. rakamimiz 4: Rootan kücük agacin soluna , 5’ten kücük 5’in sol alt Node na 1’den büyük  1’in sag Node na , 3 den büyük  3ün sag alt Node una yerlesiyor       

                                                       
                                                    7
                                                  /  \              
                                               5        8
                                              /  \        \
                                            1      6       9
                                           /  \
                                         0      3
                                               /  \
                                                   4





10. rakamimiz 2
2 Rootan kücük agacin soluna, 5 den kücük 5’in sol Node na,  1’den büyük  1’in sag Node una  , 3’ten  kücük 3’ün sol alt Node na yerlesiyor.

                                                   
                                                      
                                                    7
                                                  /  \              
                                               5        8
                                              /  \        \
                                            1      6       9
                                           /  \
                                         0      3
                                               /  \
                                             2      4





