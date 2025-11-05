//#include <stdio.h>// linear search in C
//int search(int array[], int n , int x){
////	going through array squencially
//   for (int i = 0; i<n;i++)
//       if (array[i] ==x)
//       return i;
//    return -1;
//}
//int main(){
//	int array[]={90,64,70,45,34};
//	int x=70;
//	int n = sizeof(array)/sizeof(array[0]);
//	int result =search (array, n, x);
//	(result==-1)? printf("Element not found"): printf("element found at index : %d", result);
//}

// Binary search in c
//# include <stdio.h>
//int binarySearch(int array[], int x, int low , int high){
//	// repeat until the pointers low and high meet eachother 
//	while (low<=high){
//		int mid = low +(high -low)/ 2;
//		if (x== array[mid])
//		return mid ;
//	
//		if (x> array[mid])
//		low = mid +1;
//		else
//		high = mid-1;
//		 
//	}return -1;
//}
//int main(void){
//	 int array[]={3,4,5,6,7,8,9};
//	 int n = sizeof(array)/sizeof(array[0]);
//	 int x = 4;
//	 int result = binarySearch(array , x,0,n-1);
//	 if (result ==-1)
//	 printf("Not Found")
//	 else
//	 printf("element is found at index %d", result);
//	 return 0;
//}

//malloc()
//#include <stdio.h>
//#include <stdlib.h>
//
//int main() {
//    int i, *a;
//    a = (int*) malloc(5 * sizeof(int));
//
//    for(i = 0; i < 5; i++) {
//        printf("Num %d: ", i+1);
//        scanf("%d", a+i);
//    }
//
//    printf("You entered:\n");
//    for(i = 0; i < 5; i++)
//        printf("%d\n", *(a+i));
//
//    free(a);
//    return 0;
//}
//#calloc()
//#include <stdio.h>
//#include <stdlib.h>
//
//int main() {
//    int i, *a;
//    
//    a = (int*) calloc(5, sizeof(int));  // memory for 5 integers, initialized to 0
//
//    for(i = 0; i < 5; i++)
//        printf("%d ", *(a + i));  // prints 0 0 0 0 0
//
//    free(a);  // release memory
//    return 0;
//}
//relloc()
//#include <stdio.h>
//#include <stdlib.h>
//
//int main() {
//    int *arr, n = 5, i;
//
//    // allocate memory for 5 integers
//    arr = (int*) malloc(n * sizeof(int));
//
//    printf("Enter %d numbers:\n", n);
//    for (i = 0; i < n; i++) {
//        scanf("%d", &arr[i]);
//    }
//
//    // increase size to 8
//    n = 8;
//    arr = (int*) realloc(arr, n * sizeof(int));
//
//    printf("Enter 3 more numbers:\n");
//    for (i = 5; i < n; i++) {
//        scanf("%d", &arr[i]);
//    }
//
//    printf("All %d numbers are:\n", n);
//    for (i = 0; i < n; i++) {
//        printf("%d ", arr[i]);
//    }
//
//    free(arr);
//    return 0;
//}

////#BUBBLE SORT:
//#include <stdio.h>
//
//int main() {
//    int n, i, j, temp;
//
//    // Take size of array from user
//    printf("Enter number of elements: ");
//    scanf("%d", &n);
//
//    int arr[n]; // declare array of size n
//
//    // Take array elements from user
//    printf("Enter %d elements:\n", n);
//    for (i = 0; i < n; i++) {
//        scanf("%d", &arr[i]);
//    }
//
//    // Bubble Sort
//    for (i = 0; i < n - 1; i++) {
//        for (j = 0; j < n - i - 1; j++) {
//            if (arr[j] > arr[j + 1]) {
//                // swap
//                temp = arr[j];
//                arr[j] = arr[j + 1];
//                arr[j + 1] = temp;
//            }
//        }
//    }
//
//    // Print sorted array
//    printf("Sorted array: ");
//    for (i = 0; i < n; i++) {
//        printf("%d ", arr[i]);
//    }
//
//    return 0;
//}

//#include <stdio.h>
//
//int main() {
//    int arr[5], n = 5;
//    int i, j, minIndex, temp;
//
//    // input
//    printf("Enter 5 elements: ");
//    for (i = 0; i < n; i++) {
//        scanf("%d", &arr[i]);
//    }
//
//    // selection sort
//    for (i = 0; i < n - 1; i++) {
//        minIndex = i;
//        for (j = i + 1; j < n; j++) {
//            if (arr[j] < arr[minIndex]) {
//                minIndex = j;
//            }
//        }
//        // swap
//        temp = arr[i];
//        arr[i] = arr[minIndex];
//        arr[minIndex] = temp;
//    }
//
//    // output
//    printf("Sorted array: ");
//    for (i = 0; i < n; i++) {
//        printf("%d ", arr[i]);
//    }
//
//    return 0;
//}

//#include <stdio.h>
//
//int main() {
//    int stack[5], top = -1, value;
//
//    // Push operation
//    printf("Enter value to push: ");
//    scanf("%d", &value);
//
//    if (top == 4) {
//        printf("Stack Overflow!\n");
//    } else {
//        top++;
//        stack[top] = value;
//        printf("%d pushed into stack.\n", value);
//    }
//
//    return 0;
//}
#include <stdio.h>

int main() {
    int stack[5] = {10, 20, 30};  // Stack with 3 elements
    int top = 2;  // Top is at index 2 (30 is top element)
    int value;

    // Pop operation
    if (top == -1) {
        printf("Stack Underflow!\n");  // No elements to pop
    } else {
        value = stack[top];  // Take top value
        top--;               // Decrease top
        printf("%d popped from stack.\n", value);
    }

    return 0;
}



