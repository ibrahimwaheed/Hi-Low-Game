#include <cstdlib>
#include <iostream>
#include <time.h>
#include <string>

using namespace std;

int main() {
	string answer;
	//Used to loop the game at the end if the user wants to play again
	char playAgain = 'Y';
	while (playAgain == 'Y')
	{
	//Creates a random integer everytime the game is played to ensure the same number isn't used everytime
	srand(time(NULL));
	//creates an integer that will store the computers number
	int cNumber;
	// This is used to declare the range that the random number use
	cNumber = rand() % 10 + 1;
	//displays the number that has been generated for the computer
  cout << "The Computer's number is :"<< cNumber << endl;
	//creates an integer that will store the players number
	int pNumber;
		// This is used to declare the range that the random number use
	pNumber = rand () % 10 + 1;
	cout << "Will your number be Higher or Lower?: ";
	//allows the user to enter their guess
  cin>> answer;
  //declares the output that should be shown depending on whether the player chose the right guess
	if (pNumber == cNumber) {cout<< "You Drew";}
		else if (((pNumber > cNumber) and (answer == "Higher"))
			  or ((pNumber < cNumber) and (answer == "Lower")))
			{cout<< "You have won!";}
    else if (((pNumber < cNumber) and (answer == "Higher"))
          or ((pNumber > cNumber) and (answer == "Lower")))
             {cout << "You lose!";}
  
  cout<< " Do you want to play again: ";
  cin >> playAgain;
	}
	cout << "Hope You Play Again Soon.";
}