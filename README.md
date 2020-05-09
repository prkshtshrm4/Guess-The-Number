# Guess-The-Number
1.	Problem:
	The Number guessing game is all about guessing the number randomly chosen by the computer in the given number of chances.


2.	Explanation:
	In the program, while loop runs until the number guessed by the user is equal to the generated number or the number of attempts is less than the maximum number of chances. If the number of attempts becomes greater than the number of chances the game stops and the user lose the game. If the user guesses the correct number in the given number of chances, then he or she will win. After every guess made by the user, the program informs the user whether the guessed number was smaller, greater than the actual generated number.

3.	Function to be used:
random.randint(a, b): This method is used to generate random integer between a and b (both inclusive).



4.	Algorithm:

Step1: Get Minimum and Maximum Range of number to be generated.
1.1	If Min > Max
1.1.1	Print Error message and exit
1.2. Else
	1.2.1. Continue
Step2: Define No. Of chances to attempt in game.
Step3: chance counter initializes with 0
Step4: While Chance counter < Total chance player have
	4.1: Enter the number
		4.1.1 If number guess == actual number
			4.1.1.1 Player Won Print Congratulation message.
		4.1.2 If number guess < actual number
			4.1.2.1 Print guess higher number
		4.1.3: If number guess > actual number
			4.1.3.1: Print guess lower number
Step5: If Chance counter > Total chances player have
	5.1 Print you lose and actual number.
 5.Code: is Find in .py file

 6. Variables Taken
    *kamsekam = int type input variable having min. value of range
    *zadasezada = int type input variable having max. value of range
    *baari = int type input variable having  value of number of turns player want.