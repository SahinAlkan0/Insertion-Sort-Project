# Insertion Sort Project 
* [22,27,16,2,18,6] -> Insertion Sort . Yanda  verilen dizinin sort türüne göre aşamalarını yazınız.
```
İlk başta ilk eleman yanındaki elemanla karşılaştırılır ve küçük olan sola alınır.
1-) [22,27,16,2,18,6] ilk iki elemanın dizilimi doğru.
2-)[16,22,27,2,18,6] 22 ile 3. eleman karşılaştırılır 16 daha küçük olduğu için 22 nin soluna geçer.
3-) [2,16,22,27,18,6] 2, 22 den ve diğer elemanlardan küçük olduğu içn en başa alınır.
4-) [2,16,18,22,27,6] 18, 22 den küçük 16 dan büyük olduğu için 3. sıraya alınır.
5-) [2,6,16,18,22,27] 6, 16 dan küçük 2 den büyük olduğu için 2. sıraya alınır.
Böylece işlem tamamlanır.
```
* Big-O gösterimini yazınız.
```
Worst ve average case de O(n^2) dır ve best case de ise  O(n) dir
```
* Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
```
18 average case durumundadır. Çünkü: [2,6,16,18,22,27] sıralanmasında orta kısımda bulunmaktadır.
```
* [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```
[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
```