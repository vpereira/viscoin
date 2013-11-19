## Viscoin ##
Viscoin is a visualizer for the Peercoin, based on Bitcoin blockchain.

Programmed in C++.

note from vpereira:

I just changed the magic number to use ppcoin magic number, and I added a copy from ppcoin blockain

to run it:

    xz -d blk0001.data.xz
    make
    ./viscoin blk0001.data
