# quest-o-12
include <stdio.h>

int main() {
    float fahrenheit, celsius;

    printf("Digite a temperatura em graus Fahrenheit: ");
    scanf("%f", &fahrenheit);

    celsius = (5.0/9.0) * (fahrenheit - 32);

    printf("A temperatura em graus Celsius é: %.2f\n", celsius);

    return 0;
}
