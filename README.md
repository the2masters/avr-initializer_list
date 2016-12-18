This provides the header initializer_list for use with avr gcc c++. There is no
default stdc++ library for avr gcc. This header is extracted from
libstdc++ 6.2.1 on my x86_64 machine (GPL-3).
I replaced all includes to c++ headers to c equivalents, to be able
to use this separated.

Copy this header into an avr-gcc include directory, e.g. /usr/avr/include
