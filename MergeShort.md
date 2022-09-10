**[16,21,11,8,12,22] -> Merge Sort**

**Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**

**Big-O'yu gönderin.**

1.[16,21,11,8,12,22] merge sort'a göre aşamaları:

 [16,21,11]          [8,12,22]

 [16] [21,11]       [8,12] [32]

 [16] [21] [11]     [8] [12] [32]

 [16] [11,21]       [8] [12,32]

 [11,16,21]         [8,12,32]

 [8,11,12,16,21,32]

2.Big-O:0(logn)