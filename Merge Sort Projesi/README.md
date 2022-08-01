<h1 style="text-align: center;">  Merge Sort </h1>

***

<p style="text-align: center;">[16,21,11,8,12,22]</p>

***

# 1) Yukarı verilen dizinin Merge Sort türüne göre aşamaları:

`
[16,21,11,8,12,22]
[16,21,11] - [8,12,22]
[16] - [21,11] - [8,12] - [22]
[16] - [21] - [11] - [8] - [12] - [22]
[16] - [11,21] - [8,12] - [22]
[16,11,21] - [8,12,22]
[8,11,12,16,21,22]
Result -> [8,11,12,16,21,22]
`
***
# 2) Big-O gösterimi

`
O(nlogn)
`