Block = multiple of 32 of threads (so 256 threads/block is typical)

Comparison of CUDA framwork for Python kids: 
https://gist.github.com/lazarusA/07892bdb17d87efd0252ae6d1bf5b9a5 

* CuPy (instead of numpy)
* numba:
   - easy to install and implement
* PyCUDA:
   - requires you to write a kernel function in C code
   - run on NVIDIA chips only.

* PyOpenCl:
   - can be used to run code on a variety of platforms, including Intel, AMD, NVIDIA, and ATI chips.


numba ~ cython < numpy < numba_parrallel << tf_2.0 

numba < pyCUDA
