# Magic12BallProject
#This is the Magic 12-Ball game that answers questions on buying a cryptocurrency.
# An indecisive person who wants to buy crypto is asking if they should buy some.
import random
name = "Random Crypto Investor"
question = "Should I buy this new Crypto?"
answer = ""
random_number = random.randint(1, 12)
print(random_number)
if random_number == 1:
    answer = "Yes - Please do"
elif random_number == 2:
    answer = "It is decided"
elif random_number == 3:
    answer = "Without a doubt"
elif random_number == 4:
    answer = "Reply hazy, please try again"
elif random_number == 5:
    answer = "Ask me again later, I'm very busy here"
elif random_number == 6:
    answer = "Shouldn't tell you right now"
elif random_number == 7:
    answer = "My sources say no"
elif random_number == 8:
    answer = "The graphs don't look hot"
elif random_number == 9:
    answer = "Really doubtful"
elif random_number == 10:
    answer = "You'll definitely make money"
elif random_number == 11:
    answer = "You'll lose money"
elif random_number == 12:
    answer = "Best to not develop a gambling addiction"
else:
    answer == "Error"
print (name + " asks: " + question )
print ("Magic 12-Ball's answer: " + answer)
