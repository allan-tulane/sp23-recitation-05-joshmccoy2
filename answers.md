# CMPS 2200 Reciation 5
## Answers

**Name:** Josh McCoy


Place all written answers from `recitation-06.md` here for easier grading.







- **1b.**
|      n |   qsort-fixed-pivot |   qsort-random-pivot |
|--------|---------------------|----------------------|
|    100 |               0.001 |                0.008 |
|    200 |               0.000 |                0.002 |
|    500 |               0.000 |                0.002 |
|   1000 |               0.001 |                0.003 |
|   2000 |               0.001 |                0.002 |
|   5000 |               0.001 |                0.004 |
|  10000 |               0.001 |                0.004 |
|  20000 |               0.001 |                0.004 |
|  50000 |               0.002 |                0.005 |
| 100000 |               0.002 |                0.008 |

|      n |   ssort-fixed-pivot |   ssort-random-pivot |
|--------|---------------------|----------------------|
|    100 |               0.001 |                0.007 |
|    200 |               0.000 |                0.002 |
|    500 |               0.000 |                0.002 |
|   1000 |               0.000 |                0.002 |
|   2000 |               0.000 |                0.002 |
|   5000 |               0.002 |                0.006 |
|  10000 |               0.001 |                0.005 |
|  20000 |               0.002 |                0.005 |
|  50000 |               0.002 |                0.005 |
| 100000 |               0.002 |                0.006 |

Ssort has a much higher runtime than that qsort for both sorted and unsorted lists. The asymptotic upper bound of qsort is O(nlogn) and ssort is O(n^2). Ssort did perform better for sorted lists for any size n.

- **1c.**
n	qsort-fixed-pivot	qsort-random-pivot	tim_sort
100	0.001	0.004	0.018
200	0.001	0.003	0.026
500	0.001	0.003	0.070
1000	0.001	0.003	0.159
2000	0.001	0.003	3.218
5000	0.002	0.005	1.194
10000	0.003	0.006	3.572
20000	0.003	0.006	5.888
50000	0.003	0.006	38.698
100000	0.002	0.006	33.340


The fastest sorting is qsort-fixed-pivot. For any value n the runntime is smaller than tim sort. If the data became somewhat sorted than tim_sort would be the fastest option.  Both have 0(nlogn) worst case runtimes, However mostly Qsort is faster when the list is random. 