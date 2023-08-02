Block = multiple of 32 of threads (so 256 threads/block is typical)

CUDA framwork for Python kids:
* CuPy (instead of numpy)
* numba
* PyCUDA - requires you to write a kernel function in C code
* PyOpenCl

numba < cython < numpy < numba_parrallel << tf_2.0
