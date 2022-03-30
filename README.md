# paper-rock-scissors
project

import random
def check_who_won(player,computer):
    if player == computer:
        print("Padł remis. wygrałeś",player,"a komputer",computer)
    elif (player=="Scissor") and (computer=="Rock"):
        print("Komputer wygrał")

choices = ["Rock","Paper","Scissors"]
computer_choice = random.choice(choices)
print("Witamy w grze 'Rock, Paper or Scissors")
your_choice=input("Wpisz Rock, Paper albo Scissors(wielkość liter ma znaczenie): ")
while (your_choice!="Rock") and (your_choice!="Paper") and (your_choice!="Scissors"):
    print("Wprowadziłeś zły kod")
    your_choice=input("Wpisz ponownie ")


print(your_choice)
print(computer_choice)
check_who_won(your_choice,computer_choice)
