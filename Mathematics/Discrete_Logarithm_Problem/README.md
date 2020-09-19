# Discrete Logarithm Problem
The Discrete Logarithm Problem is important in cryptography because sometimes the cryptosystem is based on the difficulty of computing the discrete logarithm in some group of some order.  
Given an element g of high order and en element a = g^x mod N find x  
Usually we try to abuse bad choices of groups

Here is a collection of DLP algorithms and their applications

Each notebook has
1. prerequisites for the attack
2. Theory
    - Background theory + resources that helped me understand it
3. Code
    - Toy implementation
    - If there is a library that makes our life easier (if i found one)
4. More resources

# The order to study them 

2. Easy
    - **Baby Step Giant Step** = Collision algorithm for solving the DLP
    - **Pohlig-Hellman** = When the order of the group is a smooth number00
3. Intermediate:
    - **Pollard-Rho** = Space-Time efficient way of computing the DLP
4. Hard
