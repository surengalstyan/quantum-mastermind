## Qiskit implementation of the Mastermind game using Grover's Quantum Algorithm

Binary Mastermind is a code-breaking game where the code maker creates a secret binary code and the code breaker tries to guess it through a series of guesses. The secret code consists of N binary digits (0s and 1s), and the code breaker is allowed to make as many guesses as needed to crack the code.

### Grover's Algorithm

We use Grover's Algorithm to search for the secret code in the space of all possible binary strings of length N.

*Grover's Algorithm allows us to search for a specific value within an unsorted list with quadratic speed-up compared to classical search algorithms.*

## Implementation

This Qiskit implementation defines the Oracle function and the Grover's diffusion operator as separate functions and then combines them in the `quantum_binary_mastermind` function. 

## How to run

The example usage at the end of the code demonstrates how to use the function with a specified secret code and for number of bits. 

- You can run this online, using IBM quantum lab. https://lab.quantum-computing.ibm.com/

- Or you'll need to have Qiskit installed to run this code locally. https://qiskit.org/


## IBM quantum lab execution result 

<img width="696" alt="image" src="https://github.com/surengalstyan/quantum-mastermind/assets/17316828/982ce2fe-0f9a-4d4c-a1fe-b7c8f221eaef">





