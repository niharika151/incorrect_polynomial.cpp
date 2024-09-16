# incorrect_polynomial.cpp


**1)To check the incorrect polynomail**


**CODE IS :**

https://github.com/niharika151/incorrect_polynomial.cpp/blob/main/decode%20the%20Y%20value

**Steps to Identify Incorrect Roots**


**Decode All Values:** Convert all the encoded values from their respective bases to decimal to obtain a list of (x, y) pairs.

**Generate All Combinations:** Since we need at least k=6 correct roots to solve for the polynomial's constant term, try different combinations of 6 roots from the 9 provided.

**Calculate Polynomial:** For each combination of 6 roots, use Lagrange interpolation to compute the polynomial and check if the remaining 3 points (which were not included in the interpolation) fit the polynomial. If they do, those 3 points are potential incorrect roots.

**Verify Polynomial:** Check if any combination of 6 roots gives a consistent polynomial where the remaining points do not fit.

**The decoded values are:**



(1,28735619723837)
(2,7165654093362) (hexadecimal)
(3,8348381700879) (base-12)
(4,481013014556258) (base-11)
(5,7165654153890) (hexadecimal)
(6,28735619654702)
(7,379086347222107) (base-14)
(8,343234514070110) (base-9)
(9,2897571638428741) (base-8)

**Generate All Combinations**


Generate combinations of 6 roots from the 9 provided.

**Calculate Polynomial and Verify**


Use Lagrange interpolation to find a polynomial for each combination of 6 roots. Verify if the remaining 3 roots fit this polynomial. If not, those roots are potential incorrect roots.



**2)OUTPUT IMAGE:**

![image](https://github.com/user-attachments/assets/8b97046b-37af-4d0c-a6be-2747563987f3)


**3)To check the Code for Verification**

**CODE IS:**


https://github.com/niharika151/incorrect_polynomial.cpp/blob/main/verification%20code

**Summary**:

1.Decode all the values from their bases.


2.Generate combinations of 6 roots.


3.Use Lagrange interpolation to compute polynomials.


4.Verify if the remaining 3 roots fit the polynomial.


5.Identify and list incorrect roots based on the fit.










