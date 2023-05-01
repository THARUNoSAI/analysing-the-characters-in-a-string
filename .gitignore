#include <stdio.h>
#include <ctype.h>

int main() {
    char str[100];
    int i, upper=0, lower=0, digits=0, space=0, special=0;
    int counts[5] = {0}; kr

    printf("Enter a string: ");
    fgets(str, sizeof(str), stdin);

    for(i=0; str[i]!='\0'; i++) {
        if(isupper(str[i])) {
            printf("%c is an uppercase alphabet.\n", str[i]);
            upper++;
            counts[0]++;
        }
        else if(islower(str[i])) {
            printf("%c is a lowercase alphabet.\n", str[i]);
            lower++;
            counts[1]++;
        }
        else if(isdigit(str[i])) {
            printf("%c is a digit.\n", str[i]);
            digits++;
            counts[2]++;
        }
        else if(isspace(str[i])) {
            printf("%c is a whitespace.\n", str[i]);
            space++;
            counts[3]++;
        }
        else {
            printf("%c is a special symbol.\n", str[i]);
            special++;
            counts[4]++;
        }
    }

    printf("\nCounts:\n");
    printf("Uppercase alphabets: %d\n", upper);
    printf("Lowercase alphabets: %d\n", lower);
    printf("Digits: %d\n", digits);
    printf("Whitespaces: %d\n", space);
    printf("Special symbols: %d\n", special);

    printf("\nCounts (using array):\n");
    printf("Uppercase alphabets: %d\n", counts[0]);
    printf("Lowercase alphabets: %d\n", counts[1]);
    printf("Digits: %d\n", counts[2]);
    printf("Whitespaces: %d\n", counts[3]);
    printf("Special symbols: %d\n", counts[4]);

    return 0;
}
