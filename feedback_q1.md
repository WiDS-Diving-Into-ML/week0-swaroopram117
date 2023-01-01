Initialise the seed using np.random.seed in the import box.


1. def iterative_mult(w) :
* The function doesn't make sense. In object oriented programming, you're supposed to work with only two kinds of variables, either data members or parameters.
* So, initialising v doesn't make sense. Also, you aren't supposed to use v, only M and w.
* Also, w is a row vector itself, so in the code you are multiplying two rows together. In matrix multiplication, you need to multiply row by column.

2. def matrix_mult(w) :
* Similar issues as part 1, the function doesn't make sense

3. def comparison(w) :
* %timeit doesn't return anything, so your variables are actually empty.
* Google the function timeit.timeit

4. Plotting
* There seem to be some extra cells,but provided that the correct cells are run, it should be ok

