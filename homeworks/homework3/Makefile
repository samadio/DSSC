all: identity.x ring.x

identity.x: identity_matrix/identity.c
	mpicc $^ -o $@

ring.x: ring_message/ring.c
	mpicc $^ -o $@
clean:
	rm -rf *.x */*~ *~

.PHONY: clean all


