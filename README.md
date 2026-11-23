# Computational Theory Assessment

This repository contains assessment work for the Computational Theory module, focused on implementing the SHA-256 algorithm and exploring computational models.

The SHA-256 work follows the NIST Secure Hash Standard, [FIPS PUB 180-4](https://doi.org/10.6028/NIST.FIPS.180-4). All of the work is in [problems.ipynb](problems.ipynb), and I'm tracking progress on each problem using [GitHub Issues](https://github.com/FionnQ-H1/comp-theory/issues).

## What's in the repository

- `problems.ipynb` is the notebook with the explanations and code for each problem.
- `requirements.txt` lists the Python packages needed to run the notebook.
- `AGENTS.md` has style guidance for any AI tools used with the repository.
- `.gitignore` tells Git which files not to track.

## Tools used

- [Python 3](https://www.python.org/)
- [NumPy](https://numpy.org/), mainly for [numpy.uint32](https://numpy.org/doc/stable/reference/arrays.scalars.html#numpy.uint32), which keeps values at exactly 32 bits like SHA-256 needs
- [Jupyter Notebook](https://jupyter.org/) to run the notebook
- Python's built-in [hashlib](https://docs.python.org/3/library/hashlib.html) to check my SHA-256 results
- [Git](https://git-scm.com/) and [GitHub](https://github.com/) for version control

## Setup & Execution

1. Clone the repository:

    ```bash
    git clone https://github.com/FionnQ-H1/comp-theory.git
    cd comp-theory
    ```

2. Install dependencies using [pip](https://pip.pypa.io/):

    ```bash
    pip install -r requirements.txt
    ```

3. Launch notebook:

    ```bash
    jupyter notebook problems.ipynb
    ```

4. In Jupyter, use Kernel > Restart Kernel and Run All Cells so every cell runs in order.

## References

- National Institute of Standards and Technology (2015). Secure Hash Standard (SHS), FIPS PUB 180-4. https://doi.org/10.6028/NIST.FIPS.180-4
- NumPy documentation: https://numpy.org/doc/stable/
- Python hashlib documentation: https://docs.python.org/3/library/hashlib.html
- PEP 8 style guide: https://peps.python.org/pep-0008/