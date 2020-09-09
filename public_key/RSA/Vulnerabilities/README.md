# Vulnerabilities
Here I collected some of the common vulnerabilities of RSA.

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

1. Begginer
    - **Begginer mistakes**: easy exploitation of bad RSA parameters
2. Easy
    - **Known (e, d) pair**: Decrypt any message if you know the pair (e,d)
    - **Halstad'b broadcast attack**: decrypt a message if it was send to k users and encrypted with different moduli N (k>e)
    - **Wiener attack**: Small d
3. Intermediate:
    - **Coppersmith's attacks** a method to find small roots of polynomials modulo
4. Hard
    - **Boneh-Durfee attack** improvement on Coppersmith
    - **Jochemsz-May attack** A multivariate polynomial case (TO DO)

    