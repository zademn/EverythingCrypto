# Hello there!

In this repository I collect my adventures in the Cryptography world.
You will find
- Medium-Highly Detailed explanations of algorithms
- Implementations in Python / Sage
- Common libraries for solving the problems
- Everything is full of resources (from Youtube videos with intuitive explanations to detailed papers on the subject)
I HIGHLY recommend using nbviewer if you're reading these online: https://nbviewer.jupyter.org/github/zademn/EverythingCrypto/tree/master/  
Github doesn't render the mathematics inside the notebooks

# Structure?

## Notebooks
- For educational and "ease to follow" purposes I decided to work in notebooks. Notebook are structured as follows:
    - Prerequisites = list of subjects/notebooks that you need to cover before attempting the subject
    - Theory = Mathematical explanation + intuitions
    - Code = Python,Sage or other library
    - Resources = List of resources for further reading
    
## Directories

Directories are organized by categories
- Mathematics = Here you will find the basic structures(groups, curves, etc) and algorithms that I studied
    - Discrete Logarithm Problem
    - Factorizations
    - Elliptic Curves
    - Lattices
- Public Key = Each cryptosystem will have a primer and a folder with vulnerabilities (NOTE: mathematical vulnerabilities such as factorizations will not be covered to avoid monotony. I assume you can connect the points) 
    - RSA
    - Diffie Hellman
- Block Ciphers

Each directory will have a README.md that will contain the difficulty MY difficulty ranking of different subjects, attacks etc.

## How to tackle this repository?
Whatever fits your needs
1. Follow along with a book
2. Depth-first fashion (for people that have good foundations):
    - Pick a bigger subject
    - Study it thoroughly (from the lowest difficulty to the highest)
3. Breadth-first fashion (for starters):
    - Go through every topic at the lowest difficulty
    - Raise the difficulty and start again
    
