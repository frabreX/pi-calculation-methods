# Pi Calculation Methods

An interactive Python collection for comparing approximations of π. It includes Archimedean polygon methods, an arctangent Taylor series, the Chudnovsky algorithm, Monte Carlo estimates, and multiprocessing variants.

## Run

```sh
python -m pip install -r requirements.txt
python calculate_pi.py
```

Enter the desired decimal precision, select a method from the Italian-language menu, and provide any method-specific input. The program compares the result with `mpmath.pi` and reports how many leading digits match. For a quick example, enter precision `30`, choose option `7` (Chudnovsky), and enter `3` terms.

`pi_algorithms.py` contains the numerical methods. `digit_utils.py` contains the comparison helper.
