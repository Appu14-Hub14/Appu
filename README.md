#include <stdio.h>

// Function to check if a number is even or odd
void checkEvenOdd(int num) {
    if (num % 2 == 0)
        printf("%d is Even.\n", num);
    else
        printf("%d is Odd.\n", num);
}

int main() {
    int number;

    printf("Enter an integer: ");
    scanf("%d", &number);

    checkEvenOdd(number);  // Function call
    return 0;
}

