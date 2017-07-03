# Ray Tracing using OpenMP and Cuda
 Implementing two versions of Ray-Tracing that utilizes CUDA and OpenMP, respectively. 
 
 
 ## Environment
 <li>OS type: Windows 10</li>
 <li>CPU type: Intel(R) Core(TM) i5-4690 CPU @ 3.50GHz 3.50GHz</li>
 <li>Graphics Card: NVIDIA GeForce GTX 750 Ti</li>
 <li>Memory Size : 16.0 GB</li>
 
 ## Screenshots
 Ray Tracing
 ![Screenshot](https://github.com/jeongkyeong/ray-tracing-OpenMP-and-Cuda/blob/master/Screenshot.png)
 
 ## Results
 
 1st Trial:
 |             |Thread 2|Thread 4|Thread 8|Thread 16|
 |:-----------:|:------:|:------:|:------:|:-------:|
 |openmp_ray.c |1.993 sec|1.019 sec|1.007 sec|1.035 sec|
 |cuda_ray.cu  |0.011 sec| 

  
 2nd Trial: 
 |             |Thread 2|Thread 4|Thread 8|Thread 16|
 |:-----------:|:------:|:------:|:------:|:-------:|
 |openmp_ray.c |1.943 sec|1.006 sec|1.009 sec|1.005 sec|
 |cuda_ray.cu  |0.012 sec|


 3rd Trial: 
 |             |Thread 2|Thread 4|Thread 8|Thread 16|
 |:-----------:|:------:|:------:|:------:|:-------:|
 |openmp_ray.c |1.943 sec|1.010 sec|1.021 sec|1.067 sec|
 |cuda_ray.cu  |0.012 sec|


 ![graph](https://github.com/jeongkyeong/ray-tracing-OpenMP-and-Cuda/blob/master/graph.png)


********
 ## Author
 JeongKyong Kang, JungYun Eum
