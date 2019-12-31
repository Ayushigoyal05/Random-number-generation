# Random-number-generation
#In this i used random module to generate a random by computer within a given range. Then the user will guess the number by giving an input.


import random
c=random.randint(0,20)
print(c)
q=int(input("enter the number"))
if(c>q):
    print("too low")
elif(c<q):
    print("too high")
else:
    print("right guess")
