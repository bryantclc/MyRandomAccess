CC=gcc
CFLAGS=-O2

all:single_node_lcg_omp
single_node_lcg_omp:single_node_lcg.c
	$(CC) $(CFLAGS) -o single_node_lcg_omp single_node_lcg.c -fopenmp
clean:
	rm -f single_node_lcg_omp
