# Vulnerabilities
Here I collected some of the common vulnerabilities of ECDSA.

Each notebook has
1. prerequisites for the attack
2. Theory
    - The vulnerability(task) we want to exploit
    - Some background theory + resources that helped me understand it
3. Code
    - Toy implementation
    - If there is a library that makes our life easier
4. More resources

# The order to study them 

1. Easy
    - **Reset_attack**: Reuse of the same nonce when signing different messages
    - **Curveball or Chain of fools**: Not checking the signature algorithm parameters (curve parameters) when issuing certificates
2. Intermediate
    - **Biased_k**: Lattice attack against small nonces given a set of messages and their signature
