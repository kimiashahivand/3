#include <stdio.h>

float ave(int a[], int n) {
    int sum = 0;
    for (int i = 0; i < n; i++) {
        sum += a[i];
    }
    return (float)sum / n;
}

int main() {
    int a[5];
    int i;

    printf("Enter 5 numbers\n");
    for (i = 0; i < 5; i++) {
        printf("a[%d] : ", i);
        scanf("%d", &a[i]);
    }

    printf("\nAverage of first 5 elements: %.2f\n", ave(a, 5));

    return 0;
}
