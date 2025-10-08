# Exercise 11 – FIR Filter Types

### Author
Tobi

### Description
This project analyzes four FIR filter types (I–IV) based on their impulse responses.
For each filter, the magnitude response, phase response, and pole-zero diagram are plotted.

### Filters Used
```matlab
h1 = [1 2 3 4 4 3 2 1];     % Type I (even, symmetric)
h2 = [1 2 3 4 3 2 1];       % Type II (odd, symmetric)
h3 = [-1 -2 -3 -4 3 3 2 1]; % Type III (even, antisymmetric)
h4 = [-1 -2 -3 0 3 2 1];    % Type IV (odd, antisymmetric)
