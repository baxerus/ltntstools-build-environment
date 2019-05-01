# Introduction

LTNTSTOOLS are a collect of command line tools that collect, analyze and perform various
MPEG-TS ISO13818 tasks.

This repo downloads ltntstools and any deps, then builds the entire project.

# LICENSE

	LGPL-V2.1
	See the included lgpl-2.1.txt for the complete license agreement.

## Dependencies
* ncurses
* libpcap
* zlib-dev
* Doxygen (if generation of API documentation is desired)

## Compilation
    ./build.sh v1.0.1
    cd ltntstools/rpm && ./make-rpm.sh


