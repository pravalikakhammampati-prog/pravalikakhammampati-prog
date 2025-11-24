### // profile.c

```c
#include <stdio.h>
#include "pravalika.h"

struct Engineer {
    char name[];
    char role[];
    char passion[];
    char current_focus[];
};

int main() {
    struct Engineer pravalika = {
        .name = "Pravalika",
        .role = "Embedded Systems Student",
        .passion = "Hardware-Software Integration",
        .current_focus = "Developing skills as an Embedded Engineer"
    };

    printf("Welcome to my hardware lab.\n");
    return 0;
}
