from datetime import datetime
import random

print(" Welcome to KashBot!")
print("Type 'bye' to exit.")

while True:
    user = input("You: ").lower()

    if user == "hello":
        print(" Hello! How are you?")

    elif user == "hi":
        print("Hi! Nice to meet you.")

    elif user == "how are you":
        print(" I'm fine. Thanks for asking!")

    elif user == "your name":
        print("My name is KashBot.")

    elif user == "who made you":
        print("I was created by Kashish using Python.")

    elif user == "time":
        print( datetime.now().strftime("%I:%M %p"))

    elif user == "date":
        print( datetime.now().strftime("%d-%m-%Y"))

    elif user == "joke":
        jokes = [
            "Why do programmers prefer Python? Because it's easy to read!",
            "Debugging is like being a detective in a crime movie.",
            "There are only 10 types of people: those who understand binary and those who don't."
        ]
        print( random.choice(jokes))

    elif user == "motivation":
        quotes = [
            "Keep learning, keep growing!",
            "Success comes from consistent practice.",
            "Every expert was once a beginner."
        ]
        print( random.choice(quotes))

    elif user == "calculator":
        num1 = float(input("First number: "))
        op = input("Operator (+, -, *, /): ")
        num2 = float(input("Second number: "))

        if op == "+":
            print(num1 + num2)
        elif op == "-":
            print(num1 - num2)
        elif op == "*":
            print( num1 * num2)
        elif op == "/":
            if num2 != 0:
                print( num1 / num2)
            else:
                print("Cannot divide by zero.")
        else:
            print("Invalid operator.")

    elif user == "bye":
        print("Goodbye! Have a nice day.")
        break

    else:
        print("Sorry, I don't understand that.")
