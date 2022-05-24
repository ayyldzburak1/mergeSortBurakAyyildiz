# mergeSortBurakAyyildiz
Merge Sort Projesi

#################
Proje 2
[16,21,11,8,12,22] -> Merge Sort

1-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.
#################

1-[16,21,11] [8,12,22] 
[16] [21,11]  [8,12] [22]
[16] [21] [11]  [8] [12] [22]
[16] [11,21]  [8,12][22]
[11,16,21] [8,12,22]
[8,11,12,16,21,22]  sonuç.

2- n basamak kadar böldüğümüz için elemanları n/2 den 2^n = x gelir bu da logn = x e tekabul eder. Big O ise buradan O(nlogn) olarak bulunur.
