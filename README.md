# Circom Examples

The project skeleton (MAKE file, etc.) is copied from [here][zklearning] 

## Dependencies

* [`circom`](https://github.com/iden3/circom)
* [`node`](https://nodejs.org/en/)
* [`snarkjs`](https://github.com/iden3/snarkjs)

## Instructions

Check your circom circuit:
`circome <c>.circom`

Check your R1CS and witness (e.g. contsraint count):
`make info`

Clean up:
`make clean`

The end-to-end target is `make verify`. See the Makefile for steps.


[zklearning]:https://github.com/rdi-berkeley/zkp-course-lecture3-code/tree/main/circom
