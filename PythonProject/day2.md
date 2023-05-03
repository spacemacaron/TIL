# Data Type

# 🚨 Don't change the code below 👇
two_digit_number = input("Type a two digit number: ")
# 🚨 Don't change the code above 👆

####################################
#Write your code below this line 👇

print(type(two_digit_number))

#string
#What can I do with these conditions?
first_digit_number = int(two_digit_number[0])
second_digit_number = int(two_digit_number[1])

two_digit_number = input("Type a two digit number: ")
print(first_digit_number + second_digit_number)
#clean code result = first_digit + second_digit)


# exercise 1

print("Hello"[0])
print("Hello"[4])


# exercise 2

num_char = len(input("What is your name?"))
print(type(num_char))
#intager

#type convert
new_num_char = str(num_char)

print("Your name has " + new_num_char + " characters.")

# exercise 3

a = 123
print(type(a))

a = str(123)
print(type(a))

# exercise 4


print(3 * 3 + 3 / 3 - 3)

print(3 * (3 + 3) / 3 - 3)




# BMI Calculator

# 🚨 Don't change the code below 👇
height = input("enter your height in m: ")
weight = input("enter your weight in kg: ")
# 🚨 Don't change the code above 👆

#Write your code below this line 👇


personal_height = float(height)
personal_weight = float(weight)

bmi = personal_weight / personal_height**2

print(int(bmi))


# exercise 5


print(round(8 / 3, 2))
print( 8 // 3)


# exercise 6 / F- string

score = 0
height = 1.8
isWinning = True

print(f"your socre is {score}")



#lifetime calculrator

# 🚨 Don't change the code below 👇
age = input("What is your current age?")
# 🚨 Don't change the code above 👆

#Write your code below this line 👇

personal_age = int(age)

# 1 year =365day 52week 12month 
day = (90 - personal_age) * 365
week = (90 - personal_age) * 52
month = (90 - personal_age) * 12 

print(f"You have {day} days, {week} weeks, and {month} months left.")


# Output Example / You have 12410 days, 1768 weeks, and 408 months left.


 
# exercise 6


#If the bill was $150.00, split between 5 people, with 12% tip. 

#Each person should pay (150.00 / 5) * 1.12 = 33.6
#Format the result to 2 decimal places = 33.60

#Tip: There are 2 ways to round a number. You might have to do some Googling to solve this.💪

#Write your code below this line 👇


# outPut Example
# Welcome to the tip calculator!
# What was the total bill? $124.56
# How much tip would you like to give? 10, 12, or 15? 12
# How many people to split the bill? 7


print("Welcome to the tip calculator!")
bill = input("What was the total bill?")
tip = input("How much tip would you like to give? 10, 12, or 15?")
split_person = input("How many people to split the bill?")

total_bill = float(bill) + float(bill) * (0.01 * int(tip)) 
each_pay = total_bill / int(split_person)
each_pay = ":.2f".format(split_person)
print(f"Each person  should pay: {round(each_pay, 2)}")





