# X25519 Implementation for ARM Cortex-M0/M0+

Original Readme File is here: https://github.com/pornin/x25519-cm0/blob/main/README.md 

# Personal Changes

Another object file `x25519-cm0.o` has been generated from the `x25519-cm0.S` using `arm-none-eabi-gcc` file.

# Personal Changes

The object file can be generated using command `arm-none-eabi-gcc -Wall -Wextra -Wshadow -Wundef -Os -mcpu=cortex-m0plus -c -o x25519-cm0.o x25519-cm0.S`

This object file can be directly imported in IAR Workbench along with `test_x25519.c`.