# F-strings
# # # today we are gone to learn about the strings formate
# # # string formate method can be done by formate method
txt = "for only {price:.2f} dollars"
print (txt.format(price = 39.999999))
# we can also use f-string
cost = "this is for only {price:.2f} ruppes"
print(cost.format(price = 56))
val = 'Geeks'  
print(f"{val}for{val} is a portal for {val}.")  
print('What is your name?')
name = input()
print("Hi, " + name + "!")
print("what is your age?")
age = input() 
print("great")
print(f"Hello, {name} you are {age} years old. You are eligible to participate in the competition.")
# we can also use f string for integers
print(f"{2 * 30}")
print(f"{2*15}")
