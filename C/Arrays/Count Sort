//Count Sort
#include<stdio.h>
#include<conio.h>

int main()
{
 clrscr();
 int a[10]={5,7,0,5,2,3,2,2,0,5};
 int k=7,i,j,b[10];
 int count[7+1]={0};
 printf("Before Count Sort\n");
 for(i=0; i<10; i++)
 {
  printf("%d\t",a[i]);
 }
 //storing the frequency of elements in given array to count array
 for(i=0; i<10; i++)
 {
  count[a[i]]+=1;
 }
/*
/ count array
 for(i=0; i<8; i++)
 {
  printf("%d\t",count[i]);
 }
*/
 //updating count array
 for(i=1; i<8; i++)
 {
  count[i]+=count[i-1];
 }
/*
 for(i=0; i<8; i++)
 {
  printf("%d\t",count[i]);
 }
*/
 // storing result in array b
 for(i=9; i>=0; i--)
 {
  count[a[i]]-=1;
  b[count[a[i]]]=a[i];
 }
 for(i=0; i<10; i++)
 {
   a[i]=b[i];
 }
 printf("After Count Sort\n");
 for(i=0; i<10; i++)
 {
  printf("%d\t",a[i]);
 }
 getch();
}
