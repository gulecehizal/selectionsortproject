# selectionsortproject


Project_1 (www.patika.dev ) veri yapıları ve algoritmaları eğitimine ait "selection sort" proesi

[22,27,16,2,18,6] "n" elemanlı sıralaması istenen dizi seti
[2,27,16,22,18,6] en küçük değer olan 2 başa geçirilir, yerine geldiği 22 sayısı ile yer değiştirir.
[2,6,16,22,18,27] 2 değeri başa geçirildiği için "n-1" elemanlı dizi içinden en küçük olan diğer sayı olan 6, 2 den sonraki yerini alarak 27 sayısı ile yer değiştirdi.
[2,6,16,22,18,27] n-2 elemanlı dizide en küçük sayı 16 olduğundan ötürü yeri değişmedi.
[2,6,16,18,22,27] n-3 elemanlı dizide sıradaki en küçük değer 18 olduğu için 22 ile 18 yer değiştirir. dizi sıralanmış olduğu için tekrar bir adıma gerek kalmamıştır.

big-o n^2 dir.

18 sayısı ordada yer aldığı için bu dizi "average case" dir.


[7,3,5,8,2,9,4,15,6] dizisinin ilk dört adımı aşağıda sıralanmıştır.

[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]

