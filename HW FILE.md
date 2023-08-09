#include <stdio.h>

#include <stdlib.h>

#include <time.h>

int main() {

srand(time (NULL)); // Seed the random number gene

:

int secretNumber = rand() % 100+ 1; // Generate int guess, attempts = 0; printf("Welcome to the Number Guessing Game!\n");

do ( printf("Enter your guess (1-100): ");

scanf("%d", &guess); attempts++;

if (guess < secretNumber) {

printf("Try higher.\n");

} else if (guess > secretNumber) { printf("Try lower.\n");

} else { printf("Congratulations! You guessed the break;

} while (1); return 0;
