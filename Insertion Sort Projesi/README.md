<h1 style="text-align: center;">  Insertion Sort </h1>

***

<p style="text-align: center;">[22,27,16,2,18,6]</p>

***

# 1) Yukarı verilen dizinin Insertion Sort türüne göre aşamaları:

`
[22|,27,16,2,18,6]
[16,27|,22,2,18,6]
[16,22,27|,2,18,6]
[2,16,22,27|,18,6]
[2,16,18,22,27|,6]
[2,6,16,18,22,27|]
Result -> [2,6,16,18,22,27]
`
***
# 2) Big-O gösterimi

`
Worst Case : O(n^2)
Avarage Case : O(n^2)
Best Case : O(n)
`
***
# 3) Time Complexity

Örneğin bu dizide 27'yi arıyoruz

`
Worst Case : [2,6,16,18,22,27]
Avarage Case : [2,6,16,27,18,22]
Best Case : [27,2,6,16,18,22]
`
***
# 4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

`
Avarage Case'e girer, çünkü dizinin ortasındadır.
`