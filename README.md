# Fundamentals-Of-Accelerated-Computing-With-CUDA

This repository contains the work done as a part of NVIDIA Deep Learning Institue's - Fundamentals of Accelerated Computing With CUDA C/C++ certification. 

To run the code:
```
!nvcc -arch=sm_70 -o output_file_name input_file/file_name.cu -run
```

To profile the code:
```
!nsys profile --stats=true ./output_file_name
```
