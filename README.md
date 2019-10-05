# K-Map-Minimization
Solving Kmap using Python
## About
The Karnaugh Map or K-Map is a method of simplifying Boolean algebra expressions. The cells in the K-Map are ordered using the Gray Code. K-Map can be created using either SOP (sum of products) or POS (product of sums). Consider the variables to be w,x,y,z. So, for 2 variables the expression will use w,x; for 3 variables the expression will use w,x,y and for 4 variables the expression will use w,x,y,z. The order of the variables is very important in the K-Map.
## Code
2 python files are attached, 1 contains the function for minimization, while the other for checking it.
The code also handles don't care conditions. Eg. of input format-
  No. of variables: 4
  Function: (1,3,7,11,15) d (0,2,5)
  Simplified expression: yz+w’x’ OR yz+w’z
## Alternative
This code is the most basic one, it can be highly optimized by Quine-McCluskey and Petrick methods.
The details about the algorithms can be found [here] (https://en.wikipedia.org/wiki/Quine%E2%80%93McCluskey_algorithm, https://en.wikipedia.org/wiki/Petrick%27s_method) & [here] (http://www.cs.columbia.edu/~cs6861/handouts/quine-mccluskey-handout.pdf)
