# Linear-Search

#include <stdio.h> 	
int main () {
	int a[100], i, j, s, position; 
	printf("Enter the number of elements \n"); 
	scanf("%d", &i); 
	printf("Enter the integers \n"); 
	for(j=0; j<i; j++) 
		scanf("%d", a[j]); 
	printf("Enter the search element"); 
	scanf("%d", &s); 
	for(j=0; j<i; j++){
		if (s == a[j]){
			printf("The element %d is found at %d",s, j+1); 
			return 0; 
		}
		else
		printf("Element not found"); 
	}
return 0; 	
}
