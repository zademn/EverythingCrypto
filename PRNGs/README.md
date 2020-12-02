
# Random number generators
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

# Order to read 
1. PRG
2. PRF_PRP
3. Choose your PRNG