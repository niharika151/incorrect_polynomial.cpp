# incorrect_polynomial.cpp


**1)To check the incorrect polynomail**


**CODE IS :**

https://github.com/niharika151/incorrect_polynomial.cpp/blob/main/decode%20the%20Y%20value

**Steps to Identify Incorrect Roots**


**Decode All Values:** Convert all the encoded values from their respective bases to decimal to obtain a list of (x, y) pairs.

**Generate All Combinations:** Since we need at least k=6 correct roots to solve for the polynomial's constant term, try different combinations of 6 roots from the 9 provided.

**Calculate Polynomial:** For each combination of 6 roots, use Lagrange interpolation to compute the polynomial and check if the remaining 3 points (which were not included in the interpolation) fit the polynomial. If they do, those 3 points are potential incorrect roots.

**Verify Polynomial:** Check if any combination of 6 roots gives a consistent polynomial where the remaining points do not fit.


**Generate All Combinations**


Generate combinations of 6 roots from the 9 provided.

**Calculate Polynomial and Verify**


Use Lagrange interpolation to find a polynomial for each combination of 6 roots. Verify if the remaining 3 roots fit this polynomial. If not, those roots are potential incorrect roots.



**2)OUTPUT IMAGE:**
![image](https://github.com/user-attachments/assets/8b5c4698-8983-4b7a-aa5d-b868220bd946)









