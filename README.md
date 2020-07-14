# Prime-Parking-Sequences

This program could be used to generate and calculate the number of parking sequences and prime parking sequences, given a length vector and the size of a trailer.
The last function, 'easyRun()', is the only function that users needs to use to run examples.
easyRun() takes in 2 parameters: the length vector and z. It prints out the number of parking sequences and the number of prime parking sequences. It could also print out all possible parking configurations, preference vectors, and prime parking sequences, if you uncomment certain lines of the code. 

You should load all the chunks and use a command like this to run examples:
length_vector = [1,1,3]
z = 1
easyRun(length_vector, z)

If you want to check which parking configuration corresponds to which preference vectors, you could add True as the third parameter to the function, just like this:
easyRun(length_vector, z, True)
