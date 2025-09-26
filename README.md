# guess-the-number-game
import  random
p=random.randint(1,10)
while True:
    user_output=int(input("inter the value of your choice:"))
    if user_output==p:
        break
    elif user_output>p:
        print("your number is to big think smaller one")
    elif user_output<p:
         print("your number is to small thing bigger one")
print("--------GAME OVER--------")
