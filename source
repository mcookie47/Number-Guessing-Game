#include <iostream>

using namespace std;

int main()
{
srand(static_cast<unsigned int>(time(0)));

int secretNumber = rand() % 100 + 1;
int guess = 0;

cout << "Guess a number between 1 to 100. " << endl;

while (guess != secretNumber)
{
cout << "Enter your guess: ";
cin >> guess;

if (guess > secretNumber)
{
cout << "Too high! Try again: " << endl;
}
else if (guess < secretNumber)
{
cout << "Too low! Try again: " << endl;
}
else
{
cout << "Correct! You WIN!" << endl;
}
return 0;

}
