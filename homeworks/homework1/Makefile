all: parallel.x

parallel.x: parallel.c
	gcc $^ -fopenmp -o $@

clean:
	rm -rf *.x */*~ *~

.PHONY: clean all


