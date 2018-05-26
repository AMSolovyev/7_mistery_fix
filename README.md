<h1> Quadratic Equations  </h1>

<pre> The script tests.py tests the method python get_root() which solves 
    quadratic equation.</pre>

<h1> How to use</h1>

<pre>There is some methods of check in tests.py:</pre>
    <li> def test_solves_real_roots(self) </li>
<pre> There check roots if descriminate = 0: </pre> 
    <li> def test_first_root_less_than_second(self)</li>
<pre> There chek roots if descriminate > 0: </pre>
    <li> def test_second_root_is_none_if_one_solution(self)</li>
<pre> There check root if descriminate = 0 the other root is None: </pre>
     <li>def test_returns_none_for_complex_solution(self)</li>
<pre> There check no roots if descriminate < 0: </pre>
     <li>def test_returns_none_for_complex_solution</li>


<pre> You run a quadratic equation solution like this:</pre>
    <li>from quadratic_equation.py import get_roots
    root1, root2 = get_roots(a, b, c)
    where a, b, c - numbers</li>

<h1> Running the tests </h1> 

<pre>You can run the scrip to use on Linux python or python3 like this:</pre>
<div> python3 tests.py </div> 
<pre> On Windows you use similarly.</pre>



<h1> Project Goals</h1>

<pre> The code is written for educational purposes. Training course for web-developers</pre><a href='#'>DEVMAN.org</a>