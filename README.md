# Number-Guessing-Game-in-Python

#Guessing of the hidden number

i=9
n = 15

while (i>0):
 print("number of guesses left",i)
 i = i - 1
 if i>-1:
    a = int(input("Enter number\n"))
    if a==n:
        print("You have entered correct number")
        break
    elif a<n:
        print("Please Increase the value")
        continue
    else:
        print("please decrease the value")
        continue
else:
    print("GAME OVER")
