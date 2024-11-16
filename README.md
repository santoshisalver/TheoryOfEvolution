# DNA Evolution Simulator

This project simulates the evolution of a binary DNA sequence by randomly flipping bits over multiple iterations. 
The program allows you to evolve a DNA sequence, represented as a string of 0s and 1s, by introducing mutations in the form of random bit flips.

## Features
- Evolves a given binary DNA sequence over a series of steps (default: 10,000 iterations).
- Each step randomly flips a bit (0 → 1 or 1 → 0) in the sequence.
- Can read an initial DNA sequence from a file (`dna_data.txt`), or generate a random sequence if the file is not found.
- Outputs the evolved DNA sequence after the specified number of iterations.

Assuming you have the following content in dna_data.txt:
<br>
Copy code
<br>
110010101011100101011001010011001011010010100101001010
<br>
Running the script will evolve this sequence over 10,000 steps. After running, the evolved DNA sequence might look something like this:
<br>
Copy code
<br>
110010100011101110101101010011001011101010110001110101
<br>
