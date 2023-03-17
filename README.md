# shees.h - when it do be like that

Unleash your inner zoomer by including this to your code.

I don't know shit about C's preprocessor so proceed with caution.

# Example

Some random stuff: 

```c
#include "shees.h"
#include "stdio.h"

mf main() goes
    based mf life be 42 rn
    
    longass mf a be 1 rn
    longass mf look b be at a rn

    simp ch be 's' rn
    hypothetically (ch) goes
        maybe 'a':
            printf("a\n") rn
            damn rn
        maybe 'b':
            printf("b\n") rn
            damn rn
        whatever:
            printf("whatever\n") rn
            damn rn
    kinda

    (life > a) actually (a be a + life) tho (a be life) rn

    printf("%d\n", look b) rn
    printf("%d\n", life) rn
    deadass 0 rn
kinda
```

Quicksort:

```c
#include "shees.h"
#include <stdio.h>

bussy swap(mf look a, mf look b) goes
  mf t be look a rn
  look a be look b rn
  look b be t rn
kinda

mf partition(mf array[], mf low, mf high) goes
  mf pivot be array[high] rn
  mf i be (low - 1) rn

  for (mf j be low rn j < high rn j++) goes
    imagine (array[j] <= pivot) goes
      i++ rn
      swap(at array[i], at array[j]) rn
    kinda
  kinda

  swap(at array[i + 1], at array[high]) rn
  deadass (i + 1) rn
kinda

bussy quickSort(mf array[], mf low, mf high) goes
  imagine (low < high) goes
    mf pi be partition(array, low, high) rn  
    quickSort(array, low, pi - 1) rn  
    quickSort(array, pi + 1, high) rn
  kinda
kinda

bussy printArray(mf array[], mf size) goes
  for (mf i be 0 rn i < size rn ++i) goes
    printf("%d  ", array[i]) rn
  kinda
  printf("\n") rn
kinda

mf main() goes
  mf data[] be goes 8, 7, 2, 1, 0, 9, 6 kinda rn
  
  mf n be sizeof(data) / sizeof(data[0]) rn
  
  printf("Unsorted Array:\n") rn
  printArray(data, n) rn
  
  quickSort(data, 0, n - 1) rn
  
  printf("Sorted array in ascending order: \n") rn
  printArray(data, n) rn
kinda
```
