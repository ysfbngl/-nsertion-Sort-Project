# -insertion-Sort-Project
[22,27,16,2,18,6] --> insertion sort

1-) insertion sort step
27<22 ? [22,27,16,2,18,6]

16<27 ? [22,16,27,2,18,6]
16<22 ? [16,22,27,2,18,6]

2<27 ? [16,22,2,27,18,6]
2<22 ? [16,2,22,27,18,6]
2<16 ? [2,16,22,27,18,6]

18<27 ? [2,16,22,18,27,6]
18<22 ? [2,16,18,22,27,6]
18<16 ? [2,16,18,22,27,6]

6<27 ? [2,16,18,22,6,27]
6<22 ? [2,16,18,6,22,27]
6<18 ? [2,16,6,18,22,27]
6<16 ? [2,6,16,18,22,27]
6<2 ? [2,6,16,18,22,27]


2-) Big-O notation 

O(n^2)


3-) Timecomplexity

Avarage Case : n^2
Best Case : n
Worst Case : n^2

4-) Which case for 18?
The number of 18 is an avarage case because it is the middle element of the array.


5-) First four insertion sort steps of the [7,3,5,8,2,9,4,15,6]

3<7 ? [3,7,5,8,2,9,4,15,6]
5<7 ? [3,5,7,8,2,9,4,15,6]
8<7 ? [3,5,7,8,3,9,4,15,6]
3<8 ? [3,5,7,3,8,9,4,15,6]
