# parallel-filter-construction
This is a parallel implementation of xor and fuse filter construction. The code has been tested with CUDA 10.x versions.

## Running the code 
nvcc -o pxorfilter pxorfilter.cu <br/>
./pxorfilter

nvcc -o pfusefilter pfusefilter.cu <br/>
./pfusefilter

## Acknowledgements
This implementation builds on the serial versions of xor and fuse filter constructions by Graf and Lemire http://https://github.com/FastFilter/xor_singleheader
