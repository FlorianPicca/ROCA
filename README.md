# ROCA

This repository contains my implementation of the ROCA attack.

It's a Sage implementation that uses multiprocessing.

For more information you can read [my blog post about it](https://bitsdeep.com/posts/analysis-of-the-roca-vulnerability/).

## Usage

```
$ sage roca_attack.py
found factorization:
p=69288134094572876629045028069371975574660226148748274586674507084213286357069
q=80688738291820833650844741016523373313635060001251156496219948915457811770063
```

The `sage_functions.py` file contains coppersmith's algorithm.
I have to place it in a separate file so that I can import it in each subprocess.