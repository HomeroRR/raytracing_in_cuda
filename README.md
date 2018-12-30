Ray Tracer written in CUDA
====================================================================================================
The aim of this project is to implement a raytracer in CUDA.

How To Run
-----------------
With the NVIDIA nvcc compiler installed, one can run the following to compile:
```bash
nvcc main.cu -o main
```
And then the following to save the output in the out.ppm image file:
```bash
main > out.ppm
```

## Alternatively, one can also output metric evaluations with nvprof as follows:
```bash
nvprof --metrics inst_fp_32,inst_fp_64 ./cudart > out.ppm
```

## Corrections
Work still in progresss. 
If you spot errors or have suggested corrections, please [submit issues via GitHub].

Acknowledgements
-----------------
Thanks to Peter Shirley for his books on raytracing along with releasing the code to the public domain.
The original inspiration was the _Ray Tracing in One Weekend_ series of books now available to the public for free in PDF
form, along with the accompanying source code. Releases are available [directly from GitHub].


[directly from GitHub]:       https://github.com/petershirley/raytracingtherestofyourlife/releases/
[submit issues via GitHub]:   https://github.com/HomeroRR/raytracing_in_cuda/issues/
