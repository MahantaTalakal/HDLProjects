Random number generators are typically software, pseudo random number generators. Their outputs are not truly random numbers. Instead they rely on algorithms to mimic the selection of a value to approximate true randomness. Pseudo random number generators work with the user setting the distribution, or scope from which the random number is selected (e.g. lowest to highest), and the number is instantly presented.
the code I have written uses the following algorithm:
X=(a*seed+b)%c

The values 'a' and 'b' are sampled from two counters which are linked to two different clocks.
The seed can be any random number and will remain constant throughout the generation.
We modulus the entire sum by c in order to bring the capacity down to the size we require.

