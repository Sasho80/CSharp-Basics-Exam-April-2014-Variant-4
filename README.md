
Problem 1 – Cinema
Most people like going to the cinema. If you are such person, help the cinema director Kircho solve his financial task.
Kircho is trying to calculate how much his incomes are for a single projection, if the movie hall is completely full. He knows the type of projection (and how much a ticket for each type costs), the number of rows and the number of columns in the hall (the cimena hall is rectangular).
There are three types of movies projected in Kircho’s cinema:
•	Premiere projection – 12.00 leva
•	Normal projection – 7.50 leva
•	Discount projection for kids, students and retirees – 5.00 leva
Your task is to calculate the incomes Kircho gets for a single projection full of people. You need to calculate how many people are watching the movie depending on the rows and columns in the hall and find the incomes in levas depending on the type of projection.
Input
•	The input data is read from the console. 
•	A string representing the type of projection stays at the first input line. It can be one of the following: “Premiere”, “Normal”, “Discount” (without the quotes).
•	The number of rows stays at the second input line.
•	The number of columns stays at the third input line.
•	The input data will always be valid and in the format described. There is no need to check it explicitly.
Output
•	The output data must be printed on the console.
•	On the only output line you must print the incomes with two digits after the decimal point with “leva” appended at the end (see the example tests). Use "." as decimal separator.
Constraints
•	The rows and columns are numbers between 1 and 100, inclusively.
•	Time limit: 0.25 seconds.
•	Allowed memory: 16 MB.
Examples
Input	  Output		            Input	 Output
Premiere                                    Normal
10      1440.00 leva                        21     2047.50 leva
13                                          12	  
	      		
Problem 2 – Illuminati
The illuminati are an ancient, very secret society that very secretly rules the world. They’ve managed to keep their existence secret by using a very secretive way of communication. Their secret is that they incorporate their secret messages into popular (non-secret) movies.
Your task is to extract the meaning of some movie lines. The messages are actually codes that can be extracted by summing the secret values of every vowel in the message. The values of the vowels are as follows: A = 65, E = 69, I = 73, O = 79, U = 85. The values apply for both upper and lowercase letters. For example, ‘I am Batman!’ has a total of 4 vowels: three times ‘A’ and one time ‘I’ and their sum is: 3 * 65 + 1 * 73 = 268.
Input
•	The input data should be read from the console.
•	The only input line holds the message that has to be deciphered.
The input data will always be valid and in the format described. There is no need to check it explicitly.
Output
•	The output data should be printed on the console.
•	On the first output line you must print the number of vowels in the message.
•	On the second output line you must print the sum of all the vowels in the message.
Constraints
•	The length of the message will be between 1 and 800 000 characters.
•	Allowed working time for your program: 0.1 seconds.
•	Allowed memory: 16 MB.
Examples
Input	Output
Listen very carefully, I shall say this only once.	13
933
Heeeeeeere’s JOHNNY!	9
631
Don’t ask me about my business!	9
669



