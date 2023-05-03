``` py


# 🚨 Don't change the code below 👇
a = input("a: ")
b = input("b: ")
# 🚨 Don't change the code above 👆

####################################
#Write your code below this line 👇

c = a 
a = b
b = c

#Write your code above this line 👆
####################################

# 🚨 Don't change the code below 👇
print("a: " + a)
print("b: " + b)




```

코드의 색깔에 익숙해지는 것이 좋다
많은 힌트를 주기 때문임

``` py

print("Hello world! \n Hello world!")
Hello world! 
 Hello world!

```
백슬래시임에 주의 

Input < 입력을 받는 함수 
(내가 어떤 값을 입력하면 그것으로 대체되는거야)


#day 1 end project

# input() will get user input in console
# Then print() will print the word "Hello" and the user input


#1. Create a greeting for your program.

#2. Ask the user for the city that they grew up in.

#3. Ask the user for the name of a pet.

#4. Combine the name of their city and pet and show them their band name.

#5. Make sure the input cursor shows on a new line:

# Solution: https://replit.com/@appbrewery/band-name-generator-end






print("Welcome to the Band Name Generator.")
city = input("What's name of the city you grew up in?\n")
pet = input("What's your pet's name?\n")
print("Your band name could be " + city + " " + pet)
