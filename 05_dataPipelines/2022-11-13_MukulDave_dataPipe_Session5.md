## Solution

nthreads, buffer_size, images/sec

16, 8,  437

32, 8,  588 

64, 8,  647

64, 16, 762

I increased the number of steps to 100 to see a visible difference. The image processing rate increases, but not linearly with number of threads.
