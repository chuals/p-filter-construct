# Parallelized filter construction
This is a parallel implementation of xor and fuse filter construction. The code has been tested with CUDA 10.x versions.

## Running the code 
nvcc -o pxorfilter pxorfilter.cu <br/>
./pxorfilter
```
testing xor8
fpp 0.0039035000 (estimated)
bits per entry 9.8
```

nvcc -o pfusefilter pfusefilter.cu <br/>
./pfusefilter
```
testing fuse8
fpp 0.0038914000 (estimated)
bits per entry 9.1
```

## Benchmarking
Update main method as necessary with input sizes

## Acknowledgements
This implementation builds on the serial versions of xor and fuse filter constructions by Graf and Lemire http://https://github.com/FastFilter/xor_singleheader
