## Bu ödevde [16, 21, 11, 8, 12, 22] dizisinin Merge Sort'a göre sıralanması ve Big-O gösteriminin yazılması istenmektedir.

0. Adım: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [16, 21, 11, 8, 12, 22]
1. Adım: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [16, 21, 11] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8, 12, 22] 
2. Adım: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [16, 21] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [11] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8, 12] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [22]
3. Adım: &nbsp;&nbsp; [16] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [21] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [12] 
4. Adım: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [16, 21] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8, 12]             
5. Adım: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [11, 16, 21] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8, 12, 22]
6. Adım: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8, 11, 12, 16, 21, 22] 

Bu adımlar ile diziyi sürekli olarak ikiye böldük ve bu parçaları kendi içlerinde sıralayarak birleştirdik.

* Merge sort'un Big-O gösterimi O(nlogn)'dir.