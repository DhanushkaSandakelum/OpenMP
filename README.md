# OpenMP

Type `gcc -o example_1 example_1.c && example_1` to compile & run the code.

To compile via OpenMP type, `cc example_1.c -fopenmp`

## Define used threads
By default number of threads will be amount of cores exists in the CPU. However it can be defined manually as well.
`$ export OMP_NUM_THREADS=2`
