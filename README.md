# Quadratic Equations

The script ```tests.py tests``` the method ```python get_root()``` which solves 
    quadratic equation

# How to use

There is some methods of check in tests.py:
 
```python
def test_solves_real_roots(self) 
```
There check roots if descriminate = 0:
```python
def test_first_root_less_than_second(self) 
```
There check roots if descriminate > 0:
```python
def test_second_root_is_none_if_one_solution(self) 
```
There check root if descriminate = 0 the other root is None:
```python
def test_returns_none_for_complex_solution(self)
```
There check no roots if descriminate < 0:

You run a quadratic equation solution like this:
```python
from quadratic_equation.py import get_roots
root1, root2 = get_roots(a, b, c)
```
where a, b, c - numbers

# Running the tests

You can run the scrip to use on Linux python or python3 like this:
```python3 tests.py``` 
On Windows you use similarly.



#Project Goals

The code is written for educational purposes. Training course for web-developers -
[DEVMAN.org](https://devman.org))