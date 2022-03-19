# Registers
Information about the loggers, to data loggers with ATLAS peculiarities.

## Guard register
The GUARD recorder stores the most significant bits (first 4 bits) of recorder B and only updates it to the next value if a ```GUARD_S``` instruction was sent, that is saved on the GUARD until another instruction, save or reset occurs.

It's use is massive since it's a backup of the last value, making it possible to make a lot of calculations with the previous value
