# ex.3.30

###### task

en: Use Program 3.9 to plot the Josephus function versus N for M =
10 and N from 2 to 1000.

ru: Используйте программу 3.9, чтобы построить график зависимости
функции Иосифа от N для M = 10 и N от 2 до 1000.

###### solution

```
$ ./ex.3.30 20 40
     +---------------------------------------> Y, Node number
   2 | 1
  51 |* 46
 100 |* 26
 149 | 3
 198 |***** 143
 247 |******** 201
 296 |****** 157
 345 |************* 335
 394 |*** 93
 443 |****** 155
 492 |****** 169
 541 |***** 131
 590 |* 34
 639 |******************** 524
 688 |************** 362
 737 |***** 127
 786 |************************ 617
 835 |************ 302
 884 |******************************* 792
 933 |*************** 387
 982 |*********************************** 877
1000 |** 63
     V
     X, N
```