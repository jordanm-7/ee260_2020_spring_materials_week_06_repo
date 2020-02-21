---
title: Exam 1
author: Jordan Macaspac
partner: N/A
date: 2/21/20
---
Embed math equations into Github Markdown file using a [web service](https://www.codecogs.com/latex/eqneditor.php)

# (5 pts)
Perform the following number-system conversions (show your work):

- a. <a href="https://www.codecogs.com/eqnedit.php?latex={129}_{10}&space;=&space;{?}_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{129}_{10}&space;=&space;{?}_{2}" title="{129}_{10} = {?}_{2}" /></a>  

129/2 = 64: 1  
64/2 = 32:  0  
32/2 = 16:  0  
16/2 = 8:   0  
8/2 = 4:    0  
4/2 = 2:    0  
2/2 = 1:    0  
1/2 = 0:    1  
<a href="https://www.codecogs.com/eqnedit.php?latex=10000001_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?10000001_{2}" title="10000001_{2}" /></a>

- b. <a href="https://www.codecogs.com/eqnedit.php?latex={0011010}_{2}&space;=&space;{?}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{0011010}_{2}&space;=&space;{?}_{10}" title="{0011010}_{2} = {?}_{10}" /></a>  

<a href="https://www.codecogs.com/eqnedit.php?latex=(2^4*1)&plus;(2^3*1)&plus;(2^1*1)=26_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(2^4*1)&plus;(2^3*1)&plus;(2^1*1)=26_{10}" title="(2^4*1)+(2^3*1)+(2^1*1)=26_{10}" /></a>

- c. <a href="https://www.codecogs.com/eqnedit.php?latex={0F100}_{16}&space;=&space;{?}_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{0F100}_{16}&space;=&space;{?}_{2}" title="{0F100}_{16} = {?}_{2}" /></a>  

<a href="https://www.codecogs.com/eqnedit.php?latex=0=0000;&space;F=&space;1111;&space;1=0001;&space;0=0000;&space;0=0000" target="_blank"><img src="https://latex.codecogs.com/gif.latex?0=0000;&space;F=&space;1111;&space;1=0001;&space;0=0000;&space;0=0000" title="0=0000; F= 1111; 1=0001; 0=0000; 0=0000" /></a>  
<a href="https://www.codecogs.com/eqnedit.php?latex=1111000100000000_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?1111000100000000_{2}" title="1111000100000000_{2}" /></a>

- d. <a href="https://www.codecogs.com/eqnedit.php?latex={1001101101101}_{2}&space;=&space;{?}_{16}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{1001101101101}_{2}&space;=&space;{?}_{16}" title="{1001101101101}_{2} = {?}_{16}" /></a> 

<a href="https://www.codecogs.com/eqnedit.php?latex=0001=1;0011=3;0110=6;1101=D" target="_blank"><img src="https://latex.codecogs.com/gif.latex?0001=1;0011=3;0110=6;1101=D" title="0001=1;0011=3;0110=6;1101=D" /></a>  
<a href="https://www.codecogs.com/eqnedit.php?latex=136D_{16}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?136D_{16}" title="136D_{16}" /></a>

# (5 pts)
Evaluate the Boolean equation F = a AND (NOT b OR (c AND d)) for the given values
of variables a, b, c, and d:  

- a. a=1, b=1, c=0, d=1   
F = 1 AND (NOT 1 OR (0 AND 1)) = 1 AND (0 OR 0) = 1 AND 0 = 0

- b. a=0, b=0, c=0, d=1  
F = 0 AND (NOT 0 OR (0 AND 1)) = 0 AND (1 OR 0) = 0 AND 1 = 0

# (5 pts)
Draw the NAND(x,y) gate CMOS transistor circuit. Show the conduction path and output
value when: 

- a. x = 1 and y = 0
![Imgur](https://i.imgur.com/VLQqNbn.jpg?1)

- b. x = 1 and y = 1
![Imgur](https://i.imgur.com/xE5kd9y.jpg?1)

# (5 pts)
Convert the following equation directly to gate-level circuits: F = a + bcd’ + a'e + f’
![Imgur](https://i.imgur.com/5BsP4Q3.jpg?1)

# (5 pts)
Expand F(w,y,z) = wy to 
- a. sum-of-minterms form  
<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;=&space;wyz'&space;&plus;&space;wyz" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;=&space;wyz'&space;&plus;&space;wyz" title="F = wyz' + wyz" /></a>

- b. product-of-maxterms form  
<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;=&space;(w'&plus;y'&plus;z')(w'&plus;y'&plus;z)(w'&plus;y&plus;z')(w'&plus;y&plus;z)(w&plus;y'&plus;z')(w&plus;y'&plus;z)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;=&space;(w'&plus;y'&plus;z')(w'&plus;y'&plus;z)(w'&plus;y&plus;z')(w'&plus;y&plus;z)(w&plus;y'&plus;z')(w&plus;y'&plus;z)" title="F = (w'+y'+z')(w'+y'+z)(w'+y+z')(w'+y+z)(w+y'+z')(w+y'+z)" /></a>

# (5 pts)
A car has a fuel-level detector that outputs the current fuel-level as a 3-bit binary number, with 000 meaning empty and 111 meaning full. Create a circuit that illuminates a “low fuel” indicator light (by setting an output L to 1) when the fuel level drops below level 3.


# (5 pts)
Convert the function F shown in the truth table in Table below to an *product-of-sum* equation. Don’t minimize the equation.

![Truth table](figures/problem_6.png)

<a href="https://www.codecogs.com/eqnedit.php?latex=F=(a'&plus;b'&plus;c')(a'&plus;b&plus;c')(a'&plus;b&plus;c)(a&plus;b'&plus;c')(a&plus;b'&plus;c)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F=(a'&plus;b'&plus;c')(a'&plus;b&plus;c')(a'&plus;b&plus;c)(a&plus;b'&plus;c')(a&plus;b'&plus;c)" title="F=(a'+b'+c')(a'+b+c')(a'+b+c)(a+b'+c')(a+b'+c)" /></a>

# (5 pts)
Implement the function above in *Dataflow Modeling* style Verilog and test its functionality via the testbench in [codes/exam/problem_7](../../codes/exam/problem_7). Include the waveform in the report.

# (5 pts) 
Use the theorems of boolean algebra to simplify the following logic function: F = m·n·o + q’·p’·n’ + p·r·m + q’·o·m·p’ + m·r (hint, the result has three terms. Don't spend too much time on this one. If stuck, move on first)



## **beyond this place there be dragons**

# (5 pts)
Implement a 4-to-2 priority encoder using only NOR gates.

- a. Derive the truth table.
- b. Derive the sum-of-product expression.
- c. Derive the product-of-sum expression.
- d. Convert the product-of-sum circuit into NOR gate implementation.

![1-bit 2-to-1 multiplexor](figures/problem_9.png)

# (5 pts)
Analyze the CMOS circuit below. 

- a. Draw the conduction paths for
    - A = 0, B = 0
    - A = 1, B = 0
    - A = 0, B = 1
    - A = 1, B = 1
- b. Write the truth table.
- c. What gate is it?

![Unknown gate](figures/problem_a.png)
