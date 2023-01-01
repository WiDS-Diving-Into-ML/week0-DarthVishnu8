In the class Tester, there are following issues in the functions: 

1. def iterative_mult(w) :
* Needs to be changed to def iterative_mult(self, w)
* Code is not indented, look up how python indentation works online.
* A matrix is stored in a "row-major" form, and w is a row vector itself, so in the code you are multiplying two rows together. In matrix multiplication, you need to multiply row by column.


2. def matrix_mult(w) :
* A self parameter needs to be added (similar to point 1). 
* np.multiply doesn't compute the matrix multiplication, it just multiplies all elements of the arrays with one another. Also, you are again multiplying row by row (similar to previous comment)

3. def comparison(w) :
* Not attempted

4. Plotting :
* Not attempted
