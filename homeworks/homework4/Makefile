all: transpose.x

transpose.x: transpose.cu
	nvicc $^ -lm-o $@

clean:
	rm -rf *.x */*~ *~

.PHONY: clean all


