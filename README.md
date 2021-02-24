# Chapter5
Exercises from the Chapter 5 of the programming book

# Exercise 1

#include <stdio.h>

int main(void) {
  
//This is a program to convert Centigrades to Farenheit

  float centigrades; //The original temperature
  
  float farenheit; //The conversion
  
  printf("Please insert a temperature, given in centigrades\n");
  
  scanf("%f", &centigrades);
  
  farenheit = (1.8)*centigrades + 32;
  
  printf("The temperature in Farenheit is %f", farenheit);

  return 0;
}
