all:
	nvcc -I /usr/local/cula/include -L /usr/local/cula/lib64 -lcula_core -lcula_lapack -lcublas -lcudart ae.cu -o ae

clean:
	rm ae