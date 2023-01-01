## Loading Data 

* The standard csv way to read a file is to use the reader class in the csv module, but if you observe the data, it's almost like a text file, just that it's structured column-wise as well.
* So a nice way to read this (especially since it has no header, which csv files usually have) is to treat it like a text file and read it line by line into a list, and then split the string with the ',' character, and you get what you want.
* Since you haven't used both of them, I'd suggest that you also try out reading from a csv file and from a text file, even though you'll have libraries like pandas, PyTorch, TensorFlow, etc. to help you out with this in the future, you'll need to know how to load assignments from these anyway

## Grouping the Data

* Here, you haven't exactly grouped the data, my intention was for you to learn how to group an array based on corresponding values of another array. Try using `np.where()` and see if you can do it. Once you're done, we can discuss better methods to group them.

## Computing Mean Images

* Here, since you didn't group the data before, you had to go through all the samples, with a for loop. Since there are around 60000 samples and `Python` for loops are slower compared to inbuilt `NumPy` functions, this will take a long time to run. If you had grouped it, you could have finished it in 10 iterations.

Nice job though, appreciate the effort and hope to see it in the coming assignments as well!
