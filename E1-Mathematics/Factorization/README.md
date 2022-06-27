# Factorizations
Factorizations are important in cryptography because sometimes the cryptosystem is based on the difficulty of factorizing some number N 
Usually N = p * q or some combination of multiple primes. We are going to explore different prorieties of these primes and we are going go exploit them with different techniques

Here is a collection of factorization algorithms and their applications

Each notebook has
1. prerequisites for the attack
2. Theory
    - The vulnerability(task) we want to exploit
    - Some background theory + resources that helped me understand it
3. Code
    - Toy implementation
    - If there is a library that makes our life easier (if i found one)
4. More resources

# The order to study them 

1. Beginner
    - **Fermat's factorization**: When p and q are close
2. Easy
    - **Lentsra's EC factorization**: use elliptic curve proprieties to factor some N
3. Intermediate:
    - **Coppersmith's attacks** a method to find small roots of polynomials modulo
    - **ROCA** 2017 vulnerability of primes p that have a special form
4. Hard
