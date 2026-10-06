//WAP in c to print a 4*4 grid of number from 1 to 4 in each row
# include <stdio.h>
void main () {
	int i,j;
	// outer loopd for rows
	for(i=1; i<=4; i++) {
		// Inner loops for Columns ( Nested inside)
		for(j=1; j<=i; j++) {
			printf("%d",j);
		}
		printf("\n"); //moves to the next line after each row
	}
}
