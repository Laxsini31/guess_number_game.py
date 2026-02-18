import random
num=random.randint(1,10)
guess=int(input("Guess: "))
if guess==num:
    print("Correct")
else:
    print("Wrong. Number was",num)



Output :
5
Wrong. Number was 8
