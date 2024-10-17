#include <stdio.h>

void mergeArrays(int arr1[], int size1, int arr2[], int size2, int merged[]) {
    int i, j;
    
    for (i = 0; i < size1; i++) {
        merged[i] = arr1[i];
    }
    
    for (j = 0; j < size2; j++) {
        merged[i + j] = arr2[j];
    }
}

int main() {
    int arr1[] = {1, 2, 3, 4};
    int arr2[] = {5, 6, 7, 8};
    
    int size1 = sizeof(arr1) / sizeof(arr1[0]);
    int size2 = sizeof(arr2) / sizeof(arr2[0]);
    
    int mergedSize = size1 + size2;
    int merged[mergedSize];
    
    mergeArrays(arr1, size1, arr2, size2, merged);
    
    printf("Merged array: ");
    for (int i = 0; i < mergedSize; i++) {
        printf("%d ", merged[i]);
    }
    
    printf("\n");
    return 0;
}
