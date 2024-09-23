import random

jackpot = random.randint(1, 100)
guess = int(input('guess kro'))
counter = 1

while guess != jackpot:
    if guess < jackpot:
        print('galat! guess higher')
    else:
        print('galat! guess lower')
    
    guess = int(input('guess kro'))
    counter += 1

print('correct guess')
print('attempts', counter)
