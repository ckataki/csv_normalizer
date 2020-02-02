
## CSV Normalizer


### Overview

Given a CSV file on stdin, normalize it, and print the normalized CSV to stdout. The normalization rules are explained in the code.


### How to Run?


#### Requirements

- Python 3.7 (Tested on MacOS, but any OS should be okay)


#### Steps

1. In the main directory, simply run the program (ensure it is executable).

`chmod +x normalizer`
 
 `./normalizer < input_file.csv > output_file.csv`

2. The program expects input from stdin, and outputs to stdout. Not providing an output file will dump the output on the terminal.

  `./normalizer < input_file.csv`


### Future Work (not exhaustive!)

- Add tests.

- Allow normalized CSV to pass through rather than raise errors.

- Add ability to specify generic input and output buffers.
