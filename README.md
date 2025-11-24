# c-1>>>>>>>>>>
program to add 2 numbers
#include <stdio.h>

int main() {
    char name[50]; // Array to store the name

    // Prompt the user for input
    printf("Enter your name: ");

    // Read a string from the user (safe input handling)
    if (fgets(name, sizeof(name), stdin) == NULL) {
        printf("Error reading input.\n");
        return 1; // Exit with error code
    }

    // Display the entered name
    printf("Hello, %s", name);

    return 0; // Successful execution
}
