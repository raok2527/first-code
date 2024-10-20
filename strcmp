#include <stdio.h>
#include <string.h>

int main() {
    const char *string1 = "Hello";
    const char *string2 = "World";
    const char *string3 = "Hello";

    // Comparing string1 and string2
    int result1 = strcmp(string1, string2);
    // Comparing string1 and string3
    int result2 = strcmp(string1, string3);

    // Output the results
    if (result1 < 0) {
        printf("\"%s\" is less than \"%s\"\n", string1, string2);
    } else if (result1 > 0) {
        printf("\"%s\" is greater than \"%s\"\n", string1, string2);
    } else {
        printf("\"%s\" is equal to \"%s\"\n", string1, string2);
    }

    if (result2 < 0) {
        printf("\"%s\" is less than \"%s\"\n", string1, string3);
    } else if (result2 > 0) {
        printf("\"%s\" is greater than \"%s\"\n", string1, string3);
    } else {
        printf("\"%s\" is equal to \"%s\"\n", string1, string3);
    }

    return 0;
}
