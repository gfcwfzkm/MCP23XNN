# MCP23XNN
Library for both the I2C and SPI variant of the MCP23x08 or MCP23x17 Port Expander.

It uses a basic I/O interface to access the SPI or I2C bus. See https://github.com/gfcwfzkm/library_template/blob/main/INTERFACE.md for more.
The library has been written in a way to be "object-oriented-ish" - so the use of multiple of these port expander chips with this library is no problem, even when mixing it with different interfaces (I2C & SPI).

As it is usual with my software libraries / projects, most of the documentation is written in the header files.
