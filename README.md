# Print-a-pyramid-of-numbers
Using C language program is made which gives the output of pyramid of numbers
#include <stdio.h>
int main() {
    int n, i = 1, j, k;
    scanf("%d", &n);
    while(i <= n) {
        j = n - i;
        while(j--) printf(" ");
        k = 1;
        while(k <= i) {
            printf("%d ", k);
            k++;
        }
        printf("\n");
        i++;
    }
    return 0;
}
