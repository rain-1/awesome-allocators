From https://web.archive.org/web/20060409094110/http://www.osdcom.info/content/view/31/39/

# The Simplest Algorithm

The complexity of an algorithm is given by the number of steps, their iteration and their timing. Since we are talking about the simplest one, it will have the fastest memory release function: it will do nothing!

The allocator will just store the address of the next free available memory block and allocate requested chunks continuously. A brief implementation follows:

```c
#define MAX_MEMORY 1024 * 1024 * MEMORY_SIZE_IN_MEGABYTES

int peak;

void *malloc(size_t size) {
    void *current;
if( MAX_MEMORY – peak < size ) return null;
    current = (void *)peak;
    peak += size;
    return current;
}

void free(void *ptr) {
    return;
}
```
