# awesome-allocators
Awesome links and information about memory allocation

## malloc/free Implementations
* the trivial bump allocator: [bump allocator](bump.md)
* liballoc (for hobby OS's): https://github.com/blanham/liballoc/
* dbestfit: https://daniel.haxx.se/projects/dbestfit/thoughts.html
* dlmalloc: http://g.oswego.edu/dl/html/malloc.html
* heapmm (AVL tree based): http://www.geocities.ws/wkaras/heapmm/heapmm.html
* jemalloc: http://jemalloc.net/
* nedmalloc: http://www.nedprod.com/programs/portable/nedmalloc/
* tcmalloc: http://goog-perftools.sourceforge.net/doc/tcmalloc.html
* download more ram: https://github.com/graphitemaster/moreram

## Garbage Collectors
* http://www.hboehm.info/gc/
* http://www.ravenbrook.com/project/mps

## General Learning
* Memory Management Enyclopedia: http://www.memorymanagement.org/
* SystemProgramming guide: [Memory, Part 1: Heap Memory Introduction](https://github.com/angrave/SystemProgramming/wiki/Memory,-Part-1:-Heap-Memory-Introduction)
* SystemProgramming guide: [Memory, Part 2: Implementing a Memory Allocator](https://github.com/angrave/SystemProgramming/wiki/Memory%2C-Part-2%3A-Implementing-a-Memory-Allocator)
* Visualizing GCs: https://spin.atomicobject.com/2014/09/03/visualizing-garbage-collection-algorithms/
* Mark and Sweep GC Tutorial: http://journal.stuffwithstuff.com/2013/12/08/babys-first-garbage-collector/
* OpenBSD code read: malloc - [1](https://junk.tintagel.pl/openbsd-daily-malloc-1.txt) [2](https://junk.tintagel.pl/openbsd-daily-malloc-2.txt) [3](https://junk.tintagel.pl/openbsd-daily-malloc-3.txt) [4](https://junk.tintagel.pl/openbsd-daily-malloc-4.txt) [5](https://junk.tintagel.pl/openbsd-daily-malloc-5.txt) [6](https://junk.tintagel.pl/openbsd-daily-malloc-6.txt) [7](https://junk.tintagel.pl/openbsd-daily-malloc-7.txt) [8](https://junk.tintagel.pl/openbsd-daily-malloc-8.txt)
* Write a simple memory allocator: http://arjunsreedharan.org/post/148675821737/write-a-simple-memory-allocator

## Great Papers
* One pass real-time generational mark-sweep garbage collection, J Armstrong, R Virding (1995) - [link1](https://link.springer.com/chapter/10.1007%2F3-540-60368-9_31) [link2](https://pdfs.semanticscholar.org/6844/271989c22aa1395466b88a65b5775ec9f791.pdf)
* Worst case fragmentation of first fit and best fit storage allocation strategies, JM Robson (1977) - [link](https://academic.oup.com/comjnl/article-pdf/20/3/242/2255805/200242.pdf)
* The Memory Fragmentation Problem: Solved?, Mark S Johnston, Paul R Wilson (1997) - [link](https://www.researchgate.net/profile/Paul_Wilson34/publication/2294861_The_Memory_Fragmentation_Problem_Solved/links/55618b1708ae8c0cab31f4c1/The-Memory-Fragmentation-Problem-Solved.pdf)

## Good Papers
* [http://www.cs.cmu.edu/~bryant/pubdir/sigcse18.pdf](Implementing Malloc: Students and Systems Programming) - Brian P. Railing, Randal E. Bryant discuss the CS coursework about implementing malloc.
