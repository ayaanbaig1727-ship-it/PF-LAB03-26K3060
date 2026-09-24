# Name: Ayaan Baig
1. Red
2. Blue
3. Silver<br>
+Sonata N-Line
+Rocky G Premium
+Yaris Hatchback G Led
Age: 18<br>
***Problem solving and logic creation are my main interests in programming***<br>
printf("Hello World")<br>
<br>
#include <stdio.h>

int main() {
    char name[50];
    int age;

    printf("Enter your name: ");
    scanf("%s", name);

    printf("Enter your age: ");
    scanf("%d", &age);

    printf("Hello %s, you are %d years old.\n", name, age);

    return 0;
}

#include <stdio.h>

int main() {

    int num1, num2;

    printf("Enter first integer: ");
    scanf("%d", &num1);

    printf("Enter second integer: ");
    scanf("%d", &num2);

    printf("Sum = %d\n", num1 + num2);
    printf("Difference = %d\n", num1 - num2);
    printf("Product = %d\n", num1 * num2);
    printf("Quotient = %d\n", num1 / num2);

    return 0;
}

#include <stdio.h>

int main() {

    printf("Name: Ayaan Baig\n");
    printf("Roll Number: 26K-3060 \n");
    printf("\tTabbed Line\n");

    return 0;
}

#include <stdio.h>

int main() {

    float number;

    printf("Enter a floating-point number: ");
    scanf("%f", &number);

    printf("With 2 decimal places: %.2f\n", number);
    printf("With 6 decimal places: %.6f\n", number);

    return 0;
}
