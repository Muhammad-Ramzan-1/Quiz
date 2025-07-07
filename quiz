questions = (("1. What does print(Hello, World!) do?"), (
    "2. Which symbol is used to get input from the user in Python?"),
    ("3. What is the output of 5 + 3 * 2?"), ("4. Which data type is used for True or False in Python?"),
    ("5. What does len(""Python"") return?"))

options = (("a) Saves data , b) Displays a message on the screen , c) Accepts user input , d) Exits the program"),
           ("a) get() , b) read() , c) input() , d) scan()"),
           ("a) 16 , b) 11 , c) 13 , d) 10"),
           ("a) int , b) float  , c) bool , d) string"),
           ("a) 5 , b) 6 , c) 7 , d) Error"))

answers = ("b", "c", "b", "c", "b")
guesses = []
score = 0
no_numb = 0

for question in questions:
    print("\n\n-----------------------------------------\n\n")
    print(question)
    print()
    for option in options[no_numb]:
        print(option, end="")
    print()

    guess = input("Enter (A),(B),(C),(D): ").lower()
    guesses.append(guess)
    if guess == answers[no_numb]:
        score += 1
        print("CORRECT")
    else:
        print(f"WRONG ANSWER, CORRECT ANSWER IS {answers[no_numb]}")
    no_numb += 1
    perc = (score/no_numb)*100
    print(f"your score is {perc}!")

    if perc >= 90:
        print("Excellent! 🎉")
    elif 50 <= perc <= 80:
        print("Good job! 👍")
    else:
        print("Keep practicing! 👨‍💻")
