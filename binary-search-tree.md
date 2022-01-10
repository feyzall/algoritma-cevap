## Binary Search Tree
Arama algoritması olarak binary search tree oluşturmak için önce bir kök/root eleman alıp diğer elemanları bu elemana göre büyükse sağa küçükse sola alt dallara ayırarak ağaç yapısı elde edilir. 

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

kök düğüm = 7

sıradaki eleman (5) root elemandan küçük olduğu için sola (1. alt)


sıradaki eleman (1) root ve 1.alt düğümdeki elemandan (5) küçük olduğu için sola (2.alt)

sıradaki eleman (8) root elemandan büyük olduğu için sağa (1. alt)

sıradaki eleman (3) root ve 1.alt düğümdeki elemandan (5) küçük olduğu için sola fakat 1 elemanından büyük olduğu için 1 in sağına (2.alt)

sıradaki eleman (6) root elemandan küçük olduğu için sola fakat 1.alt düğümdeki elemandan (5) büyük olduğu için 5 in sağına

sıradaki eleman (0) ... 2.alt düğümdeki elemandan (1) küçük olduğu için sola

. . .

![image](https://user-images.githubusercontent.com/58623086/148765923-5822f546-9ddc-4c57-9127-f2b07f895d8b.png)

			