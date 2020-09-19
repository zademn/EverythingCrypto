# Elliptic Curve Discrete Logarithm Problem
The Elliptic Curve Discrete Logarithm Problem is important in cryptography because sometimes the cryptosystem is based on the difficulty of computing the elliptic curve discrete logarithm with points on some curves
Usually we try to abuse bad choices of parameters of curves or different types of curves

Here is a collection of ECDLP algorithms and their applications

Each notebook has
1. prerequisites for the attack
2. Theory
    - Background theory + resources that helped me understand it
3. Code
    - Toy implementation
    - If there is a library that makes our life easier (if i found one)
4. More resources

# The order to study them 

2. Easy (All of these are already implemented in sage)
    - **Baby step giant step**
    - **Pohlig-Hellman on EC** = Order of the curve is smooth
    - **Pollard-rho** on EC*
3. Intermediate:
    - **Smart attack**
    - **Singular curves**
4. Hard
    - **MOV attack** - You can transition the problem from a curve into a finite group where it's easier to solve
