# My-first-project
#Mini Game - "Guess the number"
import colorama
from colorama import init
from colorama import Fore, Back, Style
init()

import random
from random import randint

print(Fore.YELLOW)
user_number = int(input("Enter your number from 1 to 10: "))
random_number = randint(1, 10)

if user_number == random_number:
    print(Fore.GREEN)
    print("Congrats! You guess the number!!! "),

else:
    print(Fore.RED)
    print("Sorry, you didn't guess the number :( ")
    print(f"Here is the number that was guessed {random_number}" )
