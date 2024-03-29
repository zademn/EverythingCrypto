
# Random number generators
(medium difficulty)

Random number generators (RNGs) are essential to cryptography since many algorithms require random numbers
- Block ciphers key / iv
- Stream cipher keystream

--- 

Yet not all RNG are created equal
- TRNG - True random number generators - physical events(throwing a dice, time of keytaps)
- PRNG - Algorithmically determined - Appear to be random

In practice we use PRNG since we don't always have a TRNG at disposal

--- 

Now, not all PRNGs are created equal
- Some PRNGs are designed for speed and don't care if you are able to predict them given some outputs
- Others are **cryptographically secure pseudo random generators** which you are unable to predict given some outputs

---

# Stream ciphers
A stream cipher is a symmetric key cipher where plaintext digits are combined with a pseudorandom cipher digit stream (keystream). In a stream cipher, each plaintext digit is encrypted one at a time with the corresponding digit of the keystream, to give a digit of the ciphertext stream.

`C = P xor KS`

`KS = key-scheduling-algo(K)` where `K` involves some secret key

# Suggested reading order
1. PRG
2. PRF_PRP
3. Choose your PRNG / stream cipher