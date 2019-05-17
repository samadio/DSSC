all: pi.x

pi.x: pi.c
	mpicc $^ -o $@

clean:
	rm -rf *.x */*~ *~

.PHONY: clean all


