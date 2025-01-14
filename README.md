# VHDL Counter Overflow Bug

This repository demonstrates a common but subtle bug in VHDL code: an integer counter that doesn't handle overflow correctly. The `buggy_counter.vhdl` file contains the flawed code, which lacks appropriate checks to prevent the counter from exceeding its defined range. This can lead to unexpected behavior, such as incorrect output or even simulation errors.

The solution, `fixed_counter.vhdl`, demonstrates how to prevent this issue with a simple modification.  It uses the `mod` operator to ensure the counter always stays within the specified range. This example highlights the importance of careful range checking in VHDL to prevent unintended consequences.