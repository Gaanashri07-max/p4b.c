# p4b.c
//C Program to check vote eligibilty 
#include <stdio.h>
int main () {
  int age;
  printf ("enter age");
  scanf("%d",&age);
  if(age>=18)
  printf("you can vote !");
  else
  printf("you cant vote!");
  return 0 ;
