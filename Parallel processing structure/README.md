**Structure of the getting access to the parallel processing execution**
```diff
+ #include <stdio.h>
+ #include <omp.h>

- int main()
- {

 This command use to the parallelize the code enclosed within the following block.
- #pragma omp parallel
- {
 parallel works mentioned here 
- }

- return 0;
- }
