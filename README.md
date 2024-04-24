# Mandelbrot_Set_CUDA
Mandelbrot Set image generator. Implemented in CUDA.

#Build Instructions
Navigate to src directory.
Compile with : nvcc kernel.cu -o mandlebrot -arch=sm_89 -lcublas

#Benchmark:
RTX 4060:
| Image Size | Time(s) |
| -------- | ------- |
| 3840 x 2160 | 0.1s|

